# Titanic Survival Prediction

This project aims to predict the survival of passengers on the Titanic using machine learning models. The data is provided by the Titanic dataset from Kaggle.

## Project Description

The goal of this project is to use historical data from the Titanic disaster to predict whether a passenger survived or not. The dataset includes features such as age, gender, class, and other relevant information about the passengers.

## Dataset

The dataset contains the following columns:

- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Amount of money the passenger paid for the ticket.
- **Cabin**: Cabin where the passenger stayed.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Project Workflow

1. **Data Preprocessing**: Clean the dataset by handling missing values, encoding categorical variables, and scaling numerical features.
2. **Modeling**: Train different machine learning models (e.g., Logistic Regression, Decision Trees, Random Forest) to predict survival.
3. **Evaluation**: Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
4. **Submission**: Make predictions on the test dataset and prepare the results for submission.

## Setup

1. Clone this repository:
git clone https://github.com/zinoubjed/titanic-survival-prediction.git

2.  Install the required libraries:
pip install -r requirements.txt

3.Run the Jupyter notebook or Python script to start the analysis.

