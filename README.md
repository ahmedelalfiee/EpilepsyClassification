# Problem
This project trains various classifiers and compare between their accuracies to detect mild epileptic from severe epileptic patients.

# Dataset
Our dataset contain 500 Epilepsy patients with 4095 channels of their EEG signal. Which ranged from class 1 to 5 according totheir severity of epilepsy level. We will focus only on class 3 and class 4 (mild and severe epilepsy).

# Methodologies 
## Extracting features
We will use the psd (power spectral density) to know how is the power is distributed across different frequency band). The following image describes the different frequency bands:

![imggg](https://github.com/ahmedelalfiee/EpilepsyClassification/assets/169726451/22037158-8847-4060-9b15-11b51d79ffde)

## Our metrics
We will focus more on the sensitivity rather than speciificty due to the fact that it is more important to identify severe epilptic patients than the mild epileptic ones.

## Training Classifiers
The following table contains each classifier and its corresponding accuracy, sensitivity, and specificity:

![image](https://github.com/ahmedelalfiee/EpilepsyClassification/assets/169726451/aaf2a87f-0a7c-4255-8a42-e9f05f5f56ec)

## Conclusion
Random Forest (Ensemble) is the most accuracte classifier in terms of the previously mentioned metrics.
