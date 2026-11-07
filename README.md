# Exploratory Data Analysis (EDA)

This repository contains the datasets and Tableau workbooks for a country-level exploratory data analysis project. The materials cover health spending, life expectancy, population, and GDP.

## Repository structure

```text
EDA/
├── README.md
├── data/
│   ├── raw/
│   │   ├── health-spending.xlsx
│   │   ├── life-expectancy.xlsx
│   │   └── population-and-gdp-by-country.xlsx
│   └── processed/
│       └── life-expectancy-cleaned.csv
└── tableau/
    ├── group11-cw2-dashboard.twbx
    └── group11-cw2-four-visuals.twbx
```

## Contents

### Data

| Location | File | Description |
|---|---|---|
| `data/raw/` | `health-spending.xlsx` | Source workbook containing health-spending data. |
| `data/raw/` | `life-expectancy.xlsx` | Source workbook containing life-expectancy data. |
| `data/raw/` | `population-and-gdp-by-country.xlsx` | Source workbook containing country-level population and GDP data. |
| `data/processed/` | `life-expectancy-cleaned.csv` | Processed life-expectancy dataset for analysis. |

### Tableau workbooks

| File | Description |
|---|---|
| `tableau/group11-cw2-dashboard.twbx` | Packaged Tableau workbook for the Group 11 coursework dashboard. |
| `tableau/group11-cw2-four-visuals.twbx` | Packaged Tableau workbook containing four visuals. |

Open the `.twbx` files in Tableau Desktop or Tableau Public (where supported).

## Getting started

1. Download or clone this repository.
2. Open the Tableau packaged workbook(s) from the `tableau/` directory.
3. Use the source spreadsheets in `data/raw/` when inspecting or reproducing the analysis.
4. Use the cleaned CSV in `data/processed/` for downstream analysis where appropriate.

## Notes

- Original datasets and Tableau workbooks are retained; this reorganization changes their folder locations and filenames only.
- The cleaned CSV is kept separate from source files to distinguish processed data from raw inputs.
- The repository currently contains no analysis scripts or notebook files.
