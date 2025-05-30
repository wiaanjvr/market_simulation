# Basic Financial Market Simulation for a Single Instrument 1.0

In economics, there is a fundamental principle of __supply and demand__ that explains how prices are determined in markets through the interaction of what people want to buy and sell. In this notebook, we will use this principle to create a simplified model of the market for a single financial instrument. More precisely, this notebook demonstrates a simulation of traders who buy and sell from each other over time.

It should be noted that while libraries such as `pandas` and `numpy` are ideal for our task, this notebook aims to show what is possible with basic, built-in python functions. 

_Further versions of this simulation incorporate the use of these external libraries._

### __Contents__

- Basic Simulation Model
- Recap
- Cleaning Up
- Fees
- Initial Trader Wealth
- Tracking Trader Wealth
- Interpreting Our Results
- Varying When a Trader Trades
- Varying How Many Shares a Trader Trades
- Refining Price Changes
- The End (for now)

### __Required libraries__
Matplotlib:
- For __conda__ users: `conda install matplotlib`
- For __pip__ users: `pip install matplotlib`
