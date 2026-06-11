# ML Data Cleaning Pipeline

A robust **data cleaning and preprocessing pipeline** built with pandas, applied to a realistic employee dataset (1000 rows × 6 columns).

## What it does

- Detects and handles **missing values** (NaN imputation by column type)
- Removes **duplicate rows** with configurable subset matching
- Enforces **type coercion** (dates, numerics, categoricals)
- Standardizes text fields (strip whitespace, normalize case)
- Generates a before/after **data quality report**

## Dataset

Synthetic `employees.csv` — 1000 rows with columns: `id`, `name`, `department`, `salary`, `hire_date`, `active`.

Intentionally contains nulls (~8%), duplicates (~5%), and mixed-type fields.

## Tech stack

- Python 3
- `pandas` — core pipeline
- `numpy` — numeric helpers

## Usage

Open `notebook.ipynb` in Google Colab or Jupyter. Each cell corresponds to one cleaning stage with before/after output.

## Topics

`python` `pandas` `data-cleaning` `etl` `machine-learning` `preprocessing` `data-quality`
