# Daily-Climate-Forecast

Using XGBRegressor from the XGBoost library to forecast the temperature in Delhi.

### The Data
For this project, the data we used was obtained from kaggle and can be found here: https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data From kaggle, we were able to dowload a pre-split training and testing data set.


### Processes
- Changed data types and removed outliers
- Using plotly we viewed the trends in humidity, temperature, pressure and wind speed over the years of the training data, we also viewed the training and test data split.
- Implemented XGBRegressor to build a model that could forecast the tempereature of our test data.
- Evaluated RMSE, MSE and MAE metrics
- Ranked the importance of features and graphically displayed them using matplotlib
- Visulized the actual and predicted temperature along with the error bars using plotly's graph objects
