Research question: "What are the effective machine learning approaches and techniques for text classification of the 20 Newsgroups dataset?" We will investigate different feature selection methods and combine them with different machine learning algorithms to understand the effectiveness of each combination of methods.

The 20 newsgroups dataset comprises around 18000 newsgroups posts on 20 topics split in two subsets: one for training (or development) and the other one for testing (or for performance evaluation). The split between the train and test set is based upon a messages posted before and after a specific date.
# Directory Structure Description

*   Uploading Train, Test and All = Train + Test datasets
*   Data Exploration
*   Literature Review
*   Preprocessing
*   Model 1 - Neural Network with regression using X\_train\_vectorized - TFidfvectorizer

    *   Neural Network Confusion Matrix
    *   Neural Network ROC Curve
*   Model 2 - Naive Bayes

    *   Naive Bayes Confusion Matrix
    *   Native Bayes ROC Cureve
*   Model 3 - KNN Classifier

    *   KNN Confusion Matrix
    *   KNN ROC Curve
*   Model 4  - Decision Tree Classifier

    *   Decision Tree Confusion Matrix
    *   Decision Tree ROC Curve
*   Model 5 - CNN

    *   CNN Learning Curve
    *   CNN Confusion Matrix
*   Model 6 - Ensemble Model(CNN and SVM)

    *   Ensemble Model Confusion Matrix

# Outcomes

| Model                            | Accuracy    | Precision   | Recall  | F1 Score  |
| :------------------------------- | :---------- | :---------- | :------ | :-------- |
| Naïve Bayes                      | 0.68        | 0.70        | 0.66    | 0.68      |
| K-Nearest Neighbours             | 0.50        | 0.48        | 0.45    | 0.46      |
| Decision Tree Model(Pre-tuning)  | 0.29(0.46)  | 0.47        | 0.46    | 0.46      |
| SVM                              | 0.48        |             |         |           |
| CNN (with word embeddings)       | 0.55        | 0.88        | 0.59    | 0.70      |
| Ensemble Model(CNN and SVM)      | 0.91        | 0.92        | 0.91    | 0.91      |
