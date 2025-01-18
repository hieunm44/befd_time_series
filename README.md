# BEFD Project - Time-Series Forecasting
<div align="center">
<a href="https://www.math.unipd.it/en/">
   <img src="https://www.math.unipd.it/~tommasi/dueloghi.png" height=100"/>
</a>
</div>

## Overview
This repo is our project "Time-Series Forecasting" in the course "Business Economics and Financial Data" at Università degli Studi di Padova (UniPd).

## Built With
<div align="center">
    <a href="https://finance.yahoo.com/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8f/Yahoo%21_Finance_logo_2021.png" height=40 hspace=10/>
    </a>
    <a href="https://pandas.pydata.org/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" height=40 hspace=10/>
    </a>
    <a href="https://numpy.org/">
        <img src="https://numpy.org/images/logo.svg" height=40 hspace=10/>
    </a>
    <a href="https://matplotlib.org/">
        <img src="https://matplotlib.org/_static/logo_light.svg" height=40 hspace=10/>
    </a>
    <a href="https://scikit-learn.org/stable/">
        <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" height=40 hspace=10/>
    </a>
    <a href="https://xgboost.readthedocs.io/en/stable/">
        <img src="https://raw.githubusercontent.com/dmlc/dmlc.github.io/master/img/logo-m/xgboost.png" height=40/>
    </a>
</div>

## Usage
1. Clone the repo
   ```sh
   git clone https://github.com/hieunm44/befd_time_series.git
   cd befd-time-series
   ```
2. Install necessary packages
   ```sh
   pip install -r requirements.txt
   ```
3. Check and run the file `Gen_Dataset.ipynb` to create the dataset (`yfinance_data.csv`).
4. Check and run two files `EUR_USD_Analysis.ipynb` and `BTC_USD_Analysis.ipynb` to load the data and implement models.