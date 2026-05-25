# Exploratory Data Analysis (EDA) on Sales Dataset

## Objective
This project performs exploratory data analysis on a sales dataset to understand numerical and categorical patterns, detect outliers, and analyze relationships between variables.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy

## Numerical Analysis
The following descriptive statistics were calculated:
- Mean
- Median
- Minimum and Maximum
- Quartiles (Q1, Q2, Q3)
- Standard Deviation
- Skewness
- Kurtosis

All values were rounded to two decimal places for clarity.

## Categorical Analysis
Frequency and relative frequency were calculated for:
- Product
- Payment Method
- Order Status
- Coupon Code
- Referral Source

## Outlier Detection
- 8 outliers were detected in the Total Price column
- Outliers were identified using statistical methods
- Corresponding Order IDs and Total Prices were recorded
- A histogram was created to visualize outliers

## Data Visualization
- Histograms for Total Price and Unit Price
- Multiple distribution plots
- Correlation heatmap for:
  - Quantity
  - Unit Price
  - Items in Cart
  - Total Price

## Key Insights
- Distribution patterns observed in price variables
- Strong/weak correlations between numerical variables
- Presence of outliers affecting total price distribution

## Project Structure

```text
data/      -> raw dataset
notebooks/ -> EDA analysis notebook
visuals/   -> plots and graphs
report/    -> final analysis report
```

## Author
Hamza Mahmoud Kamel
