
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1          [-1, 6, 196, 196]             456
       BatchNorm2d-2          [-1, 6, 196, 196]              12
            Conv2d-3          [-1, 3, 194, 194]             165
         MaxPool2d-4            [-1, 3, 97, 97]               0
            Linear-5                 [-1, 2048]      57,810,944
           Dropout-6                 [-1, 2048]               0
            Linear-7                  [-1, 256]         524,544
       BatchNorm1d-8                  [-1, 256]             512
            Linear-9                   [-1, 10]           2,570
================================================================
Total params: 58,339,203
Trainable params: 58,339,203
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.46
Forward/backward pass size (MB): 4.63
Params size (MB): 222.55
Estimated Total Size (MB): 227.63
----------------------------------------------------------------

Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [01:40<00:00, 1.42it/s]
[1,     5] loss: 3.386
[1,    10] loss: 2.372
[1,    15] loss: 2.226
[1,    20] loss: 2.239
[1,    25] loss: 2.179
[1,    30] loss: 2.171
[1,    35] loss: 2.125
[1,    40] loss: 2.121
[1,    45] loss: 2.110
[1,    50] loss: 2.153
[1,    55] loss: 2.024
[1,    60] loss: 2.084
[1,    65] loss: 2.123
[1,    70] loss: 2.113
[1,    75] loss: 2.118
[1,    80] loss: 2.129
[1,    85] loss: 2.098
[1,    90] loss: 2.104
[1,    95] loss: 2.159
[1,   100] loss: 2.132
[1,   105] loss: 2.034
[1,   110] loss: 2.039
[1,   115] loss: 2.058
[1,   120] loss: 2.039
[1,   125] loss: 2.098
[1,   130] loss: 2.081
[1,   135] loss: 2.079
[1,   140] loss: 2.054

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:16<00:00, 7.77it/s]
[1,     5] loss: 2.202
[1,    10] loss: 2.264
[1,    15] loss: 2.282
[1,    20] loss: 2.352
[1,    25] loss: 2.281
[1,    30] loss: 2.198
[1,    35] loss: 2.165
[1,    40] loss: 2.263
[1,    45] loss: 2.227
[1,    50] loss: 2.324
[1,    55] loss: 2.304
[1,    60] loss: 2.209
[1,    65] loss: 2.282
[1,    70] loss: 2.233
[1,    75] loss: 2.275
[1,    80] loss: 2.268
[1,    85] loss: 2.241
[1,    90] loss: 2.191
[1,    95] loss: 2.244
[1,   100] loss: 2.251
[1,   105] loss: 2.233
[1,   110] loss: 2.269
[1,   115] loss: 2.298
[1,   120] loss: 2.265
[1,   125] loss: 2.321

Test accuracy: 16%

Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [06:53<00:00, 2.91s/it]
[2,     5] loss: 2.213
[2,    10] loss: 2.052
[2,    15] loss: 2.071
[2,    20] loss: 2.070
[2,    25] loss: 2.024
[2,    30] loss: 1.943
[2,    35] loss: 1.997
[2,    40] loss: 2.007
[2,    45] loss: 1.977
[2,    50] loss: 2.063
[2,    55] loss: 2.003
[2,    60] loss: 1.972
[2,    65] loss: 1.969
[2,    70] loss: 2.168
[2,    75] loss: 1.980
[2,    80] loss: 2.020
[2,    85] loss: 1.995
[2,    90] loss: 1.993
[2,    95] loss: 1.896
[2,   100] loss: 2.000
[2,   105] loss: 1.960
[2,   110] loss: 1.960
[2,   115] loss: 1.971
[2,   120] loss: 1.992
[2,   125] loss: 2.004
[2,   130] loss: 1.989
[2,   135] loss: 1.946
[2,   140] loss: 1.999

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [05:37<00:00, 2.66s/it]
[2,     5] loss: 2.261
[2,    10] loss: 2.177
[2,    15] loss: 2.212
[2,    20] loss: 2.127
[2,    25] loss: 2.217
[2,    30] loss: 2.203
[2,    35] loss: 2.150
[2,    40] loss: 2.219
[2,    45] loss: 2.104
[2,    50] loss: 2.221
[2,    55] loss: 2.244
[2,    60] loss: 2.204
[2,    65] loss: 2.173
[2,    70] loss: 2.250
[2,    75] loss: 2.260
[2,    80] loss: 2.180
[2,    85] loss: 2.132
[2,    90] loss: 2.118
[2,    95] loss: 2.143
[2,   100] loss: 2.162
[2,   105] loss: 2.136
[2,   110] loss: 2.168
[2,   115] loss: 2.188
[2,   120] loss: 2.226
[2,   125] loss: 2.147

Test accuracy: 19%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [05:21<00:00, 2.27s/it]
[3,     5] loss: 1.870
[3,    10] loss: 1.824
[3,    15] loss: 1.759
[3,    20] loss: 1.965
[3,    25] loss: 1.946
[3,    30] loss: 1.944
[3,    35] loss: 1.869
[3,    40] loss: 1.884
[3,    45] loss: 1.822
[3,    50] loss: 1.932
[3,    55] loss: 1.905
[3,    60] loss: 1.863
[3,    65] loss: 1.823
[3,    70] loss: 1.853
[3,    75] loss: 1.944
[3,    80] loss: 1.805
[3,    85] loss: 1.877
[3,    90] loss: 1.808
[3,    95] loss: 1.796
[3,   100] loss: 1.888
[3,   105] loss: 1.817
[3,   110] loss: 1.879
[3,   115] loss: 1.890
[3,   120] loss: 1.831
[3,   125] loss: 1.952
[3,   130] loss: 1.849
[3,   135] loss: 1.803
[3,   140] loss: 1.840

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [04:05<00:00, 1.93s/it]
[3,     5] loss: 2.220
[3,    10] loss: 2.205
[3,    15] loss: 2.266
[3,    20] loss: 2.201
[3,    25] loss: 2.222
[3,    30] loss: 2.131
[3,    35] loss: 2.175
[3,    40] loss: 2.226
[3,    45] loss: 2.173
[3,    50] loss: 2.228
[3,    55] loss: 2.291
[3,    60] loss: 2.168
[3,    65] loss: 2.182
[3,    70] loss: 2.195
[3,    75] loss: 2.183
[3,    80] loss: 2.120
[3,    85] loss: 2.133
[3,    90] loss: 2.156
[3,    95] loss: 2.222
[3,   100] loss: 2.266
[3,   105] loss: 2.213
[3,   110] loss: 2.141
[3,   115] loss: 2.186
[3,   120] loss: 2.140
[3,   125] loss: 2.181

Test accuracy: 15%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [03:49<00:00, 1.61s/it]
[4,     5] loss: 1.771
[4,    10] loss: 1.774
[4,    15] loss: 1.563
[4,    20] loss: 1.680
[4,    25] loss: 1.693
[4,    30] loss: 1.660
[4,    35] loss: 1.629
[4,    40] loss: 1.666
[4,    45] loss: 1.590
[4,    50] loss: 1.597
[4,    55] loss: 1.618
[4,    60] loss: 1.612
[4,    65] loss: 1.757
[4,    70] loss: 1.664
[4,    75] loss: 1.588
[4,    80] loss: 1.598
[4,    85] loss: 1.565
[4,    90] loss: 1.686
[4,    95] loss: 1.638
[4,   100] loss: 1.728
[4,   105] loss: 1.494
[4,   110] loss: 1.597
[4,   115] loss: 1.701
[4,   120] loss: 1.620
[4,   125] loss: 1.739
[4,   130] loss: 1.683
[4,   135] loss: 1.697
[4,   140] loss: 1.682

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [02:29<00:00, 1.18s/it]
[4,     5] loss: 2.282
[4,    10] loss: 2.131
[4,    15] loss: 2.260
[4,    20] loss: 2.301
[4,    25] loss: 2.229
[4,    30] loss: 2.253
[4,    35] loss: 2.222
[4,    40] loss: 2.302
[4,    45] loss: 2.208
[4,    50] loss: 2.256
[4,    55] loss: 2.192
[4,    60] loss: 2.132
[4,    65] loss: 2.210
[4,    70] loss: 2.231
[4,    75] loss: 2.181
[4,    80] loss: 2.269
[4,    85] loss: 2.231
[4,    90] loss: 2.219
[4,    95] loss: 2.160
[4,   100] loss: 2.171
[4,   105] loss: 2.323
[4,   110] loss: 2.273
[4,   115] loss: 2.305
[4,   120] loss: 2.193
[4,   125] loss: 2.160

Test accuracy: 14%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [02:13<00:00, 1.07it/s]
[5,     5] loss: 1.507
[5,    10] loss: 1.403
[5,    15] loss: 1.418
[5,    20] loss: 1.404
[5,    25] loss: 1.378
[5,    30] loss: 1.232
[5,    35] loss: 1.259
[5,    40] loss: 1.432
[5,    45] loss: 1.281
[5,    50] loss: 1.216
[5,    55] loss: 1.183
[5,    60] loss: 1.286
[5,    65] loss: 1.322
[5,    70] loss: 1.362
[5,    75] loss: 1.395
[5,    80] loss: 1.314
[5,    85] loss: 1.449
[5,    90] loss: 1.263
[5,    95] loss: 1.413
[5,   100] loss: 1.297
[5,   105] loss: 1.293
[5,   110] loss: 1.258
[5,   115] loss: 1.298
[5,   120] loss: 1.263
[5,   125] loss: 1.304
[5,   130] loss: 1.291
[5,   135] loss: 1.308
[5,   140] loss: 1.397

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [00:57<00:00, 2.21it/s]
[5,     5] loss: 2.535
[5,    10] loss: 2.625
[5,    15] loss: 2.466
[5,    20] loss: 2.864
[5,    25] loss: 2.670
[5,    30] loss: 2.349
[5,    35] loss: 2.416
[5,    40] loss: 2.519
[5,    45] loss: 2.562
[5,    50] loss: 2.677
[5,    55] loss: 2.620
[5,    60] loss: 2.454
[5,    65] loss: 2.588
[5,    70] loss: 2.774
[5,    75] loss: 2.546
[5,    80] loss: 2.567
[5,    85] loss: 2.692
[5,    90] loss: 2.595
[5,    95] loss: 2.665
[5,   100] loss: 2.486
[5,   105] loss: 2.609
[5,   110] loss: 2.607
[5,   115] loss: 2.580
[5,   120] loss: 2.504
[5,   125] loss: 2.580

Test accuracy: 12%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [01:13<00:00, 1.92it/s]
[6,     5] loss: 1.190
[6,    10] loss: 1.009
[6,    15] loss: 0.942
[6,    20] loss: 0.966
[6,    25] loss: 0.913
[6,    30] loss: 0.889
[6,    35] loss: 0.949
[6,    40] loss: 0.817
[6,    45] loss: 0.911
[6,    50] loss: 0.777
[6,    55] loss: 1.026
[6,    60] loss: 0.852
[6,    65] loss: 1.040
[6,    70] loss: 0.903
[6,    75] loss: 0.899
[6,    80] loss: 0.944
[6,    85] loss: 0.867
[6,    90] loss: 0.875
[6,    95] loss: 0.981
[6,   100] loss: 0.909
[6,   105] loss: 0.894
[6,   110] loss: 0.873
[6,   115] loss: 0.888
[6,   120] loss: 0.974
[6,   125] loss: 0.914
[6,   130] loss: 0.990
[6,   135] loss: 0.989
[6,   140] loss: 1.015

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [11:46<00:00, 5.56s/it]
[6,     5] loss: 2.481
[6,    10] loss: 2.476
[6,    15] loss: 2.540
[6,    20] loss: 2.398
[6,    25] loss: 2.734
[6,    30] loss: 2.349
[6,    35] loss: 2.763
[6,    40] loss: 2.394
[6,    45] loss: 2.550
[6,    50] loss: 2.426
[6,    55] loss: 2.331
[6,    60] loss: 2.447
[6,    65] loss: 2.680
[6,    70] loss: 2.548
[6,    75] loss: 2.518
[6,    80] loss: 2.582
[6,    85] loss: 2.516
[6,    90] loss: 2.530
[6,    95] loss: 2.554
[6,   100] loss: 2.600
[6,   105] loss: 2.409
[6,   110] loss: 2.566
[6,   115] loss: 2.397
[6,   120] loss: 2.550
[6,   125] loss: 2.701

Test accuracy: 11%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [11:29<00:00, 4.86s/it]
[7,     5] loss: 0.721
[7,    10] loss: 0.677
[7,    15] loss: 0.610
[7,    20] loss: 0.649
[7,    25] loss: 0.538
[7,    30] loss: 0.621
[7,    35] loss: 0.645
[7,    40] loss: 0.601
[7,    45] loss: 0.533
[7,    50] loss: 0.573
[7,    55] loss: 0.660
[7,    60] loss: 0.711
[7,    65] loss: 0.618
[7,    70] loss: 0.573
[7,    75] loss: 0.705
[7,    80] loss: 0.654
[7,    85] loss: 0.724
[7,    90] loss: 0.624
[7,    95] loss: 0.609
[7,   100] loss: 0.571
[7,   105] loss: 0.743
[7,   110] loss: 0.678
[7,   115] loss: 0.592
[7,   120] loss: 0.639
[7,   125] loss: 0.721
[7,   130] loss: 0.665
[7,   135] loss: 0.740
[7,   140] loss: 0.721

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [10:11<00:00, 4.82s/it]
[7,     5] loss: 2.650
[7,    10] loss: 2.756
[7,    15] loss: 2.445
[7,    20] loss: 2.662
[7,    25] loss: 2.642
[7,    30] loss: 2.755
[7,    35] loss: 2.446
[7,    40] loss: 2.741
[7,    45] loss: 2.549
[7,    50] loss: 2.748
[7,    55] loss: 2.540
[7,    60] loss: 2.609
[7,    65] loss: 2.460
[7,    70] loss: 2.494
[7,    75] loss: 2.659
[7,    80] loss: 2.777
[7,    85] loss: 2.524
[7,    90] loss: 2.720
[7,    95] loss: 2.680
[7,   100] loss: 2.474
[7,   105] loss: 2.734
[7,   110] loss: 2.656
[7,   115] loss: 2.738
[7,   120] loss: 2.631
[7,   125] loss: 2.795

Test accuracy: 12%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [09:54<00:00, 4.19s/it]
[8,     5] loss: 0.433
[8,    10] loss: 0.410
[8,    15] loss: 0.395
[8,    20] loss: 0.400
[8,    25] loss: 0.351
[8,    30] loss: 0.348
[8,    35] loss: 0.493
[8,    40] loss: 0.460
[8,    45] loss: 0.454
[8,    50] loss: 0.497
[8,    55] loss: 0.451
[8,    60] loss: 0.494
[8,    65] loss: 0.498
[8,    70] loss: 0.353
[8,    75] loss: 0.414
[8,    80] loss: 0.370
[8,    85] loss: 0.431
[8,    90] loss: 0.459
[8,    95] loss: 0.466
[8,   100] loss: 0.469
[8,   105] loss: 0.495
[8,   110] loss: 0.411
[8,   115] loss: 0.512
[8,   120] loss: 0.388
[8,   125] loss: 0.470
[8,   130] loss: 0.449
[8,   135] loss: 0.521
[8,   140] loss: 0.398

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [08:37<00:00, 4.07s/it]
[8,     5] loss: 2.621
[8,    10] loss: 3.142
[8,    15] loss: 2.906
[8,    20] loss: 2.543
[8,    25] loss: 2.920
[8,    30] loss: 2.701
[8,    35] loss: 2.781
[8,    40] loss: 2.889
[8,    45] loss: 2.674
[8,    50] loss: 2.861
[8,    55] loss: 2.803
[8,    60] loss: 2.748
[8,    65] loss: 2.811
[8,    70] loss: 2.794
[8,    75] loss: 2.830
[8,    80] loss: 2.689
[8,    85] loss: 2.978
[8,    90] loss: 2.753
[8,    95] loss: 2.747
[8,   100] loss: 2.764
[8,   105] loss: 2.702
[8,   110] loss: 2.889
[8,   115] loss: 2.614
[8,   120] loss: 2.896
[8,   125] loss: 2.739

Test accuracy: 13%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
100%
142/142 [01:21<00:00, 1.74it/s]
[9,     5] loss: 0.278
[9,    10] loss: 0.299
[9,    15] loss: 0.255
[9,    20] loss: 0.244
[9,    25] loss: 0.139
[9,    30] loss: 0.316
[9,    35] loss: 0.283
[9,    40] loss: 0.239
[9,    45] loss: 0.283
[9,    50] loss: 0.255
[9,    55] loss: 0.250
[9,    60] loss: 0.256
[9,    65] loss: 0.226
[9,    70] loss: 0.286
[9,    75] loss: 0.235
[9,    80] loss: 0.287
[9,    85] loss: 0.221
[9,    90] loss: 0.270
[9,    95] loss: 0.334
[9,   100] loss: 0.233
[9,   105] loss: 0.263
[9,   110] loss: 0.230
[9,   115] loss: 0.245
[9,   120] loss: 0.280
[9,   125] loss: 0.199
[9,   130] loss: 0.344
[9,   135] loss: 0.282
[9,   140] loss: 0.298

Starting testing
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:50: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
100%
127/127 [07:02<00:00, 3.32s/it]
[9,     5] loss: 2.572
[9,    10] loss: 2.812
[9,    15] loss: 2.508
[9,    20] loss: 2.630
[9,    25] loss: 2.694
[9,    30] loss: 2.714
[9,    35] loss: 2.594
[9,    40] loss: 2.804
[9,    45] loss: 2.795
[9,    50] loss: 2.703
[9,    55] loss: 2.645
[9,    60] loss: 2.928
[9,    65] loss: 2.865
[9,    70] loss: 2.675
[9,    75] loss: 2.590
[9,    80] loss: 2.874
[9,    85] loss: 2.523
[9,    90] loss: 2.669
[9,    95] loss: 2.864
[9,   100] loss: 2.613
[9,   105] loss: 2.475
[9,   110] loss: 2.733
[9,   115] loss: 2.554
[9,   120] loss: 2.668
[9,   125] loss: 2.721

Test accuracy: 11%
Training
/opt/anaconda3/envs/myenv2/lib/python3.7/site-packages/ipykernel_launcher.py:13: TqdmDeprecationWarning: This function will be removed in tqdm==5.0.0
Please use `tqdm.notebook.tqdm` instead of `tqdm.tqdm_notebook`
  del sys.path[0]
22%
31/142 [00:19<01:08, 1.63it/s]
[10,     5] loss: 0.125
[10,    10] loss: 0.166
[10,    15] loss: 0.230
[10,    20] loss: 0.193
[10,    25] loss: 0.151
[10,    30] loss: 0.156