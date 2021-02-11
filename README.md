# Landscape Classification Using Neural Networks

#### -- Project Status: [Completed]

## Project Intro/Objective
Image recognition is a driving force behind many of today's AI advancements. It has grown so effective because it uses deep learning in order to recognize visual elements and identify patterns. The purpose of this project is to use deep learning in order to train a neural network to classify different types of landscape within images. I first did this by building my own Convolutional Neural Network. Then, I used transfer learning with the ResNet50V2 architecture to improve on those results.


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
The training dataset contained approximately 14,000 images belonging to 6 classes: buildings, forest, glacier, mountain, sea, street. For this project, my goal was to gain a better understanding of how I can use neural networks for image classification tasks. I used the ImageDataGenerator to augment my data in order to avoid overfitting. I started out by building my own CNN architecture and achieved 81% val_accuracy. After that, I used transfer learning with the ResNet50V2 architecture to achieve 86.3% val_accuracy.

### Dataset Location
The Raw Data can be found [here](https://www.kaggle.com/puneet6060/intel-image-classification)

## Featured Notebooks/Analysis/Deliverables
* [Notebook](https://github.com/lukemonington/landscape_classification/blob/main/main.ipynb)


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
