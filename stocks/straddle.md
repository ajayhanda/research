# STRADDLE
A straddle strategy is a type of options trading strategy that investors use when they believe there's going to be a significant price movement in a stock, but they are unsure about the direction of the movement. The strategy involves simultaneously buying or selling a call option and a put option with the same strike price and expiration date.

Here's a bit more about each:

1. Long Straddle: In a long straddle, the investor simultaneously buys a call option and a put option with the same strike price and expiration date. This strategy is used when an investor predicts a large price move in either direction. If the underlying stock's price changes significantly, the investor can make a profit. However, if the price does not move enough, the investor stands to lose the premium paid for the options.

2. Short Straddle: A short straddle, on the other hand, involves selling a call option and a put option with the same strike price and expiration date. This strategy is used when an investor believes that the price of the underlying stock will not fluctuate significantly and will remain relatively stable. The maximum profit in this case is the premium received from selling the options. But this strategy carries a high risk because the loss can be unlimited if the stock's price moves significantly in either direction.

Remember that options trading can be complex and involves significant risk, and it's not suitable for all investors. It's always a good idea to fully understand any strategy before deciding to use it and to consider seeking advice from financial advisors or professionals if needed.

## STRATEGY 1
1. [x] On first 15 minute close of candle, calculate, call and put open price by adding 15% to open and close of candle.
1. [ ] Calculation profit target at 100% and stop loss at 25%
1. [ ] Close the Trade at 3:15 PM if the target / sl is not met


