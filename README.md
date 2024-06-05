<h2><B></B>Stock Market Analysis</h2></B>
This project looks into the dynamic world of the stock market, focusing on four prominent players: Apple (AAPL), Microsoft (MSFT), 3M (MMM), and Tesla (TSLA). By dissecting their recent performance, we aim to uncover valuable insights and potential investment opportunities.<br>

<h2>Our analysis will encompass various aspects, including:</h2>
<li>Price Comparison:I began by comparing the prices of the Stock across a defined timeframe. This could involve looking at historical data and comparing current price</li>
<li>Return Calculation: Next, I calculated the returns for each option over the chosen period. This would involve using formulas to determine the percentage gain or loss on each investment.</li>
<li>Cumulative Returns: To understand the total growth over time, I calculated the cumulative returns for each option.</li>
<li>Volatility: I then assessed the volatility of each option. Volatility is a measure of price fluctuations, and a high volatility indicates a riskier investment.</li>
<li>Return Distribution: I analyzed the distribution of returns for each option. This could involve creating a histogram or using statistical measures to understand how frequently certain returns occurred.</li>
<li>logarithmic returns or log returns) : Finally i analzed log returns which are a common way to measure the percentage change of an asset's price over time. It is calculated by taking the natural logarithm of the ratio between the current price and the previous price</li>

<h3>Data Acquisition</h3>
yfinance function was used to download historical and current price data for the specified companies.<br>
This Project requires the following libraries:
<li>yfinance</li>
<li>Pandas(for data manipulation and analysis)</li>
<li>Matplotlib (for visualization)</li>

**You can install them using pip:
pip install yfinance pandas matplotlib***

**Note:Only Ajdusted close column was used for analysis;
The adjusted closing price is a stock's closing price that takes into account corporate actions such as stock splits and dividend distributions.It essentially reflects the true price of the stock after these events have been considered.**
