# MNIST Recognizer with CNN for high accuracy

MNIST is a database containing images of handwritten digits, with each image labeled by integer. It is used to benchmark the performance of machine learning algorithms. Deep learning performs quite well on MNIST, achieving more than 99.7% accuracy.

## Purpose

- First try for Kaggle submission
- Training on Jupyter Notebook 
- Keras front-end experience (more friendly than TF)
- Review CNN for classification
- preparing for Video Segmentation

## Network Intro

- VGG-like Network with BN.
- Training with Dropout
- AdamGrad optimizer

----------------------------
## Dataset

[MNIST data](https://www.kaggle.com/c/digit-recognizer/data)

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

