# Yallakora Scraper

A simple Python project that scrapes match data from [Yallakora Match Center](https://www.yallakora.com/match-center#nav-menu) and saves it to a CSV file.

## Features
- Extracts:
  - Championship name
  - First team
  - Second team
  - Match time
- Outputs clean CSV with UTF-8 encoding (works with Arabic text).
- Lightweight (uses only `requests` + `BeautifulSoup`).

## Installation

Before running the notebook, you must install the required Python libraries:

```bash
pip install requests beautifulsoup4
