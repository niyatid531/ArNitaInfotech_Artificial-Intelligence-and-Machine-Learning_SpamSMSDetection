# Spam SMS Detection

AI model that classifies SMS messages as spam or legitimate (ham).

## Dataset
SMS Spam Collection: 5,572 messages (UCI / Kaggle)

## Models Used
- Naive Bayes: ROC-AUC: 0.9375
- Logistic Regression: ROC-AUC: 0.9633 ✅ Best
- Linear SVM: ROC-AUC: 0.9615

## Tools
Python, scikit-learn, TF-IDF, pandas, matplotlib, seaborn

## Key Results
- Best Model: Logistic Regression
- Accuracy: 98.57%
- ROC-AUC: 0.9633
- Spam Precision: 96% | Spam Recall: 93%

## How to Run
1. Place spam.csv in data/ folder
2. pip install pandas scikit-learn matplotlib seaborn joblib
3. python classifier.py
