Garbage Detection Using Convolutional Neural Networks

Overview
Recycling waste plays a vital role in environmental protection. For an efficient recycling process, waste must be categorized based on similar recycling techniques. Properly segregating household waste into distinct categories can significantly increase the percentage of recycled materials.

In this notebook, we trained a model to classify input images into specific waste categories using the given labels. The objective of this study is to develop a model capable of accurately predicting and classifying waste into one of the predefined recycling categories: cardboard, glass, metal, paper, plastic, and trash.

Model Performance
The CNN model achieved an impressive accuracy of 92.96%, demonstrating its potential as an effective tool for classifying waste types.

Libraries Used
TensorFlow

Sequential

Keras.layers

ImageDataGenerator

Sklearn.metrics

Keras

PIL

Pathlib

Scipy

OS

NumPy

Matplotlib.pyplot

Torchvision.datasets

Torchvision.transforms

Prediction Results
The image below presents a comparison between the model’s predictions and the original waste labels. As shown, all classifications were accurate. The confidence levels for each category were as follows:

Cardboard – 99%

Glass – 87%

Metal – 99%

Paper – 96%

Plastic – 83%

Trash – 98%