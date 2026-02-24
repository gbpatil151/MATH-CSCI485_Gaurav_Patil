# Assignment 2 – Recursive Feature Elimination (RFE)

**Course:** CSCI 485  
**Student:** Gaurav Patil  

---

## Repository Contents

- **Assignment2_485.ipynb**  
  Jupyter Notebook containing full implementation, outputs, tables, and figures.

- **485_A2.pdf**  
  Final written report summarizing methodology, results, and analysis.

- **485_A2_run.pdf**  
  PDF export of the notebook without execution outputs.

---

## Project Overview

This project implements **Recursive Feature Elimination (RFE)** using **Linear Regression** on the scikit-learn Diabetes dataset.

The objectives were to:

- Train a baseline linear regression model  
- Apply RFE to iteratively eliminate features  
- Track test R² across different feature counts  
- Identify the optimal number of retained features  
- Analyze feature importance and model behavior  

The optimal model retained **6 features** and achieved a test R² of approximately **0.4628**, slightly improving over the full 10-feature baseline model.

---

## Requirements

Python 3.x with the following libraries:

- numpy  
- pandas  
- scikit-learn  
- matplotlib  

Install dependencies using:

```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## How to Run

1. Open `Assignment2_485.ipynb` in:
   - Jupyter Notebook, or  
   - Google Colab  

2. Run all cells from top to bottom.

All tables, figures, and outputs used in the report will be generated automatically.

The train/test split uses:

```python
random_state = 42
```

to ensure reproducibility.

---

## Key Results

- Baseline Linear Regression Test R²: **0.4526**  
- Optimal RFE Model (k = 6) Test R²: **0.4628**  
- Selected Features:  
  `sex, bmi, bp, s1, s2, s5`

---

## Notes

- The notebook (`Assignment2_485.ipynb`) contains all required outputs.
- The report (`485_A2.pdf`) summarizes findings and includes figures and analysis.
- `485_A2_run.pdf` is a clean export of the notebook without execution outputs.