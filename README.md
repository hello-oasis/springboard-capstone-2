# springboard-capstone-2

# Airbnb Price & Booking Analysis

## Overview
Analysis of Airbnb listing data across multiple US cities to identify 
which features drive pricing and booking rates.

## Project Structure
```
Capstone 2 - Airbnb/
├── data/
│   ├── raw/          ← original CSV files (not tracked in git)
│   └── processed/    ← cleaned outputs (not tracked in git)
├── notebooks/
│   └── Captstone_2_Airbnb_Data_Wrangling.ipynb
└── README.md
```

## Data Source
Inside Airbnb — http://insideairbnb.com/get-the-data  
Download detailed listings CSV files for target cities (or all cities) 
and place them in `data/raw/` before running the notebook.

## Notebooks
| Notebook | Description |
|----------|-------------|
| `Captstone_2_Airbnb_Data_Wrangling.ipynb` | Data cleaning, amenity standardization, feature engineering |

## Requirements
```
pip install pandas scikit-learn
```

## Key Steps
- Combined listings data across multiple US cities (268,387 listings)
- Cleaned and standardized 40,000+ raw amenity strings into 54 canonical categories
- Engineered features for room type, bathrooms, host responsiveness, and review signals
- Output: `data/processed/airbnb_clean.csv`
```
