## Fine-Tuning on the CIFAR-10 dataset
### Context
This assignment involves fine-tuning advanced pretrained models to classify 32x32x3 images from the CIFAR-10 dataset into 10 categories. This assignment emphasizes cost-effective solutions and explores the use of custom models followed by the application of transfer learning to pretrained models.
We compared three approaches for classifying images from the CIFAR-10 dataset, each constrained by a parameter budget of 70,000. These approaches are:
1. A custom, small ResNet model.
2. Fine-tuning a VGG16 model pre-trained on ImageNet.
3. Fine-tuning a pre-trained (unspecified) model initially trained on the MNIST dataset


### Dataset
The dataset used for this project is the CIFAR-10 dataset, consisting of 32x32x3 images belonging to 10 classes (e.g., airplanes, cars, birds).

**How to Obtain the Dataset:**
The CIFAR-10 dataset is readily available through Keras and TensorFlow. You can load it directly using `tf.keras.datasets.cifar10.load_data()` or equivalent methods. No external downloads are required. The dataset is built into the tensorflow library.

## Report
A brief report is available. It answers the assignment's questions by comparing the 3 approaches.