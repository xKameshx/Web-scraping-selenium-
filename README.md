Web Scraping Script

Description

This Python script is designed to scrape product information from various fashion websites. It currently supports the following websites:

Zara

Pryka

Papa Don't Preach

Kshitij Jalori

Gucci

The script utilizes Selenium for web scraping and BeautifulSoup for HTML parsing.

Prerequisites

Make sure you have the following installed:

Python (version 3.6 or higher)

Google Chrome browser

ChromeDriver installed and added to your system's PATH

Install the required Python packages using:

pip install -r requirements.txt

Usage

Run the script with the URL of the product page you want to scrape. The script will automatically identify the website and extract relevant information.

Example:

python web_scraping_script.py https://pryka.in/product/off-white-bloom-maxi-dress/

Supported Websites

Zara: https://www.zara.com/

Pryka: https://pryka.in/

Papa Don't Preach: https://www.papadontpreach.com/

Kshitij Jalori: https://kshitijjalori.com/

Gucci: https://www.gucci.com/

Output

The script saves the scraped data in a structured manner within the current working directory. Each website has its own folder, and within each website folder, data is organized by categories and product titles.

Disclaimer

This script is for educational purposes only. Use it responsibly and in compliance with the terms of service of the respective websites.
