## End to End Machine Learning Project

# Student Performance Prediction- Darshan Patil

## Overview
This project aims to predict student performance based on various factors such as Gender, Ethnicity, Parental Level of Education, Lunch, and Test Preparation Course. By analyzing these variables, the goal is to understand how they affect students' test scores and overall academic performance.
Use of various classification models like Decision Tree, Random Forest, XGBoost,Linear Regression was done. Linear Regression was selected as best model from above. The Linear Regression model provided 88.03% accuracy in training. Testing accuracy for model was 87.3%. 80% data was used for training and 20% data was used for testing.
After Providing various details the model will predict whether student will pass or not.

## Problem Statement
The project seeks to investigate the impact of student characteristics on their performance in exams. Specifically, it analyzes how variables such as Gender, Ethnicity, Parental Level of Education, Lunch, and Test Preparation Course influence students' test scores.

## Data Source

The dataset consists of 1000 rows and 8 columns:

gender: Sex of students (Male/female)
race/ethnicity: Ethnicity of students (Group A, B, C, D, E)
parental level of education: Parents' final education (Bachelor's degree, Some college, Master's degree, Associate's degree, High school)
lunch: Whether students had lunch before the test (Standard or Free/reduced)
test preparation course: Whether students completed the test preparation course before the test (Complete or Not complete)
math score: Student's score in Math
reading score: Student's score in Reading
writing score: Student's score in Writing

URL - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977

## Software Requirements 

1) Python 3.8.12
2) Visual Studio Code
3) Git Cli
4) Jupyter Notebook
5) GitHub account

## Approach

Below are steps taken to build this project
1) Create Repository on GitHub with gitignore as pyhton.
2) Clone Repository from GitHub to Local using git clone command in VS Studio Code
3) Create a virtual environment inside working foleder named venv use command - python -m venv "path/venv"
4) Create a requirements.txt file which contains all libraries that are required to run this project.
5) Read Dataset using pandas library
6) Start Exploratory data analysis
7) Start building various models like Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier, KNN Classifier, MLP Clasiifier
8) Tune the models with cross validation using GridSearchCV
9) Select best model and make pickle file.
10) Create app.py file which used dash library for front-end design.
11) Test the app.py on local system.
12) Add, Commit and Push all files from Local to GitHub

## Author Linkedin URL 

Linkedin URL - https://www.linkedin.com/in/patil-darshan

## Author

[@DarshanPatil02](https://github.com/DarshanPatil02)

