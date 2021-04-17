# Apple-Stock-price-Prediction-using-LSTM
Developed a machine learning model for predicting the trends of stock prices using machine  learning architecture of LSTM while also making use of prominent python libraries such as tensorflow. keras etc  
In this project we will give our model a Stock Price history of Apple, and then will work in this data to identify patterns and make a lot of calculus to, get the predictions!
So first, we need to download our data. For this project, I used a dataset exported directly from https://www.tiingo.com/

Steps to get te data:
step 1: sign in to https://www.tiingo.com/
step 2: click on the </> Api from Left vertical menu
step 3: click on Take me to the documentation tab scroll down and there you will get your API.
Our dataset contains 1257 rows and 14 columns
The columns are:
     symbol       object 
 1   date         object 
 2   close        float64
 3   high         float64
 4   low          float64
 5   open         float64
 6   volume       int64  
 7   adjClose     float64
 8   adjHigh      float64
 9   adjLow       float64
 10  adjOpen      float64
 11  adjVolume    int64  
 12  divCash      float64
 13  splitFactor  float64

Algorithm
# Import all the libraries
# Get the data from  https://www.tiingo.com/  by using pandas get_data_tiingo()
# Convert the data into csv. 
# Read the CSV file.
# Do some EDA.
# After this the values from the ‘close’ column, we need to scale them. Normalizing data, scale between 0 and 1, This makes our Model performs better!
# Splitting dataset into train and test; split 65 % data for training purpose and rest for testing.
# Reshape input to be [samples, time steps, features] which is required for LSTM.
# Create the Stacked LSTM model.
# Lets Do the prediction and check performance metrics.
# Transform back to original form.
# Calculate RMSE performance metrics.
# Demonstrate prediction for next 10 days.
