 :exclamation: Click **Reload** when Jupyter Notebook is not properly loaded for preview. :exclamation:

# The NASDAQ Composite, S&P 500 and the Dow in 2020

This project, conducted with Python and its data analysis libraries such as Pandas and Matplotlib, evaluates and compares performance of the Nasdaq Composite, S&P 500 index, and the Dow in 2020. Historical data are sourced from MarketWatch, a subsidiary of Dow Jones & Company and a property of News Corp.

PDF report of this project can be found at this [link](https://drive.google.com/file/d/1c4dLmZM6pU8bYPf0y1OrcyhPjsFfWoRJ/view?usp=sharing).

### Overview

2020 was a year of uncertainty and financial hardships, even more so with a sudden major stock market crash caused by the coronavirus that began on February 20th, 2020 and ended on April 7th. Therefore, it may be worth investigating some major stock indices to gauge the magnitude of the impact inflicted by the pandemic on the US stock market.

Nasdaq Composite (~3000 stocks), S&P 500 index (500 stocks), and the Dow (30 stocks) are known as major stock market indices measuring the performance of a stock market, or a subset of the stock market. Each calculation for an index varies because each covers different stocks. The Nasdaq Composite (ticker symbol ^IXIC) is a stock market index that includes almost all stocks listed on the Nasdaq stock exchange. The composition of the Nasdaq Composite is heavily weighted towards companies in the information technology sector. The Nasdaq-100, which includes 100 of the largest non-financial companies in the Nasdaq Composite, accounts for over 90% of the movement of the Nasdaq Composite.

The Standard and Poor's 500, also known as the S&P 500 (ticker symbol ^GSPC), is a stock market index tracking the stock performance of the 500 largest listed companies in the United States. It is widely followed for being one of the best representations of the US stock market and economy. The 10 largest companies in the index, in order of weighting, are Apple Inc., Microsoft, Amazon.com, Facebook, Alphabet Inc., Tesla, Inc., Berkshire Hathaway, JPMorgan Chase & Co., and Johnson & Johnson.

The Dow Jones Industrial Average or simply the Dow (ticker symbol ^DJI) is a stock market index of 30 large listed companies in the United States, where the number 30 is because few American stocks existed when the index was created in the late 1800s. 

In sum, the Nasdaq Composite is for tech, S&P 500 index is for a broad understanding of the US economy, and the Dow measures the movements of the leading companies in the United States that engage in industrial activities.

### Procedure

Step 1: Data Understanding & Preparation

Step 2: Data Analysis

Step 3: Evaluation

### Data Understanding & Preparation

![Data Understanding & Preparation](images/DataPrep.jpg)

The federal holiday, which dates back to 1885, occurs on the third Monday of February. U.S. exchanges are closed for Presidents Day 2020, which falls on February 17 this year. The New York Stock Exchange, Nasdaq, and bond markets will resume trading at their normal hours on Tuesday, February 18.

### Data Analysis

Technical analysis is employed in this simple stock analysis project to assess how the stock indices have performed in 2020 with little attention given to the value of the company.

![Data Analysis](images/DA_1.jpg)

Line chart communicates a stock’s price action very quickly and simply without any significant detail. As a long-term investor, you want your price chart rising from bottom left to top right. That means the stock is rising in price over time. As a short-term investor staying in a stock for weeks or months, you still want the same price action, but you’re looking to exit before the long-term investor does.

Why is a Stock’s Closing Price Significant? A stock’s closing price that determines how a share performs during the day. The close price is considered the reference point for any time frame. It’s the price traders agreed on after all the action throughout the day. When researching historical stock price data, most will use the closing price as the standard measure of the stock’s value as of a specific date. Especially, a stock’s closing price on December 31 in any year is also the closing price for not only that day, but also that week, month, quarter, and year.

**Stock Returns in 2020**

The difference between a stock’s open and close divided by the open is its stock return or its performance in percentage terms. To take a longer-term view of a stock’s performance, such as one-year, we will use the closing price from a year ago and compare it to the closing price from today to get the annual return.


NASDAQ Composite (^IXIC) grows by 42.58 percent.
- Mean Difference between Open and Close of NASDAQ Composite (^IXIC): $5.82

S&P 500 (^GSPC) grows by 15.76 percent.
- Mean Difference between Open and Close of S&P 500 (^GSPC): $0.11

Dow Jones Industrial Average (^DJI) grows by 6.87 percent.
- Mean Difference between Open and Close of Dow Jones Industrial Average (^DJI): $-3.43

![Data Analysis](images/DA_2.jpg)

A cumulative return on an investment is the aggregate amount that the investment has gained or lost over time in percentage. In this simple project, the raw closing price is used to calculate the cumulative return.

The cumulative return usually grows over time, so it tends to make older stocks and funds look impressive. It follows that the cumulative return is not a good way to compare investments unless they launched at the same time. An example of cumulative return is investing $10,000 in a company's stock for a 10-year period that results in $66,000. With no taxes and no dividends reinvested, there is a cumulative return of 560%.

![Data Analysis](images/DA_3.jpg)

The 2020 stock market crash began just as the World Health Organization moved to declare COVID-19 an official pandemic.

The market climbed higher on a combination of unprecedented fiscal and monetary stimulus in response to the pandemic, as well as hopes for a swift economic rebound.

![Data Analysis](images/DA_4.jpg)

Moving averages are plotted on stock charts to help smooth out period-to-period price fluctuation and highlight overall trend direction. The longer the time period that you chart a moving average, the smoother it becomes, since each additional data point becomes less meaningful because there are more points before it.

Most growth investors like to see moving averages trending up and they like to see the stock’s current price continually close above the trailing average. This is a sign the stock is on the right track to continue rising in price.

In this chart, the orange line is the 50-day moving average, represents the average price over the previous 50 trading sessions, and is calculated by summing the closing price over the last 50 trading sessions and dividing by 50. 

The green line is the 200-day moving average. It represents the average price over the previous 200 trading sessions and is calculated by summing the closing price over the last 200 trading sessions and dividing by 200.

The 200-day moving average is considered especially significant in stock trading. As long as the 50-day moving average of a stock price remains above the 200-day moving average, the stock is generally thought to be in a bullish trend.

If the short-term average is below the long-term average, but at some point, it crosses that graph and becomes higher, that intersection is called a golden cross. The golden cross occurs when the 50-day moving average of a stock crosses above its 200-day moving average. The golden cross, in direct contrast to the cross of death when the short-term moving average descends below the long-term moving average, is a strong bullish market signal, indicating the start of a long-term uptrend. Analysts that look for this pattern consider a positive golden cross to be a signal that the stock or other asset's price is headed higher. 

The idea behind a golden cross is that if an investment's performance is continuing to lag, both the 50-day and the 200-day averages should stay about the same distance from each other. If the 50-day average picks up and crosses the longer-term average, it's a sign that the investment's price has started to increase and that there could be further upward momentum.

![Data Analysis](images/DA_5.jpg)

![Data Analysis](images/DA_6.jpg)

![Data Analysis](images/DA_7.jpg)


![Data Analysis](images/DA_8.jpg)
![Data Analysis](images/DA_9.jpg)
![Data Analysis](images/DA_10.jpg)

![Data Analysis](images/DA_11.jpg)

The Nasdaq Composite is as old as the exchange and is different from another popular index, the Nasdaq-100. The Nasdaq-100 comprises of the top 100 non-financial companies listed on the Nasdaq exchange and accounts for over 90% of the movement of the Nasdaq Composite.

At the same time, around 80% of the companies in the Nasdaq-100 are also in the S&P 500. That hasn't always been the case. Fifteen years ago, the overlap was less than 50%.

