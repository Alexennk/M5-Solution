# M5-Solution
"M5-Forecasting Accuracy" Kaggle challenge solution

# **About Dataset**

**Problem:** https://www.kaggle.com/competitions/m5-forecasting-accuracy/overview

In the challenge, you are predicting item sales at stores in various locations for two 28-day time periods.

### **Files**
- *calendar.csv* - Contains information about the dates on which the products are sold.
- *sales_train_validation.csv* - Contains the historical daily unit sales data per product and store [d_1 - d_1913]
- *sample_submission.csv* - The correct format for submissions. Reference the Evaluation tab for more info.
- *sell_prices.csv* - Contains information about the price of the products sold per store and date.
- *sales_train_evaluation.csv* - Includes sales [d_1 - d_1941] (labels used for the Public leaderboard)

# **All needed data:** https://drive.google.com/drive/folders/1Rle2Ysxht92-Ot-wRrVk5Y3p2-EJhH2B?usp=drive_link

# **Steps made**
- EDA
- Applying LightGBM and DummyRegressor to forecast
- Analysis of the problem: what methods were used and why
- Thoughts about the competition using a Weighted Root Mean Squared Scaled Error
