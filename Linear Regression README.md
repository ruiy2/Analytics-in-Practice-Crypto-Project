# Analytics-in-Practice-Crypto-Project

READ ME

This project aims to build a linear regression model using Python. There are 4 seperate Linear Regression python notebooks. 
This READ ME corresponds to all 4 notebooks. See notebook names below:
1. BTC Regression with Financial Market 2023.ipynb
2. MATIC Regression with Financial Market 2023.ipynb
3. SOL Regression with Financial Market 2023.ipynb
4. ETH Regression with Financial Market 2023.ipynb

The model uses the following libraries and packages:

yfinance: to download stock market data
numpy: for mathematical operations
pandas: for data manipulation and analysis
matplotlib: for data visualization
seaborn: for enhanced data visualization
statsmodels: for building the linear regression model
To run this project, you must first ensure that the necessary packages and libraries are installed. If not, please uncomment the pip install lines and run them in the terminal or command prompt.


Data and Dependancy Files:

Majority of the data is downloaded through the yfinance API, however there are two excel files that will need to be dowloaded and saved it the same file location. 

Depency Files: 

Bond Yield Relative to Yield on 10-Year Treasury (BAA10Y) Data: 
    Link: https://fred.stlouisfed.org/series/BAA10Y save as BAA10Y.csv in the same file location as the .ipnyb file. 
    Important note: Dowload the the daily percetage data not the daily pricing data. This can be done on the tool icon   
    next to the graph. You should dowload from 2020-01-01 on.
    
MSCI Intl Emerging Market Currency Data (em_currency): 
    Link: https://www.investing.com/indices/msci-intl-em-currency-historical-data save as MSCI Intl Emerging Market Currency 
    Historical Data.csv in the same file location as the .ipnyb file. You should dowload from 2020-01-01 on.
    

Data cleaning:
The downloading of the data, and clenaning the data is done in the method lr_data_cleanser(start_date=str,end_date=str, interval_='str) and eq_lr_data_cleanser(start_date=str,end_date=str, interval_='str) This step may includes downloading data, merging data, removing missing values, column renaming and feature selection

lr_data_cleanser method and the eq_lr_data_cleanser method takes in 3 optional arguements:
1.) start_date="yyyy-mm-dd" (data type: string)
2.) end_date="yyyy-mm-dd" (data type: string)
3.) interval_= any of the following 1m, 2m, 5m, 15m, 30m, 60m, 90m, 1h, 1d, 5d, 1wk, 1mo, 3mo (data type: string)

The regression models are built using ordinary least squares (OLS). We use the statsmodel library for this

