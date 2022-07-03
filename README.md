# Analysis Overview

In this repository I've used my knowledge of machine learning to analyze credit card risk using a credit card dataset from a lending services company named LendingClub. Using RandomOverSampler and SMOTE algorithms I've managed to oversample this data whereas I've undersampled the data using an algorithm called ClusterCentroids. Using the SMOTEENN algorithm I took both an over and under-sampling approach in this analysis. Ultimately, to predict credit risk I've used two machine learning models that are designed to reduce bias. These models are called BalancedRandomForestClassifier and EasyEnsembleClassifier. I was then able to come to my conclusion of whether these models are an affective way to determine credit risk.

# Results

## RandomOverSampler
Using this machine learning algorithm, I retrieved the following results:
* Balanced Accuracy Score: 66%
* Precision Score: 1%
* Recall Score: 64%

<img width="786" alt="Screen Shot 2022-07-03 at 2 27 18 PM" src="https://user-images.githubusercontent.com/100390727/177054523-539a6986-ff69-4d1d-b9d0-6fd294cdb0f5.png">

## SMOTE
Using this machine learning algorithm, I retrieved the following results:
* Balanced Accurary Score: 66%
* Precision Score: 1%
* Recall Score: 67%

<img width="709" alt="Screen Shot 2022-07-03 at 2 36 14 PM" src="https://user-images.githubusercontent.com/100390727/177054766-55f11419-bf89-4297-938f-15921c653791.png">

## Cluster Centroids
Using this machine learning algorithm, I retrieved the following results:
* Balanced Accuracy Score: 52%
* Precision Score: 1%
* Recall Score: 61%

<img width="709" alt="Screen Shot 2022-07-03 at 2 40 00 PM" src="https://user-images.githubusercontent.com/100390727/177054874-b6fb8d0a-c0a1-4fd3-b48d-1df79ffd457c.png">

## SMOTEENN
Using this machine learning algorithm, I retrieved the following results:
* Balanced Accuracy Score: 62%
* Precision Score: 1%
* Recall Score: 70%

<img width="709" alt="Screen Shot 2022-07-03 at 2 42 17 PM" src="https://user-images.githubusercontent.com/100390727/177054939-b731ba07-10cd-419a-ab91-bffc33ad0b3e.png">

## Balanced Random Forest Classifier
Using this machine learning algorithm, I retrieved the following results:
* Balanced Accuracy Score: 79%
* Precision Score: 3%
* Recall Score: 70%

<img width="709" alt="Screen Shot 2022-07-03 at 2 46 04 PM" src="https://user-images.githubusercontent.com/100390727/177055049-4b09a885-8400-40d0-a7f2-072e84f1daff.png">

## Easy Ensemble Classifier
Using this machine learning algorithm, I retrieved the following results:
* Balanced Accuracy Score: 93%
* Precision Score: 9%
* Recall Score: 92%

<img width="709" alt="Screen Shot 2022-07-03 at 2 49 01 PM" src="https://user-images.githubusercontent.com/100390727/177055161-485d6345-2dbd-4bf0-9b86-cff3f07cce8a.png">

# Summary

Using these 6 machine learning algorithms and analyzing their outputs, we're able to see just how accurate and precise they each are and determine which of these would be the most affective at determining credit risk. Ordering each model from least accurate to most accurate, this is what we see:

* Cluster Centroids (52% accurate)
* SMOTEENN (62% accurate)
* RandomOverSampler & SMOTE (both 66% accurate)
* Balanced Random Forest Classifier (79% accurate)
* Easy Ensemble Classifier (93% accurate)

By a longfall, it's apparent that the Easy Ensemble classifier is the most accurate machine learning algorithm for determining credit risk. The Cluster Centroids algorithm is the least accurate, so this is the one that I would definitely disregard. All in all, it's good to consider as many machine learning models as possible to get a more clear understanding of analyzed data. 



