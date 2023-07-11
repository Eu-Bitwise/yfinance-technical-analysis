# Yahoo Finance Technical Indicators
This script fetches historical data from Yahoo Finance and calculates technical indicators using the pandas_ta library. It then plots the indicators with machine learning regression using the seaborn and scikit-learn libraries.

## Installation
To use this script, you'll need to have Python 3 installed on your system. 

You'll also need to install several Python packages:

`yfinance`
`pandas_ta`
`seaborn`
`matplotlib`
`numpy`
`scikit-learn`

Open a terminal or command prompt and run the following command:

`pip install yfinance pandas_ta seaborn matplotlib numpy scikit-learn`

## Usage
you can run it from a terminal or command prompt using the following command:

`python tech_indicators_yfinance.py`

To use the script, you'll need to specify the symbol and indicator you want to plot.
You can do this by modifying the following lines in the script:

```
symbol = "AAPL"
indicator = 'RSI'
```

Replace "AAPL" with the symbol you want to fetch data for, and replace "RSI" with the indicator you want to plot. You can choose from the following indicators:
- RSI
- SMA
