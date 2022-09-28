# Credit_Risk_Analysis

## Overview

## Results

### Balanced Random Forest Classifier

<img width="159" alt="BRFC_balanced_accuracy_score" src="https://user-images.githubusercontent.com/106006911/192796592-cfe4d21e-67d4-4f2b-90b2-c0250e37573e.png">

* The balanced accuracy score for the Balanced Forest Classifier is ~79%. Although not the best, it falls within the realistic range of scores.

<img width="693" alt="BRFC_classification_report" src="https://user-images.githubusercontent.com/106006911/192799032-bc256a3f-f941-441e-b2b4-48bb9d336e1d.png">

* High-risk has a precision score of 4% and a F1 score of 7%. Both of these are very low, with a large number of false positives.

* Low-risk has a precision score of 100% and a F1 score of 95%. These are excellent, very few high-risk were mistaken for low-risk.

### Adaboost

<img width="166" alt="Adaboost_balanced_accuracy_score" src="https://user-images.githubusercontent.com/106006911/192801515-57b89173-f2f6-49e1-9149-a9e4d6cf34df.png">

* The balanced accuracy score is ~92%. This was the best results of all the tests.

<img width="676" alt="Adaboost_classification_report" src="https://user-images.githubusercontent.com/106006911/192802272-31337f73-d5ec-4858-8df8-d90ba152f191.png">

* High-risk has a precision score of 7% and a F1 score of 14%. While slightly better, it will still produce a large number of false-positives.

* Low-risk had much better results, with a precision score of 100% and a F1 score of 97%.

### Naive Random Oversampling

<img width="160" alt="NRO_balanced_accuracy_score" src="https://user-images.githubusercontent.com/106006911/192805265-a37edac7-b890-4c2a-a58f-51ad02f8b037.png">

<img width="688" alt="NRO_classification_report" src="https://user-images.githubusercontent.com/106006911/192805369-09bb254e-00e6-4195-9efd-e4d450b54c87.png">

### SMOTE Oversampling

<img width="146" alt="SMOTE_balanced_accuracy_score" src="https://user-images.githubusercontent.com/106006911/192805753-47196ebf-023f-496e-9825-2c3d00e1ed00.png">

<img width="659" alt="SMOTE_classification_report" src="https://user-images.githubusercontent.com/106006911/192805841-bda54cf8-f7c7-4ee9-a06b-5a0a001b6db9.png">

### Undersampling

<img width="156" alt="Undersampling_balanced_accuracy_score" src="https://user-images.githubusercontent.com/106006911/192806239-18d79071-afd5-444b-8ddd-19183309e47b.png">


<img width="672" alt="Undersampling_classification_report" src="https://user-images.githubusercontent.com/106006911/192806306-5943292d-a71b-46c5-b077-8ec447c8e29b.png">

### Combination (Over and Under) Sampling

<img width="180" alt="SMOTEENN_balanced_accuracy_score" src="https://user-images.githubusercontent.com/106006911/192806717-cf3ac237-e45b-4a70-b148-8e19584028d6.png">

<img width="676" alt="SMOTEENN_classification_report" src="https://user-images.githubusercontent.com/106006911/192806792-761fb5f7-4079-41d9-bb01-41a9c4e723e7.png">


