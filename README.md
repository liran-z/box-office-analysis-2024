# 2024 Box Office Data — Scraping & Visualization

A data project that scrapes worldwide box office data for 2024 and visualizes
the domestic vs. foreign gross breakdown for the top 50 films.

## Project Overview

Box office performance data is publicly available but not easily downloadable.
This project automates the collection of the top 100 highest-grossing films of
2024 from Box Office Mojo using Selenium, then visualizes the domestic/foreign
revenue split via Tableau.

## Files

| File | Description |
|------|-------------|
| `box_office_scraping_code.ipynb` | Web scraping script using Selenium |
| `box_office_top_100_2024.csv` | Scraped dataset — top 100 worldwide grossing films of 2024 |
| `Data_Visualization_Preview.pdf` | Tableau bar chart: Domestic vs Foreign Gross for top 50 films |

## Key Findings

- **Inside Out 2** topped the 2024 worldwide box office at ~$1.7B
- Most top-grossing films were heavily foreign-dominant (pink), reflecting
  the global reach of major franchises
- **Deadpool & Wolverine** had the highest domestic share among the top 5

## Tech Stack

- Python, Selenium, Pandas — data scraping & export
- Tableau — data visualization
