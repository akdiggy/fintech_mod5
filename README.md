# fintech_mod5

# Financial planning for emergencies and retirement

Two financial analysis tools were created using a single Jupyter notebook the perform the following:


1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Technologies

Install the MCForecastTools.py file in the same directory that you store the financial_planning_tools.ipynb file before trying to execute. 

You will need to create a .env file and enter the following credentials in it to be able to retreive data from Alpaca:

* ALPACA_API_KEY = "<enter your value here>

* ALPACA_SECRET_KEY = "<enter your value here>"

The ipynb file was run using VC Code version 1.74.2.
