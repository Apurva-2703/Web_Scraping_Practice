**My First Data Scraping Project: Stock Data Scraping and Visualization (TSLA and GME)**

This is a data scraping project that uses the yfinance library together with matplotlib, BeautifulSoup, pandas, and requests in order to extract and visualize stock data from TSLA and GME. This project was completed as part of a capstone course for the IBM Data Science Professional Certificate. 

**Project aims**
1. Scrape historical stock data for TSLA and GME using the `yfinance` library.
2. Scrape revenue data from the official websites of TSLA and AMD using `requests` and `BeautifulSoup`.
3. Process and visualize the data using `pandas` and `matplotlib`.

**Libraries used**

`yfinance`:
- Extracted TSLA and GME historical stock price data from yfinance library.
  
`requests`:
- Webscraped TSLA and AMD revenue data from their respective websites using HTTP requests.
  
`BeautifulSoup`:
- Parsed HTML data using html.parser
- Extracted revenue tables for TSLA and GME to store it in a dataframe.

`pandas`:
- Constructed dataframes to store and manipulate data, preparing it for data visualization.

`matplotlib`:
- Visualized stock and revenue data for GME and TSLA tickers.

