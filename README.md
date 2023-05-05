# Algorithmic Trading Strategy Capstone Project

This is the README file for an Algorthmic Trading Capstone Project for the end of a University bachelor project which aims to develop and optimize three type of algorithmic trading strategies for the following cryptocurrencies: Bitcoin, Ethereum and Binance Coin.

## DISCLAIMER
**It is  critical to remember that the material in this work is only intended primarily for educational and simulation purposes. The outcomes from the simulated trading strategy may considerably differ from actual results from trading on a live brokerage platform because this work is not expert financial work. As a result, care should be used when applying the techniques presented in this paper to actual trading scenarios. Users should do extensive study and analysis before making any financial decisions.**

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Strategies](#strategies)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Algorithmic trading is the usage of computer programs to automate the execution of trades based on a pre-set rules and conditions. The goal of this project is to create, optimize and evaluate the performance of three different algorithmic strategies on three different cryptocurrencies. The strategies are based on two strategy which do not implment AI that are Multiple Average Crossovers and Harmonic Detection Pattern, and one strategy implements machine learning which is the usage of a ResNet-LSTM model created by Jinlei Zhang.

## Installation
To install this project, please clone this repository by running the following code:

<pre>
git clone https://github.com/Vassily24/algo-trading.git
</pre>


Then once it is cloned, it is necessary to install the required packages for an optimum usage: 

<pre>
pip install -r requirements.txt
</pre>

## Usage
To visualize the entire project and analysis, you can run the Jupyter Notebook with the following command:

<pre>
Jupyter Notebook algo_trading.ipynb
</pre>

## Strategies
This project includes three algorithmic trading strategies:

1. **Multiple Average Crossovers** - This strategy involves buying and selling an asset based on the crossover of short and long simple moving averages crossovers and a third longer moving average is used to determine if the market is bear or bull if bull it buys, if bearish it shorts.

2. **Harmonic Pattern Detection** - This strategy involves using harmonic patterns and more specifically Gartley, Butterfly, Bat, and Crab patterns to identify potential price reversals and generate buy and sell entry positions.

3. **ResNet-LSTM Model** - This strategy involves using a ResNet-LSTM model to forecast future price movement and to generate buy and sell signals.

## Data
The data used is extracted from the yahoo finance api called "yfinance", it consist of three datasets of cryptocurrencies which are BTC, ETH and BNB prices in USD from April 28th 2018 to April 28th 2023.

## Results
The results of each model of each cryptocurrency was backtested and optimized by using the the total return on investment % from an intial capital investement of $10'000.

## Contributing 
If you would like to participate to this project, please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.
