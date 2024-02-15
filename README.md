# Fashion Class Classification

Fashion Class Classification based on convolutional neural network &amp; deep learning 

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

- t-shirt/top

- trouser

- pullover

- dress

- coat

- sandal

- shirt 

- sneaker

- bag

- ankle

- boot

## What's an image ?

A greyscale image is a system of 256 tones with values ranging from 0-255, 0 represents black and 255 represents white. Numbers in-between represents gerys between black and white. Binary sistem use digits '0' and '1' chere '00000000' for black and '11111111' for white (8-bit image).

Binary value of '11111111' is equal to decimal value of '255'

## Our Fashion Dataset 

Fashion dataset contains 28x28 greyscale image with values ranging from 0-255

'0' represents black and '255' represents white

Each image is represented by a row with 784 (i.e 28x28) values 