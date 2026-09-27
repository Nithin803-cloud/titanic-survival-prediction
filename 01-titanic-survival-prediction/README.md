# Titanic Survival Prediction

A supervised machine learning classification project predicting whether a Titanic passenger survived.

## Workflow
- Load and inspect the dataset
- Exploratory data analysis
- Handle missing values
- Feature engineering
- Encode categorical variables
- Train/test split
- Compare Logistic Regression, Decision Tree, Random Forest and Gradient Boosting
- Evaluate using accuracy, precision, recall, F1-score and confusion matrix
- Tune the best model with GridSearchCV

## Dataset
The notebook loads the Titanic dataset using Seaborn's public dataset loader.

## Run
```bash
pip install -r requirements.txt
jupyter notebook titanic_survival.ipynb
```

## Note
Model metrics are generated when the notebook is executed; no historical result is fabricated in this repository.
