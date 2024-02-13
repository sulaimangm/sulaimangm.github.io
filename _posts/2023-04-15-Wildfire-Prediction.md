---
layout: post
title: Wildfire Prediction
thumbnail-img: /assets/img/project_images/Wildfire_Prediction_Thumbnail.jpeg
tags: [CNN, Transfer Learning, Deep Learning]
---

<h4>Summary</h4>
This project presents a wildfire prediction model developed using the Keras API. The model consists of a four-layer convolutional neural network with max pooling, batch normalization, and ReLU activation, followed by four dense layers with ReLU activation and an output layer with softmax activation. The model was trained using an ImageDataGenerator with augmentation techniques and Gaussian Blur preprocessing and was compiled with categorical cross-entropy loss and Adam optimizer. After training for 30 epochs, the model achieved an accuracy of 58%. To improve accuracy, several other models, including EfficientNetB0, ResNet50, VGG19, and InceptionV3, were tested. The VGG19 model achieved the highest accuracy of 96% on wildfire prediction. Overall, the presented wildfire prediction model shows promise for early detection and prevention of catastrophic wildfires.

<h4>Sample Dataset</h4>
The Wildfire Prediction Dataset is a collection of satellite images from the National Oceanic and Atmospheric Administration (NOAA) that has been processed and categorized with labels.
The dataset contains over 42,000 images covering 6 regions in the U.S.
![Sample Dataset](/assets/img/project_images/Wildfire_Prediction_Dataset.png)

<h4>Model</h4>
![Model Architecture](/assets/img/project_images/Wildfire_Prediction_Model.png)

Trained a CNN model to predict wildfire occurrences using the Keras API. 
The model has four convolutional layers with max pooling, batch normalization, and ReLU activation, followed by four dense layers with ReLU activation and an output layer with softmax activation. 
The training data is generated using an ImageDataGenerator with augmentation techniques and Gaussian Blur preprocessing. The model is compiled with categorical cross-entropy loss and Adam optimizer.
The model is trained for 30 epochs.

![Own Implementation](/assets/img/project_images/Wildfire_Prediction_Implementation.png)

<h4>Transfer Learning</h4>

Pretrained models are frequently used as the foundation for transfer learning, in which the concepts and variables discovered during initial training can be adjusted or applied to a new task. This method, especially when the size of the new dataset is constrained, can greatly minimise the quantity of data and time needed to train a new model and can result in enhanced performance.
For our data, we used the 4 pretrained models shown below.

![Transfer Learning](/assets/img/project_images/Wildfire_Prediction_TransferLearning.png)

![Comparision](/assets/img/project_images/Wildfire_Prediction_Comparision.png)

<h4>Conclusion</h4>

The initial self-trained model was showing signs of overfitting and high variance, which could be addressed with regularization techniques. The confusion matrix revealed an issue of class imbalance in the test set, leading to lower accuracy. In contrast, pre-trained models, especially VGG19, performed well on the test set with high accuracy and low mean squared error, indicating good performance. However, further experimentation with hyperparameters, different architectures, and data augmentation could lead to even better results. Ultimately, the choice of model and approach would depend on the specific problem and dataset being analysed.

[GitHub](https://github.com/sulaimangm/DeepLearning)
