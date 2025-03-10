# EPL Match Winner Prediction

## Project Overview
This project aims to predict the winner of football matches in the English Premier League (EPL) using machine learning techniques. The project is divided into two main parts:

1. **Data Scraping:** Extract match data from FBref using `requests`, `BeautifulSoup`, and `pandas`.
2. **Prediction Modeling:** Use `scikit-learn` to train a model and make predictions on match outcomes.

## Project Steps

- **Scrape match data** using web scraping techniques.
- **Clean and preprocess** the data to make it suitable for machine learning.
- **Train and evaluate models** to predict match winners.
- **Measure error and refine predictions** for better accuracy.

## File Overview

- `scraping.ipynb` - Jupyter Notebook that scrapes match data from FBref.
- `predictions.ipynb` - Jupyter Notebook that builds a machine learning model and predicts match outcomes.
- `matches.csv` - Pre-scraped match data for those who want to skip the scraping step.

## Local Setup

### Prerequisites
Before running the project, make sure you have:
- **Python 3.8+** installed. 
- **JupyterLab** installed for running the notebooks.

### Running the Project

#### 1. Scraping Data
To scrape match data from FBref, follow these steps:

1. Open `scraping.ipynb` in JupyterLab.
2. Run all the cells to extract match data.
3. The scraped data will be saved as `matches.csv`.

#### 2. Making Predictions
If you already have match data, you can proceed directly to predictions:

1. Open `predictions.ipynb` in JupyterLab.
2. Run all the cells to:
   - Load the dataset.
   - Train a machine learning model.
   - Predict match winners.

## Data
- Data is scraped from **FBref**.
- If you prefer to skip scraping, you can download `matches.csv` and use it directly in the prediction notebook.
