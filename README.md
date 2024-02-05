# Oblivion MT4 - Trading Robot Code

This code is developed for the Oblivion MT4 Forex trading software by Forex Robot Easy Team (forexroboteasy.com). The Oblivion MT4 trading robot acts as a trend advisor and provides market analysis for traders.

## Trading Functions

### StartSeriesOfOrders()
This function starts a new series of orders. It loops through a maximum of 10 orders and places new orders based on the market trends.

### BuyOrder()
This function executes a buy order based on the market trend.

### SellOrder()
This function executes a sell order based on the market trend.

### ManageManualOrders()
This function manages manual orders. It can be used to implement custom trading strategies or control manual trades.

### ImplementHedge()
This function implements hedge for both buy and sell directions. It can be used to offset risk or protect positions.

## Market Analysis

### MarketTrend()
This function analyzes the market and determines the current trend. It returns the detected trend as TREND_UP.

## Main Function

### OnTick()
The main function of the Oblivion MT4 trading robot. It starts a new series of orders, manages manual orders, and implements hedge for buy and sell directions.

For detailed reviews and trading results of this product, visit [Forex Robot Easy - Oblivion MT4 Review](https://forexroboteasy.com/forex-robot-review/oblivion-mt4-review-day-trading-robot-with-trend-advisor/). Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please refer to MQL5.
