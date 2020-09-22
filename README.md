# Lung-X-Ray-Classification-Deep-Learning

This is a Convolutional Neural Network (CNN) based PyTorch model to classify the X-Ray radiographs into one of the 3 categories : Covid-19, Pneumonia (Viral) and Normal
and consists of 18-Layers in depth. Our model uses a ResNet-18 architecture pretrained on Imagenet Dataset, using the Transfer Learning. The dataset used to train 
this model is taken from the COVID-19 Open Research Dataset (CORD-19) and consists of about 220 Covid, 1341 Viral and 1345 Normal High Pixel Quality Radiographs.

The model achieved an accuracy of 97.06% on the test dataset on 5000 epochs and outperforms many state-of-the-art models trained before.
