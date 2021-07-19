# Credit_Risk_Analysis

## Analysis Overview

The purpose of this analysis is to demonstrate resampling models using machine learning imbalanced-learn and scikit-learn to predit Credit Risk.
The techniques used are:

-RandomOverSampler
-SMOTE (Synthetic Minority Oversampling Technique)
-ClusterCentroids (under sampling)
-SMOTEENN (SMOTE and Edited Nearest Neighbors (ENN)).
-Ensemble Classifiers BalancedRandomForestClassifier
-EasyEnsembleClassifier

## Results

### Random Over Sampling

![image](https://user-images.githubusercontent.com/80069183/126095126-1d73820a-d23d-4d92-8b47-17534677651b.png)

*Accuracy Score: 0.677
Precision - High Risk: 0.01
Precision -Low Risk: 1.00
Recall -High Risk: 0.76
Recall -Low Risk: 0.59

### SMOTE Over Sampling

![image](https://user-images.githubusercontent.com/80069183/126095473-108b21a2-e260-461d-a2e4-74784f29c58c.png)

*Accuracy Score: 0.662
Precision - High Risk: 0.01
Precision -Low Risk: 1.00
Recall -High Risk: 0..63
Recall -Low Risk: 0.69

### Under Sampling

![image](https://user-images.githubusercontent.com/80069183/126095819-cfa8c98d-38f0-4594-9318-ce83518c0d6e.png)

*Accuracy Score: 0.644
Precision - High Risk: 0.01
Precision -Low Risk: 1.00
Recall -High Risk: 0.64
Recall -Low Risk: 0.54


### Combination (Over Under) Sampling

![image](https://user-images.githubusercontent.com/80069183/126096203-3375c955-8f36-49f4-ba36-3633b33d6e7e.png)

*Accuracy Score: 0.644
Precision - High Risk: 0.01
Precision -Low Risk: 1.00
Recall -High Risk: 0.72
Recall -Low Risk: 0.57

### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/80069183/126096745-c4c400da-0493-4eee-b149-c7fa271a0049.png)

*Accuracy Score: 0.766

### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/80069183/126097415-91388a23-690e-491c-9699-4e5ab5a53868.png)

*Accuracy Score: 0.766
Precision - High Risk: 0.03
Precision -Low Risk: 1.00
Recall -High Risk: 0.66
Recall -Low Risk: 0.87







