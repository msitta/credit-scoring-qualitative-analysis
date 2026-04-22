# credit-scoring-qualitative-analysis
Leveraging Qualitative Field Data to Reduce False Negatives in Credit Scoring Models. 
# Leveraging Qualitative Field Data to Reduce False Negatives in Credit Scoring Models

## Executive Summary
Traditional credit scoring models often fail to capture real-time operational health, leading to high "False Negative" rates—rejecting viable businesses due to rigid, outdated financial data. This project demonstrates a **Credit Scoring 2.0** approach, integrating qualitative indicators into a Machine Learning pipeline to improve decision accuracy and recapture lost revenue.

## Key Features (The "Human" Alpha)
Unlike "Black Box" models, this approach uses features derived from field experience:
* **Store Foot Traffic:** Real-time pulse of business activity.
* **Debt Mix Ratio:** Distinguishes healthy leverage from "toxic" short-term debt.
* **Managerial Revenue:** Actual cash flow observed versus official tax filings.
* **Reinvestment Index:** Tracks modernization as a proxy for long-term solvency.

## Performance Metrics
* **F1-Score:** 0.89
* **Precision (Class 1):** 90%
* **Business Impact:** Identified a significant percentage of "safe" clients rejected by standard models, representing potential additional revenue with controlled risk.

## Tech Stack
* Python (Pandas, NumPy)
* Scikit-Learn (Random Forest Classifier)
* Data Visualization (Matplotlib, Seaborn)
