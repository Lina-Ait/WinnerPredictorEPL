# Football Match Winner Prediction - English Premier League (EPL)

## Project Overview
This project aims to predict the winner of football matches in the English Premier League (EPL) using machine learning techniques.

## Project Steps
1. **Scrape match data** using `requests`, `BeautifulSoup`, and `pandas`.
2. **Clean and preprocess data** to prepare it for machine learning.
3. **Make predictions** using `scikit-learn`.
4. **Evaluate and improve predictions** by measuring errors and refining models.

## Code
You can find the code for this project in the following files:
- **`scraping.ipynb`** - A Jupyter notebook that scrapes match data from FBref.
- **`predictions.ipynb`** - A Jupyter notebook that makes predictions based on scraped data.

## Local Setup
### Installation
To run this project locally, install the following dependencies:

#### Prerequisites:
- JupyterLab
- Python 3.8+

#### Required Python Packages:
```bash
pip install pandas requests beautifulsoup4 scikit-learn
```

## Data
The project collects match data from **FBref** using web scraping techniques. The scraped data is stored in a CSV file.

- If you want to scrape fresh data, run **`scraping.ipynb`**.
- If you only want to work with existing data, download `matches.csv` and proceed with **`predictions.ipynb`**.

## Usage
1. Open **JupyterLab**.
2. Run `scraping.ipynb` to gather match data (if needed).
3. Run `predictions.ipynb` to train the model and make predictions.
