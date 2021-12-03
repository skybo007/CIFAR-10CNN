README Lab 8

Name: Prentiss BEam
Class: EE-104

CIFAR-10 datset CNN
to insta enter in command prompt: python -m  pip install (name of library)

import tensorflow as tf
from tensorflow.keras import datasets, layers, models, optimizers
from tensorflow.keras.layers import RandomFlip, RandomRotation, RandomZoom, Rescaling
from tensorflow.keras.optimizers import Adam, SGD, RMSprop
import keras
from tensorflow.keras import preprocessing
from keras.callbacks import LearningRateScheduler
import matplotlib.pyplot as plt

resources:
https://www.tensorflow.org/
https://keras.io/