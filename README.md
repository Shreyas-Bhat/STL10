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
