# Housing-Market-Price-Prediction
Predicting Future House Prices.

Project Overview¶


In this project, we'll predict future house prices. We'll use economy data from the U.S Federal Reserve, along with house price data from Zillow. We'll merge and combine this data, then use it to train a random forest model. The model will predict if house prices will increase or decrease in the future.

We'll measure error using backtesting, then improve our model with new predictors.

Objective: prediction of future house price changes in New york, United States

Files Needed:
Federal reserve data

CPI dataset - CPIAUCSL.csv:US CPI (inflation measure) [The CPI can be used to recognize periods of inflation and deflation. Significant increases in the CPI within a short time frame might indicate a period of inflation, and significant decreases in CPI within a short time frame might indicate a period of deflation.]

Rental vacancy rate - RRVRUSQ156N.csv : rental vacancy rate, quarterly(rental properties that are vacant)
[The rental vacancy rate is the proportion of the rental inventory that is vacant for rent.]


Mortgage interest rates - MORTGAGE30US.csv :mortgage interest rates, weekly[30-Year Fixed Rate Mortgage Average in the United States (MORTGAGE30US)]
Metro_median_sale_price_uc_sfrcondo_week.csv - median sale price for US houses



Zillow data
ZHVI (raw, weekly) - Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv : Zillow home value index
Median sale price (raw, all homes, weekly) - Metro_median_sale_price_uc_sfrcondo_week.csv


