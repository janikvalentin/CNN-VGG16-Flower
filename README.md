### Project Overview
This project is my contribution to the PyTorch Image Classifier Challenge.

Goal of the challenge was to build a CNN which can accurately predict the flower
species from images depicting 103 different flower categories.
The original dataset is hosted by the University of Oxford and can be found
[here](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html).

### Model specifications
My approach used transfer learning of the VGG19 neural network, a model
pretrained on the ImageNet dataset.

The trained model reached a test accuracy of 92.1%.

Learning rate, scheduler step size, epochs, batch size and number of hidden layers
are all designed to be easily interchangeable to allow for further improvements
by finding better combinations.

### Technologies

- Python
- Libraries: torch, torchvision, numpy, json, random, os, copy, PIL, matplotlib,
seaborn
- the project is documented in a jupyter notebook, the training and evaluation phase
was run on the [Google colab cloud](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d) to have access to GPU acceleration.
