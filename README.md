# Titanic-passenger-survival-prediction

📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.
The dataset is taken from the Kaggle Titanic Competition.

The objective is to perform data preprocessing, feature engineering, and model building to achieve high prediction accuracy.

📊 Dataset

Dataset: Kaggle Titanic Dataset

Training set: 891 passengers

Test set: 418 passengers

Target variable: Survived (0 = No, 1 = Yes)

🛠️ Project Workflow
1️⃣ Data Cleaning

Dropped unnecessary columns (Cabin, Ticket, etc.)

Filled missing Age using class-wise mean

Filled missing Embarked using mode

Filled missing Fare using mean

2️⃣ Feature Engineering

Created powerful new features:

Title Extraction (Mr, Mrs, Miss, Master, Rare)

Family Size

Single (Is Alone)

Age Groups

Sex + Pclass Combination

Log Transformation of Fare

These features significantly improved model performance.

3️⃣ Encoding

Applied One-Hot Encoding on categorical features:

Sex

Embarked

Age Group

Title

Sex_Pclass

4️⃣ Models Used

Logistic Regression

Random Forest (Improved version)

Gradient Boosting (Optional improvement)

Final model used for submission:
Random Forest / Gradient Boosting

📈 Kaggle Score

Public Leaderboard Accuracy: 78%+

Further tuning can improve performance to 85%+.

🔍 Key Learnings

Importance of Feature Engineering

Handling Missing Values

Avoiding Data Leakage

Difference between Linear and Tree Models

Why scaling is not required for tree-based models

Proper validation using train-test split

🧠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

📁 Project Structure
├── train.csv
├── test.csv
├── final_submission.csv
├── titanic_model.ipynb
└── README.md

🚀 Future Improvements

Hyperparameter tuning using GridSearchCV

Ensemble of multiple models

Feature importance analysis

Cross-validation optimization

💡 Conclusion

This project demonstrates a complete end-to-end Machine Learning pipeline including preprocessing, feature engineering, model training, evaluation, and Kaggle submission.

It highlights how domain-based feature engineering plays a crucial role in improving prediction accuracy.
