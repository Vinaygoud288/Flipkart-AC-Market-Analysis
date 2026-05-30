# Flipkart AC Market Analysis: Web Scraping & EDA

## Project Overview
This project scrapes AC product data from Flipkart using Python 
and performs data cleaning, feature engineering, and exploratory 
data analysis to extract meaningful business insights.

## Project Structure
Flipkart-AC-Market-Analysis/
├── data/
│   ├── raw.csv   - raw data
│   └── cleaned.csv - cleaned data
├── notebooks/
│   └── cleaning.ipynb - main ipynb file
└── README.md

## Key Insights
- Split ACs dominate Flipkart listings over Window ACs
- Most ACs are priced between ₹25,000 – ₹45,000
- Daikin and Hitachi are the most premium brands
- Higher tonnage and star rating = higher price
- 1.5 Ton is the most popular AC segment
- Some brands offer heavy discounts as their primary selling strategy
- Price Per Ton reveals which brand offers best value for money

## Technologies Used
- Python
- BeautifulSoup & Requests (Web Scraping)
- Pandas & NumPy (Data Cleaning)
- Matplotlib & Seaborn (Visualization)
- Regex (Feature Extraction)
- Jupyter Notebook

## How to Run
1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Run cleaning.ipynb in Jupyter Notebook

## Dataset
- Source: Flipkart.com (scraped using BeautifulSoup)
- Raw data: ~37 pages, 8 columns
- Cleaned data: 18 columns after feature engineering
- Features extracted: Brand, Tonnage, Star Rating, AC Type, Room Size

## Future Scope
- Price prediction model using ML
- Brand comparison dashboard in Power BI
- Sentiment analysis on customer reviews