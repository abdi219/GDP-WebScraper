# World GDP Web Scraper

## Overview

World GDP Web Scraper is a Python project that demonstrates how to collect, clean, transform, and export tabular data from a webpage using the Pandas library.

The project extracts a table containing the world's largest economies by nominal Gross Domestic Product (GDP) from an archived Wikipedia page. After retrieving the data, it performs several preprocessing steps before exporting the cleaned dataset as a CSV file.

This project serves as a practical introduction to web scraping with Pandas and basic data preprocessing techniques.

## Objectives

Extract HTML tables from a webpage.

Select the required dataset from multiple tables.

Clean and organize the extracted data.

Convert GDP values from millions to billions of US dollars.

Round numerical values for improved readability.

Export the processed dataset to a CSV file.

## Dataset Source

Archived Wikipedia page containing the list of countries by nominal GDP.

https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)

## Technologies Used

Python

Pandas

NumPy

lxml

Jupyter Notebook

HTML Table Parsing

Web Scraping

CSV Data Export

## Libraries

```python
import pandas as pd
import numpy as np
```

Additional package

```
lxml
```

## Project Workflow

The project follows these steps.

Install the required Python packages.

Import the necessary libraries.

Load the archived Wikipedia page.

Extract all HTML tables using Pandas.

Select the table containing IMF GDP data.

Keep only the Country and GDP columns.

Filter the dataset to include only the top ten economies.

Rename the columns.

Convert GDP values from millions to billions.

Round GDP values to two decimal places.

Export the cleaned dataset as a CSV file.

## Project Structure

```
world-gdp-web-scraper/
│
├── World_GDP_Web_Scraper.ipynb
├── Largest_economies.csv
├── README.md
├── .gitignore
└── LICENSE
```

## Output

The final output is a CSV file named

```
Largest_economies.csv
```

The dataset contains

Country

GDP (Billion USD)

## Skills Demonstrated

Web scraping

HTML table extraction

Data cleaning

Data transformation

Data preprocessing

Working with DataFrames

CSV file generation

Basic data engineering

## Requirements

Python 3.9 or later

Install the required packages

```bash
pip install pandas numpy lxml
```

## Running the Project

Clone the repository.

```bash
git clone https://github.com/yourusername/world-gdp-web-scraper.git
```

Move into the project directory.

```bash
cd world-gdp-web-scraper
```

Install the dependencies.

```bash
pip install pandas numpy lxml
```

Open the notebook.

```bash
jupyter notebook
```

Run each notebook cell from top to bottom.

## Learning Outcomes

After completing this project you will understand how to

Extract tables directly from webpages using Pandas.

Work with HTML tables without using BeautifulSoup.

Select and manipulate DataFrame columns and rows.

Convert and format numerical data.

Export processed data into CSV format.

Build a complete data extraction workflow using Python.

## License

This project is available under the MIT License.
