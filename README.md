# Financial-Analysis

![Share-Holdings-2](https://user-images.githubusercontent.com/107895872/236651272-e41b7ef0-bf09-48a7-a43f-8c47efaffd30.jpg)

BlackRock is a large MNC that holds world's largest investment portfolio worth $10 Trillion. Financial analysis was done to know the fundamentals and technicals of the company using different methods using Balance Sheets, Income and Cash Flow statements to calculate different ratios and trend analysis for 4 years from the year 2019 to 2022. All the statements were collected from the Yahoo finance official website and the analysis & visualiztion was done using Microsoft Excel.

## Different Ratio Analysis
  ### Liquidity Ratio
  ```
  In Liquidity ratio we measure how much company is capable to meet its short term obligations or debt. 
  This ratio helps investors and lenders to determine whether the company is able to generate sufficient 
  cash flow to pay-off their short term debt (generally <= 1 year). 
  
  There are generally 3 types of ratios to calculate the company's cash and asset liquidity.
    1. Cash Ratio
    2. Quick Ratio
    3. Current Ratio
  ```
  ![liquidity](https://user-images.githubusercontent.com/107895872/236649548-9ed09ee4-f66e-4706-b386-3b26547d246a.jpg)
  
  
  ### Solvency Ratio
  ```
  In this ratio we measure how much company is capable to meet it's long term obligations or debt. This ratio helps investors 
  and lenders to determine whether the company is able to generate sufficient cash flow to pay-off their long term debt 
  (generally more than 1 year). 
  
  There are generally 2 types of ratio's
    1. Debt-to-Equity Ratio
    2. Solvency Ratio
  ```
![Solvency](https://user-images.githubusercontent.com/107895872/236651638-e50495bc-f368-4ffc-9916-c6e134b03a7b.jpg)

  
  
  ### Profitability Ratio
  ```
  In this ratio we assess the ability of the company to generate profits relative to its Sales, Assets and/or Equity. 
  This is one of the financial health indicator to measure its efficiency of making profits from its operations.
  
  There are generally 4 types of ratios to calculate the company's profitability.
    1. Return on Equity (ROE)
    2. Return on Assets (ROA)
    3. Operating Profit Margin (OPM)
    4. Gross Profit Margin (GPM)
  ```
![Profitability](https://user-images.githubusercontent.com/107895872/236649866-11d7915c-6d8b-4cca-91f1-2168705545ae.jpg)


### Turnover Ratio
  ```
  In this ratio we assess how company is efficiently making use of it's assets and resources to generate revenue.
  It shows how many times a company has converted it's assets into sales over a particular period of time.
  
  There are generally 2 types of ratios to calculate the company's turnover.
    1. Accounts Receivable Ratio
    2. Accounts Payable Ratio
  ```
![Turnover](https://user-images.githubusercontent.com/107895872/236651641-0e7857f7-cfd1-4d40-b2f8-a34a69b131d1.jpg)


### Earning Ratio
  ```
  Earnings per share (EPS) is a financial ratio that measures the amount of net income earned by a company per share of its outstanding common stock. 
  It is a commonly used financial metric to assess a company's profitability and is a key component of many fundamental analyses.
  A higher EPS generally indicates that a company is more profitable and has better earnings potential, making it more attractive to investors. 
  However, it is important to note that a higher EPS does not necessarily guarantee a company's long-term financial health, as it can be influenced by 
  various factors such as changes in the company's revenue, expenses, and outstanding shares. It is recommended to evaluate EPS in conjunction with other 
  financial metrics to gain a more comprehensive understanding of a company's financial performance.
  ```
![Earning](https://user-images.githubusercontent.com/107895872/236651647-eeec34b7-addf-43ca-8a06-97d753733590.jpg)


## WACC (Weighted Average Cost of Capital)
  ```
  In this ratio we calculate the company's average cost of company's capital, including debt and equity. 
  It represent's minimum rate of return that company must earn on it's investments. This is useful for metric for company and investors.
  ```
![WACC](https://user-images.githubusercontent.com/107895872/236650311-31d39be3-d613-4671-81cc-063f9fdb2922.jpg)


## Monte-Carlo Analysis
  ```
  Monte Carlo analysis, also known as Monte Carlo simulation, is a statistical technique used in finance to model and analyze the potential 
  outcomes of an uncertain event or decision. Monte Carlo analysis involves the use of random sampling techniques to generate a large number 
  of possible outcomes for a particular scenario or decision. These outcomes are then analyzed to determine the probabilities of different 
  outcomes occurring and to identify potential risks and opportunities. 
  Monte Carlo analysis can be used in a wide range of financial applications, such as option pricing, risk management, and portfolio optimization. 
  It is particularly useful for complex scenarios with many variables and uncertainties, where traditional analytical methods may not be sufficient.
  ```
![Monte-Carlo](https://user-images.githubusercontent.com/107895872/236650644-3e13a265-6ab1-4317-9fcf-e9b0e1c8558f.jpg)


## Trend Analysis
  ```
  Trend analysis is a technique used in financial analysis to identify and evaluate the direction and magnitude of changes in key financial metrics over time. 
  It involves the comparison of financial data from multiple periods to identify patterns and trends in a company's financial performance. 
  Trend analysis is particularly useful for identifying long-term trends and forecasting future financial performance. By analyzing historical data, 
  financial analysts can make informed predictions about a company's future financial performance and use this information to make investment decisions.
  ```
![Trend](https://user-images.githubusercontent.com/107895872/236650757-7aeb3388-87ca-4f57-aa36-c09630232e1f.jpg)


## Time Series Analysis
  ```
  Time series analysis is a statistical technique used in financial analysis to analyze and forecast trends over time. It involves the analysis of 
  historical data on a particular financial metric, such as stock prices, sales revenue, or GDP, to identify patterns, trends, and relationships 
  between variables. The primary objective of time series analysis is to identify patterns and trends in historical data and to use this information 
  to make predictions about future trends and behavior. To achieve this objective, financial analysts use a range of statistical models and techniques, 
  including autoregressive integrated moving average (ARIMA), exponential smoothing, and Fourier analysis.
  time series analysis is a powerful statistical technique that can provide valuable insights into the behavior of financial metrics over time and help 
  analysts and investors make informed decisions based on historical data and future trends.
  ```
![time-series](https://user-images.githubusercontent.com/107895872/236651339-6756348c-a1f2-42a0-9778-af3092b55abf.jpg)


## Facebook Prophet
  ```
  Prophet uses an additive model that combines four key components of a time series: trend, seasonality, holidays, and error. It can handle missing data 
  and outliers, and automatically detects changes in trend and seasonality over time. Prophet is designed to be easy to use and has a simple and intuitive 
  interface. Users can input their time series data and configure various parameters such as seasonality and holidays. Prophet then automatically generates 
  a forecast and provides visualizations of the forecast and its components. One of the key features of Prophet is its ability to handle multiple seasonalities, 
  such as weekly, monthly, and yearly seasonality, which can be particularly useful for analyzing data with complex seasonal patterns.
  ```
  ![FB-Prophet](https://user-images.githubusercontent.com/107895872/236651406-bf98916c-d52a-4dab-9330-91fdf8a6c91c.jpg)

  ![FB-Prophet-2](https://user-images.githubusercontent.com/107895872/236651401-ca4158dd-c095-4f0c-98c8-635110ccf98d.jpg)
  
  
## Dashboard
  ```
    Further, I have prepare dashboard to visualiza all the analysis in a single frame and give better insights about the
  ```
  ![Dashboard](https://user-images.githubusercontent.com/107895872/236651177-23c13a1f-eb1a-4e82-b574-427e0485c836.jpg)
