# Homework 1
### Walid Ajbar, Arya Jakkli, Alen Rostomyan

## Overview
#### This notebook processes and visualizes temperature anomaly data from the Northern and Southern Hemispheres to calculate and display the global average temperature anomaly for each year. The final visualization is presented as a "stripes" plot, with each stripe representing the temperature anomaly of a specific year and colored according to a predefined color palette.

## Packages
The following packages are required to run this code:
- Pandas
- Matplotlib
#### You can install required packages via: 
```bash
pip install pandas numpy scipy matplotlib 
```

## Data used
- SoMon.csv: Contains monthly temperature anomalies for the Northern Hemisphere
- NoMon.csv: Contains monthly temperature anomalies for the Southern Hemisphere <br/>
### Each CSV file has the following columns:
- **Time**: The month and year (in YYYY-MM format).
- **Anomaly** (deg C): Temperature anomaly relative to the 1961-1990 baseline.
- **Lower confidence limit (2.5%)**: Not used
- **Upper confidence limit (97.5%)**: Not used

## How to run
Once you have installed the following files to the same directory:
- "Homework 1 - WA, AJ, AR.ipynb"
- "SoMon.csv"
- "NoMon.csv"
<b/>
Open "Homework 1 - WA, AJ, AR.ipynb" in your chosen notebook interface and run all the code.
