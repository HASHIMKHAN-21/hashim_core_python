PROJECT OVERVIEW : 
This project focuses on predicting the rating of a movie using machine learning techniques in Python. The model analyzes different movie features such as genre, director, actors, duration, votes, and year to estimate the expected movie rating.
The project demonstrates how data cleaning, preprocessing, and basic machine learning can be used to build a predictive model.

OBJECTIVE : 
The main objective of this project is to:
Analyze movie data
Clean and preprocess the dataset
Convert categorical data into numerical format
Build a regression model to predict movie ratings
Evaluate the performance of the model
the movie dataset was cleaned and prepared using data preprocessing techniques such as handling missing values and encoding categorical variables. A Linear Regression model was then built to predict movie ratings based on features like genre, director, actors, duration, votes, and year. The evaluation metrics showed how well the model performed in predicting ratings, demonstrating the use of basic data analysis and machine learning techniques in Python.

TECHNOLOGIES USED :
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

STEPS PERFORMED :

1 Data Collection
The movie dataset was loaded using Pandas for analysis.
2 Data Cleaning
Removed duplicate records
Handled missing values
Cleaned columns such as Year, Duration, and Votes
3 Feature Engineering
Categorical columns like Genre, Director, and Actor were encoded using Label Encoding.
4 Data Splitting
The dataset was split into:
Training set (80%)
Testing set (20%)
5 Model Building
A Linear Regression model was used to predict movie ratings.
6 Model Evaluation

The model was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

RESULTS  :

The model was able to predict movie ratings based on the selected features. While the predictions are not perfectly accurate, the project demonstrates how machine learning can be applied to analyze and estimate movie ratings.