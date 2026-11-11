# Machine Learning Projects

Five end-to-end machine learning projects built in Jupyter notebooks as part of the Future Connect data analytics course (2026). Each folder holds the notebook and the dataset it uses.

| Project | Problem type | Models | Headline result |
|---|---|---|---|
| [Cancer prediction](cancer-prediction) | Binary classification (malignant vs benign) | Decision tree with depth tuning and cross validation | Depth sweep used to balance training accuracy against cross validation score |
| [Wine quality](wine-quality) | Binary classification (good vs not good) | Random forest, SVC, GridSearchCV | Accuracy around 0.88 to 0.90 on the test set |
| [Weather prediction](weather-prediction) | Multi class classification (Seattle weather) | XGBoost with GridSearchCV (10 fold) | Accuracy improved from 0.76 to 0.81 after tuning |
| [Stock price prediction](stock-price-prediction) | Regression (Tesla close price) | XGBoost regressor, MinMax scaling | Evaluated with MSE and MAE, plotted with Plotly |
| [Bank marketing](bank-marketing) | Binary classification (term deposit take up) | Decision tree, ordinal encoding, GridSearchCV | Confusion matrix and class imbalance discussed |

## Tools
Python, pandas, NumPy, scikit-learn, XGBoost, matplotlib, seaborn, Plotly, Jupyter

## What I practised
- Data cleaning and exploratory data analysis
- Encoding, scaling and train/test splitting
- Hyperparameter tuning with grid search and cross validation
- Reading precision, recall and F1, especially on imbalanced classes

## Running
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn plotly
jupyter notebook
```
