# StressStrain-Regression-Models
This repository contains Python projects that analyze **tensile test stress–strain data** using regression techniques.  
The goal is to demonstrate how data science and mechanical engineering concepts (like elasticity and Young's modulus) can be combined for material property analysis.

---

## Projects Included

### 1. **Linear Regression on Elastic Region**
- Reads stress–strain data from Excel.
- Extracts the elastic region (user-defined strain limit). Here assumed to be 0.002. 
- Applies **linear regression** to estimate the slope (≈ Young’s modulus).
- Visualizes the fit against experimental data.

### 2. **General Stress–Strain Linear Fit**
- Works for **any dataset** with two columns (strain, stress).
- No fixed 0.002 cutoff; user can provide elastic limit or use the full dataset.
- Auto-detects column names.
- Outputs regression equation and plot.

Future Scope -

### 3.  **Multiple Linear Regression**  
- Extends analysis to cases with multiple input variables (features).
- Demonstrates how stress can be modeled as a function of **more than one predictor** (e.g., strain, temperature, strain rate).
- Useful for advanced material behavior prediction.

---

## Example Workflow

1. Prepare your tensile test data in Excel format:
   - Column 1: Strain
   - Column 2: Stress

2. Run the program
3. Enter elastic limit if prompted (e.g., 0.002) or use 0 for full dataset.

4. Get output:
- Regression equation
S- tress–strain plot with fitted line

## Applications
- Estimation of Young’s modulus from experimental data
- Curve fitting of stress–strain response
- Extension to multi-feature regression for advanced material models
- Educational demos for engineering + machine learning
