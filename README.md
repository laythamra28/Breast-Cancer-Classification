# Breast Cancer Classification using PyTorch


## Project Description

The purpose of this project is to compare the metrics of 3 different neural network architectures on classifying segmented MRI scans of breast cancer patints that are healthy and sick. The whole process of data cleaning, preprocessing, traning the network, and testing the networks is done in this project. The 3 networks that were choosen are: AlexNet, VGG, and LeNet. The project was coded in Python using Google collab notebooks and Pytorch was used to create the neural networks. Hyperparamter tuning was also performed on the network with the best accruacy to explore the possibilty of increasing accuracy. This project provides a great framework for people thinking of doing a personal deep learning project.



## Dataset

The dataset was sourced from kaggle and consisted of greyscale 480x640 JPG images of  labeled MRI scans from breast cancer patients that are healthy and sick. 

Source:  https://www.kaggle.com/datasets/uzairkhan45/breast-cancer-patients-data

## Usage

1. Download the Raw Data and upload it to your google drive
2. Run Alex+Resnet+Preprocessing.ipynb from the start. The first part of this notebook performs the preprocessing steps needed.
3. After you preproccess raw data and split the data into training and testing data you can run any of the other notebooks attaining to the other networks.

## Results

Learning Curve of all networks(this also includes ResNet:

![alt text](https://github.com/laythamra28/Breast-Cancer-Classification/blob/main/Results/Learning-curves-All.png)

HyperParameter Tuning of LeNet 5:

![alt text](https://github.com/laythamra28/Breast-Cancer-Classification/blob/main/Results/Hyperparam-tuning.png)


