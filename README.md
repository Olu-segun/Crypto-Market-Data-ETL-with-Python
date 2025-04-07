# Crypto-Market-Data-ETL-with-Python

This project is a Python-based ETL (Extract, Transform, Load) pipeline that collects real-time cryptocurrency data from the CoinGecko API, transforms the data using pandas, and saves the cleaned dataset to a CSV file for further analysis or reporting.

📌 Features
✅ Extracts market data for the top 250 cryptocurrencies by market cap

✅ Includes useful metrics like:

Current Price

Market Cap

24h Price Change %

All-Time High (ATH)

All-Time Low (ATL)

✅ Adds a timestamp for data versioning

✅ Exports the data to a .csv file

✅ Easily scalable for automation or cloud workflows

🛠️ Tools & Libraries Used
requests – for sending HTTP requests to the API

pandas – for data transformation and CSV export

datetime – to create a timestamp
