# Rosoku Robot

## Description
Rosoku Robot is a trading robot developed by the Forex Robot Easy team. It is designed to trade based on the movement of candlesticks in the forex market. This code is a sample implementation of the robot's trading strategy.

## Installation
To use Rosoku Robot, you need to have a MetaTrader 4 platform installed on your computer. Follow the steps below to install the robot:

1. Download the robot's code from [here](https://forexroboteasy.com/forex-robot-review/rosoku-robot-review-unique-forex-ea-for-profitable-trades/).
2. Open the MetaEditor in your MetaTrader 4 platform.
3. Create a new Expert Advisor (EA) and paste the downloaded code into the editor.
4. Save the EA and compile it.
5. Attach the EA to a chart in the MetaTrader 4 platform.

## Usage
Rosoku Robot is designed to automatically execute trades based on the movement of candlesticks. The robot follows a simple strategy:

1. It checks the current candlestick and the previous candlestick.
2. If the current candlestick is bullish (close > open) and the previous candlestick is bearish (close < open), it enters a buy trade.
3. If the current candlestick is bearish (close < open) and the previous candlestick is bullish (close > open), it enters a sell trade.

The lot size for trades, stop loss in pips, and take profit in pips can be configured using the input variables `lotSize`, `stopLoss`, and `takeProfit`, respectively.

## Disclaimer
Please note that Forex Robot Easy is not the official developer of Rosoku Robot. We only provide a sample code that can work as described in the product. For detailed reviews and trading results of this product, refer to [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/rosoku-robot-review-unique-forex-ea-for-profitable-trades/). To find the official developer of this product, use MQL5.

## Support
For any inquiries or support regarding Rosoku Robot, please contact the official developer through the website mentioned above.
