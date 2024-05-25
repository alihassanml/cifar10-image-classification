# CIFAR-10 Image Classification with TensorFlow

This repository contains a Convolutional Neural Network (CNN) model built using TensorFlow and Keras for classifying images from the CIFAR-10 dataset. The model is trained to recognize 10 different classes of objects commonly found in images.

## Overview

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. The classes are mutually exclusive and contain objects like airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

This project demonstrates how to build, train, and evaluate a CNN model for image classification using TensorFlow and Keras.

## Model Architecture

The CNN model is defined using the `tf.keras.Sequential` API and consists of the following layers:

- **Conv2D**: 32 filters, 3x3 kernel, ReLU activation
- **MaxPooling2D**: 2x2 pool size
- **Conv2D**: 64 filters, 3x3 kernel, ReLU activation
- **MaxPooling2D**: 2x2 pool size
- **Conv2D**: 128 filters, 3x3 kernel, ReLU activation
- **Flatten**: Flatten the input
- **Dense**: 128 units, ReLU activation
- **BatchNormalization**: Batch normalization layer
- **Dropout**: 20% dropout rate
- **Dense**: 10 units, softmax activation (output layer)

## Dependencies

- Python 3.x
- TensorFlow
- Matplotlib

You can install the required libraries using pip:

```bash
pip install tensorflow matplotlib
```

## Usage

1. **Clone the repository**:

    ```bash
    git clone https://github.com/alihassanml/cifar10-image-classification.git
    cd cifar10-image-classification
    ```


## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Feel free to customize the README with any additional details specific to your project or repository structure.
