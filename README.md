# Noon-Web-Scraping


This project scrapes product information from Noon.com and saves the data to CSV and Excel files.

## Requirements

- Python 3.x
- Selenium
- Pandas
- Chrome WebDriver

## Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/AbanoupRefat/Noon-Web-Scraping.git
    cd Noon-Web-Scraping
    ```

2. **Install the required Python packages:**

    ```sh
    pip install -r requirements.txt
    ```

3. **Download Chrome WebDriver:**

    Ensure you have Chrome WebDriver installed and it's in your system PATH. You can download it from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads).

## Usage

1. **Run the script:**

    ```sh
    python scrape_noon.py
    ```

    The script will:
    - Open the Noon.com website.
    - Search for "samsung" products.
    - Scrape product titles, prices, and ratings from multiple pages.
    - Save the data to `NoonPrice_list.csv` and `NoonPrice_list.xlsx`.

2. **Find the output files:**

    The output files (`NoonPrice_list.csv` and `NoonPrice_list.xlsx`) will be saved in the current working directory.

## Notes

- Ensure you have a stable internet connection as the script interacts with a live website.
- Adjust the sleep times in the script if needed to account for slower/faster page loads.
