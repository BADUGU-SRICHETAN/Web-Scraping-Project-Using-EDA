# Web-Scraping-Project-Using-EDA

## Project Overview
This project demonstrates web scraping techniques using Python to extract product information from **Shopsy.com**. The data is collected by parsing HTML content with **BeautifulSoup** and extracting specific patterns using **Regular Expressions (Regex)**. The scraped data is then cleaned and organized into a structured format for further analysis.

## Business Problem
E-commerce websites contain large amounts of valuable product data, including product names, prices, ratings, and discounts. Manually collecting this information is time-consuming and inefficient. This project automates the data extraction process, making it easier to gather and analyze product information.

## Project Objectives
- Extract product data from Shopsy.com.
- Parse webpage content using BeautifulSoup.
- Use Regex to identify and extract specific data patterns.
- Clean and structure the scraped data.
- Export the data for analysis and reporting.

## Technologies Used
- Python
- Jupyter Notebook
- BeautifulSoup
- Regular Expressions (Regex)
- Requests
- Pandas

## Project Workflow
1. Send HTTP requests to retrieve webpage content.
2. Parse HTML content using BeautifulSoup.
3. Extract product details using HTML tags and Regex patterns.
4. Store extracted information in a Pandas DataFrame.
5. Clean and preprocess the data.
6. Export the dataset to CSV format.

## Features
- Automated web data extraction.
- HTML parsing and navigation.
- Pattern matching using Regex.
- Data cleaning and transformation.
- Structured dataset generation.

## Data Extracted
Depending on the webpage structure, the project extracts:
- Product Name
- Product Price
- Discount Information
- Product Rating
- Product Link
- Other Product Details

## Project Structure

```text
Shopsy-Web-Scraping/
│
├── shopsy_web_scraping.ipynb
├── scraped_data.csv
├── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Shopsy-Web-Scraping.git
```

Install required libraries:

```bash
pip install -r requirements.txt
```

## Requirements

```text
requests
beautifulsoup4
pandas
numpy
```

## How to Run

1. Open the Jupyter Notebook.
2. Run all cells sequentially.
3. The script will scrape product data from Shopsy.com.
4. The extracted data will be stored in a DataFrame and can be exported as a CSV file.

## Learning Outcomes
- Web Scraping Fundamentals
- HTML Parsing with BeautifulSoup
- Regular Expressions (Regex)
- Data Collection and Cleaning
- Data Processing with Pandas
- Automation Using Python

## Disclaimer
This project was developed for educational and learning purposes only. All scraped content belongs to the respective website owners. Users should comply with the website's Terms of Service and robots.txt policies before scraping.

## Author
**Your Name**
