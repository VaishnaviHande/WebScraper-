# WebScraper
Here's a simple README file for your WebScraper project:

---

# Web Scraper Tool

This is a Python-based Web Scraper that fetches product data from provided URLs. It extracts important information like product names, prices, and links, then saves it into an Excel file for easy access.

## Features
- Scrapes product names, prices, and individual links from any provided URL.
- Saves the data automatically into an Excel sheet.
- Easy to use and set up.

## Requirements
- Python 3.x
- The following Python libraries:
  - `requests`
  - `beautifulsoup4`
  - `openpyxl`

You can install these dependencies by running:
```bash
pip install requests beautifulsoup4 openpyxl
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/VaishnaviHande/WebScraper.git
   ```
2. Navigate to the project folder:
   ```bash
   cd WebScraper
   ```
3. Run the scraper script:
   ```bash
   python scraper.py
   ```
4. Enter the URLs you want to scrape, and the script will automatically extract the data and save it to an Excel file.

## How It Works
- The tool sends a request to the provided webpage using `requests`.
- It parses the page with `BeautifulSoup` to find the product details.
- It then saves the data into an Excel file using `openpyxl`.

## Contribution
Feel free to fork this project and improve it. Contributions are welcome!

---

You can customize the file as needed.
