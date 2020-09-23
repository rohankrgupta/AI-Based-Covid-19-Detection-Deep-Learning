# Lung-X-Ray-Classification-Deep-Learning

This is a Convolutional Neural Network (CNN) based PyTorch model to classify the X-Ray radiographs into one of the 3 categories : Covid-19, Pneumonia (Viral) and Normal. We build and compare  2 Models : ResNet-18 (18-Layers Deep) and ResNet-50 (50-Layers Deep) architecture pretrained on Imagenet Dataset, using the Transfer Learning. The dataset is taken from the COVID-19 Open Research Dataset (CORD-19) and consists of about 231 Covid, 1341 Viral and 1355 Normal High Pixel Quality Radiographs.

The ResNet-18 model achieved an accuracy of 97.78% and a validation loss of 0.1337 on the test dataset.
The ResNet-50 model achieved an accuracy of 98.89% and a validation loss of 0.1074 on the test dataset and outperforms many state-of-the-art models trained before.
