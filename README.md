# S7EVA4
Session 7 CIFAR + Advanced Convolutions
### Model Used: 
      
```
    from RekogNizer import basemodelclass.CIFARModelDepthDilate
    ----------------------------------------------------------------
            Layer (type)               Output Shape         Param #
    ================================================================
                Conv2d-1           [-1, 32, 32, 32]             864
           BatchNorm2d-2           [-1, 32, 32, 32]              64
                  ReLU-3           [-1, 32, 32, 32]               0
               Dropout-4           [-1, 32, 32, 32]               0
                Conv2d-5           [-1, 32, 32, 32]             288
                Conv2d-6           [-1, 32, 32, 32]           1,024
           BatchNorm2d-7           [-1, 32, 32, 32]              64
                  ReLU-8           [-1, 32, 32, 32]               0
             MaxPool2d-9           [-1, 32, 16, 16]               0
              Dropout-10           [-1, 32, 16, 16]               0
               Conv2d-11           [-1, 64, 16, 16]          18,432
          BatchNorm2d-12           [-1, 64, 16, 16]             128
                 ReLU-13           [-1, 64, 16, 16]               0
              Dropout-14           [-1, 64, 16, 16]               0
               Conv2d-15           [-1, 64, 16, 16]             576
               Conv2d-16           [-1, 64, 16, 16]           4,096
          BatchNorm2d-17           [-1, 64, 16, 16]             128
                 ReLU-18           [-1, 64, 16, 16]               0
            MaxPool2d-19             [-1, 64, 8, 8]               0
              Dropout-20             [-1, 64, 8, 8]               0
               Conv2d-21            [-1, 128, 6, 6]          73,728
          BatchNorm2d-22            [-1, 128, 6, 6]             256
                 ReLU-23            [-1, 128, 6, 6]               0
              Dropout-24            [-1, 128, 6, 6]               0
               Conv2d-25            [-1, 128, 4, 4]           1,152
               Conv2d-26            [-1, 128, 4, 4]          16,384
          BatchNorm2d-27            [-1, 128, 4, 4]             256
                 ReLU-28            [-1, 128, 4, 4]               0
            MaxPool2d-29            [-1, 128, 2, 2]               0
              Dropout-30            [-1, 128, 2, 2]               0
                Conv2d-31            [-1, 256, 2, 2]         294,912
          BatchNorm2d-32            [-1, 256, 2, 2]             512
                 ReLU-33            [-1, 256, 2, 2]               0
              Dropout-34            [-1, 256, 2, 2]               0
               Conv2d-35            [-1, 256, 2, 2]          18,432
               Conv2d-36            [-1, 256, 2, 2]          65,536
          BatchNorm2d-37            [-1, 256, 2, 2]             512
                 ReLU-38            [-1, 256, 2, 2]               0
              Dropout-39            [-1, 256, 2, 2]               0
    AdaptiveAvgPool2d-40            [-1, 256, 1, 1]               0
               Conv2d-41             [-1, 10, 1, 1]           2,560
    ================================================================
    Total params: 499,904
    Trainable params: 499,904
    Non-trainable params: 0
    ----------------------------------------------------------------
    Input size (MB): 0.01
    Forward/backward pass size (MB): 3.47
    Params size (MB): 1.91
    Estimated Total Size (MB): 5.39
    ----------------------------------------------------------------
```
