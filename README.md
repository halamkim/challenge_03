# Bitstamp vs Coinbase Arbitrage 

The file calculates profits by comparing the prices on the two exchanges (Bitstamp and Coinbase) and determining the potential profits that could have been made by buying bitcoin on one exchange and selling it on the other. 

## Requirements
- Python 3.6 or higher
- Jupyter Lab
- Pandas
- Matplotlib
- Pathlib

## Installation
1. Install **Python 3.6** or higher on your computer (if not already installed).
2. Go into your dev environment and open **Jupyter Lab Notebook** 
3. Install the required libraries by running the following command:
``` 
% from pathlib import Path
% import pandas as pd
% matplotlib inline
```

## Output
This file generates data for the whole duration (2018-01-01 - 2018-03-31) and goes deeper into seeing one month at a time and certain dates. It compares 3 specific dates (2018-01-01, 2018-02-15, and 2018-03-31) and shows line graphs and box and whiskers plots. Lastly, it shows graphs that show profits over 1$. 

Please note that selecting different dates produce different results. 