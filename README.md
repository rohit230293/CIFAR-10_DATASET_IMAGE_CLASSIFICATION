# CIFAR-10_DATASET_IMAGE_CLASSIFICATION
In this project, we'll classify images from the CIFAR-10 dataset (https://www.cs.toronto.edu/~kriz/cifar.html). 

The dataset consists of airplanes, dogs, cats, and other objects.We'll preprocess the images, then train a convolutional neural network on all the samples. The images need to be normalized and the labels need to be one-hot encoded. We'll build a convolutional, max pooling, dropout, and fully connected layers. At the end, we'll get to see your neural network's predictions on the sample images.

# About the Data
CIFAR-10 is an established computer-vision dataset used for object recognition. It is a subset of the
80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10
object classes, with 6000 images per class. 

The dataset is broken into batches to prevent your machine from running out of memory. The
CIFAR-10 dataset consists of 5 batches, named data_batch_1, data_batch_2, etc.. Each batch
contains the labels and images that are one of the following:
*airplane
automobile
bird
cat
deer
dog
frog
horse
ship
truck
Understanding a dataset is part of making predictions on the data.

