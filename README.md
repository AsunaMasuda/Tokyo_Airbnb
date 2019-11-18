# Data Analysis and Price prediction using Tokyo Airbnb data
This repository holds an ipython file where I performed data analysis and a accomodation price prediction on Tokyo Airbnb data (Sep 2019 - July 2020).

It uses three datasets (csv.files) which are available in [Inside Airbnb](http://insideairbnb.com/get-the-data.html).

For price predictions, I used random forest regression model in scikit learn package with Python. 
<br>For explortory data analysis, I used numpy, pandas, matplotlib and seaborn. 

# Executive Summary
- The occupancy rate becomes lower around October and November in 2019 and towards 2020 spring the rate becomes higher.
- There are many accomodations available in apartment type, but its occupancy rate is not high and seems not so popular
- The trained model performance.
  Mean Squared Error(MSE) train_set: 77.165 (yen), test_set: 294.628 (yen),  R^2 train_set: 1.000, test_set: 1.000 
- The most important feature to predict accomodation prices is 'Accomodates'.
