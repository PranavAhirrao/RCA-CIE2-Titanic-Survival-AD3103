# Titanic Survival Prediction Using Logistic Regression

## About the Activity
This project is part of the **RCA (Regression and Classification Algorithms)** activity. It demonstrates the application of Logistic Regression, a supervised machine learning classification algorithm, to predict the survival of passengers aboard the Titanic.

## Objective
- To understand the working of Logistic Regression.
- To perform data preprocessing and exploratory data analysis.
- To train a classification model using passenger information.
- To evaluate the model using classification performance metrics.

## Dataset
The project uses the Titanic dataset, which contains information about passengers aboard the Titanic.

**Selected Features:**
- `pclass` – Passenger class
- `sex` – Gender of the passenger
- `age` – Age of the passenger
- `sibsp` – Number of siblings or spouses aboard
- `parch` – Number of parents or children aboard
- `fare` – Ticket fare
- `embarked` – Port of embarkation

**Target Variable:**
- `survived = 0` – Did not survive
- `survived = 1` – Survived

**Dataset Source:** [Titanic Dataset – GitHub](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)

## Algorithm Used
**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for classification problems. It predicts the probability of an outcome belonging to a particular class.

In this project, it predicts whether a Titanic passenger survived or did not survive.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Steps Performed
1. Loaded and explored the Titanic dataset.
2. Checked missing values and duplicate records.
3. Performed data cleaning and preprocessing.
4. Conducted exploratory data analysis using graphs.
5. Selected relevant features for prediction.
6. Split the dataset into training and testing sets.
7. Trained the Logistic Regression model.
8. Predicted passenger survival.
9. Evaluated the model using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve.

## Conclusion
This activity helped in understanding Logistic Regression and its application to classification problems. It provided practical experience in data preprocessing, model training, prediction, and evaluation using a real-world dataset.
