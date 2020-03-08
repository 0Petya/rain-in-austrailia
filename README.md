# Rain in Australia

This is an introductory project I picked to get familar with scikit-learn and the general flow of a machine learning project. I'm working with the [Rain in Australia](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) dataset from Kaggle, where the goal is to perform binary classification to predict whether it will rain tomorrow given some meteorological data from today.

The final model chosen was logistic regression optimized with stochastic gradient descent. I optimized for recall and had a final score of 76% recall at 79% accuracy. The notebook can be viewed [here](https://github.com/0Petya/rain-in-australia/blob/master/rain.ipynb).

## Setup
This project was done with Python 3.8.1, and all the requirements are under `requirements.txt`. `setup` can be executed to install and get the development environment set up.
