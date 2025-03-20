# Bitcoin Mean Reversion Trading Strategy

This Jupyter Notebook implements a Bitcoin trading strategy based on mean reversion using Python.

## Overview

This project uses a 20-hour Simple Moving Average (SMA) and volatility (4 standard deviations) to identify trading opportunities for Bitcoin (BTC-USD). The notebook includes data fetching, strategy logic, back-testing, and performance metrics like Sharpe Ratio.

## Setup

Please ensure you using Python 3 or later.

```
python3 --version
```

### Clone repo

```
git clone https://github.com/Algo_Trading.git
$ cd Algo_Trading
```

### Create an environment and install dependencies

### Mac/Linux/WSL

```
$ python3 -m venv algo_env
$ source algo_env/bin/activate
$ pip insall -r requirment.txt
```

## Results

Total Return: 3.38%

Sharpe Ratio: 0.22

Maximum Drawdown: -6.75%

Number of Trades: 305

![alt text](image.png)
