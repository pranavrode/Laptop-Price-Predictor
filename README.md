# Laptop-Price-Predictor 
This project works on data of different laptop prices according to various specifications of laptop brands. I have done feature engineering on data and have build different Machine Learning models to achieve maximum accuracy and choosen best ML algorithm for best predictions with its real life working deployment. 

## 1. Business Context: -
A company providing complete IT hardware to the end user customers like big organisation company selling laptop PCs of different brands and specifications as per needs of customer. So, when customer here visits store to buy laptop firstly he/she will want to know price quote of laptop as customer requirements. This solution can help both customers and store employee to guide about various specification with ease and simplicity. An online ecommerce laptop pc selling site can also use this same solution for above business purpose.

## 2. Problem Statement: -
End user customer who wants to buy laptop pc within his/her budget range with desired specifications doesn’t have an idea about what specification of pc will I get within my budget constraints or what price will be for desired specifications of laptop.
Target variable type - Continuous Numerical data, Model type - Regression

## 3. Solution Developed: -
#### Step 1: Gathered data from Kaggle or any other open source as required of overall laptop brands in excel sheet with attributes like memory, display, processor, storage etc. Load this data using pandas data frame.

#### Step 2: Pre-processing data and feature engineering, creating new variables from uncleaned and cluttered variables. Create data visualizations using seaborn and matplotlib to get basic insights of dependent variable(y) and independent variables(X) and correlations between then if any.

#### Step 3: Selecting cleaned and newly created independent variables for model building. Build model using various supervised regression algorithms using sklearn library. And selecting best algorithm among all which is best. Evaluation for best algorithm used is metrics like R2 Score, RMSE (Root Mean Square Error), MAE (Mean Absolute Error). 

#### Step 4: Did hyperparameter tunning from chosen best algorithm like using “Gradient Boosting Regressor” with experimenting with its different hyperparameters and achieve right and best parameters to achieve best R2 score with least RMSE and MAE on both test and train predictions with taking care model to not be overfitted or underfitted.

#### Step 5: Saving model into pickle file and integrating with UI. Deploying the model on Heroku App which is a cloud platform where we can deploy machine learning models. Used PyCharm and basic dependencies to deploy it on Heroku platform for its actual working model.
Platforms used – Jupyter notebook (Python), Pycharm, Heroku, git.

## 4. Improvements to the Solution: -
Scope of improvement is that we can clean data more and get even more better parameters and achieve best results with better R2 score and lowest RMSE and MAE.

## 5. Link to the working project demo/prototype developed: -
Working deployment link -  https://lpp-pranav-rode.herokuapp.com/
Code and Dataset- https://github.com/pranavrode/Laptop-Price-Predictor
