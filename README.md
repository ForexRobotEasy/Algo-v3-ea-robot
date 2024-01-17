# Algo v3 EA Robot

This is the source code for the Algo v3 EA Robot developed by the Forex Robot Easy Team. The robot is designed to trade on the forex market using the Strategic Smart Move Trading (SMT) strategy. It aims to generate profits while managing risks by implementing risk management strategies such as setting stop loss and take profit levels.

## Input Parameters
- RiskPercentage: This parameter determines the risk percentage per trade.
- MaxDailyDrawdown: This parameter sets the maximum daily drawdown percentage.

## Global Variables
- AccountBalance: Stores the current account balance.
- MaxDailyProfit: Stores the maximum daily profit percentage.
- MaxDailyLoss: Stores the maximum daily loss amount.

## Expert Initialization Function - OnInit()
In this function, the variables are initialized and the trading pairs are set. The trading pairs enabled for trading are XAUUSD (gold), NAS100, and US30.

## Expert Deinitialization Function - OnDeinit()
This function is called when the expert advisor is being removed from the chart. It disables trading on the previously enabled trading pairs.

## Expert Start Function - OnTick()
This function is called on every tick of the market. It performs the following actions:

1. Checks if the daily profit target has been reached. If it has, it closes all open positions on the enabled trading pairs.
2. Checks if the daily loss limit has been reached. If it has, it closes all open positions on the enabled trading pairs.
3. Places new trades if the daily profit target and loss limit have not been reached. The specific trading strategy and risk management logic are to be implemented in this section.

## Product Description
This code represents the Algo v3 EA Robot, a forex trading robot developed by the Forex Robot Easy Team. It is designed to trade on the forex market using the Strategic Smart Move Trading (SMT) strategy to generate profits while managing risks effectively.

The robot allows users to set the risk percentage per trade and the maximum daily drawdown percentage, providing them with control over their trading strategy and risk management.

To use this product, users can copy and paste the code into their MetaTrader platform and customize the input parameters according to their preferences. It is important to note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, users should refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/algo-v3-ea-robot-review-profitable-forex-software-strategy/).
