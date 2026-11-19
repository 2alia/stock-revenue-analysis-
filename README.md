# Historical Stock Price and Revenue Analysis: Tesla & GameStop

### Python | Data Science | Financial Data Analysis | Web Scraping | Data Visualisation

## Project Overview

This project explores the relationship between historical stock prices and company revenue using Tesla (TSLA) and GameStop (GME) as case studies.

The analysis uses Python to retrieve financial market data, extract historical revenue information from web sources, organise datasets and visualise financial trends.

The project was completed as part of the **IBM Data Science Professional Certificate** on Coursera, demonstrating practical skills in data extraction, data manipulation and visualisation.

## Project Objectives

The main objectives were to:

- Retrieve historical stock market data using the `yfinance` Python library.
- Extract quarterly company revenue data through web scraping.
- Clean and organise financial datasets using Pandas.
- Visualise historical stock prices and revenue using Matplotlib.
- Compare stock price movements with company revenue trends.
- Identify differences between market valuations and financial performance.

## Technologies and Libraries

| Technology | Purpose |
|---|---|
| Python | Data processing and analysis |
| yfinance | Historical stock market data extraction |
| Pandas | Data cleaning and manipulation |
| BeautifulSoup | HTML parsing and web scraping |
| Requests | Retrieving webpage content |
| Matplotlib | Financial data visualisation |
| Jupyter Notebook | Interactive development and analysis |

## Methodology

### 1. Stock Data Extraction

Historical stock market data was retrieved for Tesla (`TSLA`) and GameStop (`GME`) using the `yfinance` library.

The datasets included opening prices, highest and lowest prices, closing prices, trading volumes and trading dates.

The DataFrame indexes were reset to make dates accessible as separate columns for subsequent analysis.

### 2. Revenue Data Extraction

Historical quarterly revenue data was extracted from financial webpages using Python web scraping techniques.

BeautifulSoup and Pandas were used to process HTML content and organise the extracted information into structured datasets.

The resulting DataFrames contained two primary columns:

- **Date:** The financial reporting period.
- **Revenue:** The company's reported quarterly revenue in millions of US dollars.

### 3. Data Preparation

The datasets were prepared for analysis by:

- Converting date values into appropriate formats.
- Removing currency symbols and commas from revenue values.
- Converting revenue figures into numerical data.
- Organising stock price and revenue information into Pandas DataFrames.

### 4. Data Visualisation

A reusable `make_graph()` function was used to produce historical financial visualisations for both companies.

The function generated two graphs for each company:

1. Historical share price movements.
2. Historical quarterly revenue trends.

Matplotlib was used to create static visualisations, allowing both financial measures to be examined over time.

## Key Findings

### Tesla (TSLA)

The analysis identified substantial growth in Tesla's share price and reported revenue, particularly during the period leading up to 2021.

Both measures showed strong upward trends, suggesting that Tesla's increasing business activity occurred alongside growing investor interest and market valuation.

However, the graphs alone do not establish a causal relationship between revenue growth and share price movements.

### GameStop (GME)

GameStop demonstrated a significantly different pattern.

The company's share price experienced an exceptional increase during 2021, while quarterly revenue did not demonstrate a corresponding surge.

This illustrates how financial market movements can differ considerably from underlying company revenue trends.

### Comparative Analysis

The comparison highlights an important distinction:

**Stock prices are influenced by more than a company's reported revenue.**

Tesla's historical results demonstrated growth in both revenue and share price, whereas GameStop's results showed a substantial divergence between these measures.

The findings demonstrate the importance of considering multiple financial indicators when evaluating company performance.

## Repository Contents

`Revenue Data and Building a Dashboard-v1.ipynb`

The Jupyter Notebook contains the six exercises:

1. Tesla historical stock data extraction.
2. Tesla quarterly revenue extraction.
3. GameStop historical stock data extraction.
4. GameStop quarterly revenue extraction.
5. Tesla stock price and revenue visualisation.
6. GameStop stock price and revenue visualisation.

## Running the Project

Clone the repository:

```bash
git clone https://github.com/2alia/stock-revenue-analysis-.git
```

Install the required libraries:

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib jupyter
```

Open the Jupyter Notebook using Jupyter or VS Code and run the cells in sequence.

An internet connection is required to retrieve financial data from external sources.

**Note:** Financial data and webpage structures may change over time, so results can differ when the notebook is rerun.

## Skills Demonstrated

- Financial data extraction using Python.
- Web scraping and HTML parsing.
- Data cleaning and transformation.
- Working with Pandas DataFrames.
- Time-series data visualisation.
- Comparative financial analysis.
- Interpreting trends and communicating analytical findings.

## Project Context

This project was developed as part of the IBM Data Science Professional Certificate on Coursera.

The notebook demonstrates the application of foundational data science techniques to real-world financial information, with an emphasis on extracting, preparing, visualising and interpreting data.

## Disclaimer

This project is intended for educational and analytical purposes only. The findings do not constitute financial or investment advice.
