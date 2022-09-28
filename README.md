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

### 
