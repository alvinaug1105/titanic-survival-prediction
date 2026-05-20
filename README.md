# Titanic Survival Prediction 🚢

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0-orange)
![Kaggle](https://img.shields.io/badge/Kaggle-0.78808-green)

## Overview
Predicting survival of Titanic passengers using Machine Learning.  
This is my solution to the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic).

## Result
- **Kaggle Score: 0.78708**
- Model: Soft Voting Ensemble (GBM + Random Forest + Logistic Regression)

## Tools Used
- Python, Pandas, NumPy, Scikit-learn

## Key Steps
- Data cleaning & EDA
- Feature engineering (Title, FamilySize, LogFare, Deck, Age*Class...)
- Model training & evaluation (5-fold Cross Validation)
- Soft Voting Ensemble

## File Structure
```
titanic-survival-prediction/
├── README.md
├── titanic.ipynb
├── submission.csv
└── data/
    ├── train.csv
    └── test.csv
```

## How to Run
```bash
pip install pandas numpy scikit-learn jupyter
jupyter notebook titanic.ipynb
```
