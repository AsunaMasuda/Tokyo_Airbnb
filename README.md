# Data Analysis and Price prediction using Tokyo Airbnb data
Japan is a host country of the Rugby World Cup in 2019 and Summer Olympics in 2020. Some media reported that there is a shortage of accomodation at the places where the matches are held. Airbnb is expected to be a great alternative for conventional accomodations such as hotels. In this report, I performed Exploratory Data Analysis and price prediction on Tokyo Airbnb data.

<p align="center"><img src = "https://github.com/AsunaMasuda/Tokyo_Airbnb/blob/master/image_for_README.jpg" width=500></p>
<p align="center">Photo by Louie Martinez on Unsplash</p>

## Overview
This repository holds an ipython file where detailed analysis was explained. I used three datasets (csv.files) between September 2019 and August 2020 which are available in [Inside Airbnb](http://insideairbnb.com/get-the-data.html).

For price predictions, I chose random forest regression model in scikit learn package with Python.

For explortory data analysis and data visualization, I used numpy, pandas, matplotlib and seaborn. 

## Executive Summary
- The occupancy rate becomes lower around October and November in 2019 and towards 2020 spring the rate becomes higher.
- There are many accomodations available in apartment type, but its occupancy rate is not high and seems not so popular
- The trained model performance.
  Mean Squared Error(MSE) train_set: 77.165 (yen), test_set: 294.628 (yen),  R^2 train_set: 1.000, test_set: 1.000 
- The most important feature to predict accomodation prices is 'Accomodates'.
