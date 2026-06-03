# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using a dataset of individual purchases. It is built around exploratory data analysis and insight generation from purchase, demographic, and promotional data.

## Repository Structure
- `data/`
  - `customer_shopping_behavior.csv`: The main dataset containing transaction and customer metadata.
- `notebook/`
  - `EDA.ipynb`: Jupyter notebook for exploratory data analysis and visualizations.
- `sql/`
  - `customer_queries.sql`: SQL queries for extracting customer behavior insights.
- `power bi/`
    - customer_behaviour_dashboard.pbix  
      Main Power BI dashboard file.
  - `screenshots/`: Visual artifacts and dashboard screenshots created for reporting.
- `requirements.txt`: Python dependencies used to run the notebook and analysis.

## Dataset Summary
The dataset includes the following key fields:
- `Customer ID`, `Age`, `Gender`
- `Item Purchased`, `Category`, `Purchase Amount (USD)`
- `Location`, `Size`, `Color`, `Season`
- `Review Rating`, `Subscription Status`, `Shipping Type`
- `Discount Applied`, `Promo Code Used`, `Previous Purchases`
- `Payment Method`, `Frequency of Purchases`

### What this dataset enables
- analysis of purchase behavior by age, gender, category, and geography
- understanding the impact of discounts, promo codes, and subscription status
- evaluating customer satisfaction through review ratings
- identifying seasonal and purchase frequency patterns

## Setup Instructions
1. Create a Python virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/Scripts/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `notebook/EDA.ipynb` to explore the data and run the analysis.

## Recommended Analysis Flow
1. Inspect the dataset in the notebook.
2. Clean or transform the data as needed.
3. Visualize spending trends by customer segments.
4. Evaluate promotional effectiveness and shipping patterns.
5. Use SQL queries in `sql/customer_queries.sql` for additional filtering or joins when working with a database.

## Notes
- The notebook is the main analysis asset for generating charts, tables, and observations.
- `requirements.txt` contains the packages needed for pandas, Jupyter, and plotting libraries.

## Contact
For questions or updates, review the notebook comments or the SQL query file for implementation details.
