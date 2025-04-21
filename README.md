# Using Logistic Regression to Determine How Well an NHL Team Will Do in the Playoffs

This project uses logistic regression to predict how NHL teams might perform in the Stanley Cup playoffs based on regular-season performance metrics. The analysis is conducted in Google Colab and is broken into three separate models.
Trhutfully, the only good one is the first model, but they are included to see the steps taken to get the bets model.

##  Overview

The main goal is to explore how well a machine learning model—specifically logistic regression—can predict playoff outcomes. This project dives into NHL team stats and attempts to assign probabilities to different levels of playoff success.

## Models Explained
There are three models, but the first one is the best one. The other two either under or over predict different classses.

### Model 1 - Primary Model
Predicts agood amount of each class, very heplful and also includes the probabilites of each class.

### Model 2 
Predicts agood amount of each class but I think overall underpredicts classes 3 and 2, heplful but could be better and also includes the probabilites of each class.

### Model 3
Not good, highly overpredicts and is not trained correctly either.

## Dependencies
To run this notebook, you'll need the following Python packages:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

If you're using Google Colab, these are already available by default.

## ▶How to Run
1. Open the notebook in [Google Colab]
2. Run each cell in order (top to bottom)
3. Review the outputs and focus primarily on Model 1

## Author
Created by Anthony Holleran and Madison Montgomery


