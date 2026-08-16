# Data Collection from Multiple Sources (Web Scraping, APIs, Google Sheets)

## Objective
Practice different ways to obtain data for analysis beyond static CSV files: HTML tables, REST APIs, and Google Sheets spreadsheets.

## Content
- Direct reading of **HTML tables** from a web page (air quality data — GIOS) using `pandas.read_html`
- Data consumption via a public **REST API** (JSON) using `requests` / `pandas.read_json`
- Normalization of nested JSON using `pandas.json_normalize`
- Integration with **Google Sheets** as a data source
- Aggregations with `groupby` on the collected data

## Technologies
`Python` `pandas` `requests`

## How to Run
```bash
pip install pandas requests
jupyter notebook "pobieranie danych z rożnych źródeł, praca z bazą i groupby.ipynb"
