# Titanic Survival Prediction - Exploratory Data Analysis (EDA) & Model Training

## Overview
This project performs an exploratory data analysis (EDA) on the Titanic dataset, preprocesses the data, and builds a machine learning model to predict passenger survival. The model's predictions are compared with the `gender_submission.csv` dataset.

## Steps Covered:
1. Import necessary modules
2. Load the Titanic dataset
3. Perform EDA to analyze survival data
4. Data preprocessing (handle null values)
5. Apply log transformation for uniform data distribution
6. Convert categorical columns using label encoding
7. Train-test split of the dataset
8. Model training
9. Complete model training on the full dataset
10. Compare model predictions with the `gender_submission.csv` dataset

## Installation
Ensure you have the required libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```


## Results
- The dataset was analyzed for survival trends.
- Missing values were filled using median/mode strategies.
- A Random Forest classifier was trained and evaluated.
- The final model was trained on the full dataset and compared with the `gender_submission.csv` dataset.

## Conclusion
This project demonstrates how EDA and preprocessing enhance model performance for predicting survival on the Titanic dataset.

## References
- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- [Scikit-learn Documentation](https://scikit-learn.org/)
