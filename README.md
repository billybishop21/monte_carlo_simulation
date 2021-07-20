# Monte Carlo Simulation

## Financial Analysis for Members of the Credit Union

This project entails building a tool to help credit union members evaluate their financial health. Specifically, the client needs the following:

* The program should be able to assess the clients monthly budgets.
* The program should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds.

## Technologies

The following technologies needed to run the program:

```python
import os
import requests
import json
import pandas as pd
import numpy as np
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```

## Program Information

1. Created a financial planner for emergencies.
2. Evaluate the cryptocurrency wallet by using requests library.
3. Evaulated the stock and bond holdings by using Alpaca SDK.
4. Evaulated the current status of the emergency fund.
5. Created a financial planner for retirement using Monte Carlo Simulations.
6. Analyzed retirement portfolio forecasts.
7. Forecasted cumulative returns in 10 and 30 years.


## Contributors

Analysis is brought to you by Billy Bishop

## License

MIT
