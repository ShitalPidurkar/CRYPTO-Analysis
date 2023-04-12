#Cryptocurrency Analysis
ABOUT PROJECT
A cryptocurrency is a digital or virtual currency secured by cryptography, which makes it extremely difficult to counterfeit or double-spend. Many cryptocurrencies use decentralized networks based on blockchain technology - a distributed ledger enforced by a network of computers. The objective of this project is to analyze various types of cryptocurrencies over different years, and an interactive dashboard for cryptocurrency analysis has been built using Power BI. The dashboard provides real-time data visualization and forecasting of cryptocurrency prices. The dashboard includes five pages: Home, Dashboard, Pricing, Overall, and Forecasting, and features easy navigation for quick access to each page..

ABOUT THE DATASET
The dataset used in this project includes historical price information of some of the top cryptocurrencies by market capitalization, and is sourced from various cryptocurrency APIs. The data is stored in CSV files, with one file for each currency, and price history is available on a daily basis from April 2013. The data is then transformed and loaded into both Jupyter Notebook and Power BI. The analysis includes various visualizations such as scatter plots, heat maps, and line charts, and uses descriptive statistics and correlation analysis to gain insights into the cryptocurrency market trends. The dashboard in Power BI uses DAX formulas, charts, tables, and other visualizations to display the data in an interactive manner.

REQUIREMENTS:
- Power BI Desktop
- Jupyter Notebook
- Python 3.x
- CoinMarketCap API key

INSTALLATION:
- Install Power BI Desktop from the Microsoft website.
- Install Jupyter Notebook using the pip command: "pip install jupyter".
- Install the required libraries in Jupyter Notebook using the pip command: "pip install pandas, numpy, matplotlib, seaborn, requests".

USAGE:
- Clone the repository to your local machine.
- Open "cryptoCurrency_EDA.ipynb" in Jupyter Notebook.
- Run each cell to retrieve the data and perform analysis on the data.
- Open "crypto.pbix" in Power BI Desktop.
- Click on "Edit Queries" to change the data source to the CSV file generated by the Jupyter Notebook.
- Update the visuals in Power BI to match the analysis performed in Jupyter Notebook.

DETAILS OF THE DATASET
1. DATE		    : The DATE describes the date of observations.
2. OPEN		    : The OPEN is the Opening Price on the given day.
3. HIGH		    : The HIGH is the highest price on the given day.
4. LOW		    : The LOW is the lowest price on the given day.
5. CLOSE	    : The CLOSE is the closing price on the given day.
6. VOLUME	    : The VOLUMNE is the volume of transactions on the given day.
7. MARKET CAP	: The MARKET CAP is the market capitalization in USD.

CRYPTOCURRIENCIES USED
1 - AAVE COIN
2 - BINANCE COIN
3 - BITCOIN
4 - CARDANO COIN
5 - CHAINLINK COIN
6 - COSMOS COIN
7 - CRYPTO.COM COIN
8 - DOGE COIN
9 - EOS COIN
10 - ETHERIUM 
11 - IOTA COIN
12 - LITE COIN
13 - MONOCOIN
14 - NEM COIN
15 - POLKADOT COIN
16 - SOLANA COIN
17 - STELLAR COIN
18 - TETHER COIN
19 - TRON COIN
20 - UNISWAP COIN
21 - USD COIN
22 - WRAPPED 
23 - BITCOIN
24 - XRP COIN

ABOUT DASHBOARD
The dashboard includes several visualizations that allow users to explore the data and gain insights into cryptocurrency trends. The following visualizations are included:

1 - A line chart showing the price history of a selected cryptocurrency over time.
2 - A scatter chart comparing the market capitalization of different cryptocurrencies to their trading volume.
3 - A bar chart showing the top 10 cryptocurrencies by market capitalization.
4 - A donut chart showing the distribution of cryptocurrencies by market capitalization range.
5 - The dashboard is fully interactive, allowing users to filter and drill down into the data. For example, users can select a specific cryptocurrency to         focus on, or filter by date range to see how prices and volumes have changed over time.

ANALYSIS
The analysis performed in this project includes:
Retrieving and cleaning the data using Python and pandas.
Exploring the data using various visualizations such as scatter plots, heat maps, and line charts.
Analyzing the data using descriptive statistics and correlation analysis.
Creating a dashboard in Power BI to display the findings.

Credits
This dashboard was developed by Shital Pidurkar, using data from various cryptocurrency APIs and the Power BI software.


