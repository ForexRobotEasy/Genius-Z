# Genius Z Forex Software ReadMe

This code is an expert advisor (EA) for trading in the foreign exchange market. The Genius Z Forex Software is developed by the Forex Robot Easy Team and can be found at [www.forexroboteasy.com](www.forexroboteasy.com). Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Expert Initialization Function

The `OnInit()` function is called during the initialization of the expert advisor. You can add any required initialization code here.

## Expert Deinitialization Function

The `OnDeinit()` function is called when the expert advisor is being deinitialized. You can add any required deinitialization code here.

## Expert Start Function

The `OnTick()` function is the main function of the expert advisor and is called on each tick of the market. The following steps are performed in this function:

1. The values of the Zig Zag indicator are obtained using the `iCustom()` function.
2. The obtained values are filtered to determine the opening position.
3. If the Zig Zag high is greater than the Zig Zag low, a long position (buy) is opened using the `OrderSend()` function.
4. If the Zig Zag high is less than the Zig Zag low, a short position (sell) is opened using the `OrderSend()` function.
5. Positions are closed based on the filtered data using the `OrderClose()` function.

Please note that this code assumes a fixed lot size of 0.01 for opening and closing positions. You can modify these values according to your trading strategy.

For detailed reviews and trading results of this product, please visit [Genius Z Forex Software Review](https://forexroboteasy.com/forex-robot-review/genius-z-forex-software-review-unveiling-its-unique-zig-zag-algorithm/).

