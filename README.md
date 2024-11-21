# Megaline Plan Recommendation

## Overview
This project involves developing a machine learning model to recommend new mobile plans (Surf or Ultimate) for customers of the mobile carrier Megaline. The model is trained on monthly user behavior data to predict which plan is optimal for each customer.

## Dataset
The dataset contains behavioral information for each user, with features such as:

- `calls`: Number of calls made
- `minutes`: Total call duration in minutes
- `messages`: Number of text messages
- `mb_used`: Internet traffic used in MB
- `is_ultimate`: Current plan (Ultimate-1, Surf-0)

## Installation
Ensure you have [Python](https://www.python.org/downloads/) and the following packages installed:
- pandas
- scikit-learn
- numpy
- matplotlib

## Results

We created and trained 3 models: Decision Tree, Random Forrest, and Logistical Regression to determine whether buyers will likely purchase the Ultra plan from Megaline.

We have found that although the Random Forrest model would yield the most accurate predictions based on our training of the model, the test sample showed that the Decision Tree model had the highest accuracy at 79%, followed by Random Forest at 78% accuracy rating.
