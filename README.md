# Bitcoin_Market_Analysis

This is a simple demonstration of how cryptocurrency analysis using Python can be implemented.We walk through a simple Python script to retrieve, analyze, and visualize data on different cryptocurrencies. In the process, we will uncover an interesting trend in how these volatile markets behave, and how they are evolving. My main goal here is procuring the raw crypto-currency data and uncovering the stories hidden in the numbers.

Requirements:
import os
import numpy as np
import pandas as pd
import pickle #We're using pickle to serialize and save the downloaded data as a file
import quandl
from datetime import datetime

Steps:
1. Import Dependencies
2. Create function to get data from quandl API
3. Pull from major BTC exchanges
4. Build Scatterplot to visualize how the dataset compare
5. Clean and Aggregate the Pricing Data
6. Retrieve Altcoin Pricing Data and Download Trading Data From Poloniex
7. Visualize all datasets
8. Perform Correlation Analysis

All steps have been described and implemented in the Jupyter Notebook

Reference Links:
1. http://www.quantatrisk.com/2017/03/20/download-crypto-currency-time-series-portfolio-python/
2. https://nbviewer.jupyter.org/github/ghgr/HFT_Bitcoin/blob/master/hftbitcoin.ipynb
3. https://medium.com/towards-data-science/predicting-bitcoins-market-cap-early-ml-inroads-to-pre-processing-part-1-5a85aefd4c7d

