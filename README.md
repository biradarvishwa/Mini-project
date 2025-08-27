This notebook implements a convolutional neural network (CNN) for handwritten digit recognition on MNIST dataset images resized to 128x128 pixels. The key parts of the notebook are:

Importing TensorFlow/Keras and image processing libraries.

Loading MNIST digits and resizing them from 28x28 to 128x128.

Preprocessing data by normalizing pixels and one-hot encoding labels.

Visualizing sample training images.

Building a CNN model with two convolutional layers, max pooling, dropout, and dense layers.

Training the model for 5 epochs with batch size 64 and 20% validation split.

Saving the trained model as mnist_cnn_128x128_model.h5.

Evaluating test accuracy around 98.5% and printing a classification report.

Plotting training/validation accuracy and loss curves.

Displaying a confusion matrix and sample predictions visually.

The model achieves strong performance on enlarged MNIST dataset images, demonstrating effective CNN training and digit classification.
