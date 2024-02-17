---
layout: post
title: Diabetic Retinopathy Prediction
thumbnail-img: /assets/img/project_images/Diabetic_Retinopathy_Thumbnail.jpg
tags: [Backward Search, PCA, LDA, KNN, SVM]
---

<h4>Summary</h4>
This project presents a comparision between different Feature Extraction approaches such as Backward Search and PCA and evaluated the model using LDA. We also compared different classifiers such as LDA, KNN and SVM and applied them to a large scale classification task. this included analysing and predicting the chances of the presence of diabetic retinopathy with data pulled from a Diabetic Retinopathy Debrecen Data Set using Linear Discriminant Analysis and Random Forest classifier. Performance accuracy of 74% was achieved using the models.

<h4>Sample Dataset</h4>
The data set comprises of features that are pulled out from a Messiodor image set to prognosticate whether there are traces of diabetic retinopathy in the image or not. The dimensions or features of data corresponds to either a discovered lesion, a descriptive feature of an anatomical part or an image-level descriptor.

<h4>Comparing Feature Extraction Approaches</h4>
<h5>Experiments Conducted:</h5>

There are conducted 4 experiments in total for this project:

- 2 experiments for PCA with Classifier 1 and 2
- 2 experiments for BACKWARD SEARCH (Feature Selection) with Classifier 1 and 2.

<h5>Classifiers Used:</h5>

1. Linear Discrimant Analysis(LDA)

- It is linear classification machine learning algorithm.
- Library used to implement LDA was SK Learn using “sklearn. discrimant_analysis”.

2. Random Forest Classifier

- Random Forest algorithm is based on decision Trees.
- Library used to implement RFC was SK Learn using “sklearn. ensemble import random forest classifier”

<h5>Result</h5>

After conducting all the 4 Experiments on the data set used from UCI repository, observations were collected by analysing the results:

- Classification time (Training) for PCA is less than Backward Search (Feature Selection).
- In terms of accuracy, Backward Search (Feature Selection) works better than PCA.
- Comparing the computational time of both the classifiers, LDA is way faster than Random Forest.

<h4>Comparing Classifiers</h4>
<h5>Experiments Conducted:</h5>

Here are 3 classifiers usedfor this experiment:

- K-Nearest Neighbour
- Naïve Bayes
- Support Vector Machine

<h5>Result</h5>

After conducting all the 3 Experiments on the data set used from UCI repository, these observations were collected by analysing the results:

- Training times for Naïve Bayes and KNN are much shorter than that of SVM and quadratic optimization problem plays a big part in that
- Accuracy for Non-Linear kernel in SVM is significantly higher compared to the other two for this problem
- Training times for KNN would usually be very low since the distances for the test data are calculated only during the testing time which forms the core of classification process
- Training time for linear Kernel is significantly higher than RBF kernel after tuning, probably due to the data set and might be because the underlying quadratic optimization problem for linear kernel was much more difficult to compute
- AUC score for SVM is also higher than the other two classifiers signifying that it generally performs better across various decision boundaries and not just the best one for which the confusion matrix has been calculated.

[GitHub](https://github.com/sulaimangm/MachineLearning)
