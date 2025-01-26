# First Web Scraping Trial

This project demonstrates a basic web scraping tool using Python and BeautifulSoup. It extracts quotes and their respective authors from the website [Quotes to Scrape](https://quotes.toscrape.com) and saves the data in a CSV file.

## Features

- Scrapes quotes and authors from up to 5 pages.
- Handles pagination automatically.
- Outputs the data into a structured CSV file.

## Requirements

The following Python libraries are required:

- `requests`
- `BeautifulSoup` from `bs4`
- `lxml`
- `pandas`

Install the required packages using pip:
```bash
pip install requests beautifulsoup4 lxml pandas
```



## Code Overview

### Functions

- `get_html(url)`: Sends an HTTP GET request to the specified URL and parses the HTML content using BeautifulSoup.
- `Extract_quote_and_author(soup)`: Extracts quotes and authors from the given BeautifulSoup object.
- `next_page(soup)`: Identifies and returns the URL of the next page, if available.

### Main Logic

- Initializes scraping from the base URL: `https://quotes.toscrape.com`.
- Loops through up to 5 pages, extracting data and moving to the next page.
- Saves the extracted data into a CSV file using pandas.

## Output

## "new_quotes.csv"

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Website used for scraping: [Quotes to Scrape](https://quotes.toscrape.com).
- Inspired by beginners' tutorials on web scraping.

