[README.md.md](https://github.com/user-attachments/files/24995094/README.md.md)
# Sentiment Analysis on Twitter Data
Classical ML pipeline to classify tweets into positive, neutral, and negative sentiment.
## Problem Statement
Social media platforms generate massive unstructured text data. 
This project builds a machine learning pipeline to classify tweet sentiment 
using classical NLP techniques.
## What This Project Covers
- Data cleaning and preprocessing
- Handling missing values
- Train-test split with correct alignment
- TF-IDF vectorization
- Model training (SVC,Decision tree, Naive Bayes,Logistic Regression)
- Hyperparameter tuning with GridSearchCV
- Model evaluation using confusion matrix and F1-score
## Tech Stack
- Python
- Pandas
- scikit-learn
- NumPy
## Results
- Linear SVC performed best
- Model performance evaluated using F1-score
- Accuracy alone was misleading due to class imbalance
## Key Learnings
- Importance of aligning features and labels after preprocessing
- Why TF-IDF must be fit only on training data
- How small data leakage can invalidate ML results
## Business Impact
- Identifies customers at risk of churn based on sentiment
- Helps prioritize customer retention strategies
- Demonstrates how NLP can turn unstructured text into actionable insights
## Future Improvements
- Add more robust imbalance handling
- Compare Logistic Regression and Naive Bayes
- Deploy model using a simple API
