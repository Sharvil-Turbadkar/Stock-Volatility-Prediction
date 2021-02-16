# Stock-Volatility-Prediction

# R Packages Used
### tidyverse,ggplot2,quantmod,fastDummies

# Aim
Our project goal is to predict the value of beta by building several time-series models and comparing the prediction with the beta value we computed from the CAPM formula.

## What is Beta
Beta measures the volatility of an individual stock in relation to the overall market. The beta of the individual stock measures the degree of its deviation from the market. A beta value larger than one represents the stock swings more than the market stock. If a stock's beta is less than one, it means that the stock has a lower movement than the market. In this project, we utilized different features to build the time series model and predict the beta value.

#Approach
1.Download stock and Dow jones data from yahoo.com
	
2.Download risk free rate from Federal reserve bank of St Louis 
	
3.Add trend and seasonal variables (4 seasons)to the dataset

4.Add dummy variables (two if three stocks are considered)
	
5.Compute true beta value by using actual CAPM formula 
	
6.Forecast using time series modelling
	
7.Compute p-value for all predictors and using backward propagation remove attributes that have high p-values
	
8.Interpreting and summarizing the model
	


# Results

# Recommendations:
