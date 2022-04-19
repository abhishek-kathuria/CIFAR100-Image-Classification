# CSC 421 Course Project 

### CIFAR 100 Image Classification using Deep Learning
This repository contains the code for implementation of CIFAR-100 classification using various models such as Linear Classifier, Convolutional Neural Net (CNNs) from scratch, Residual Neural Nets (ResNet) from scratch, Pretrained ResNet-18 and Pretrained ResNet-50. 

## Requirements and How to use
The following are the basic requirements needed:
* Anaconda
* Pytorch <br>

For Executing the code directly from the Github Repo:
* Download the repo (make sure you have fulfilled the requirements)
* You can either run the code on python 3.6 or on the Google Colab GPU.
* The Dataset will be automatically downloaded from the torchvision.datasets.CIFAR100 library
  
## Files
The usage of the following python files is given as follows:
* **Linear_Classifier** contains an Artificial Neural Net with two hidden layers. 
* **CNN** contains a four layered CNN built from scratch.
* **RESNET** contains a custom ResNet with two residual blocks.
* **PRETRAINED_RESNET** contains pretrained ResNet-18 and ResNet-50 architectures fine tuned on the given dataset.

## Key Learnings
Through this project, I have learned the following:
* Building an ANN and a Convolutional NN from scratch.
* Build custom ResNet architectures from scratch.
* Pretraining and transfer learning.
* Identifying the maximum learning rate.
* Learning Schedulers such as OneCycleLR and CosineAnnealingLR and their needs.
* Usage of different optimizers such as SGD and ADAM.
* Various Data Augmentation techniques such as random crop, random split and random rotate.
* Regularization methods such as L1 and L2 regularization, dropout, and early stopping.
