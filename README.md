# Fibonacci Retracement strategy with python

![Fibonacci Plot](img/fibonacci.png)

This Python script visualizes the Fibonacci retracement levels using both real-time and historical market data. Fibonacci retracement is a technical analysis tool used to identify potential support and resistance levels in financial markets.

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

**Reminder:**
Your unique `CLIENT_ID` and `CLIENT_SECRET` can be obtained from your personal account on the platform. Ensure you keep them confidential to protect your data.

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

### Why Use Fibonacci Retracement?

1. **Identifying Key Levels:**
   - Helps traders identify potential levels of support and resistance.

2. **Predictive Tool:**
   - Provides insights into potential price movements and reversals.

3. **Widely Used:**
   - Recognized and utilized by traders globally, increasing its reliability.

4. **Combines Well with Other Tools:**
   - Can be used in conjunction with other technical analysis tools for better decision-making.

## Conclusion

Fibonacci retracement is a powerful tool for technical analysis, offering traders a method to identify potential support and resistance levels. Its ability to predict possible retracement levels makes it an invaluable indicator for both novice and experienced traders.