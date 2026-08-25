# 🚀 Python Automation & Data Portfolio

A collection of practical Python utility scripts, web scrapers, and API integration projects designed to automate workflows, pull real-time financial data, and parse structured web data into clean file formats—and many more...

---

## 🛠️ Projects Included

### 1. Automated File Sorter (`file_sorter.py`)
A script that cleans up messy directories (like your Downloads folder) by sorting files into dedicated categorized subfolders (`pages`, `css`, `js`, `images`, `videos`, `audio`, `text_files`).
* **Key Features:** Uses robust `.endswith()` extension checks, case-insensitive mapping (`.lower()`), and prevents overwriting existing files.

### 2. Crypto Website API Pull (`crypto_tracker.py`)
A script that interfaces with the **CoinMarketCap API** to fetch real-time pricing, market capitalization, and volume metrics for cryptocurrencies.
* **Key Features:** Handles secure header authentication (`X-CMC_PRO_API_KEY`), parses JSON responses, and structures live market data.

### 3. Wikipedia Data Scraper & CSV Exporter (`wiki_scraper.py`)
A web scraper built using Python (`BeautifulSoup` / `requests`) that targets Wikipedia articles, extracts structured table data or infobox content, and outputs a clean, ready-to-use dataset (`scrappeddatafromwikipedia.csv`).
* **Key Features:** Handles HTML parsing, cleans text formatting, and automates tabular data export using the `pandas` library.

### 4. ...and Many More!
This repository is constantly expanding. Future updates will include more automation tools, web scraping scripts, data analysis pipelines, and API integrations. Stay tuned!

```bash
pip install requests beautifulsoup4 pandas
