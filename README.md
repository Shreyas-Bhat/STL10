# STL10

* Performed different learning procedures on the STL10 dataset - supervised learning, semi-supervised learning and self-supervised learning

## Supervised Learning 
* Used ResNet-50 Architecture and got validation accuracy of 68.7
![image](https://user-images.githubusercontent.com/56354373/147820288-fe83a08b-62bc-4ba3-88b6-2a10c476df63.png)
![image](https://user-images.githubusercontent.com/56354373/147820297-5f38a357-ebdf-48e2-a6dd-1971ea3e2939.png)
![image](https://user-images.githubusercontent.com/56354373/147820300-aa912ce1-bb22-4e07-a9f4-a06ecd314f2b.png)

## Semi-Supervised Learning 
* Used Pseudo-Labeling method using the same encoder architecture as in supervised learning 

| Model         | Supervised Validation Accuracy         | Semi-Supervised Validation Accuracy   |  Change in Accuracy  |
| ------------- |:-------------:| -----:|                     ------:                                                                       |
| CNN Model     | 59.4          | 64.62 |  5.08                                                                         |
| ResNet-50 Model| 68.73        |   72  |  3.27                                                                         | 

## Self-Supervised Learning 

* For this I used the SimClr framework for contrastive learning and get a valiation accuracy of 53.30%
![68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d2d764834504b704539596f2f586f3461324259657276492f414141414141414146704d2f766146447750584f79416f6b4143385868383532447a4f67457332324e68625877434c634247417](https://user-images.githubusercontent.com/56354373/147820857-56e0cc92-9d23-434a-874a-bfd79cfe6183.gif)


## AutoAugment 
* I tried to implement semi-supervised tasks using SimClr and augment images using AutoAugment method. The operations we will be using are shearing, translating, rotation,
auto_contrasting, brightness, sharpness, cutout, etc., and the policies for each augmentation are selected randomly and applied in our dataset for producing image augmentations
