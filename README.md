#  Mental Health Score Prediction

A machine learning regression project that predicts a **mental health score** from behavioral, academic, lifestyle, and demographic features.

The project focuses on building a complete machine learning pipeline, including exploratory data analysis, feature preprocessing, model comparison, evaluation, and hyperparameter optimization.

##  Problem Statement

The goal is to investigate whether behavioral, lifestyle, academic, and demographic variables can be used to predict a continuous mental health score.

This is formulated as a **regression problem** because the target variable is a numerical mental health score.

## Machine Learning Workflow

```text
Dataset
   ↓
Exploratory Data Analysis
   ↓
Feature Analysis
   ↓
Train/Test Split
   ↓
Feature-Specific Preprocessing
   ↓
ColumnTransformer
   ↓
Linear Regression
   ↓
Random Forest Regression
   ↓
Model Evaluation
   ↓
Randomized Hyperparameter Search
   ↓
Cross-Validation
   ↓
Final Model
```

##  Features

### Numerical Features

* Age
* Study Hours
* Average Daily Usage Hours
* Daily Unlocks
* Physical Activity Hours
* Sleep Hours Per Night

### Ordinal Feature

* Stress Level

Categories:

```text
Low → Medium → High → Very High
```

### Categorical Features

* Gender
* Academic Level
* Most Used Platform
* Purpose of Use
* Grouped Country

### Target

`Mental_Health_Score`

##  Data Preprocessing

Different preprocessing strategies are applied according to feature type.

##  Models

### Linear Regression

A baseline Linear Regression model is trained to establish a simple predictive benchmark.

### Random Forest Regression

A Random Forest Regressor is then trained to capture nonlinear relationships between the input variables and the target mental health score.

##  Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* ColumnTransformer
* Pipeline
* StandardScaler
* OrdinalEncoder
* OneHotEncoder
* Linear Regression
* Random Forest Regression
* RandomizedSearchCV

## Learning Outcomes

* Exploratory data analysis
* Feature engineering
* Feature-specific preprocessing
* Regression modeling
* Model comparison
* Cross-validation
* Hyperparameter optimization
* Model evaluation


##  Notebook

The complete implementation is available in `mentalhealth_predict.ipynb`.
