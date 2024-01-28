# WebScraping_BeautifulSoup

# Cryptocurrency Data Extraction Project

In this project, we used the BeautifulSoup library to extract information about the current prices of various cryptocurrencies from the [Investing.com - Cryptocurrencies](https://br.investing.com/crypto/) website. Below, we detail the project steps:

## Project Steps

1. **Site Access and Data Extraction:**
   - We used BeautifulSoup to access the content of the [Cryptocurrencies site](https://br.investing.com/crypto/) and navigated to the table containing the desired information.

2. **Data Collection Loop:**
   - Implemented a loop to iterate through the table rows, extracting values related to cryptocurrencies.

3. **Creation of CSV File:**
   - With the collected data, we created a CSV file named "cryptocurrencies.csv".

4. **Import and Presentation of Results with Pandas:**
   - Used the Pandas library to import the CSV file and present the results in a tabular format.

## Final Results

The final result was a DataFrame displaying cryptocurrencies and their current prices:

```plaintext
 Moeda     Valor
0    BTC  39,000.7
1    ETH  2,234.68
2   USDT    0.9999
3    BNB    297.2
4    SOL    80.12
5    XRP    0.5083
6   USDC    1.0008
7  stETH  2,224.49
8    ADA    0.4598
9   DOGE  0.077209
