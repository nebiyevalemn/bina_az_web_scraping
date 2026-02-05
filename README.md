# Bina.az Web Data Collection Project

## 🔍 Overview
This project is designed to automatically collect real estate listing data from the Bina.az platform using Python. The scraper retrieves the most recent listings, extracts detailed information from each ad, and stores the results in structured formats for further analysis.

## ⚙️ How It Works
- Reads the official sitemap to identify newly published listings
- Visits individual listing pages and parses relevant data fields
- Fetches phone numbers via the internal request endpoint
- Applies random delays to reduce request frequency
- Saves collected data into Excel and CSV files

## 📌 Extracted Information
- Listing title  
- Update date  
- Property category and building type  
- Area size and number of rooms  
- Sale or rental type  
- Price, currency, and price format  
- Contact phone number  
- Location and listing ID  

## 🧠 Key Techniques Used
- HTTP session handling with custom headers
- HTML parsing with BeautifulSoup
- Regular expressions for sitemap and URL extraction
- Error handling and logging
- Batch-based Excel file writing

## 🛠 Technologies
- Python 3
- Requests
- BeautifulSoup (bs4)
- Pandas
- Regular Expressions
- Logging module

## 📂 Project Structure
- `scraper.py` – main scraping script  
- `bina_az_data.xlsx` – scraped data (Excel format)  
- `bina_az_data.csv` – scraped data (CSV format)

## ⚠️ Disclaimer
This project is created for educational and analytical purposes only. The data is publicly available and collected responsibly with request delays.
