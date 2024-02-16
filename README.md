# Fashion Class Classification

<img src="https://github.com/I2S9/Fashion-class-classification/assets/111307883/02fa2040-0de4-4072-96a0-a2572d874cbd" width="800">

**Fashion Class Classification** based on convolutional neural network &amp; deep learning 

The fashion industry is undergoing a dramatic transformation by adopting new computer vision and ML and deep learning techniques.

We're going to use the Fashion MNIST data that contains images like dress, bags and shoes

We want to build a model (based on deep learning & machine learning model) that look at an image and tell us what type of clothes

We can do target marketing to specific customer

**Objective** : build a classifier, build a kind of a deep learning network that can look at these images and can tell us the category of clothes

## MNIST Dataset

Our Dataset for fashion consists of 70.000 images (28x28 grayscale) with :

* 60.000 training

* 10.000 testing

In addition, we have at our disposal 10 target class : 

t-shirt/top - trouser - pullover - dress - coat - sandal - shirt - sneaker - bag - ankle - boot

## What's an image ?

<p align="center">
  <img src="https://github.com/I2S9/Fashion-class-classification/assets/111307883/87a21275-6617-4b8b-8fe6-5942da1871b8" width="900">
</p>

<p align="justify">
  A greyscale image is a system of 256 tones with values ranging from 0-255, 0 represents black and 255 represents white. Numbers in-between represents gerys between black and white. Binary sistem use digits '0' and '1' chere '00000000' for black and '11111111' for white (8-bit image).

  Binary value of '11111111' is equal to decimal value of '255'
</p>

<p align="center">
  <img src="https://github.com/I2S9/Fashion-class-classification/assets/111307883/7de8acae-e4ef-452a-8cd1-8b2b6f4c81cb" width="300">
</p>


## Our Fashion Dataset 

Fashion dataset contains 28x28 greyscale image with values ranging from 0-255

'0' represents black and '255' represents white

Each image is represented by a row with 784 (i.e 28x28) values 


## Artificial Neural Network basics

* The neuron collects signals from input channels named dendrites, processes information in its nucleus, and then generates an output in a long thin branch called the axon.

* Human learning occurs adaptively by varying the bond strength between these neurons.

## Convolutional neural network feature detector


* Convolutions use a kernel matrix to scan a given image and apply a filter to obtain a certain effect.

* An image Kernel is a matrix used to apply effects such as blurring and sharpening.

* Kernels are used in machine learning for _*feature extraction*_ to select most important pixels of an image.

* Convolution preserves the spatial relationship between pixels.
