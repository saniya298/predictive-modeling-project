# Predictive Modeling Using Machine Learning

## Project Overview

This project applies machine learning techniques to predict passenger survival on the Titanic dataset. The project demonstrates the complete machine learning workflow, including data cleaning, preprocessing, feature engineering, model training, and model evaluation.

## Objective

To build a predictive model that can determine whether a passenger survived the Titanic disaster based on passenger information.

## Dataset

Titanic Dataset

Features used:

* PassengerId
* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

Target Variable:

* Survived

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

1. Handled missing values:

   * Filled missing Age values using the median.
   * Filled missing Embarked values using the mode.
   * Removed the Cabin column due to excessive missing values.

2. Removed unnecessary columns:

   * Name
   * Ticket

3. Converted categorical variables into numerical format using one-hot encoding.

## Machine Learning Model

Algorithm Used:

* Random Forest Classifier

Training Process:

* Split dataset into training and testing sets (80:20 ratio)
* Trained Random Forest model on training data
* Evaluated model on testing data

## Model Evaluation

Evaluation Metrics:

* Accuracy Score
* Confusion Matrix
* ROC Curve

Model Accuracy:

* Approximately 82%

## Visualizations

- Confusion Matrix
- ROC Curve
- Feature Importance Chart

## Results

Key Findings:

* The Random Forest model achieved approximately 82% accuracy.
* Feature importance analysis identified the most influential factors affecting passenger survival.
* Data preprocessing significantly improved model readiness.
* The model successfully classified passenger survival outcomes.
* Confusion Matrix and ROC Curve were used to evaluate performance.
* The project demonstrates the complete machine learning workflow from data preprocessing to model evaluation.

## Project Structure

predictive-modeling-project/

├── train.csv

├── predictive_model.ipynb

├── confusion_matrix.png

├── roc_curve.png

├── README.md

└── requirements.txt

## Conclusion

This project demonstrates the practical application of supervised machine learning techniques. By cleaning data, engineering features, training a Random Forest model, and evaluating performance, valuable insights were gained into predictive analytics and classification modeling.
