CarAdsDataScraper

Overview

CarAdsDataScraper is a Python project for scraping and analyzing car advertisement data from the ad.co.il website. It collects detailed car information, processes the data, and exports it to a structured format (CSV) for further analysis.

Features

Web Scraping: Extracts car details like manufacturer, model, year, price, engine specs, and more from multiple pages.
Data Processing: Cleans and preprocesses the data to ensure accuracy and consistency.
Data Export: Saves the structured data to a CSV file for easy access and analysis.

Tech Stack

Language: Python
Libraries:
requests and BeautifulSoup for web scraping
pandas for data manipulation
re for pattern matching
datetime for handling date formats
Setup and Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/CarAdsDataScraper.git
cd CarAdsDataScraper
Install dependencies:

bash
Copy code
pip install requests beautifulsoup4 pandas
Run the script:

bash
Copy code
python car_ads_scraper.py
The scraped data will be saved as a CSV file in the project directory.

Output Fields
The CSV file includes the following fields:

Manufacturer: Car brand
Model: Car model
Year: Manufacturing year
Price: Listed price
Mileage (Km): Distance driven
Engine Type: Gasoline, Diesel, Hybrid, etc.
Gear Type: Automatic, Manual, etc.
Images Count: Number of images in the ad
Description: Ad details provided by the seller
Location: City and region
