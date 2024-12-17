# JustWatch Web Scraper

This project provides a Python-based solution for scraping movie and TV show data from JustWatch, a popular streaming guide. It allows users to extract detailed information such as titles, genres, streaming platforms, prices, and more.

## Features

- **Comprehensive Data**: Extract details on movies, TV shows, and streaming availability.
- **Platform Support**: Scrapes data for multiple streaming platforms supported by JustWatch.
- **Customizable Queries**: Search and filter data based on genre, year, and other parameters.
- **Notebook-Based Workflow**: Includes an interactive Jupyter Notebook for easy usage and experimentation.

## Prerequisites

- **Python 3.7+**
- Jupyter Notebook (for running `.ipynb` files)
- Essential Python libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `json` (standard library)

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the provided notebook: `JustWatch_Web_Scraping_Tukaram_Munde.ipynb`.
3. Follow the steps in the notebook to:
   - Configure your scraping parameters.
   - Run the scraping script.
   - Export and analyze the scraped data.

## Output

The scraper generates a structured dataset in a CSV format (or another specified format), which includes information such as:

- Movie/Show Title
- Genre
- Release Year
- Streaming Platforms
- Pricing Details (if available)

## Notes

- **Legal Disclaimer**: Ensure your usage complies with JustWatch's Terms of Service and any applicable laws. This scraper is intended for educational and personal use.
- **Responsibility**: Be mindful of the load placed on JustWatch's servers when using this tool.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss changes or new features.

