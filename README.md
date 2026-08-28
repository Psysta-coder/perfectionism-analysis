# Perfectionism Survey Analysis

This project analyzes psychological survey data (N=82) measuring **Perfectionism**, **Procrastination**, **Resilience**, and **Self-Efficacy** among university students.

## What's in this repository?
- **perfectionism.xlsx** – Raw survey data (Farsi Likert-scale responses).
- **perfectionism.ipynb** – Complete Python analysis notebook.

## Key Steps in the Notebook
1. **Data Cleaning**: Converted Farsi responses to numeric values (1–5).
2. **Reverse-Coding**: Corrected reversed items in Procrastination and Resilience scales using `new_score = 6 - old_score`.
3. **Composite Scores**: Calculated average scores for each psychological construct.
4. **Statistical Tests**: Performed t-tests, Pearson correlations, and ANOVA.

## Results Summary
- **Significant Gender Difference**: Females scored higher in Perfectionism (p = 0.003).
- **Positive Correlations** (after corrections):
  - Perfectionism ↔ Self-Efficacy (r = 0.28, p = 0.011)
  - Resilience ↔ Self-Efficacy (r = 0.25, p = 0.026)
- No significant differences found across education levels.

## How to Run
1. Clone this repository.
2. Install required libraries:  
   `pip install pandas numpy matplotlib seaborn scipy openpyxl`
3. Open `perfectionism.ipynb` in Jupyter Notebook and run all cells.

## Tools Used
- Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)
- Jupyter Notebook
