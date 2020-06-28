# Handwritten-Digit-Recognition-MNIST
Recognizes handwritten digits using Keras and convnets

Model training is done using MNIST dataset.
The MNIST database of handwritten digits has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST.
It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data.

The original black and white (bilevel) images from NIST were size normalized to fit in a 20x20 pixel box while preserving their aspect ratio. The resulting images contain grey levels as a result of the anti-aliasing technique used by the normalization algorithm. the images were centered in a 28x28 image by computing the center of mass of the pixels, and translating the image so as to position this point at the center of the 28x28 field.

For more info on the dataset, please refer:
http://yann.lecun.com/exdb/mnist/

The model is finally tested on my own handwritten digit and its performing pretty well
