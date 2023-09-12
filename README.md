# ResNet - 50

This repo is inspired from the ResNet algorithm from He et al. (2015).

* Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun - [Deep Residual Learning for Image Recognition (2015)](https://arxiv.org/abs/1512.03385)


The model is 50 layers of convolutional layer trained on the SIGNS dataset. The model has 99% accuracy in the training set and 91% accuracy in the dev/test set.
You can use this pretrained model and finetune it by changing the last Softmax layer or even adding some Fully Connected Layers for your image classification problem.

## Model Architecture
The ResNet - 50 model architecture:

![ResNet - 50 Architecture](images/ResNet_Arcitecture.png?raw=true "ResNet - 50 Architecture")

## Dataset
The SIGNS dataset used in training and testing the model:


![SIGNS dataset](images/signs_data.png?raw=true "SIGNS dataset")

## Setup
1. Clone this repository
```shell
git clone https://github.com/abel-shimeles/ResNet-50.git
cd ResNet-50
```
2. Run the [ResNet-50](ResNet - 50.ipynb) file.
