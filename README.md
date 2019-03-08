# Face Generation using GAN
[![Build Status](https://travis-ci.org/pruthiviraj71/Face-Generation-GAN.svg?branch=master)](https://travis-ci.org/pruthiviraj71/Face-Generation-GAN)


Using Generative Adversarial Networks to generate novel and realistic human faces.

## Requirements

- Tensorflow
- GPU for training (or Google Colaboratory for training purposes)

## Implementation

We used 2 datasets for training the deep convolutional neural network MNIST and CelebA (much larger dataset). To build the neural network we implemented the following functions:
1. model_inputs
2. discriminator (to create a discriminator neural network that discriminates on images)
3. generator (to generate an image using z)
4. model_loss (for training and calculate the loss)
5. model_opt (to create the optimization operations for the GAN)
6. train

## Training Result

### MNIST
Result after 2 Epochs

![](https://github.com/pruthiviraj71/Face-Generation-GAN/blob/master/mnist.PNG)

### Celebrity Faces
Result after 1 Epoch

![](https://github.com/pruthiviraj71/Face-Generation-GAN/blob/master/face.PNG)
