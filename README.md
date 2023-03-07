# ultrasound-nerve-segmentation
This is an archive 

[ultrasound nerve segmentation challange](https://www.kaggle.com/c/ultrasound-nerve-segmentation) 


# Performance
This network was finaly get .69196/.70452 accuracy on the test set. 

Basic Param:
| Param | Model 1 | Model 2|
|:----|:----:|:----:|
|  Acti-Func | con-relu | con-elu | 
|  Res-block | 1 | 1 | 
|  Batch-Norm | true | true | 
|  Gate | true | true | 
|  Steps | 80079 | 183039 | 

Optimize:

| Param | Model 1 | Model 2|
|:----|:----:|:----:|
|  Rein method | 3 | 3 | 
|  Resize | to 1/4 | to 1/4 | 
|  RLenc Drop| < 3000 | < 3600  | 
|  Len Drop | < 560 |  >1600 | 
|  Optimize | > 1650 | >1500 | 

Kaggle Score:
| Score | Model 1 | Model 2|
|:----|:----:|:----:|
|  Private  | .70452 | .70443 | 
|  Public  | .69196 | .69185 | 


# References
[https://github.com/loliverhennigh/ultrasound-nerve-segmentation-in-tensorflow](https://github.com/loliverhennigh/ultrasound-nerve-segmentation-in-tensorflow)


[https://github.com/jocicmarko/ultrasound-nerve-segmentation](https://github.com/jocicmarko/ultrasound-nerve-segmentation)


[https://github.com/EdwardTyantov/ultrasound-nerve-segmentation](https://github.com/EdwardTyantov/ultrasound-nerve-segmentation)


