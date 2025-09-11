PROJECT FOR PYTHON DATA SCIENCE: ANALYZING HISTORICAL STOCKS
Project Overview
This project focuses on analyzing historical stock data for two major companies:
Tesla (TSLA)
GameStop (GME)
The project was developed as part of a Python for Data Science learning module. It demonstrates the use of data analysis, web scraping, and visualization techniques to explore how stock prices and revenues have changed over time.
Key Steps & Tasks Completed
Data Collection
Downloaded Tesla stock data using the yfinance library.
Used requests and BeautifulSoup to web scrape Tesla and GameStop revenue data.
Used pandas.read_html to parse financial tables into dataframes.
Data Cleaning
Removed extra characters like commas and dollar signs from revenue values.
Converted data columns (Date, Revenue) into proper formats.
Checked and displayed dataframe columns using .columns.
Data Analysis
Compared historical stock data and revenues for both Tesla and GameStop.
Displayed trends using .head(), .tail(), and summary statistics.
Data Visualization
Created a custom function make_graph() to visualize Stock Prices vs. Revenues on a dual-axis plot.
Plotted:
📈 Tesla Stock Price (up to June 2021)

📉 GameStop Stock Price (up to June 2021)
Insights
Tesla shows strong growth in both stock price and revenue.
GameStop exhibits high stock volatility (spike during the 2021 short squeeze) while revenues decline.
  Tools & Libraries Used
Python
Pandas → Data manipulation
Matplotlib → Visualization
yfinance → Stock data download
Requests + BeautifulSoup → Web scraping financial data
📂 Files in this Repository
notebook.ipynb → Jupyter Notebook with all code & outputs
README.md → Project description (this file)

To run
Install dependencies:
pip install pandas matplotlib yfinance beautifulsoup4 lxml html5lib requests
