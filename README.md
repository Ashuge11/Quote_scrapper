# Quotes Web Scraper

A Python web-scraping project that collects quotes, authors, and tags from [Quotes to Scrape](https://quotes.toscrape.com/).

## Features

- Extracts quotes, author names, and tags.
- Scrapes multiple pages using pagination.
- Handles HTTP request errors and timeouts.
- Stores the collected data in a CSV file.
- Uses Pandas for structured data handling.
- Logs scraping progress and errors.

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas

## Installation

1. Clone this repository.
2. Open the project folder in your terminal.
3. Install the dependencies:

   `pip install -r requirements.txt`

## Usage

Run the scraper:

`python scraper.py`

The collected data will be saved to `quotes_final.csv` when scraping succeeds.

## Output

The CSV file contains three columns:

- Quote
- Author
- Tags

## Learning Outcomes

This project demonstrates HTML parsing, CSS selectors, pagination, exception handling, data cleaning basics, and CSV export.

## Data Source

[Quotes to Scrape](https://quotes.toscrape.com/)

This project is intended for educational purposes.
