Project Title-
        Flight Price Prediction
Description-
         1.In this project created a tool that estimates Flight Prices to help users look for best prices when booking flight tickets.
         2.This project was challanging for me because all independent fearures were of categorical type.To convert it into numeric values LabelEncoder and OneHotEncoder             were required.
         3.I userd Regression type of algorithm to continuous type of target variable.(I worked on Flight Price Prediction using Random Forest Regressor)
         4.In this dataset i used MAE,MSE,RMSE.Main goal is to reduce the MSE as much as possible.The RMSE is square root of MSE.The mean absolute error(MAE) is an                  indication of how close your predictions are, on average, to the actual values of the test data.
         5.In this project i used scatter plot which give me plot values in increasing order.
         6.CV(cross validation)provides the ability to estimate model performance on unseen data not used while training.
         7.Feature Engineering is the important process used to extracting and organizing the important features from raw data in such a way that it fits the purpose              of the machine learning model.
         8.I also used the Hyperparameter Tunning to  enhance the performance of a machine learning model.
               In this way i used different techniques to achieve my goal that is prediction of flight PRICE.
               
 Installation-  
         For installation process i initialized different libraries tesr were:
                import numpy as np
                import pandas as pd
                import matplotlib.pyplot as plt
                import seaborn as sns
                import warnings
                warnings.filterwarnings("ignore")
                sns.set()
                from sklearn.ensemble import ExtraTreesRegressor
                selection.feature_importances_
                from sklearn.model_selection import train_test_split
                from sklearn.linear_model import LinearRegression
                lr=LinearRegression()
                from sklearn.metrics import mean_squared_error,r2_score
                from sklearn.ensemble import RandomForestRegressor
                from sklearn import metrics
                from sklearn.model_selection import RandomizedSearchCV
                
 Data sets-1.Train_data- https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh?select=Data_Train.xlsx 
           2. Test_data- https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh?select=Test_set.xlsx           
                
 Kaggle link-https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh           
                
 Credits -
          to Kaggle and to Krish Naik For providing wonderful videos on youtube.
