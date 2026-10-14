 # Housing price analysis

## Question

Which housing attributes are most useful for explaining the target house-price measure in the supplied course dataset?

## Dataset

The dataset is the course-provided `housing.csv` used in CISC7204 Assignment 01. It contains no credentials or personal records.

## Methods and tools

Python, pandas, NumPy, Matplotlib, and scikit-learn. The notebook documents loading, cleaning, exploratory plots, feature/target preparation, and a baseline regression comparison.

## Main finding

Living-area and location/income-related variables show the clearest visible relationship with the target in the exploratory analysis. The baseline model is a reproducible reference for later improvement.

## Visual evidence

- `visualizations/price_distribution.png` — distribution of the target price.
- `visualizations/living_area_price.png` — relationship between living area and price.

## Limitation

This is a coursework demonstration rather than a production valuation model: the data vintage, omitted external factors, and linear baseline limit generalisation.

## Run instructions

Open `housing_analysis.ipynb` in Jupyter and run the cells from top to bottom. Keep `housing.csv` beside the notebook. The two PNG files in `visualizations/` were generated from the same dataset.

The project is prepared locally. A public GitHub URL will be added only after the student confirms repository names and visibility.
