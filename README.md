# Objective
In order to improve my skills and do some exercises on data analytics, I've started analyzing Apple Stock Dataset that I've got it from Kaggle. The dataset is related to stock trading on Apple from 1980 to 2025. Each record represents a trading day along with the prices and volume. This dataset provides historical data of APPLE INC. stock (AAPL). The data is available at a daily level. Currency is USD. The dataset consists of 11107 records and 7 columns along with outlier values, wrong entries and different price formats that I found it later as I analyzed it in detail. I am planning to use Excel, Python and PowerBI to analyze, implement ML algorithms on dataset and visualize all of the things related to dataset. 

# Columns
* Date : Represents trading day.
* Open : Price from the first transaction of a trading day
* High : Maximum price in a trading day
* Low : Minimum price in a trading day
* Close : Price from the last transaction of a trading day
* Adj Close : Closing price adjusted to reflect the value after accounting for any corporate actions
* Volume : Number of units traded in a day.

# Files' Content
* apple_stock_raw_data : Represents raw dataset that I've got from Kaggle in csv format.
  
* apple_stock_as_xlsx : Represents raw dataset in xlsx format that I've turned into from the raw dataset in csv format
  
* Apple_Stock_ChatGPT_Recommendations : This file shows that analyses and ML algorithms that ChatGPT recommended and I could implement on this dataset
  
* apple_stock_main_file:
> This is the Excel file that I've started doing analyses. In this file, I've found out the descriptive statistics on this dataset. Then I've realized that columns have outliers, wrong data entries (date format values in prices) and different date formats because of the dots and commas. At this point, I've assumed that wrong data entries are null values. Then, I've created box-plots, line charts and histograms of numerical columns. After that I've performed correlation analysis and found insights about all of the things I've found. Finally I created a pivot table of price and volume values based on the date column.
  
* Volatility_Analyses_In_Apple_Stock :
> This file includes Volatility analysis and moving average calculations of me on price columns. Before doing that, I've preferred removing null values since they are wrong data entries and keeping outliers since they give us clues about price swings and therefore, volatility. Then I've found insights according to the volatility values. Finally, I've tried calculating simple moving average values on 5 consecutive trades for each price column. I will be doing detailed analyses for moving averages on Python.

* AppleStock_PowerBI : This file includes the dashboard that I started creating on PowerBI for AppleStock dataset. It's not completely ready yet but you could look at it to get to know about my PowerBI skills.
