# PineScript-Custom-Indicators-TradingView
Custom Indicators for TradingView made in Pinescript

# ARI-DPO 2.0

This script is written in Pine Script and is used for technical analysis in trading. It calculates the Detrended Price Oscillator (DPO), Hull Moving Average (HMA), Exponential Moving Average (EMA), and Relative Strength Index (RSI). It also includes functionality to color-code lines based on certain conditions.

## Features

- **DPO Calculation**: The DPO is a tool used in technical analysis to remove the trend from price. This is done to help identify the underlying cycle.
- **HMA and EMA Calculation**: The HMA and EMA are types of moving averages that give more weight to recent price data. They are used to identify trends in the market.
- **RSI Calculation**: The RSI is a momentum oscillator used to measure the speed and change of price movements. It is used to identify overbought or oversold conditions in a market.
- **Color-Coding**: The script includes functionality to color-code lines based on certain conditions. This can help in visualizing the data and making trading decisions.

## Inputs

- **Period**: The number of bars to calculate the DPO (default is 21).
- **Trend Period**: The number of bars to calculate the HMA and EMA (default is 200).
- **RSI Length**: The number of bars to calculate the RSI (default is 14).
- **Draw Lines**: A boolean value to decide whether to draw lines or not (default is false).
- **Draw Indicator**: A boolean value to decide whether to draw the indicator or not (default is true).

## Usage

To use this script, you need to have a trading platform that supports Pine Script. Once you have that, you can add this script to your chart to start analyzing the market.

Please note that this script is for educational purposes only and should not be used as financial advice. Always do your own research before making trading decisions.


# ARI-Overextension

This script is written in Pine Script and is used for technical analysis in trading. It calculates the Hull Moving Average (HMA), Exponential Moving Average (EMA), and a line that represents the percentage difference between the close price and the HMA. It also includes functionality to color-code the line based on certain conditions.

## Features

- **HMA Calculation**: The HMA is a type of moving average that gives more weight to recent price data. It is used to identify trends in the market.
- **EMA Calculation**: The EMA is another type of moving average that also gives more weight to recent price data. It is used to identify trends in the market.
- **Line Calculation**: The line represents the percentage difference between the close price and the HMA. This can help in identifying overextensions in the market.
- **Color-Coding**: The script includes functionality to color-code the line based on certain conditions. This can help in visualizing the data and making trading decisions.

## Inputs

- **Period**: The number of bars to calculate the HMA and EMA (default is 21).
- **Trend Period**: The number of bars to calculate the HMA and EMA (default is 200).

## Usage

To use this script, you need to have a trading platform that supports Pine Script. Once you have that, you can add this script to your chart to start analyzing the market.

Please note that this script is for educational purposes only and should not be used as financial advice. Always do your own research before making trading decisions.


# ARI-zScore

This script is written in Pine Script and is used for technical analysis in trading. It calculates the z-score, a statistical measurement that describes a value's relationship to the mean of a group of values. It also includes functionality to color-code the z-score based on certain conditions.

## Features

- **z-Score Calculation**: The z-score is a statistical measurement that describes a value's relationship to the mean of a group of values. It is used to identify how far away a particular data point is from the mean.
- **Color-Coding**: The script includes functionality to color-code the z-score based on certain conditions. This can help in visualizing the data and making trading decisions.

## Inputs

- **Fast**: The number of bars to calculate the fast moving average (default is 5).
- **Slow**: The number of bars to calculate the slow moving average (default is 20).
- **St Dev**: The number of bars to calculate the standard deviation (default is 20).
- **z first band**: The first z-score band (default is 1).
- **Show Bands**: A boolean value to decide whether to show the bands or not (default is false).
- **Show zScore line**: A boolean value to decide whether to show the z-score line or not (default is false).
- **Show zScore cross**: A boolean value to decide whether to show the z-score cross or not (default is true).
- **Show PSAR**: A boolean value to decide whether to show the Parabolic SAR or not (default is false).

## Usage

To use this script, you need to have a trading platform that supports Pine Script. Once you have that, you can add this script to your chart to start analyzing the market.

Please note that this script is for educational purposes only and should not be used as financial advice. Always do your own research before making trading decisions.