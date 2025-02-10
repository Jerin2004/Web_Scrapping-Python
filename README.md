# Amazon Web Scraper

![Project Screenshot](https://github.com/Jerin2004/Web_Scrapping-Python/blob/main/app.py)

## Project Description
This project is a web scraper built using Python to extract product details from the Amazon website. It gathers information such as product names, prices, ratings, and reviews, and stores the data in a structured format for further analysis.

## Features
- Extracts product details like name, price, rating, and reviews.
- Supports multiple product categories.
- Saves data in CSV/JSON format.
- Can be scheduled for automated data collection.
- Implements request headers to mimic a real browser and avoid blocking.

## Tech Stack
- **Programming Language:** Python
- **Libraries Used:**
  - `requests`
  - `BeautifulSoup`
  - `pandas`
  - `selenium` (if required for dynamic content)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-webscraper.git
   cd amazon-webscraper
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the scraper:
   ```bash
   python scraper.py
   ```
2. The scraped data will be saved in the `output` folder in CSV format.

## Notes
- Ensure that you comply with Amazon's [robots.txt](https://www.amazon.com/robots.txt) and **terms of service** before scraping.
- Use appropriate delays or proxies to avoid getting blocked.
---
### Disclaimer
This scraper is for educational purposes only. Scraping Amazon without permission may violate their terms of service.

