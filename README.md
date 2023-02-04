## TaxiFarePrediction

### Description 
This notebook is created as a part of **New York City Taxi Fare Prediction** Kaggle challenge and supposed to predict taxi fare.

### **Objectives**
Imagine you are in Big Apple. New to town and have no clue how to get from Central park to Empire State Building. After some useless attemps and short fair buttle you finally got your cab. But hey! How much is it gonna cost you in this crazy city?

### **Goal of the project**
To analyze data and predict the fare amount for a taxi ride in New York City given the pickup and dropoff locations.

### **Data**
[New York City Taxi Fare Prediction](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction) dataset available at Kaggle as part of competition.

The dataset contains the following fields:

Field name | Description
--- |--- 
*key* | identifier for each trip
*fare_amount* | the cost of each trip in usd
*pickup_datetime* | date and time when the meter was engaged
*passenger_count* | the number of passengers in the vehicle (driver entered value)
*pickup_longitude* | the longitude where the meter was engaged
*pickup_latitude* | the latitude where the meter was engaged
*dropoff_longitude* | the longitude where the meter was disengaged
*dropoff_latitude* | the latitude where the meter was disengaged

### **Techniques**
In this project I will use:
* **Data preprocessing**: PolynomialFeatures, StandardScaler
* **ML algorihms**: LinearRegression
* **Model training/applying:** Pipeline, tran_test_split

### Installation:
You shouldn't really install this code, just click on the "TaxiFarePrediction.ipynb" file and in the follow window click on "Open in Colab" button. This will redirect you on [Colab](colab.research.google.com) by Google website. 
