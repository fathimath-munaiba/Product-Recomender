# 🛒 Product Recommendation System using Supervised Machine Learning

This project builds a product recommendation system using several supervised learning algorithms such as Logistic Regression, Random Forest, Gradient Boosting, SVM, and more.

##  Overview

We use an e-commerce dataset (`merrec.csv`) to predict whether a user will "favorite" a product based on session and product features, then generate Top-N personalized recommendations.

## 📌 Dataset
 File: `merrec.csv`
- Type:  e-commerce user-item interactions
- Key Columns:
  - `user_id`, `item_id`, `session_id`
  - `action_type`: whether the item was viewed, clicked, or favorited
  - `category`, `price`, `title`

##  Features

- Binary classification of user interactions
- Multiple ML models with evaluation metrics
- Top-N item recommendations for users
- Visualizations: confusion matrices, metric comparisons, and recommendation scores

##  Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

##  Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

- ##  Results Summary

| Model               | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|--------------------|----------|-----------|--------|----------|---------|
| Logistic Regression| 0.9340   | 0.7412    | 0.3520 | 0.4762   | 0.7321  |
| Decision Tree      | 0.9035   | 0.5581    | 0.4982 | 0.5266   | 0.7109  |
| Random Forest      | 0.9395   | 0.7353    | 0.4851 | 0.5822   | 0.8034  |
| Gradient Boosting  | 0.9440   | 0.7600    | 0.5100 | 0.6107   | 0.8176  |
| SVM                | 0.9370   | 0.6900    | 0.4400 | 0.5362   | 0.7560  |
| KNN                | 0.9200   | 0.6129    | 0.3920 | 0.4762   | 0.7201  |

>  **Gradient Boosting** performed the best overall, especially in ROC-AUC and F1-score.

- Confusion Matrix

## Data source
https://huggingface.co/datasets/mercari-us/merrec


