# Mutual Fund Return Prediction - Mini Project

## Our client is a fund management firm

- The firm aims to develop a robust machine learning model to predict
the returns of a mutual fund after a 3-year investment period.
- Will it be High or Low?

## Current Practice

Traditional investment analysis techniques fall short in accurately forecasting mutual fund performance due to their reliance on historical data and qualitative factors.

## Our Role as Consultants

- We intend to leverage machine learning's power to process extensive data and uncover hidden patterns, enhancing our investment decision-making.

- With a tailored predictive model, we strive to provide clients with valuable insights for informed investment choices.

## Problem Specifics
Deliverable: <b> Predict whether an investment will give High or Low returns. </b> <br>
Machine learning task: <b> Classification </b> <br>
Target variable: <b> Return_3yr(Tagret Category) [High Return / Low Return] </b> <br>
Model win condition: <b> Accuracy (Baseline Acc. is 90%)

# Data Description

- Scheme Name: Name of the mutual fund scheme
- Min sip: Min sip amount required to start
- Min lumpsum: Min lumpsum amount required to start. A larger amount that is invested in one go
- Expense ratio: calculated as a percentage of the Scheme's average Net Asset Value (NAV). Its basically the commission
- Fund size: the total amount of money that a mutual fund manager must oversee and invest
- Fund age: years since inception of scheme
- Fund manager: A fund manager is responsible for implementing a fund's investment strategy and managing its trading activities. (Remove)
- Sortino : Sortino ratio measures the risk-adjusted return of an investment asset, portfolio, or strategy
- Alpha: Alpha is the excess returns relative to market benchmark for a given amount of risk taken by the scheme
- Standard deviation: A standard deviation is a number that can be used to show how much the returns of a mutual fund scheme are likely to deviate from its average annual returns
- Beta: Beta in a mutual fund is often used to convey the fund's volatility (gains or losses) in relation to its respective benchmark index
- Sharpe: Sharpe Ratio of a mutual fund reveals its potential risk-adjusted returns
- Risk level: <br>
    1- Low risk <br>
    2- Low to moderate <br>
    3- Moderate <br>
    4- Moderately High <br>
    5- High <br>
    6- Very High
- AMC name: Mutual fund house managing the assets
- Rating: 0-5 rating assigned to scheme
- Category: The category to which the mutual fund belongs (e.g. equity, debt, hybrid)
- Sub-category : It includes category like Small cap, Large cap, ELSS, etc.
- Return_3yr(Tagret Category): The return type of the mutual fund scheme over 3 year
   1- High Return
   0- Low Return

  <h1><center>
Conclusions from Exploratory Data Analysis
</center></h1>

- The Categories that we found to have high returns are Equity and 'Others'
- We have shown the sub-categories that give relatively high return.
- Analysis remains to be done: which sub-categories have guranteed High Retun (no Low Return)
- Fund ages between 6-9 years are better, beyond 10 years the the schemes do not show advantage (more Low return)
- As expected - high risk funds yeild more benefit


