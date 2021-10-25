# personal-financial-planner

This project creates a financial planner for emergencies and for retirements. Users will be able to use this tool to visualize their current savings, and then determine if they have enough reserves for an emergency fund based off of 3x their monthly income. Users will also be able to forecast the performance of their retirement portfolio in 30 years and 10 years based off of Monte Carlo simulations using the Alpaca API. Users will be able to determine the 95% confidence interval in which their portfolio value will end in after the selected number of years.

## Technologies

This project leverages Python 3.7 with Pandas, Numpy, os, requests, json, dotenv, Alpaca, and MCForecastTools.


## Installation Guide

No additional installs are required. Alpaca API Key and Secret Key required.

## Usage

Before using the notebook, be sure to have an Alpaca API Key and Secret Key stored in a .env file labeled "API.env". Input the keys under: 

ALPACA_API_KEY = "<YOUR ALPACA API KEY HERE!>"
ALPACA_SECRET_KEY = "<YOUR ALPACA SECRET KEY HERE!>"

Then, simply clone the repo and open the financial_planning_tools.ipynb notebook in order to review the analysis.

## Contributors

Brough to you by Austin Do. Email: austindotech@gmail.com

## License

MIT