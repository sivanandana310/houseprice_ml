#  House Price Prediction 

##  Project Overview
This project builds an end-to-end Machine Learning pipeline to predict house prices using regression techniques.  
The workflow includes data preprocessing, feature scaling, model training, hyperparameter tuning, and evaluation.

This project demonstrates production style ML structure using Scikit learn Pipelines.


##  Objective
To build a robust regression model that predicts housing prices with strong generalization performance using cross-validation and hyperparameter optimization.



##  Project Structure

house-price-ml-pipeline/
│
├── notebooks/
│   └── eda.ipynb
│
├── src/
│   ├── train.py
│   ├── evaluate.py
│
├── models/
│   └── model.pkl
│
├── requirements.txt
└── README.md



##  Exploratory Data Analysis
- Checked missing values
- Analyzed feature distributions
- Identified correlation patterns
- Visualized important predictors



##  Machine Learning Pipeline

The model pipeline includes:

- Data Scaling (StandardScaler)
- Random Forest Regressor
- Cross Validation
- Hyperparameter Tuning (GridSearchCV)

Pipeline ensures:
- No data leakage
- Reproducibility
- Clean modular structure
- Production readiness



## Model Evaluation

Metrics Used:
- RMSE (Root Mean Squared Error)
- R² Score

Achieved:
- R² Score: 0.89(89%)
- RMSE: 2.81




##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


##  Future Improvements

- Compare multiple regression models
- Add feature importance visualization
- Deploy model using Flask or Streamlit
- Create REST API for predictions

