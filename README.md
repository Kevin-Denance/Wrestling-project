## 🤼‍♂️ Collegiate Athlete Web Scraper

This project features a Python-based web scraping pipeline designed to extract, clean, and structure player information from collegiate athletics websites (specifically targeting wrestling rosters).

### 📋 Project Overview

The script automates the collection of athlete data, transforming unstructured HTML content into a structured dataset. The workflow includes:

* **Web Scraping**: Utilizing `BeautifulSoup` and `Requests` to crawl roster pages and individual player profiles.
* **Data Structuring**: Extracting specific attributes such as **Name, Weight Class, Academic Class, Hometown,** and **High School**.
* **Data Cleaning**: Implementing `pandas` logic to handle inconsistent web formatting (e.g., shifting data columns when "Weight Class" is missing).
* **Exporting**: Generating a final, cleaned `TeamData.csv` for downstream analysis.

### 🔍 View Detailed Project

To see the full technical implementation, code commentary, and data cleaning logic, please open the Jupyter Notebook:
👉 **[Web scraper to get players info.ipynb](https://github.com/Kevin-Denance/Wrestling-project/blob/main/Web%20scraper%20to%20get%20players%20info.ipynb)**

### 🛠️ Technologies Used

* **Python 3**
* **BeautifulSoup4** (HTML Parsing)
* **Requests** (HTTP Library)
* **Pandas** (Data Manipulation & Cleaning)

