# Quora-question-answer-pair-similarity

## Problem Statement
To build a machine learning model which can identify which question asked on quora are duplicates of question that have already been asked.

## Data 
Data has been taken from Quora. The train.data contains 5 columns qid1, qid2, question1, question2 is_duplicate. It contains around 404290 rows.

## Mapping to ML Problem
It is a binary classification problem, for a given pair of questions we have to find whether the given pair is duplicate of not.

## Performance Metrics
* Log-Loss
* Binary Confusion Matrix
















## Algorithm For classical ML model

| Algorithms                    | train log loss         | Test log loss|
| ------------------------------|:--------------------   | ------       |
| Logistic Regression           | 0.460                  | 0.52         |
| SVM                           | 0.636                  | 0.639        |
| XGB                           | 0.257                  | 0.380        |
