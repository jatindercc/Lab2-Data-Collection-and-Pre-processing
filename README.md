# Sales Data Cleaning & Profiling Project

This project demonstrates an end-to-end mini data pipeline using a public sales dataset.  
It covers loading raw CSVs, implementing custom data structures, cleaning rules, profiling statistics, feature engineering, and lightweight aggregations.  
The goal is to practice reproducible analysis, function-driven design, and structured data documentation through a notebook format.  
Outputs are saved into organized subfolders (`data/outputs/`) for JSON, CSV, and reporting.

## Quick Start

```bash
# create a virtual environment
python -m venv venv

# activate environment
# On Mac/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

# install dependencies
pip install -r requirements.txt

# launch Jupyter
jupyter notebook



### Data Sources

## Primary dataset (1000 Sales Records): ExcelBIAnalytics sample 
 (trimmed to 500 rows for this project)

## Secondary metadata (Product Catalogue / City lookup): 
public open-data catalogue samples & synthetic enhancements created for coursework.

##How to use:

## Place this file in your project root as requirements.txt.

Run:
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
jupyter notebook
