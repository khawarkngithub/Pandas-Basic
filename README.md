# Pandas Practice

## Project Overview

This repository contains a beginner-level Jupyter Notebook documenting my practical
Pandas learning examples. The notebook focuses on core data structures and indexing
with small, reproducible datasets.

This repository demonstrates the topics actually practiced in the notebook; it does
not imply experience with topics not included in the examples.

## Learning Objectives

- Import Pandas in the two common styles demonstrated in the notebook
- Create Pandas DataFrames from dictionaries
- Create Pandas Series from lists and dictionaries
- Use default and custom labels for Series and DataFrame indexes
- Access rows with DataFrame `.loc`
- Compare duplicate examples and understand which indexing syntax they demonstrate

## Actual Topics Covered

- Pandas import styles:
  - `import pandas`
  - `import pandas as pd`
- Checking the installed Pandas version
- DataFrame creation from a dictionary
- Series creation from a list
- Series creation from a dictionary
- Default numeric indexes
- Custom string indexes
- Selecting a Series value by label
- Creating a DataFrame from a dictionary of lists
- Row selection with `DataFrame.loc`
  - One row
  - Multiple rows
  - A row with a custom index label

## Technologies Used

- Python
- Pandas
- Jupyter Notebook

## Repository Structure

```text
Pandas-Practice/
├── notebooks/
│   └── pandas.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

## Installation

From the repository root, create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

On macOS or Linux, activate the environment with:

```bash
source .venv/bin/activate
python -m pip install -r requirements.txt
```

## Running the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open `notebooks/pandas.ipynb`.

You can also run the notebook from the command line:

```bash
jupyter nbconvert --execute --inplace notebooks/pandas.ipynb
```

## Future Learning Goals

- Reading CSV and Excel data
- Inspecting datasets with `head`, `tail`, `shape`, `info`, and `describe`
- Selecting and filtering rows and columns
- Handling missing values
- Cleaning and transforming data
- Grouping and aggregating
- Creating pivot tables
- Merging and concatenating DataFrames
- Visualizing Pandas data

## Author

**Khawar Khan**

- GitHub: [@khawarkngithub](https://github.com/khawarkngithub)
- Repository: [Pandas-Practice](https://github.com/khawarkngithub/Pandas-Practice)
