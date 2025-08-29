# Building simple CNN model using Tensorflow

1. Conv2D with a kernel size of (3,3), and ReLU activation function.
2. MaxPooling2D Layer with a kernel size of (2,2).
3. Conv2D with a kernel size of (3,3), and ReLU activation function..
4. MaxPooling2D Layer with a kernel size of (2,2).
5. Additional layers: Conv2d, AveragePooling2D, Batch Normalization, ...
6. FullyConnected Layer with input size of 512 and output size of 256 and ReLU activation function.
7. FullyConnected Layer with input size of 256 and output size of number of classes and Softmax activation function.

# Training

Loss: [CategoricalCrossentropy](https://www.tensorflow.org/api_docs/python/tf/keras/losses/CategoricalCrossentropy)

Optimizer: [Adam](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adam)

# Dataset
[Link Dataset](https://www.kaggle.com/datasets/mauriciofigueiredo/amazon-fruits-small)
