# AI-Based-Covid-19-Detection-Deep-Learning

This is a Convolutional Neural Network (CNN) based ensemble model - CovidNet to classify the X-Ray radiographs into one of the 3 categories : Covid-19, Pneumonia (Viral) and Normal. I have build the ensemble model using 2 parallel pretrained EfficientNet-B0 as backbone networks and averaged their results to classify the High Resolution RadioGraphs accurately reducing the variations in predictions. The dataset is taken from the COVID-19 Open Research Dataset (CORD-19) and consists of about 1300 Covid, 1341 Viral and 1355 Normal High Res Radiographs.

The model outperforms the state-of-the-art models trained before achieving about 98% accuracy and loss of about 4% on the test-set consisting of 120 random radiographs each from 3 classes.
![Radiograph Predictions](https://github.com/rohankrgupta/Lung-X-Ray-Classification-Deep-Learning/blob/master/Screenshot%20from%202021-02-19%2014-00-10.png)
