# Amazon Data Scraper
This project is an Amazon product data scraper developed in Python. It uses libraries like `Selenium` and `BeautifulSoup` to extract product information from Amazon. The scraper retrieves data such as product titles, prices, ratings, and more, which can be used for analysis, comparisons, or market research purposes.

## Features

- Scrapes product details such as:
  - Description
  - Price
  - Rating
  - Number of reviews
  - Product URL
- Saves the extracted data in CSV format for easy analysis.
- Error handling for failed requests or missing data fields.
- Can be extended to scrape other product attributes or different Amazon categories.


## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine
- Required libraries:
  - `requests`
  - `beautifulsoup4`
  - `Selenium`

You can install these dependencies using the following command:

```
pip install -r requirements.txt
```



## Usage
1. Clone the repository:
```
git clone https://github.com/ibrahimYldzz/Amazon-Data-Scraper.git
cd Amazon-Data-Scraper
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Run the scraper script:
```
python scraper.py
```
4. The script will extract data and save it in a CSV file.

## Limitations
- Amazon's CAPTCHA system: If too many requests are made in a short time, Amazon may block the scraping attempts or show CAPTCHA challenges. You may need to add delays between requests or use proxy servers.
- Legal limitations: Scraping data from Amazon without permission may violate their terms of service. Be sure to review and comply with Amazon's policies before scraping.
## Future Improvements
- Add proxy support to bypass CAPTCHA challenges.
- Implement multithreading for faster data scraping.
- Support for additional product attributes, such as product descriptions and specifications.
- Extend the scraper to work on international Amazon websites (e.g., amazon.co.uk, amazon.de).

## Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License.

### Disclaimer 
This scraper is for educational purposes only. Always ensure that you are complying with Amazon's terms of service when scraping their data.

