# MNIST_CNN_Handwritten_Digit_Recognition
A simple convolutional neural network (CNN) deployed on the MNIST dataset trained to recognize handwritten digits. The MNIST Dataset is available for download online, However I used the version that is incuded in the ``keras.datasets`` module.

Techonologies used:
- Keras
- matplotlib (for visualisation)
- Google Colab (utilised the cloud service for model training)

With 15 epochs of training, the model was able to achieve 99.7% accuracy:

![image](https://github.com/sgspencer2618/MNIST_CNN_Handwritten_Digit_Recognition/assets/144366072/90410538-b065-4548-8a3a-913cff0f76a2)

# Model Architecture:
- Input Layer: Convolutional layer (Conv2D) with 64 filters, output shape (None, 26, 26, 64), with 640 parameters.
- Hidden Layer 1: Flatten layer (Flatten) to transform the output into a vector, output shape (None, 43264).
- Hidden Layer 2: Dense layer (Dense) with 64 neurons, output shape (None, 64), with 2,768,960 parameters.
- Hidden Layer 3: Dense layer (Dense) with 64 neurons, output shape (None, 64), with 4,160 parameters.
- Output Layer: Dense layer (Dense) with 10 neurons (classification task with 10 classes), output shape (None, 10), with 650 parameters.

![image](https://github.com/sgspencer2618/MNIST_CNN_Handwritten_Digit_Recognition/assets/144366072/4c96fb57-dc11-4f1e-a1a0-e74b571afcbe)
