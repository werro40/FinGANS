# FinGANS
Using GANs to opimize a stock portfolio for long term profitability.
Based on this paper: https://arxiv.org/pdf/1901.01751.pdf

Feature selection: https://arxiv.org/ftp/arxiv/papers/2005/2005.12483.pdf

The plan is to follow this 3 step procedure:

1) Financial Data Science
-Identify features not publicly available to avoid arbtirage.
-convert raw data into features

2) Machine Learning Model
-Use GANs
-avoid overfitting
-run multiple forecasts
-yahoo finance API

3) Construct Trading Strategy
-Use predictions in more elaborate trading strategy
-Test to see if predictions are accurate
