# Web Scraping Quotes Dataset

## Project Overview

This Python project scrapes quotes, author names, and tags from [Quotes to Scrape](http://quotes.toscrape.com/), a website built for safe web-scraping practice.

## What It Does

- Collects data from multiple pages using pagination
- Extracts quotes, authors, and related tags
- Cleans duplicate data
- Analyzes popular authors and tags
- Saves the final dataset as `quotes_dataset.csv`

## Tools Used

- Python
- Requests
- BeautifulSoup
- Pandas
- lxml

## How to Run

```bash
pip install requests beautifulsoup4 pandas lxml
