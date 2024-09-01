# Handwritten-Digit-Recognition

The goal of handwritten digit recognition is to determine what digit is from an image of a single handwritten digit. It can be used to test pattern recognition theories and machine learning algorithms, Deep learning algorithms. Preprocessed standard handwritten digit image database has been developed to compare different digit recognizers. We used modified National Institute of Standards and Technology (MNIST) handwritten digit images dataset.

# Requirements

* Keras
* Sklearn
* Python 3.5
* Numpy
* Matplotlib

**1.** Download the four MNIST dataset files from this link:

```
http://yann.lecun.com/exdb/mnist/
train-images-idx3-ubyte
train-labels-idx1-ubyte
t10k-images-idx3-ubyte
t10k-labels-idx1-ubyte

```

## Accuracy using Machine Learning Algorithms:

i)	 K Nearest Neighbors: 95.57%

ii)	 Random Forest Classifier:	97.71%

iii) Support Vector Machine:	96.62%


## Accuracy using Deep Neural Networks:

i)	Three Layer Convolutional Neural Network using Keras:	99.57%
