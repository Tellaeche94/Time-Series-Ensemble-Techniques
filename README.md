# Time-Series-Ensemble-Techniques
Time series forecast using LSTM, GRU, ARIMAX and ensemble techniques to improve the final forecast

In this project I performed time series forecast using retail sales data obtained from the USDA (https://www.ers.usda.gov/data-products/weekly-retail-food-sales/) and weather data obtained from the National Center for Environmental Information (https://www.ncei.noaa.gov/cdo-web/datatools/selectlocation). 

Both data sets had to be treated and combined to end up with a single data set that could be used for the forecast.

I implemented LSTM and GRU from the TensorFlow library and an ARIMAX from statsmodel.api and then used weighted averages to combine the results of the individual models to improve the final forecast.
