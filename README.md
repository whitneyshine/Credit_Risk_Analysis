# Credit_Risk_Analysis<br><br>

## Overview Of Analysis<br>

### Background<br><br>
Jill commends you for all your hard work. Piece by piece, you have been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.<br><br>
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you will need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.<br><br>
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you are done, you will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.<br><br>
### What Has Been Created<br><br>
This new assignment consists of three technical analysis deliverables and a written report. The following has been submitted:<br><br>
* Used Resampling Models to Predict Credit Risk<br>
* Used the SMOTEENN Algorithm to Predict Credit Risk<br>
* Used Ensemble Classifiers to Predict Credit Risk<br><br>

## Results<br><br>
**RandomOverSampler**<br>
* Balanced Accuracy Score: 0.66<br>
* Precision Score<br>
      * High Risk Score: 0.01<br>
      * Low Risk Score: 1.00<br>
      * Overall Average/Total Score: 0.99<br>
* Recall Score<br>
      * High Risk Score: 0.72<br>
      * Low Risk Score: 0.59<br>
      * Overall Average/Total Score: 0.59<br>
![Random_Over_Sampler](Resources/Random_Over_Sampler.png)<br><br>

**SMOTE**<br>
* Balanced Accuracy Score: 0.65<br>
* Precision Score<br>
      * High Risk Score: 0.01<br>
      * Low Risk Score: 1.00<br>
      * Overall Average/Total Score: 0.99<br>
* Recall Score<br>
      * High Risk Score: 0.60<br>
      * Low Risk Score: 0.69<br>
      * Overall Average/Total Score: 0.69<br>
![SMOTE](Resources/SMOTE.png)<br><br>

**ClusterCentroids**<br>
* Balanced Accuracy Score: 0.65<br>
* Precision Score<br>
      * High Risk Score: 0.01<br>
      * Low Risk Score: 1.00<br>
      * Overall Average/Total Score: 0.99<br>
* Recall Score<br>
      * High Risk Score: 0.69<br>
      * Low Risk Score: 0.40<br>
      * Overall Average/Total Score: 0.40<br>
![Cluster_Centroids](Resources/Cluster_Centroids.png)<br><br>

**SMOTEENN**<br>
* Balanced Accuracy Score: 0.54<br>
* Precision Score<br>
      * High Risk Score: 0.01<br>
      * Low Risk Score: 1.00<br>
      * Overall Average/Total Score: 0.99<br>
* Recall Score<br>
      * High Risk Score: 0.76<br>
      * Low Risk Score: 0.57<br>
      * Overall Average/Total Score: 0.58<br>
![SMOTEENN](Resources/SMOTEENN.png)<br><br>

**BalancedRandomForestClassifier**<br>
* Balanced Accuracy Score: 0.79<br>
* Precision Score<br>
      * High Risk Score: 0.03<br>
      * Low Risk Score: 1.00<br>
      * Overall Average/Total Score: 0.99<br>
* Recall Score<br>
      * High Risk Score: 0.70<br>
      * Low Risk Score: 0.87<br>
      * Overall Average/Total Score: 0.87<br>
![Balanced_Random_Forest_Classifier](Resources/Balanced_Random_Forest_Classifier.png)<br><br>

**EasyEnsembleClassifier**<br>
* Balanced Accuracy Score: 0.93<br>
* Precision Score<br>
      * High Risk Score: 0.09<br>
      * Low Risk Score: 1.00<br>
      * Overall Average/Total Score: 0.99<br>
* Recall Score<br>
      * High Risk Score: 0.92<br>
      * Low Risk Score: 0.94<br>
      * Overall Average/Total Score: 0.94<br>
![Easy_Ensemble_Classifier](Resources/Easy_Ensemble_Classifier.png)<br><br>

## Summary<br><br>
