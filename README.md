# Scrapping-and-Skill-Analysis

## Description
This project is designed to scrape job vacancy data from websites and analyze required skills. The scripts collect data from web pages, count the frequency of various skills mentioned, and visualize the results in a histogram.

## Project Structure
- `scraper.py`: Script for scraping job vacancies.
- `counter.py`: Script for counting skill mentions on job vacancy pages.
- `main.py`: The main script that coordinates the work of `scraper.py` and `counter.py`, and saves the results to a CSV file.
- `writer.py`: Script for writing results to a CSV file.
- `data_analysis`: Folder for saving the CSV file and Jupyter Notebook for data analysis.
- `requirements.txt`: A file listing the project dependencies.

## Execution
To run the project, execute:
1. `pip install -r requirements.txt`
2. `python main.py`

The results will be saved in the `data_analysis` folder as a CSV file. Use the Jupyter Notebook in this folder to visualize the results.

## Data Visualization
Open the Jupyter Notebook in the `data_analysis` folder to view the histogram of skills.

## Dependencies
- Python 3
- Requests
- BeautifulSoup4
- Pandas
- Matplotlib
- Jupyter Notebook