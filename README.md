# Fianace-ML
## I. Stock Returns Prediction:
### Contents:
- perform EDA to understand the financial data to be analysed
- perform Feature Engeneering
- predict 5 day future percentage return using different models
### Tools:
- create moving averages and rsi
- dummy coding for day of the week
- LinearRegressor, RandomForestRegressor, GradientBoostingRegressor, KNN
- feature importance
- neural Networks with custom loss function, dropout and ensembling
## II. ML for Modern Portfolio Theory
### Contents:
- combine six stocks and create a combined portfolio
- generate random portfolios with random weights on the three stocks to compute efficient frontiers
- calculate an optimal portfolio by selecting the portfolio with best sharpe ratio
- predict the portfolio weights using a RandomForest Regressor with exponentially weighted moving averages of prices
- compare return of predictions on portfolio with individual stock
### Tools:
- MPT, Sharpe Ratios
- RandomForestRegressor
## III. Debts Discontinuity
###Backgrounds:
- after a debt has been legally declared "uncollectable" by a bank, the account is considered "charged-off." But the bank will score the account to assess the expected recovery amount, that is, the expected amount that the bank may be able to receive from the customer in the future
- this amount is a function of the probability of the customer paying, the total debt, and other factors that impact the ability and willingness to pay
- the bank has implemented different recovery strategies at different thresholds (1000, 2000, etc.) where the greater the expected recovery amount, the more effort the bank puts into contacting the customer
- each additional level of recovery strategy requires an additional 50 per customer so that customers in the Recovery Strategy Level 1 cost the company 50 more than those in Level 0
Contents:
- explore whether there is a discontinuity of more than 50 in the amount recovered at the higher strategy level
