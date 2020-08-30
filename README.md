# Car-Value-Prediction

![Python 3.7](https://img.shields.io/badge/Pyhton-3.7-blue) ![Flask](https://img.shields.io/badge/Flask-1.1-orange) ![Heroku](https://img.shields.io/badge/Heroku-Deployment-brightgreen)

## Objective

The objective of this project is to calculate the <strong>resale value of a car</strong> based on various parameters such as year of purchase, type of owner, etc.

## Dataset

The dataset is taken from kaggle. This dataset contains information about used cars listed on www.cardekho.com. The dataset link is given <a href="https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho">here</a>.

## Live Demo

<a href="https://carvaluepred.herokuapp.com/">Car Value Prediction</a>

  ### Glimpse of the Web App
  <br>

  ![GIF](carvaluepred.gif)

## Important Attributes

* Year of Purchase
* Showroom Price
* Distance Driven
* Number of previous Owners 
* Car Fuel Type (Petrol or Diesel)
* Seller Type (Individual or Dealer)
* Transmission Type

## Model Information

Since we are predicting a continuos value (Price of the car) ,regression should be used to get the output. For this purpose, I have used RandomForest Regressor. You can know more about RandomForest Regressor <a href="https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html">here</a>.

## Web App and Deployment

This project uses Flask for the web app and its deployment is done on Heroku.

#### Other Information
This project is a modified version of an older project on the same topic.The original project is available <a href="https://github.com/krishnaik06/Car-Price-Prediction">here</a>.
