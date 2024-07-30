
# Noon EDA

This Jupyter Notebook performs an exploratory data analysis (EDA) on a dataset obtained from a web scraping of the Noon e-commerce platform. The analysis includes data cleaning, transformation, and visualization to extract insights about the products listed.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Cleaning](#data-cleaning)
4. [Analysis and Visualization](#analysis-and-visualization)
5. [Requirements](#requirements)
6. [How to Run](#how-to-run)

## Introduction

This analysis aims to explore the products on Noon by examining features such as price, rating, and title. The analysis includes:

- Identifying the most and least expensive products.
- Understanding the distribution of product ratings.
- Exploring the relationship between price and rating.

## Dataset

The dataset used in this analysis is `NoonPricelist.csv`, which contains product information such as:

- `Title`: The name of the product.
- `Price`: The price of the product.
- `Rating`: The rating of the product.

## Data Cleaning

The data cleaning process involved:

- Removing unnecessary columns.
- Converting price values to numeric format.
- Handling missing or placeholder values in the rating column.

## Analysis and Visualization

The analysis includes:

- Distribution of product ratings.
- Scatter plots to show the relationship between price and rating.
- Identification of the most and least expensive products.

## Requirements

The analysis requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn

## How to Run

1. Clone the repository or download the notebook.
2. Ensure you have Python installed (preferably version 3.6 or higher).
3. Install the required libraries using `pip`:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook using Jupyter:
   ```bash
   jupyter notebook Noon__EDA.ipynb
   ```
5. Run the cells in the notebook to see the analysis and visualizations.
