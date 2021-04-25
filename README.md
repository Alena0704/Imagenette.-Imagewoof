# Imagenette.-Imagewoof
Imagewoof-это подмножество из 10 классов пород собак. Породы: Австралийский терьер, бордер-терьер, Самоед, Бигль, Ши-тцу, английский фоксхаунд, родезийский риджбек, Динго, Золотистый ретривер, староанглийская овчарка.
Здесь я попробовала разработать свою нейросеть на основе фреймворка PyTorch:
```
class SimpleConvNet(nn.Module):
    def __init__(self):
        # вызов конструктора предка nn.Module
        super(SimpleConvNet, self).__init__()
        # необходмо заранее знать, сколько каналов у картинки (сейчас = 3),
        # которую будем подавать в сеть, больше ничего
        # про входящие картинки знать не нужно
        self.conv1 = nn.Conv2d(in_channels=3, out_channels=6, kernel_size=3) #сверточный слой, ядро = 3х3, на выхое каналов - 6
        self.bn1 = nn.BatchNorm2d(6) #слой, обеспечивающий пакетную (batch) нормализацию
        self.conv2 = nn.Conv2d(in_channels=6, out_channels=12, kernel_size=3)
        self.pool2 = nn.MaxPool2d(kernel_size=2, stride=2)
        self.conv3 = nn.Conv2d(in_channels=12, out_channels=6, kernel_size=3)
        self.pool3 = nn.MaxPool2d(kernel_size=2, stride=2)
        
        self.fc1 = nn.Linear(13824, 2048)  # !!!  #- fully-connected, Dense в Keras, linear - tensorflow
        self.drop = nn.Dropout(p=0.4)
        
        self.fc4 = nn.Linear(2048,  256)
        self.bn3 = nn.BatchNorm1d(256)
        self.fc3 = nn.Linear(256, 10)
```
Но к сожалению, весомых результатов это не дало :-(
Матрица ошибок:
```
array([[ 96,  18,  39,  20,  40,  28,  43,  56,  34,  35],
       [ 20,  98,  43,  14,  48,  57,  54,  12,   3,  59],
       [ 49,  53,  67,  27,  49,  41,  43,  23,  20,  46],
       [ 27,  18,  37,  41,  27,  15,  20,  12,   9,  18],
       [ 41,  47,  42,  24,  71,  54,  45,  27,  17,  33],
       [ 26,  68,  38,  15,  51,  77,  56,  21,  10,  45],
       [ 23,  64,  33,  11,  32,  70,  77,  27,  21,  43],
       [ 42,  15,  39,  21,  35,  24,  32, 117,  69,  28],
       [ 57,  11,  28,  17,  27,  22,  27,  83, 131,  26],
       [ 24,  67,  34,  15,  40,  50,  61,  21,  13,  85]])
```
Результат:
```
Accuracy of Australian terrier : 19 %
Accuracy of Border terrier : 12 %
Accuracy of Samoyed : 15 %
Accuracy of Beagle : 11 %
Accuracy of Shih-Tzu : 10 %
Accuracy of English foxhound : 13 %
Accuracy of Rhodesian ridgeback :  9 %
Accuracy of Dingo : 12 %
Accuracy of Golden retriever : 12 %
Accuracy of Old English sheepdog : 15 %
```
Второй способ решения, был с помощью нейросети ResNet. Результаты теста по классам показали такие результаты:
```
Accuracy of Australian terrier : 55 %
Accuracy of Border terrier : 59 %
Accuracy of Samoyed : 73 %
Accuracy of Beagle : 43 %
Accuracy of Shih-Tzu : 60 %
Accuracy of English foxhound : 64 %
Accuracy of Rhodesian ridgeback : 56 %
Accuracy of Dingo : 61 %
Accuracy of Golden retriever : 72 %
Accuracy of Old English sheepdog : 61 %
```
Матрица ошибок:

```
array([[255,   3,  17,   5,  30,  23,  15,  44,  11,   6],
       [  3, 269,  14,   4,  18,  28,  39,   0,   5,  28],
       [ 25,  10, 241,  56,   9,  13,  25,   7,   9,  23],
       [  7,   8,  52, 122,   3,   8,  10,   3,   1,  10],
       [ 37,  19,   9,   4, 240,  48,  14,  14,   4,  12],
       [ 22,  12,  12,   5,  42, 271,  23,   6,   2,  12],
       [ 18,  28,  21,   6,  16,  18, 243,   7,  13,  31],
       [ 46,   0,   6,   9,   1,  17,  12, 279,  49,   3],
       [ 11,   2,   6,   7,   6,   2,  16,  34, 337,   8],
       [ 12,  36,  22,   6,   8,  17,  36,  10,   7, 256]])
```
Код в файле test.ipynb
