# FINTECH-Project-01

## Team 07
* Corey Recai
* Louis Zibi
* Toufic Lawand

## Project summary
This project aims to compare the US financial market performance (SPY at the macro level) over the period between Nov 2019 and Apr 2020 vs. Covid-19 cases (_11/19 through 4/20 vs 11/18 through 4/19_).

Throughout our analysis, we will be covering the following sectors:
* technology (toufic)
* commercial real estate (corey)
* retail (louis)

## Datasets used
* Bureau of Labor Statistics (for unemployment data)- https://fred.stlouisfed.org/series/UNRATE
* Bureau of Economic Analysis (for gdp data) - https://www.bea.gov/data/gdp/gross-domestic-product
* S&P Dow Jones Indices (for S&P500 data) - https://us.spindices.com/indices/equity/sp-500
* NY Times COVID-19 repo - https://github.com/nytimes/covid-19-data/

## Tools used
* Python libraries:
 * Pandas (for dataframes and analysis)
 * Numpy
 * PyViz libraries (for vizualization)
* Alpaca/Quandl API's for stock data
* HTML/CSS + JavaScript, Flask, or Django for dashboard (optional)

## Questions
1. How has the COVID-19 pandemic affected the US economy and the financial markets?
2. Out of the three sectors we've chosen (technology, commercial real estate, and retail), which sector has been hit the most? And which one has benefited the most (if any)?
3. Which (publicly listed) companies have gained the most from the COVID-19 pandemic? And which have lost the most?
4. If we were to pick one of the top 5 performers and one of the bottom 5 performers from each sector we're examining, what is the range of their expected price in 5 years for a 90% confidence interval? (based on historical data for the past _20 years_ if available)

## Process
1. Collecting data
2. Create data frames to perform basic financial analysis
 * moving averages
 * standard deviation
 * average returns
 * sharpe ratios
3. Visualizing data
4. Present data in dashboard

## Project outline

### Introduction
* Purpose of project
* Motivation
* Executive summary

### Macro analysis
Analysis of macro-economic and financial performance for the period between Q4 '19 and Q1 '20 vs Q4 '18 and Q1 '19. The analysis will include:
* SPY data --> Toufic
* unemployment rate --> Corey
* gdp growth rate --> Louis

### Deep dive into sectors

#### Technology --> Toufic
* Performance for the current period:
  * Top 5 performers in the sector
  * Bottom 5 performers in the sector
* Sector performance vs same period in the previous year
* Forecasting one of the bottom 5 and one of the top 5 performers' price 5 years from now

#### Commercial real estate --> Corey
* Performance for the current period:
  * Top 5 performers in the sector
  * Bottom 5 performers in the sector
* Sector performance vs same period in the previous year
* Forecasting one of the bottom 5 and one of the top 5 performers' price 5 years from now

#### Retail --> Louis
* Performance for the current period:
  * Top 5 performers in the sector
  * Bottom 5 performers in the sector
* Sector performance vs same period in the previous year
* Forecasting one of the bottom 5 and one of the top 5 performers' price 5 years from now
