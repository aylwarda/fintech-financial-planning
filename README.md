# fintech-financial-planning
This project is my FinTech homework, incorporating Pandas, the use of APIs (Alpaca, etc.) and financial analysis.  It uses a Jupyter Labs Notebook and my work builds on coursework that I am involved in.

---
## Instructions
Within this Project, there is one main Jupyter Notebook.
 - Financial Planner (financial_planner.ipynb)

All one need do, is to execute the Notebook and read the comments, noting the data and/or graphs that are returned.

### Financial Planner - Part 1
*Part 1* is simply a retrieving of stock/crypto data using the Alpaca Markets API (stocks and bonds) and Alternative Crypto API, then determining ones total savings, given an asset mix of shares and crypto.  
More on APIs: -
 - Alpaca and their Alpaca Markets API (v2), found [here](https://alpaca.markets/docs/api-documentation/api-v2/)
 - Alternative software and their Free Crypto API, found [here](https://alternative.me/crypto/api/)

### Financial Planner - Part 2
*Part 2* is all about a number of Monte Carlo Simulations against data (similarly pulled from Alpaca) for `SPY` and `AGG` with a 60/40 portfolio weighting respectively.

The simulation data is then plotted to show the potential cumulative returns, distribution and other useful bits and pieces; then that data used to understand the impact to an initial investment of $20k, increasing that simulated investment using the 95% percentile for each distribution.

I say sumulations (plural), as the simulations start with extrapolation over 30 years with a weighted split of 40% bonds and 60% stocks over 30, then over 5 years, then 10, all the while altering the initial investment.

What is obvious from the simulations and differing initial investments, weightings, etc. is that the old saying of 'time in the market over timing the market' holds true.  From the results, which you as the reader of this README will determine for yourself (one hopes), one can see that one would have to throw an ordinate amount of initial capital at an evenly weighted portfolio (given it is contant) to attempt to "catch up" to a portfolio that started with a fairly conservative amount but early on, thus gaining the benefit of compounding returns over time.

Anyway, have a squiz; you'll see the results for yourself.

---
## Acknowledgements
### Sources
- The Monte Carlo Simulation Python (the [MCForecastTools.py](./MCForecastTools.py) file itself and therefore its logic) is not my own and was supplied by the University/Trinity Education, along with the skeleton structure of the Notebook (e.g. markdown headings).
- Although I didn't end up using it, I learnt that one can reset the index of a DataFrame which is useful if you want to get at the index data.  Perhaps there is another way (there always is :)), but I found that cool.  Details found at Stackoverflow, [here](https://stackoverflow.com/questions/56131833/extract-data-from-index-in-new-column-in-dataframe).