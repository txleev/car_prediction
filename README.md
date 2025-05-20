# Car Price Prediction Lab

A Python project for scraping car listings from Mashina.kg, preprocessing data, building regression models to predict car prices, and interpreting model outputs.

---


## Overview

This lab (`project.ipynb`) demonstrates an end-to-end machine learning workflow:

- **Scrape** car data (model, year, mileage, engine volume, etc.) from [Mashina.kg](https://www.mashina.kg)  
- **Process** and encode features (categorical encoding)  
- **Train** regression models (Linear Regression, Random Forest, XGBoost)  
- **Evaluate** model performance  
- **Interpret** model coefficients to derive insights on pricing factors  

---

## Features

- Web scraping of multiple pages of car listings using `requests` and `BeautifulSoup`  
- Assembly of data into a `pandas` DataFrame  
- Handling of missing values and type conversions  
- One-hot encoding of categorical variables  
- Train/test split for model validation  
- Comparison of multiple regression algorithms  
- Coefficient analysis of Linear Regression  
- Feature-importance visualization for tree-based models  

---

## Prerequisites

- Python 3.6 or higher  
- Packages:
  - `pandas`
  - `numpy`
  - `requests`
  - `beautifulsoup4`
  - `scikit-learn`
  - `xgboost`
  - `matplotlib`

Install dependencies via:

```bash
pip install pandas numpy requests beautifulsoup4 scikit-learn xgboost matplotlib
