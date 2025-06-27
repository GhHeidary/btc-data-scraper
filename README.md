# btc-data-scraper
 Scrapes historical Bitcoin blockchain metrics and indicators (2010–2023) from BitInfoCharts. Converts them into clean CSV datasets for analysis, including raw values and technical indicators (SMA, EMA, RSI, etc.). Built with Python, requests, BeautifulSoup, and pandas.
# 🧠 Bitcoin Data Scraper (BTC Metrics from BitInfoCharts)

A Python-based data scraper that extracts historical Bitcoin metrics and indicators (e.g., transactions, hashrate, fees) from [bitinfocharts.com](https://bitinfocharts.com) and saves them as clean CSV files for further analysis.

## 📊 Features

- Collects data from **2010 to 2023**
- Includes **raw features** and **technical indicators** (e.g., SMA, EMA, RSI)
- Merges and cleans all data into a single CSV
- Automatically retries on connection failure
- Multithreaded scraping using `multiprocessing`

## 🔧 Technologies Used

- Python
- `requests`, `beautifulsoup4` for web scraping
- `pandas` for data processing
- `multiprocessing` for faster downloads
- `tqdm` for progress bars

## 📦 Installation

```bash
pip install -r requirements.txt
