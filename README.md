![visitors](https://visitor-badge.laobi.icu/badge?page_id=github.com/tanmay-kalbande/Handwritten-Digits-Recognition&left_color=crimson&right_color=708090)
# <font color='blue'> MNIST Digit Recognition using Convolutional Neural Networks (CNNs)!</font>

This is a Convolutional Neural Network (CNN) model for classifying the MNIST dataset. The MNIST dataset consists of 70,000 images of handwritten digits, with 60,000 images in the training set and 10,000 images in the test set.

## Model Description

The model consists of multiple layers, including convolutional layers, max pooling layers, and fully connected layers. The input images are normalized and reshaped to include a channel dimension. The output layer has 10 units with softmax activation, representing the probability of each digit class.

The model is compiled with categorical cross-entropy loss and Adam optimizer. During training, the model is trained on the training set and validated on the test set. The performance of the model is evaluated based on the accuracy metric.

## Model Architecture

The CNN model has the following architecture:

- Convolutional layer with 32 filters, 3x3 kernel, and ReLU activation
- Max pooling layer with 2x2 pool size
- Dropout layer with 25% rate
- Convolutional layer with 64 filters, 3x3 kernel, and ReLU activation
- Max pooling layer with 2x2 pool size
- Dropout layer with 25% rate
- Flatten layer to convert the output from convolutional layers to a 1D array
- Fully connected layer with 128 units and ReLU activation
- Dropout layer with 50% rate
- Output layer with 10 units and softmax activation

## Results

The model achieved a test accuracy of 99.31% after 20 epochs of training. The loss and accuracy were monitored during training and validation, and the model did not appear to overfit to the training set.

## Conclusion

This CNN model demonstrates strong performance on the MNIST dataset, achieving a high accuracy with a relatively simple architecture. With further tuning and optimization, it may be possible to improve the performance even further.
