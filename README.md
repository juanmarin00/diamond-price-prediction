# Diamonds Project

![Diamond Image](./images/diamond_image.jpeg)

**Introduction:**
In this project we will carry out an Exploratory Data Analysis and try to predict the price of diamonds using several different regression algorithms and criteria such as volume, cut, color, clarity and carat. (source: https://www.kaggle.com/shivam2503/diamonds)

**Data:**
This classic dataset contains the prices and other attributes of almost 54,000 diamonds, which will then split into test and train set to train our algorithms.

**Project Structure:**

- Notebooks
  Contains two Jupyter notebooks.

  - Data preprocessing & EDA.ipynb: In this notebook we import the data and carry out our exploratory data analysis and then prepare our data for our modelling with techniques such as outlier removal, normalisation of numerical variables and removing features which dont correlate to our objective variable (the price of the diamond)

  - Modelling.ipynb: Here we split our data into train and test and then apply Linear, Decision Tree, Random Forest, K Nearest Neighbors and Extreme Gradient Boosting Regressors to create our models and then test them to find which fits our data best and then evaluate using metrics such as R^2 (and adjusted), Mean Absolute Error, Mean Squared error and Root Mean Squared error.

- Data Folder
  - Diamonds.csv contains the data specified above which is later exported as export_diamonds.csv after preprocessing to be split and used for model training.

**Technologies used:**
Python, NumPy, Pandas, Seaborn, MatplotLib, SKLearn, Statsmodels
