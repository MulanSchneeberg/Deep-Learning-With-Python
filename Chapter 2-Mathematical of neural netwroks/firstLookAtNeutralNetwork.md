# A first look at a neural network

## The problem
The problem we’re trying to solve here is to classify grayscale images of handwritten digits (28 × 28 pixels) into their 10 categories (0 through 9). We’ll use the MNIST dataset, a classic in the machine learning community, which has been around almost as long as the field itself and has been intensively studied. It’s a set of 60,000 training images, plus 10,000 test images, assembled by the National Institute of Standards and Technology (the NIST in MNIST) in the 1980s.

![MNIST sample digits](./screenshots/MNIST.jpg)

## Step 1. Loading the MNIST datasets in keras
Check on the MINIST.ipynb file