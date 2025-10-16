# Project 1: Classification Algorithms

## Overview
This project compares 6 classification algorithms on 2 datasets using 10-fold cross-validation with enhanced visualization and reporting.

## Files
- `Project1.ipynb` - Main notebook with analysis and visualizations
- `project1_dataset1.txt` - Breast Cancer dataset (568 samples, 30 features)
- `project1_dataset2.txt` - Diabetes dataset (461 samples, 9 features)
- `classification_outputs/` - CSV results from experiments
- `classification_results_visualization.png` - Performance comparison charts
- `classification_results_table.txt` - Formatted results table
- `requirements.txt` - Python dependencies

## Quick Start
```bash
pip install -r requirements.txt
jupyter notebook Project1.ipynb
```

## Results Summary
- **Dataset 1 (Breast Cancer)**: All algorithms achieve F1 > 0.89
- **Dataset 2 (Diabetes)**: More challenging classification (F1 0.46-0.60)
- **Best Performers**: SVM and Neural Network on Dataset 1, Naive Bayes on Dataset 2

## Outputs
- Comprehensive visualizations (4-panel chart)
- Formatted results tables
- CSV exports for further analysis
- PNG visualization for reports
