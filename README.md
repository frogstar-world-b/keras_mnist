
# Deep Neural Network with Keras 

Grayscale images (28 × 28 pixels) of handwritten digits are classified into their 10 categories (0 through 9). The infamous `mNIST` dataset is used. It's a set of 60,000 training images, plus 10,000 test images, along with all their lables. The set was assembled by the National Institute of Standards and Technology (the NIST in MNIST) in the 1980s. 

As you will see in the code, training a neural network revolves around the following objects:
- Layers, which are combined into a network (or model)
- The input data and corresponding targets
- The loss function, which defines the feedback signal used for learning
- The optimizer, which determines how learning proceeds

The NN is built by stacking two `Dense` layers on top of each other.

**Reference**: Deep Learning with Python by FRANÇOIS CHOLLET

**Technical note **: Code was run with Python 3.6 and on MacBook Pro / macOS Mojave Version 10.14.
