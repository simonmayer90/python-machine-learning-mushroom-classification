# mushroom-classification: Building a classification model for poisonous mushrooms.
This project is a part of the [DataScience Bootcamp](https://www.wbscodingschool.com/data-science-bootcamp/) at [WBS Coding School](https://www.wbscodingschool.com/).  Other datascience projects can be found at the [main GitHub repo](https://github.com/simonmayer90).

#### Project Status: Completed

## Project Intro/Objective
The purpose of this project is to build a classification model for mushrooms with Pythons sklearn library. 
Based on some training data, the model should predict the outcome of the test data: Are the mushrooms poisonous or not?
Special weight should be put on avoiding false negatives (i.e. predicting mushrooms as not poisonous when in fact they are poisonous).

### Methods Used
* Data exploration
* Data preprocessing (using sklearns OneHotEncoder)
* Building custom functions to manipulate the train data to put extra weight on avoiding fals negatives in the predicted test data
* Building dlassification models with RandomForest and XGBoost and finding the best parameters for these models using GridSearch

### Technologies
* python, jupyter
* pandas, numpy
* matplotlib
* scikit-learn, xgboost

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Data is being kept [here](https://github.com/simonmayer90/python-machine-learning-mushroom-classification/tree/main/data) within this repo. 
3. Jupyter notebooks are being kept [here](https://github.com/simonmayer90/python-machine-learning-mushroom-classification) at the parent level of this repo.

## Contributing Members  
[Tobias (github)](https://github.com/tobiasaurer)

## Contact
* https://github.com/simonmayer90
