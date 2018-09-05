Ames Housing Data and Kaggle Challenge


1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

In this project, I will use a linear regression model on the Ames Housing Dataset. This model will predict the prices of homes on sale in Ames, Iowa.

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

This model will focus on using train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process

## Set-up

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. **IMPORTANT**: Click this link ([Regression Challenge Sign Up](https://www.kaggle.com/t/378b31fc149442439eefeb1028d841fa)) to **join** the competition (otherwise you will not be able to make submissions!)


## The Modeling Process

1. The train dataset has all of the columns to generate and refine models. The test dataset has all of those columns except for the target or the housing prices to predict in my Regression model.
2. Generate a regression model using the training data.
    - feature engineering to quantify additional factors that influence housing prices
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for the target column or housing prices in the test dataset and submit the predictions to Kaggle to see how the model does against unknown data.
