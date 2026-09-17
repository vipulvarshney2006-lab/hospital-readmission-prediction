# Hospital Readmission Prediction

## About the Project

This project predicts whether a patient will be readmitted to the hospital within 30 days.

## Dataset

The project uses the Diabetes 130-US Hospitals dataset from Kaggle.

## Machine Learning Model

- Logistic Regression
- L2 Regularization
- StandardScaler
- Train-Test Split

## Evaluation

The model was evaluated using ROC-AUC and a confusion matrix.

ROC-AUC: 0.637

## Confusion Matrix

- True Negative: 17,976
- False Positive: 93
- False Negative: 2,238
- True Positive: 47

## Conclusion

The model achieved a ROC-AUC of approximately 0.637. The confusion matrix shows a high number of false negatives, which is important in hospital readmission prediction because missing a high-risk patient can have clinical consequences.

Changing the classification threshold or using techniques to handle class imbalance could be explored to improve detection of readmission cases.
