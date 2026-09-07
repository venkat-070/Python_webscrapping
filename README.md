# 🕷️ Web Scraping with Python & BeautifulSoup

## 📌 Overview

This project demonstrates how to scrape data from websites using **Python, Requests, BeautifulSoup, and Pandas**.

The notebook starts with basic HTML scraping concepts and then applies them to a real-world webpage to extract structured information from an HTML table.

## 🛠️ Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook
* HTML Parsing
* Web Scraping

## 🔍 Project Workflow

1. Send HTTP requests to a website using `Requests`
2. Retrieve the webpage HTML
3. Parse the HTML using `BeautifulSoup`
4. Find specific HTML elements using:

   * `find()`
   * `find_all()`
5. Extract text and table headers
6. Extract table row and cell data
7. Convert the scraped data into a Pandas DataFrame
8. Export the final dataset to a CSV file

## 🌐 Websites Used

### Practice Website

The project initially uses:

**Scrape This Site**
`https://www.scrapethissite.com/pages/forms/`

This section demonstrates basic HTML element searching and extraction.

### Real-World Website

The project then scrapes the table from:

**Wikipedia – List of largest companies in the United States by revenue**

`https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue`

The notebook extracts the first sortable Wikipedia table and converts its contents into a Pandas DataFrame.

## 📊 Data Extraction

The scraping process extracts:

* Table headers
* Table rows
* Individual table cells
* Text content from HTML elements

The extracted information is stored in a Pandas DataFrame for further analysis or processing.

## 💻 Libraries

```python
from bs4 import BeautifulSoup
import requests
import pandas as pd
```

## 📁 Output

The scraped company data is converted into a Pandas DataFrame and exported as a CSV file:

```text
companies.csv
```

## 🧠 Key Concepts Demonstrated

* HTTP Requests
* HTML Parsing
* BeautifulSoup
* `find()`
* `find_all()`
* HTML Tags
* HTML Classes
* Table Scraping
* Data Extraction
* Pandas DataFrame
* CSV Export
* Basic Web Scraping Workflow

## 🚀 How to Run

1. Clone this repository.
2. Open `WebScraping.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab.
3. Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
```

4. Run the notebook cells sequentially.
5. The scraped data will be stored in a Pandas DataFrame and exported as a CSV file.

## 📌 Project Objective

The main objective of this project is to understand how to **collect structured data from webpages and convert unstructured HTML content into a usable dataset using Python**.

## 👨‍💻 Author

**Venkata Vedhadri Marisetti**

Aspiring Data Analyst & GenAI Engineer

* GitHub: https://github.com/venkat-070
* LinkedIn: https://linkedin.com/in/venkat-vedhadri-7253a52a1
