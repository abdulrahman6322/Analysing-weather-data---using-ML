Objective:
• The objective of this assignment is to analyze the weather data and extract the
hypotheses to arrive at a prediction
Dataset: weather prediction dataset(weatherHistory.csv)
• Available at:
https://github.com/martandsingh/datasets/blob/master/weatherHistory.csv
• The dataset consists of different attributes describing the weather condition
such as temperature, humidity, pressure…etc
Hint..
You can follow the following steps:
1- Load the data and perform some pandas function to
explore data (e.g. data.head() )
2- Split the Whole data into X (input features ) and y
(Apparent Temperature (C) )
3- Split X , y into x-train , y-train , x-valid , y-valid
4- Import LinearRegression from sklearn
5- Create linear regression object
6- Train the linear regression model using fit function.
7- Predict x-valid by using predict function
8- Evaluate your model using r2-score and MSE (Mean
Square Error)
