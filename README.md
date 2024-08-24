# Fibonacci Retracement strategy with python

![Fibonacci Plot](img/fibonacci.png)

This Python script visualizes the Fibonacci retracement levels using both real-time and historical market data.
## Prerequisites

Ensure you have the requirements file installed.

To install the libraries listed in the `requirements.txt` file, use the following command:

```sh
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in your project directory and add your `CLIENT_ID` and `CLIENT_SECRET`:

```env
CLIENT_ID=your_client_id
CLIENT_SECRET=your_client_secret
```

These variables enable secure access to market data from the [HSTRADER](https://staging.hstrader.com/login) platform.

**Note:**
Your unique `CLIENT_ID` and `CLIENT_SECRET` can be obtained from your personal account on the platform. Keep them confidential to ensure the security of your data.

### Fibonacci Retracement

Fibonacci retracement is a popular technical analysis tool used by traders to identify potential support and resistance levels. The levels are derived from the Fibonacci sequence and are used to predict the possible retracement of a market move.

### Components of Fibonacci Retracement

1. **0.0% Level:**
   - Represents the highest point in the selected period.
   - Purpose: Indicates the starting point of the retracement.

2. **23.6% Level:**
   - Calculation: Highest point - (Difference between high and low) * 0.236
   - Purpose: A potential support/resistance level.

3. **38.2% Level:**
   - Calculation: Highest point - (Difference between high and low) * 0.382
   - Purpose: A potential support/resistance level.

4. **50.0% Level:**
   - Calculation: Highest point - (Difference between high and low) * 0.5
   - Purpose: A significant support/resistance level, although not a Fibonacci ratio.

5. **61.8% Level:**
   - Calculation: Highest point - (Difference between high and low) * 0.618
   - Purpose: A key Fibonacci level often considered as a strong support/resistance.

6. **100.0% Level:**
   - Represents the lowest point in the selected period.
   - Purpose: Indicates the end point of the retracement.

### What Do Fibonacci Retracement Levels Tell You?

Fibonacci retracements can be used to place entry orders, determine stop-loss levels, or set price targets. For example, a trader may see a stock moving higher. After a move up, it retraces to the 61.8% level. Then, it starts to go up again. Since the bounce occurred at a Fibonacci level during an uptrend, the trader decides to buy. The trader might set a stop loss at the 61.8% level, as a return below that level could indicate that the rally has failed.
