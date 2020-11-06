# Walmart-Store-Sales-Prediction

#### The aim of the project is to predict the store sales from historical data from 45 Walmart stores in the State. First, through data visualization, we could know more about the data. After that, two forecasting models has been developed. 
To know more about thee meta data, please refer to Kaggle. 

### Project Outline:
1.	Knowing Data

    1.1	About time series
    
        1.1.1 Loading data
    
        1.1.2 Data preprocessing 
    
        1.1.3 Visualizing data
  
    1.2 About other feature
    
        1.2.1 Loading data
    
        1.2.2 Visualizing data

2. Building Models
  
    2.1 Timeseries forecasting by FBProphet
  
    2.2 Timeseries forecasting by ARIMA
    
        2.2.1 Dickey-Fuller test
    
        2.2.2 ARIMA modeling
    
        2.2.3 Finding the best parameters and evaluating
        
        2.2.4 The result of the predictions  



### File description: 
Train.csv: 
-	Store: 45 stores' number
-	Dept: Department of the store
-	Date: Recorded week
-	Weekly_Sales: Sales amount at that date
-	IsHoliday: If that week is the holiday week marked True. 

features.csv: 
- store: Store number
- Date: The recorded week
- Temperature: average temperature in the region
- Fuel_price: Cost of fuel
- MarkDown 1-5 - anonymized data related to promotional markdowns that Walmart is runnung. 
- CPI: Consumer price index
- Unemployment: the unemployment rate
- IsHoliday: If that week is the holiday week marked True. 

### Results:
- There is not specific factor will affect the sales amount, except time. 
- Through two different time series model, we could forecast the trend of the future sales amount and the trend. 
- Based on the FBProphet model, the selling trend is increase. And selling amount in February is the floor during a year, but the trend will rapidly go high at the end of a year. 
- Based on the ARIMA model, we could specifically predict the selling amount with pretty well Mean Absolute percentage error.

### Reference:
Data source from [Kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting). 
