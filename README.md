# Python Job Listings Scraper

A lightweight, automated Python scraper built to extract, clean, and organize job postings into structured data. Instead of manually browsing multiple job boards, this tool aggregates relevant listings instantly into a single file.

## Project Context
This tool was developed to solve the practical challenge outlined in the [Roadmap.sh Job Listings Scraper Project](https://roadmap.sh/projects/job-listings-scraper).

## Why This Matters
Finding the right job is a data problem. This tool solves it by saving hours of manual searching. It allows you to track market trends, monitor specific companies, and build a localized job database on demand.

## Key Features
* **Automated Extraction:** Pulls job titles, companies, locations, and application links in seconds.
* **Smart Data Cleaning:** Filters out duplicates and formats raw HTML into clean text.
* **Instant Export:** Saves results directly to a structured `job_listings.csv` for easy filtering in Excel or Google Sheets.
* **Jupyter Native:** Built inside a `.ipynb` notebook for easy step-by-step execution and visual data debugging.

## Tech Stack
* **Python 3**
* **Requests** (for handling HTTP requests and fetching page HTML)
* **BeautifulSoup4** (for parsing HTML and extracting job data)
* **Built-in `csv` module** (for zero-dependency CSV data exporting)

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Python-Job-Listings-Scraper
   ```

2. **Set up your environment & install dependencies:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Run the scraper:**
   Open `Python_Job_Listings_Scraper.ipynb` in VS Code or Jupyter Notebook and run all cells.
