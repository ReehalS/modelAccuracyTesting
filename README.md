# Comparing 10 different ML models to find the best one for classification of breast cancer
Predicting the possibility of having breast cancer using different ML models

## Logistic Regression

Confusion Matrix: 

[[ 62   1]

[  2 106]]
 
Classification Report: 

|       heading   |  precision |  recall |   f1-score  |  support |
| -------- | ------- | -------- | ------- | ------- |
| 0 | 0.97 | 0.98 | 0.98 | 63 |   
|    1    |    0.99    |   0.98  |    0.99    |    108  |
| | | | | |
|   accuracy   |          |     |   0.98     |   171    |
|   macro avg    |  0.98     |  0.98   |   0.98   |     171   | 
|  weighted avg  |  0.98     |  0.98   |   0.98   |     171    |

AUC Score: 0.9980893592004703

## KNN

Confusion Matrix: 

[[ 59   4]

 [  3 105]]
 
 
Classification Report: 

|    heading   |  precision  |  recall | f1-score |  support |
| -------- | ------- | -------- | ------- | ------- |
|           0     |   0.95   |   0.94   |   0.94    |    63 |
|           1     |   0.96   |   0.97   |   0.97    |   108 |
| | | | | |
|    accuracy     |           |          |  0.96   |    171 |  
|    macro avg    |   0.96   |   0.95    |  0.96   |    171 |
|    weighted avg |   0.96   |   0.96    |  0.96   |    171 |

##  SVM

Confusion Matrix: 

[[ 61   2]

 [  3 105]]
 
Classification Report: 

| heading | precision  |  recall  |f1-score  | support |
| -------- | ------- | -------- | ------- | ------- |
|           0    |    0.95   |   0.97  |    0.96    |    63 |
|           1    |    0.98   |   0.97  |    0.98    |   108 |
| | | | | |
|    accuracy     |          |         |    0.97   |    171  |  
|    macro avg    |   0.97   |   0.97   |   0.97  |     171  | 
|    weighted avg |   0.97   |   0.97   |   0.97 |      171 |

AUC Score: 0.9964726631393297

## Decision Tree

Confusion Matrix: 

[[59  4]

 [ 9 99]]
 
Classification Report: 

| heading |    precision  |  recall |  f1-score |  support  |
| -------- | ------- | -------- | ------- | ------- |
|          0      |  0.87   |   0.94    |  0.90    |    63|
|          1    |    0.96   |   0.92    |  0.94   |    108|
| | | | | |
|   accuracy      |         |          |   0.92   |    171    |
|    macro avg     |  0.91  |    0.93   |   0.92   |    171   |
|   weighted avg  |  0.93  |    0.92  |    0.92  |     171|

AUC Score: 0.9265873015873015

## Random Classifier

Confusion Matrix: 

[[ 59   4]

 [  2 106]]
 
Classification Report: 

| heading |   precision |   recall | f1-score |  support |
| -------- | ------- | -------- | ------- | ------- |
|       0 |       0.97   |   0.94 |     0.95   |     63 |
|        1    |    0.96  |    0.98   |   0.97    |   108 |
| | | | | |
|    accuracy    |          |          |    0.96   |    171    |
|    macro avg    |   0.97   |   0.96    |  0.96   |    171 |
|    weighted avg |   0.96  |    0.96   |   0.96    |   171 |

AUC Score: 0.9961787184009406

## Gradient Boosting

Confusion Matrix: 

[[ 59   4]

 [  3 105]]
 
Classification Report:

| heading |    precision |   recall|  f1-score  | support|
| -------- | ------- | -------- | ------- | ------- |
|           0    |   0.95   |   0.94  |    0.94     |   63|
|           1   |    0.96   |   0.97    |  0.97  |     108|
| | | | | |
|    accuracy   |           |          |   0.96   |    171   |
|    macro avg    |  0.96   |   0.95   |   0.96    |   171   |
|    weighted avg |  0.96   |   0.96   |   0.96   |    171|

AUC Score: 0.9954438565549677

## Naive Bayes

Confusion Matrix: 

[[ 57   6]

 [  5 103]]
 
Classification Report: 

| heading |    precision  |  recall |  f1-score  | support |
| -------- | ------- | -------- | ------- | ------- |
|           0   |     0.92   |   0.90  |    0.91   |     63 |
|           1    |    0.94   |   0.95  |    0.95  |     108|
| | | | | |
|    accuracy     |          |          |   0.94  |     171    |
|    macro avg    |   0.93  |    0.93   |   0.93   |    171   |
| weighted avg  |  0.94   |   0.94   |   0.94   |    171|
 
AUC Score: 0.9926513815402704

## Neural Networks

Confusion Matrix: 

[[ 61   2]

 [  2 106]]
 
Classification Report: 

| heading |    precision  |  recall | f1-score |  support|
| -------- | ------- | -------- | ------- | ------- |
|           0     |   0.97   |   0.97  |    0.97    |    63|
|           1     |   0.98    |  0.98  |    0.98    |   108|
| | | | | |
|    accuracy      |         |          |   0.98  |     171    |
|    macro avg    |   0.97    |  0.97    |  0.97    |   171   |
|    weighted avg  |  0.98    |  0.98   |   0.98   |    171|

AUC Score: 0.9966196355085244

## AdaBoost

Confusion Matrix: 

[[ 61   2]

 [  2 106]]
 
Classification Report: 

|heading |    precision |   recall | f1-score |  support|
| -------- | ------- | -------- | ------- | ------- |
|           0    |    0.97   |   0.97   |   0.97   |     63|
|           1    |    0.98  |    0.98  |    0.98    |   108|
| | | | | |
|    accuracy     |          |         |    0.98   |    171  |
|    macro avg    |   0.97   |   0.97   |   0.97   |    171   |
|    weighted avg |   0.98   |   0.98   |   0.98  |     171|

AUC Score: 0.9961787184009406

## XGBoost

Confusion Matrix: 

[[ 61   2]

 [  3 105]]
 
Classification Report: 

| heading |     precision  |  recall | f1-score |  support|
| -------- | ------- | -------- | ------- | ------- |
|           0    |    0.95   |   0.97  |    0.96    |    63|
|           1    |    0.98   |   0.97   |   0.98   |    108|
| | | | | |
|    accuracy     |           |         |   0.97   |    171|
|    macro avg     |  0.97    |  0.97   |   0.97   |    171|
|    weighted avg  |  0.97  |    0.97   |   0.97   |    171|

AUC Score: 0.9944150499706055



