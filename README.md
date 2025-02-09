# Yektanet Data Analysis

## Overview
This project analyzes a dataset provided by Yektanet, a digital advertising company. The dataset contains information about Persian websites, including:
- Keywords associated with each website.
- Website segmentation categories used for advertising.
- Average daily visit counts.

The goal is to analyze and visualize the popularity of Persian websites based on commonly used keywords.

## Dataset
The dataset (`yektanet.csv`) consists of the following columns:
- `keywords`: Keywords describing each website, typically used for search rankings.
- `segments`: Categories assigned to websites for advertising purposes.
- `visit count`: The average number of daily page visits.

## Dependencies
To run this analysis, you need the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. Open `yektanet.ipynb` in Jupyter Notebook.
2. Run the cells sequentially to:
   - Load and inspect the dataset.
   - Analyze keyword popularity.
   - Visualize trends using charts.

## Results
The notebook provides insights into the most popular keywords used in Persian websites and their relative popularity based on visit counts.
