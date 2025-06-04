# credit-card-fraud-detection
Machine learning model to detect fraudulent credit card transactions using logistic regression. Achieved 93% accuracy on a highly imbalanced dataset using data preprocessing and model tuning.


# Credit Card Fraud Detection

A machine learning model to detect fraudulent credit card transactions using logistic regression.

## 🔍 Project Summary
- Built on the Kaggle Credit Card Fraud dataset (284,807 transactions).
- Achieved 93% accuracy using Logistic Regression with feature scaling and class balancing (SMOTE).
- Evaluated using accuracy.

## 🔍 Project Highlights
- **Model Used:** Logistic Regression
- **Evaluation Metric:** Accuracy Score
- Used `accuracy_score` from Scikit-learn to evaluate model performance on test data.
- Model predicts transaction class (fraud or not fraud) based on features using `.predict()` method.
- Accuracy on test set: **93%**

## 🛠️ Tools & Libraries
- Python, Pandas, matplotlib, seaborn

## 📈 Results

| Metric   | Score |
|----------|-------|
| Accuracy | 93%   |

### 📊 Visualizations

- **Transaction Distribution (Before & After Sampling):** Shows class imbalance and how it was corrected with undersampling.
- **Feature Correlation Heatmap:** Helps understand feature relationships.
- **Confusion Matrix:** Provides insight into classification performance — how many frauds were correctly identified.

<p align="center">
  <img src="images/class_distributions.png" width="600"/>
</p>



## 📁 Dataset
[Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)
