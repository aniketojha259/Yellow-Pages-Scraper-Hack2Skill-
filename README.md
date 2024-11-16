## Yellow Pages Scraper
A Python-based web scraper that automates the extraction of business information from the Yellow Pages website. The tool is designed to gather data on companies in specific industries or locations and save the results into a structured CSV file.

Features
Dynamic Content Handling: Uses Selenium to load and scrape dynamic content.
Data Extraction: Retrieves details such as:
Company Name
Website URL
Contact Number
Address
Industry/Category
Description
Error Handling: Gracefully skips over missing or incomplete data.
CSV Export: Saves the scraped data into a CSV file for easy analysis.
Prerequisites
Before running the script, ensure you have the following installed:

Python 3.x
Google Chrome
ChromeDriver (Download the version matching your Chrome browser from here)
Required Python libraries:
Selenium: Automates web browsers to handle dynamic content and interact with web pages.
BeautifulSoup: Parses and extracts data from HTML content efficiently.
pandas: Organizes scraped data into a structured format and saves it as a CSV file.
time: Adds delays to prevent being blocked by the website during scraping.
