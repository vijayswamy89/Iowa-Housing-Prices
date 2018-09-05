Ames Housing Data and Kaggle Challenge


1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

In this project, I will use a linear regression model on the Ames Housing Dataset. This model will predict the prices of homes on sale in Ames, Iowa.

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

This model will focus on using train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process

## Set-up

Before you begin working on this project, please do the following:

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. **IMPORTANT**: Click this link ([Regression Challenge Sign Up](https://www.kaggle.com/t/378b31fc149442439eefeb1028d841fa)) to **join** the competition (otherwise you will not be able to make submissions!)
3. Review the material on (https://www.kaggle.com/c/dsi-us-5-project-2-regression-challenge)

## The Modeling Process

1. The train dataset has all of the columns that you will need to generate and refine your models. The test dataset has all of those columns except for the target that you are trying to predict in your Regression model.
2. Generate your regression model using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for your target column in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data.
