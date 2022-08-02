# Impact-of-COVID-19-on-GDP
Analysed the effect of COVID-19 on the GDP of the influential nations of the world
Objective: To study the impact of COVID-19 on GDP of influential nations of the world

## Countries included in the study:
United States of America (North America)
France (Europe)
India (Asia)

## Data Source :   https://datacatalog.worldbank.org/public-licenses#cc-by

## Preparation
No missing values found
Data frame transposed for desirable format to visualize

## Exploratory Data Analysis (Tableau)

### United States of America
2020 = Pandemic Year
2008-09 = Great Economic Depression
1991 = Economic Recession
1982 = Tight monetary policy in an effort to fight mounting inflation

### India
2020 = Pandemic Year
2008-09 = Great Economic Depression
1991 = Economic Recession
1982 = Tight monetary policy in an effort to fight mounting inflation

### France
2020 = Pandemic Year
2008-09 = Great Economic Depression
1992-93 = Economic Recession


## Models Used:
ARIMA
Prophet by Facebook
RNN
Long Short Term Memory (extended version of Simple RNN)


### ARIMA
A statistical model which takes an order of (p,d,q) for time series forecasting
The data Stationarity is required

Parameters to ARIMA:
p = the number of lagged terms which are related to the current values
d = the number of times differentiation needs to be done to make the data    stationary
q = the number of forecast error terms to be considered in the model training


### Prophet
A black box model developed by Facebook , for generating automatically the forecasted terms for a series and plotting the same on the graph
Model did not perform well in this problem, it generalized too well in the training set and could not perform well on the test set.
Model has high root mean square error compared to other models



### LSTM 
Long Short Term Memory is modification of RNN to take into account long term memory as well as short term memory
It adds 3 gates : input gate (from previous layer), forget gate ( checks if the info is useful to be carried forward), 
output gate ( checks how much of this information should be carried forward)


## Model Evaluation
Root Mean Square Error - it is the measure of spread of the error of prediction from regression line.
ARIMA model performed the best according to RMSE comparison.

## Results:
The impact in the US was seen from the Q2 of 2020, when the lockdown was implemented.
The cases in the US also soared and were the highest in the world. The impact on the US economy is -1.6

The impact on India was seen from the Q2 to Q3 of 2020, when the lockdown was implemented.
The cases in the India were second highest and started to soar in the september Q3, 2020.
The impact on the Indian economy was -5.63


The impact in France was seen from the Q1 to Q3 of 2020, when the lockdown was implemented.
The cases in France were the fourth highest and started to soar in the september Q3, 2020.
The impact on the french economy was -1.9

## Conclusion:
Devastating impact on the world economies
The impact of COVID-19 was the highest on the Indian GDP, followed by France and then America.
India has the second largest population followed by the US and France is not even in the top 10 list.
Having mentioned the fact, France is second most impacted country, so if we see the impact individually on people it was very high compared to the US and India.










