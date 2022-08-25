# Bangalore-House-price-prediction
#Bangalore-house's-rate
  This notebook is for people who are looking to buy a place in Bangalore city(INDIA)
  Created a model that predicts Bangalore house rate to help people to know about the prices of house in various places without the need of contacting different agents     for the same.
  Data was collected from Kaggle
  Data shape is 13320 rows and 9 columns.

#ML MODEL:
     Performed One hot encoding to represent the categorical values in binary form since machine learning algorithms cannot operate on label data directly.
     I also split the data into train and tests sets with a test size of 20%. Model Used:-
     Multiple Linear Regression - r^2 value of 0.82
     
#Prediction:
     Built a function to predict the house price with location, number of Square foot area, Bathroom, and BHK.
     The prices mentioned are in Lakhs(Indian Currency)
