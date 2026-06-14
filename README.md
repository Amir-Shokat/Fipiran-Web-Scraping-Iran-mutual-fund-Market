# Fipiran Web Scraping — Iran's Mutual Fund Market

## Overview
This project scrapes data from **[Fipiran.com](https://fipiran.com)**, a comprehensive website containing information about all mutual funds in the Iranian market. The scraped data is collected and stored in a structured CSV file for easy analysis.

## Data Collected
### From Fipiran.com (All Mutual Funds)
- Fund price
- NAV (Net Asset Value)
- Asset composition/combinations
- Price date
- And all other related mutual fund information

## Project Structure
```
📁 Repository
   📄 Main.ipynb        ← Full scraper (runs from scratch)
   📄 Update.ipynb      ← Updates existing CSV with new data
   📄 fund_data.csv     ← Pre-scraped dataset (ready to use)
```

## How to Use

### Option 1 — Full Scrape (from scratch)
Run `Main.ipynb` — it will scrape all data from Fipiran.com and generate the `fund_data.csv` file.

### Option 2 — Quick Update (recommended ✅)
If you want to save time and avoid scraping everything from the beginning:
1. Download `fund_data.csv` and `Update.ipynb`
2. Run `Update.ipynb`
3. It will automatically fetch only the **new/recent data** and append it to the existing CSV

## Requirements
- Python 3.x
- Jupyter Notebook

## 🔜 Coming Soon
In future updates, we will also cover how to gather **trading data for ETFs** (mutual funds that are publicly traded on the Tehran Stock Exchange) from **[TSETMC.com](https://tsetmc.com)**. Stay tuned!
