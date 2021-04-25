----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1         [-1, 64, 125, 125]           9,408
       BatchNorm2d-2         [-1, 64, 125, 125]             128
              ReLU-3         [-1, 64, 125, 125]               0
         MaxPool2d-4           [-1, 64, 63, 63]               0
            Conv2d-5           [-1, 64, 63, 63]          36,864
       BatchNorm2d-6           [-1, 64, 63, 63]             128
              ReLU-7           [-1, 64, 63, 63]               0
            Conv2d-8           [-1, 64, 63, 63]          36,864
       BatchNorm2d-9           [-1, 64, 63, 63]             128
             ReLU-10           [-1, 64, 63, 63]               0
       BasicBlock-11           [-1, 64, 63, 63]               0
           Conv2d-12           [-1, 64, 63, 63]          36,864
      BatchNorm2d-13           [-1, 64, 63, 63]             128
             ReLU-14           [-1, 64, 63, 63]               0
           Conv2d-15           [-1, 64, 63, 63]          36,864
      BatchNorm2d-16           [-1, 64, 63, 63]             128
             ReLU-17           [-1, 64, 63, 63]               0
       BasicBlock-18           [-1, 64, 63, 63]               0
           Conv2d-19          [-1, 128, 32, 32]          73,728
      BatchNorm2d-20          [-1, 128, 32, 32]             256
             ReLU-21          [-1, 128, 32, 32]               0
           Conv2d-22          [-1, 128, 32, 32]         147,456
      BatchNorm2d-23          [-1, 128, 32, 32]             256
           Conv2d-24          [-1, 128, 32, 32]           8,192
      BatchNorm2d-25          [-1, 128, 32, 32]             256
             ReLU-26          [-1, 128, 32, 32]               0
       BasicBlock-27          [-1, 128, 32, 32]               0
           Conv2d-28          [-1, 128, 32, 32]         147,456
      BatchNorm2d-29          [-1, 128, 32, 32]             256
             ReLU-30          [-1, 128, 32, 32]               0
           Conv2d-31          [-1, 128, 32, 32]         147,456
      BatchNorm2d-32          [-1, 128, 32, 32]             256
             ReLU-33          [-1, 128, 32, 32]               0
       BasicBlock-34          [-1, 128, 32, 32]               0
           Conv2d-35          [-1, 256, 16, 16]         294,912
      BatchNorm2d-36          [-1, 256, 16, 16]             512
             ReLU-37          [-1, 256, 16, 16]               0
           Conv2d-38          [-1, 256, 16, 16]         589,824
      BatchNorm2d-39          [-1, 256, 16, 16]             512
           Conv2d-40          [-1, 256, 16, 16]          32,768
      BatchNorm2d-41          [-1, 256, 16, 16]             512
             ReLU-42          [-1, 256, 16, 16]               0
       BasicBlock-43          [-1, 256, 16, 16]               0
           Conv2d-44          [-1, 256, 16, 16]         589,824
      BatchNorm2d-45          [-1, 256, 16, 16]             512
             ReLU-46          [-1, 256, 16, 16]               0
           Conv2d-47          [-1, 256, 16, 16]         589,824
      BatchNorm2d-48          [-1, 256, 16, 16]             512
             ReLU-49          [-1, 256, 16, 16]               0
       BasicBlock-50          [-1, 256, 16, 16]               0
           Conv2d-51            [-1, 512, 8, 8]       1,179,648
      BatchNorm2d-52            [-1, 512, 8, 8]           1,024
             ReLU-53            [-1, 512, 8, 8]               0
           Conv2d-54            [-1, 512, 8, 8]       2,359,296
      BatchNorm2d-55            [-1, 512, 8, 8]           1,024
           Conv2d-56            [-1, 512, 8, 8]         131,072
      BatchNorm2d-57            [-1, 512, 8, 8]           1,024
             ReLU-58            [-1, 512, 8, 8]               0
       BasicBlock-59            [-1, 512, 8, 8]               0
           Conv2d-60            [-1, 512, 8, 8]       2,359,296
      BatchNorm2d-61            [-1, 512, 8, 8]           1,024
             ReLU-62            [-1, 512, 8, 8]               0
           Conv2d-63            [-1, 512, 8, 8]       2,359,296
      BatchNorm2d-64            [-1, 512, 8, 8]           1,024
             ReLU-65            [-1, 512, 8, 8]               0
       BasicBlock-66            [-1, 512, 8, 8]               0
AdaptiveAvgPool2d-67            [-1, 512, 1, 1]               0
           Linear-68                   [-1, 10]           5,130
================================================================
Total params: 11,181,642
Trainable params: 11,181,642
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.72
Forward/backward pass size (MB): 79.96
Params size (MB): 42.65
Estimated Total Size (MB): 123.33
----------------------------------------------------------------

Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:11: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  # This is added back by InteractiveShellApp.init_path()
100%
110/110 [02:22<00:00, 1.29s/it]
[1,     5] loss: 1.004
[1,    10] loss: 0.989
[1,    15] loss: 1.038
[1,    20] loss: 1.116
[1,    25] loss: 0.995
[1,    30] loss: 1.124
[1,    35] loss: 1.062
[1,    40] loss: 1.014
[1,    45] loss: 1.051
[1,    50] loss: 1.070
[1,    55] loss: 1.110
[1,    60] loss: 1.111
[1,    65] loss: 1.062
[1,    70] loss: 1.046
[1,    75] loss: 0.949
[1,    80] loss: 1.102
[1,    85] loss: 1.110
[1,    90] loss: 1.052
[1,    95] loss: 1.062
[1,   100] loss: 1.101
[1,   105] loss: 1.052
[1,   110] loss: 1.104

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:46: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:33<00:00, 3.76it/s]
[1,     5] loss: 1.672
[1,    10] loss: 1.522
[1,    15] loss: 1.542
[1,    20] loss: 1.718
[1,    25] loss: 1.719
[1,    30] loss: 1.919
[1,    35] loss: 1.646
[1,    40] loss: 1.772
[1,    45] loss: 1.529
[1,    50] loss: 1.807
[1,    55] loss: 1.930
[1,    60] loss: 1.819
[1,    65] loss: 1.581
[1,    70] loss: 1.707
[1,    75] loss: 1.337
[1,    80] loss: 1.724
[1,    85] loss: 1.534
[1,    90] loss: 1.554
[1,    95] loss: 1.635
[1,   100] loss: 1.704
[1,   105] loss: 1.641
[1,   110] loss: 1.730
[1,   115] loss: 2.001
[1,   120] loss: 1.583
[1,   125] loss: 1.797

Test accuracy: 44%

Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:11: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  # This is added back by InteractiveShellApp.init_path()
100%
110/110 [02:58<00:00, 1.63s/it]
[2,     5] loss: 0.965
[2,    10] loss: 0.949
[2,    15] loss: 0.918
[2,    20] loss: 0.880
[2,    25] loss: 0.974
[2,    30] loss: 0.975
[2,    35] loss: 0.948
[2,    40] loss: 0.921
[2,    45] loss: 0.998
[2,    50] loss: 0.963
[2,    55] loss: 1.121
[2,    60] loss: 1.192
[2,    65] loss: 1.216
[2,    70] loss: 1.082
[2,    75] loss: 1.026
[2,    80] loss: 0.938
[2,    85] loss: 0.977
[2,    90] loss: 1.014
[2,    95] loss: 1.089
[2,   100] loss: 0.931
[2,   105] loss: 0.896
[2,   110] loss: 0.993

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:46: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:32<00:00, 3.94it/s]
[2,     5] loss: 1.384
[2,    10] loss: 1.782
[2,    15] loss: 1.613
[2,    20] loss: 1.697
[2,    25] loss: 1.582
[2,    30] loss: 2.068
[2,    35] loss: 1.756
[2,    40] loss: 1.860
[2,    45] loss: 1.565
[2,    50] loss: 1.715
[2,    55] loss: 1.686
[2,    60] loss: 1.993
[2,    65] loss: 1.728
[2,    70] loss: 1.850
[2,    75] loss: 2.001
[2,    80] loss: 1.840
[2,    85] loss: 1.799
[2,    90] loss: 1.753
[2,    95] loss: 1.800
[2,   100] loss: 1.871
[2,   105] loss: 1.442
[2,   110] loss: 2.007
[2,   115] loss: 1.561
[2,   120] loss: 1.550
[2,   125] loss: 1.984

Test accuracy: 44%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:11: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  # This is added back by InteractiveShellApp.init_path()
100%
110/110 [02:09<00:00, 1.18s/it]
[3,     5] loss: 0.842
[3,    10] loss: 0.828
[3,    15] loss: 0.942
[3,    20] loss: 0.918
[3,    25] loss: 0.847
[3,    30] loss: 0.959
[3,    35] loss: 0.870
[3,    40] loss: 0.832
[3,    45] loss: 0.814
[3,    50] loss: 0.920
[3,    55] loss: 0.899
[3,    60] loss: 0.936
[3,    65] loss: 0.977
[3,    70] loss: 0.990
[3,    75] loss: 0.944
[3,    80] loss: 1.043
[3,    85] loss: 1.025
[3,    90] loss: 0.945
[3,    95] loss: 0.814
[3,   100] loss: 0.981
[3,   105] loss: 0.941
[3,   110] loss: 1.131

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:46: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:26<00:00, 4.80it/s]
[3,     5] loss: 1.702
[3,    10] loss: 1.791
[3,    15] loss: 1.737
[3,    20] loss: 1.823
[3,    25] loss: 1.699
[3,    30] loss: 1.912
[3,    35] loss: 1.348
[3,    40] loss: 1.816
[3,    45] loss: 1.576
[3,    50] loss: 1.428
[3,    55] loss: 1.645
[3,    60] loss: 1.634
[3,    65] loss: 1.710
[3,    70] loss: 1.532
[3,    75] loss: 1.474
[3,    80] loss: 1.638
[3,    85] loss: 1.831
[3,    90] loss: 1.330
[3,    95] loss: 1.645
[3,   100] loss: 1.675
[3,   105] loss: 1.617
[3,   110] loss: 1.380
[3,   115] loss: 1.805
[3,   120] loss: 1.772
[3,   125] loss: 1.486

Test accuracy: 45%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:11: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  # This is added back by InteractiveShellApp.init_path()
100%
110/110 [02:43<00:00, 1.49s/it]
[4,     5] loss: 0.814
[4,    10] loss: 0.770
[4,    15] loss: 0.806
[4,    20] loss: 0.778
[4,    25] loss: 0.743
[4,    30] loss: 0.760
[4,    35] loss: 0.809
[4,    40] loss: 0.865
[4,    45] loss: 0.829
[4,    50] loss: 0.753
[4,    55] loss: 0.849
[4,    60] loss: 0.756
[4,    65] loss: 0.861
[4,    70] loss: 0.853
[4,    75] loss: 0.782
[4,    80] loss: 0.840
[4,    85] loss: 0.882
[4,    90] loss: 0.888
[4,    95] loss: 0.892
[4,   100] loss: 0.748
[4,   105] loss: 1.047
[4,   110] loss: 0.903

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:46: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:49<00:00, 2.59it/s]
[4,     5] loss: 1.623
[4,    10] loss: 1.813
[4,    15] loss: 1.687
[4,    20] loss: 2.127
[4,    25] loss: 1.898
[4,    30] loss: 1.744
[4,    35] loss: 2.044
[4,    40] loss: 1.591
[4,    45] loss: 2.071
[4,    50] loss: 1.766
[4,    55] loss: 1.873
[4,    60] loss: 1.491
[4,    65] loss: 1.643
[4,    70] loss: 1.679
[4,    75] loss: 1.972
[4,    80] loss: 1.584
[4,    85] loss: 1.557
[4,    90] loss: 1.748
[4,    95] loss: 1.857
[4,   100] loss: 1.407
[4,   105] loss: 1.951
[4,   110] loss: 1.613
[4,   115] loss: 1.810
[4,   120] loss: 1.915
[4,   125] loss: 1.860

Test accuracy: 46%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:11: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  # This is added back by InteractiveShellApp.init_path()
100%
110/110 [02:51<00:00, 1.56s/it]
[5,     5] loss: 0.808
[5,    10] loss: 0.754
[5,    15] loss: 0.654
[5,    20] loss: 0.791
[5,    25] loss: 0.787
[5,    30] loss: 0.698
[5,    35] loss: 0.644
[5,    40] loss: 0.730
[5,    45] loss: 0.711
[5,    50] loss: 0.765
[5,    55] loss: 0.822
[5,    60] loss: 0.676
[5,    65] loss: 0.705
[5,    70] loss: 0.801
[5,    75] loss: 0.677
[5,    80] loss: 0.683
[5,    85] loss: 0.703
[5,    90] loss: 0.829
[5,    95] loss: 0.840
[5,   100] loss: 0.748
[5,   105] loss: 0.752
[5,   110] loss: 0.795

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:46: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:28<00:00, 4.45it/s]
[5,     5] loss: 1.569
[5,    10] loss: 2.198
[5,    15] loss: 1.777
[5,    20] loss: 2.119
[5,    25] loss: 1.609
[5,    30] loss: 2.320
[5,    35] loss: 1.804
[5,    40] loss: 2.303
[5,    45] loss: 1.490
[5,    50] loss: 1.690
[5,    55] loss: 2.169
[5,    60] loss: 1.835
[5,    65] loss: 1.662
[5,    70] loss: 2.155
[5,    75] loss: 2.087
[5,    80] loss: 2.205
[5,    85] loss: 1.548
[5,    90] loss: 2.046
[5,    95] loss: 1.695
[5,   100] loss: 2.041
[5,   105] loss: 1.595
[5,   110] loss: 1.543
[5,   115] loss: 1.832
[5,   120] loss: 1.918
[5,   125] loss: 1.934

Test accuracy: 46%