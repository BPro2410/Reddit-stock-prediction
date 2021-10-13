# Reddit-stock-prediction
*Course project - University of Vienna (Python for finance II)*

<br>

**Stock market prediction (early signal model) for most trending S&P 500 stocks on Reddit**

This project work deals with scraping the Reddit API in order to get information about the most discussed S&P 500 stocks as well as creating an early signal model for the three most discussed stocks.

In order to get information about the structure, data and methodology of this project please have a look at the corresponding project report (PFF2_Project_presentation.pdf)!

This project is divided into two separate classes. Each class stands individually and can be used for separate analysis if needed. Class description:

- **RedditData:** Scraps data from the Reddit 'praw' library. Provides information about the most discussed S&P 500 stocks and their corresponding sentiment.
- **RedditPredict:** Scraps stock market data from the 'yfinance' library for the most trending stocks out of the RedditData class. Predicts the stock market development within the next 5 days based on a random forest algorithm and creates an early signal model.


In addition to some standard libraries (e.g. numpy, pandas, sklearn, etc.), the research used the following more specialized libraries:<br>
- __[praw:](https://praw.readthedocs.io/en/stable/)__ Scraping Reddit API<br>
- __[Vader Sentiment Analyzer:](https://github.com/cjhutto/vaderSentiment)__ Sentiment analysis<br>
- __[yfinance:](https://pypi.org/project/yfinance/)__ Scraping stock market data<br>
- __[TA-Lib:](https://github.com/mrjbq7/ta-lib)__ Performing technical analysis

