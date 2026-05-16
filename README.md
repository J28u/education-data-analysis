# Education Data Analysis

**OpenClassrooms — Data Scientist Path | Project 2** (September–October 2022)

> Note: project deliverables (notebook, presentation) are in French.

## Sector
Education

## Tech Stack
- Jupyter Notebook
- Python: pandas, numpy, matplotlib, seaborn, missingno

## Context
The client, a fictional startup called *Academy*, offers online courses for high school students and above. They are planning to expand internationally and want to identify which countries to prioritize.

We were provided with several files containing thousands of education-related indicators across hundreds of countries, collected by the World Bank.

## Mission
Conduct a pre-exploratory analysis to assess whether the dataset is of sufficient quality to inform the company's expansion strategy. If so, propose a shortlist of countries matching the client's criteria.

## Deliverables
- `notebook.ipynb` — Jupyter notebook with the full pre-exploratory analysis
- `toolbox.py` — helper functions used in the notebook
- `presentation.pdf` — presentation slides (in French)

## Methodology
1. **Data cleaning**
   - Understand available variables and select the most relevant ones
   - Assess data quality and discard countries, indicators, and years with excessive missing values
   - Impute missing values using linear interpolation (annually spaced data)

2. **Data analysis**
   - Visualize data distributions using boxplots
   - Build a country attractiveness score using percentile ranking

## Skills
- Setting up a Python environment
- Creating data visualizations with Python libraries
- Applying core Python operations for data science
- Manipulating data with specialized Python libraries
- Using Jupyter Notebook for analysis and collaboration

## Data Source
[World Bank — Education Statistics](https://datacatalog.worldbank.org/dataset/education-statistics)
