# fintech-financial-planning
This project is my FinTech homework, incorporating Pandas, the use of APIs (Alpaca, etc.) and financial analysis.  It uses a Jupyter Labs Notebook(s) and my work builds on coursework that I am involved in.

---
## Instructions
Within this Project, there is one main Jupyter Notebook.
 - Financial Planner (financial_planner.ipynb)

All one need do, is to execute the Notebook and read the comments, noting the data and/or graphs that are returned.

### Financial Planner - Part 1
Part 1 is simply a retrieving of stock/crypto data using the Alpaca Markets API (stocks and bonds) and Alternative Crypto API, then determining ones total savings, given an asset mix of shares and crypto.
More on APIs: -
 - Alpaca and their Alpaca Markets API (v2) found [here](https://alpaca.markets/docs/api-documentation/api-v2/)
 - Alternative software and their Free Crypto API found [here](https://alternative.me/crypto/api/)

### Financial Planner - Part 2
Part 2 is all about a Monte Carlo Simulation against data (similarly pulled from Alpaca) for `SPY` and `AGG` with a 60/40 portfolio weighting respectively.

The simulation data is then plotted to show the potential cumulative returns, distribution and other useful bits and pieces.

---
## Acknowledgements
### Sources
- Although I didn't end up using it, I learnt that one can reset the index of a DataFrame which is useful if you want to get at the index data.  Perhaps there is another way (there always is :)), but I found that cool.  Details found at Stackoverflow, [here](https://stackoverflow.com/questions/56131833/extract-data-from-index-in-new-column-in-dataframe).