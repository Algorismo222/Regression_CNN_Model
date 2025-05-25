# Regression_CNN_Model

This is a simple implementation of a convolutional neural network CNN 
for evaluation of a scalar field (with n elements) and one single output
parameter. The network relies on supervised learning with training data
containing the predictor variable as label. After training the network
predicts a single output variable.

In its current format the training data contain in each row at the initial
position a normalized (0-1) label value and 13000 data points (variables).
The test data are organized similar. Currently the test dataset contains
20 samples and the training dataset contains 80 datasets.

The implementation was realized with Anaconda as package manager and a
Jupyter Notebook for coding. As code editor Visual-Studio-Code was
utilized. The implementation works with Python 3.9 or higher and 
relies on the following libraries:

import tensorflow as tf
from tensorflow.keras import datasets, layers, models

# Helper libraries
import numpy #as np
import matplotlib.pyplot as plt
