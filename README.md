ko# altcoin-dashboard

Project Name: Altcoin Dashboard
API Used: CoinGecko API
--------------------------------------------------------------------------------------------
ABOUT THE API:
Coingecko API is a cryptocurrency data API that provides information about various cryptocurrencies. In this program, we are using the Coingecko API to fetch the top 250 cryptocurrencies by market capitalization in USD.



INTEGRATION:
The API endpoint we are accessing is https://api.coingecko.com/api/v3/coins/markets, and we are passing the necessary parameters such as vs_currency, order, per_page, and page to customize the API response.
The vs_currency parameter specifies the currency in which the market data is returned (in this case, USD). The order parameter is set to market_cap_desc to sort the cryptocurrencies by market capitalization in descending order. The per_page parameter determines the number of results per page, and the page parameter specifies the page number of the result set.

Once we receive the API response, we extract the necessary data such as the cryptocurrency names and market capitalizations. We then manipulate and format this data to fit the requirements of the charts.

--------------------------------------------------------------------------------------------
Github Repository: https://github.com/Aerith13/altcoin-dashboard

Video for Re-checking: 

https://bit.ly/Modified-Altcoin-Dashboard

--------------------------------------------------------------------------------------------

ORGANIZED AND DEVELOPED BY: Esguerra, Desiree E.
BSIT 3A


