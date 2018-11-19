# Image-Classifier-Project-Pytorch-Deep-Learning-AI

In this project, we'll train an image classifier to recognize different species of flowers. We can imagine using something like this in a phone app that tells us the name of the flower our camera is looking at. In practice we'd train this classifier, then export it for use in our application. We'll be using a dataset of 102 flower categories available on the website of Oxford University.

Note: *This is part of the pytorch challenge offered by Udacity and Facebook*

## Prerequisites: 

In order to run this project, you will need the following packages: 

* Python 3.6 or higher
* Pytorch (Cuda version)
* Torchvision
* In order train your model, you will need to run this code on your GPU since your CPU will take very huge training time. 
* Data Set to be be downloaded from [this link ](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) or
* If you want to use the preprocessed version of the data, use [download it here](https://s3.amazonaws.com/content.udacity-data.com/nd089/flower_data.tar.gz)


## Hyperparamters: 

This project was trained on VGG19 with only two fully connected layers, the exact number of which can be found on the jupyter notebook file. In order to get an accuracy of 87%, you need to set your learning rate to 0.008 and run it for 10 epochs. 

## Authors: 
**Naseer Faheem** - Initial Work 
**Udacity / Facebook** - Final Lab work for the PyTorch Challenge 2018. 

