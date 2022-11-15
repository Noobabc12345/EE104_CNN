# EE104_CNN
Convolutional Neural Network
Name: Yichun Hsieh, Shunyu Chuang
Class: EE 104

Reference: Laboratory Assignment 7

About this lab: In this project, there are three parts, the first two are about using the Convolutional Neural Network to train the AI to recognize the images. The last one is the balloon flight python game.

1)CNN - Baseline + Increasing Dropout + Data Augmentation + Batch Normalization + Your own method
In part one, we should download the CIFAR10 dataset online, and import some packages as below:
import tensorflow as tf

from tensorflow.keras import datasets, layers, models
import matplotlib.pyplot as plt
import sys
from matplotlib import pyplot
from keras.datasets import cifar10
from keras.utils import to_categorical
from keras.models import Sequential
from keras.layers import Conv2D
from keras.layers import MaxPooling2D
from keras.layers import Dense
from keras.layers import Flatten
from keras.optimizers import SGD
from keras.preprocessing.image import ImageDataGenerator
from keras.layers import Dropout
from keras.layers import BatchNormalization
from keras.regularizers import l2
 
And this should run in google Colab, or your computer might feel too tired when doing the machine learning.

OR, you just run my code (because everything is set up already). But remember to change the Epoch to at least 90 to make the model accuracy over 87 percent.

2)CNN - Challenge test
This part is just based on the previous one. If you train it well, the test result will be perfecto.
If you want to test other pictures, just copy the URL and paste it into the code. After running it you will be surprised why the AI can recognize every 10 different pictures of objects. 
