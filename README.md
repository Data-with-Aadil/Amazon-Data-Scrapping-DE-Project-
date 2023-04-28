# Amazon Data Scraper Project

This Python program scrapes data from Amazon's search page for Sony headphones and stores it in an Excel file. The program uses the Requests library to send HTTP GET requests and the BeautifulSoup library to parse the HTML content of the pages.

## Installation

Before running the program, ensure that you have installed the following libraries:

- requests
- pandas
- beautifulsoup4

You can install these libraries using pip by running the following command in your terminal:

```bash
pip install requests pandas beautifulsoup4
```

## Usage

To use the program, simply run the provided Python script `amazon_scraper.py`. The script will scrape data from Amazon's search page for Sony headphones and store it in an Excel file named `Amazon-data.xlsx` in the same directory as the script.

## How it Works

The program sends an HTTP GET request to Amazon's search page for Sony headphones with specified headers. It then uses BeautifulSoup to parse the HTML content of the page and extract the links to the product pages. For each product page link, the program sends another HTTP GET request and extracts the required product information using BeautifulSoup. The program stores the extracted data in a list and then converts it to a Pandas DataFrame before saving it to an Excel file.

## Usage
To use this script, you need to have Python 3.x installed on your machine. You will also need to install the necessary libraries: requests, pandas, and BeautifulSoup. You can install them using pip with the following command:

```python
pip install requests pandas beautifulsoup4
```
After installing the libraries, save the script as "scrape_amazon.py" on your machine. Then, navigate to the directory where you saved the file and run the following command in your terminal:

```python
python scrape_amazon.py
```
The script will run and scrape the data from Amazon India's search results for "Sony headphones". The extracted data will be saved in an Excel file called "Amazon-data.xlsx" in the same directory as the script.

## Contributors
This script was created by Aadil Mansoori and is open to contributions from anyone. If you find a bug or have a suggestion for improvement, feel free to submit an issue or pull request on GitHub.

## Credits
This script was created using the following libraries:

- requests: for sending HTTP requests
- pandas: for creating and manipulating dataframes
- BeautifulSoup: for parsing HTML content

Special Thanks to Code with harry and Darshil Parmar for giving a good knowledge on Scraping.

## License
This script is licensed under the MIT License. You can read the full text of the license in the LICENSE file.

## Conclusion
This script provides a simple example of how to scrape data from a website using Python. It can be customized to scrape data from other websites and for different types of products. If you have any questions or comments, feel free to contact me.

## Disclaimer

Please note that scraping data from websites without their permission may be against their terms of service or may even be illegal in some cases. Use this program at your own risk.
