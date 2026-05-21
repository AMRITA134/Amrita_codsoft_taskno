# Titanic Survival Prediction using Machine Learning

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.

The model is trained using passenger information such as:

- Age
- Gender
- Passenger Class
- Fare
- Embarked Location
- Family Information

This is one of the most popular beginner Machine Learning projects and demonstrates:

- Data Cleaning
- Data Visualization
- Feature Engineering
- Logistic Regression
- Model Evaluation

---

## Dataset

Dataset used:
Titanic Dataset

Features include:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

Target Variable:

- Survived
  - 0 = Did Not Survive
  - 1 = Survived

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithm

- Logistic Regression

---

## Project Workflow

1. Load Dataset
2. Explore Data
3. Handle Missing Values
4. Encode Categorical Data
5. Feature Selection
6. Train-Test Split
7. Train Logistic Regression Model
8. Evaluate Model Performance

---

## Visualizations Included

- Survival Count Plot
- Missing Values Heatmap
- Correlation Heatmap
- Age Distribution
- Gender Survival Comparison

---

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## Run the Project
titanic.ipynb

## Results

The model achieves good prediction accuracy and demonstrates the importance of data preprocessing and feature engineering in Machine Learning.
## Dataset Source
https://www.kaggle.com/datasets/yasserh/titanic-dataset


---

# README — Credit Card Fraud Detection

```markdown
# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project detects fraudulent credit card transactions using Machine Learning techniques.

The system analyzes transaction patterns and classifies transactions as:

- Genuine
- Fraudulent

This project demonstrates:

- Data Analysis
- Imbalanced Dataset Handling
- Data Normalization
- Logistic Regression
- Fraud Detection Techniques

---

## Dataset

Dataset used:
Credit Card Fraud Detection Dataset

Features:

- Time
- Amount
- V1 to V28 (PCA transformed features)
- Class

Target Variable:

- Class
  - 0 = Genuine Transaction
  - 1 = Fraudulent Transaction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## Machine Learning Algorithm

- Logistic Regression

---

## Project Workflow

1. Load Dataset
2. Explore Dataset
3. Visualize Fraud Distribution
4. Normalize Amount Feature
5. Handle Class Imbalance using SMOTE
6. Split Dataset
7. Train Logistic Regression Model
8. Evaluate Model Performance

---

## Visualizations Included

- Fraud vs Genuine Transactions
- Transaction Amount Distribution
- Correlation Heatmap
- Confusion Matrix
- Feature Importance Graph

---

## Handling Imbalanced Data

The dataset contains very few fraud transactions.

SMOTE (Synthetic Minority Oversampling Technique) is used to balance the dataset and improve prediction performance.

---

## Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

## Run the Project
credit_fraud.ipynb

## Results

The model successfully detects fraudulent transactions with high precision and recall.

## Dataset Source

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud



---

# README — Movie Rating Prediction

```markdown
# Movie Rating Prediction using Machine Learning

## Project Overview

This project predicts movie ratings based on various movie features such as:

- Genre
- Director
- Actors
- Duration
- Votes

The goal is to analyze historical movie data and build a Machine Learning model that estimates movie ratings accurately.

This project demonstrates:

- Data Cleaning
- Feature Engineering
- Label Encoding
- Regression Techniques
- Data Visualization

---

## Dataset

Dataset used:
IMDb Movies India Dataset

Features include:

- Name
- Year
- Duration
- Genre
- Rating
- Votes
- Director
- Actor 1
- Actor 2
- Actor 3

Target Variable:

- Rating

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithm

- Linear Regression

---

## Project Workflow

1. Load Dataset
2. Explore Dataset
3. Handle Missing Values
4. Feature Engineering
5. Encode Categorical Variables
6. Train-Test Split
7. Train Regression Model
8. Predict Ratings
9. Evaluate Performance

---

## Visualizations Included

- Rating Distribution
- Top Genres
- Top Directors
- Votes Distribution
- Actual vs Predicted Ratings
- Feature Importance Graph

---

## Feature Engineering

The project converts:

- Votes into numerical values
- Duration into numeric format
- Text features using Label Encoding

---

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## Run the Project
movie_predict.ipynb

## Results

The model predicts movie ratings based on movie characteristics and provides insights into factors influencing ratings.
