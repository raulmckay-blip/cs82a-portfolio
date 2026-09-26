# cs82a-portfolio

Hi, I'm Raul Mac Mckay.
This is my portfolio for **CS 82A** at Santa Monica College, an intro to data science with Python.

Each module has its own folder with the lab notebooks (`.ipynb`) and the datasets they use, so every notebook runs as-is from inside its folder.

---

## Module 1: What Is Data Science / Setting Up the Toolkit

| Lab | What it covers |
|---|---|
| `module1_lab.ipynb` | My AI-use policy for the course: how I use AI tools to learn without letting them do the work for me. |
| `module1_lab2.ipynb` | Summary table of chick weights by feed type (min / mean / max) and a recommendation on the best feed. |
| `module1_lab3.ipynb` | **Problem 1.2:** Picking an auto insurance provider from customer ratings by comparing min, mean, and max. |

## Module 2: Python Foundations

| Lab | What it covers |
|---|---|
| `Module2Lab1.ipynb` | Python warm-up: variables, f-strings, lists, loops, functions, dictionaries, and loading a CSV with pandas (`chickwts.csv`). |
| `Module2Lab2.ipynb` | **Problem 4.2:** Multiplication using only repeated addition, written with a `for` loop and a `while` loop. |
| `Module2Lab3.ipynb` | **Problem 4.4:** Sorting temperature readings into Cold / Warm / Hot with a loop and an `if/elif/else` chain. |

## Module 3: Data Types, Storage, and Cleaning

| Lab | What it covers |
|---|---|
| `module3_lab.ipynb` | Cleaning a messy sales dataset: duplicates, zip codes with lost leading zeros, mixed date formats, and negative quantities (flagged as returns). Saves `sales_clean.csv`. |
| `Module3Lab2.ipynb` | **Problem 2.1:** Finding impossible and extreme values in the US arrests data (`usarrests.csv`) using logic checks and the IQR rule. |
| `Module3Lab3.ipynb` | **Problem 2.2:** Screening bridge lengths for outliers (`bridges.csv`) when there's no obvious "impossible" cutoff. |

## Module 4: Describing Data (Center, Spread, and Correlation)

| Lab | What it covers |
|---|---|
| `Module4Lab1.ipynb` | Mean vs. median on skewed prices, a histogram, a new `revenue` column, a correlation matrix, and a scatter plot, all on the cleaned sales data from Module 3. |
| `Module4Lab2.ipynb` | **Problem 3.1:** Bookstore inventory. Median of a category (cover type), overall mean weight, and hardcover vs. paperback group means (`allbacks.csv`). |
| `Module4Lab3.ipynb` | **Problem 3.2:** Truck list price vs. sale price. Pearson's r ≈ 0.999, a scatter plot, and a straight-line prediction with a confidence argument (`truck.csv`). |

---

## Skills so far

- **Python basics:** variables, loops, conditionals, functions, lists, dictionaries
- **pandas:** loading CSVs, inspecting data, cleaning, `groupby`, summary statistics
- **Data cleaning:** duplicates, type fixes, dates, zip codes, spotting impossible values and outliers
- **Descriptive stats:** mean, median, standard deviation, skew, IQR
- **Relationships:** correlation matrices, Pearson's r, scatter plots, simple predictions
- **Visualization:** matplotlib histograms and scatter plots

## Tools

Python 3 · pandas · NumPy · matplotlib · Jupyter · VS Code · Git/GitHub

## How to run

1. Clone the repo: `git clone https://github.com/raulmckay-blip/cs82a-portfolio.git`
2. Open any module folder in VS Code or Jupyter.
3. Run the notebook top to bottom. The CSVs it needs are in the same folder.
