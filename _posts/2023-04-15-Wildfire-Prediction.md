---
layout: post
title: Wildfire Prediction
thumbnail-img: /assets/img/project_images/Diet_Analyzer_Thumbnail.jpg
tags: [CNN, Transfer Learning, Deep Learning]
---

<h4>Summary</h4>
This project presents a wildfire prediction model developed using the Keras API. The model consists of a four-layer convolutional neural network with max pooling, batch normalization, and ReLU activation, followed by four dense layers with ReLU activation and an output layer with softmax activation. The model was trained using an ImageDataGenerator with augmentation techniques and Gaussian Blur preprocessing and was compiled with categorical cross-entropy loss and Adam optimizer. After training for 30 epochs, the model achieved an accuracy of 58%. To improve accuracy, several other models, including EfficientNetB0, ResNet50, VGG19, and InceptionV3, were tested. The VGG19 model achieved the highest accuracy of 96% on wildfire prediction. Overall, the presented wildfire prediction model shows promise for early detection and prevention of catastrophic wildfires.

|         | Food-101 | CNFood-241 |
| ------- | -------- | ---------- |
| Classes | 101      | 241        |
| Total   | 101000   | 191811     |

| Food-101                                                                           | CNFood-241                                                                             |
| ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| ![Food101 Accuracy](/assets/img/project_images/Diet_Analyzer_Food101_Accuracy.jpg) | ![CNFood241 Accuracy](/assets/img/project_images/Diet_Analyzer_CNFood241_Accuracy.jpg) |
| ![Food101 Epochs](/assets/img/project_images/Diet_Analyzer_Food101_Epochs.jpg)     | ![CNFood241 Accuracy](/assets/img/project_images/Diet_Analyzer_CNFood241_Epochs.jpg)   |

<b>Restaurant Identification</b> - Extracted GPS coordinates from over 10,000 user-submitted food photos, successfully identifying restaurant locations in 90% of cases for precise meal-name matching.

<b>Food Description Segmentation</b> - Devised an approach to apply NLP techniques to segment food descriptions and extract pertinent features, including food items and preparation methods, enhancing data accuracy and usability.

[GitHub](https://github.com/sulaimangm/AIFoodClassification)
