# Module 3 Final Project Cervical Cancer Classification


## Introduction

This repo contains a Cervical Cancer Risk classifcation on a dataset from Venezuela. 

Hospital Y has learned that machine learning is the new buzzword that may help their hospitals save patients, as well as save money. Hospital Y has contacted Company X to inquire about machine learning methods and would like a model to determine the risk for cervical cancer.


## Contents

kag_risk_factors_cervical_cancer.csv  - Cervical Cancer Risk Classification

confusion_matrix.png                  - Confusion Matrix graph

Cervical Cancer Risk Classification   - Power point presentation


## Summary

The best model used to determine the need for a Biopsy is a Logistic Regression with specific hyperparameters after GridSearches. Since we are more focused on preventing false negatives, a higher recall score is more important than the overall accuracy of the model. The logistic regression had a 100% recall rate with the test set. The patients that did have a Biopsy also had a higher prevalence of STDs, IUDs, hormonal contraceptives, and smoking. 

The confusion matrix below illustrates this:

![alt text]https://github.com/jefferyrosario/dsc-learn-lessons-lab-onl01-dtsc-pt-012120/blob/master/Untitled%20Folder/confusion_matrix.png

## Conclusion

Hospital Y should use this logistic regression algorithm to help determine the need for a Biopsy. The 100% recall rate prevents any false negatives to occur. 
