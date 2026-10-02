# Countries Data Analysis

Exploratory analysis of a countries dataset using Python, Pandas, and NumPy.

## Project Overview

This project focuses on inspecting and querying a countries dataset containing geographic, demographic, economic, and political attributes.

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Analysis Performed

- Loaded the dataset with Pandas
- Inspected dataset shape and structure
- Used `info()` and `describe()` for dataset inspection
- Queried countries by maximum and minimum population
- Retrieved related capital-city information
- Sorted countries by democracy score
- Counted countries by region using `value_counts()`
- Filtered records by region
- Used `nlargest()` to inspect population rankings
- Identified missing values in the political leader column using `isna()`

## Dataset

The notebook expects a file named `Countries.csv` in the project directory.

## How to Run

1. Install the dependencies:
   ```bash
   pip install pandas numpy jupyter
   ```
2. Place `Countries.csv` in the project directory.
3. Open `countries.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells in order.

## Learning Focus

This project was created to practice practical Pandas operations including filtering, sorting, aggregation, missing-value detection, and basic dataset exploration.
