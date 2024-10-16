# Largest U.S. Companies by Revenue

This project focuses on scraping and analyzing the largest companies in the United States by revenue from Wikipedia. The goal is to extract the data, clean it, and store it for further analysis.

## Overview
- **Website Scraped**: https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue
- **Techniques Used**: Web scraping with BeautifulSoup, data cleaning, and storage in CSV format using pandas.
- **Programming Language and Libraries**: Python, Pandas, BeautifulSoup

## Steps

1. **Web Scraping**: Fetched the webpage using `requests` and parsed the HTML using `BeautifulSoup`.
2. **Data Extraction**: Identified the correct table and extracted relevant data (company names, revenue, and other details).
3. **Data Cleaning**: Processed and cleaned the extracted data to ensure consistency.
4. **CSV Export**: Saved the cleaned data into a CSV file for further analysis or use in other projects.

## Results
The project successfully scraped and stored data on the largest U.S. companies by revenue, which can now be used for financial analysis, comparisons, or reporting.

## How to Run the Script

1. Clone the repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
3. Run the script to scrape the data and save it as a CSV file:
  ```bash
  python scrape_companies.py



