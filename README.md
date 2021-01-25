# Landscape Classification Using Neural Networks

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to learn about the implentation of CNN's for use with classifying 6 different types of landscape. 


### Methods Used
* Deep Learning
* Data Visualization
* Data Augmentation
* Transfer Learning
* 2D Convolutional layers
* MaxPooling layers
* Dense layers
* Dropout layers
* EarlyStopping callback

### Technologies
* Python
* TensorFlow
* pandas
* numpy
* matplotlib
* jupyter

## Project Description
The training dataset contained approximately 14,000 images belonging to 6 classes: buildings, forest, glacier, mountain, sea, street. For this project, my goal was to gain a better understanding of how I can use neural networks for image classification tasks. I used the ImageDataGenerator to augment my data in order to avoid overfitting. I started out by building my own NN architecture and achieved 81% val_accuracy. After that, I used transfer learning with the ResNet50V2 architecture to achieve 86.3% val_accuracy.

