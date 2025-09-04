# Linear Regression on Stress-Strain (Elastic Region)

This project applies **linear regression** to the elastic portion of a stress-strain curve to estimate **Young’s Modulus**.

## Files
- `linear_regression_elastic.py` → Python script for data loading, regression, and plotting  
- `tensile.xlsx` → Example dataset (strain vs stress)

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn openpyxl
2. Run the script:

python linear_regression_elastic.py

3. The script will:

- Read tensile.xlsx
- Extract the elastic region
- Fit a linear regression model
- Plot stress-strain curve with regression line

Output:
- A plot showing experimental data (blue) and linear regression fit in the elastic region (red).
- Estimated Young’s Modulus (slope of regression line) printed in console.
