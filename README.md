# Big Mart Sales Prediction

Predicting product sales at retail outlets using machine learning.
Built for **DataSprint 2026 – Analyze, Predict, Innovate**, a state-level
Data Science contest by Vidyalankar Polytechnic, supported by Siemens.

## Problem
Retail stores struggle with overstocking and understocking. This project
predicts the sales of a product at a given outlet from product and outlet
attributes.

## Dataset
Big Mart Sales dataset (Kaggle): 8,523 training rows, 11 feature columns,
target = `Item_Outlet_Sales`.

## Method (Altair AI Studio / RapidMiner)
Retrieve data → Set role → Replace missing values → Select attributes →
Split data (70/30) → Random Forest (100 trees) → Apply model → Performance

## Results
| Model | Correlation |
|---|---|
| Decision Tree | 0.664 |
| Gradient Boosted Trees | 0.721 |
| **Random Forest (final)** | **0.841** |

Final model RMSE: 1,030.13

## Files
- `bigMart_Sales_Prediction.pdf` – project presentation
- `BIGMART_D.rmp` – RapidMiner process file
- `bigmart_train.csv` – dataset used

## Tools
Altair AI Studio (RapidMiner)

## Future work
Time-series seasonality and additional store-level features.

## Author
Harshada Shingade
