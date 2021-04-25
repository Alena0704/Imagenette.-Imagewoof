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
Второй способ решения, был с помощью нейросети ResNet. Результаты теста по классам показали такие результаты:
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

