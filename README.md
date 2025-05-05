# Chocolate Sales Performance Dashboard

## Overview

This project analyzes chocolate sales data from January to August 2022 to uncover trends in product performance, regional sales, and customer behavior. The workflow combines **Python (Pandas)** for data preprocessing and analysis, and **Tableau** for interactive dashboard visualization.

---

## Tools & Technologies

- **Python (Jupyter Notebook)** – data cleaning, transformation, and analysis
- **Pandas** – tabular data manipulation and feature engineering
- **Tableau** – dashboard design and interactive visual exploration
- **Jupyter Notebook** – end-to-end data pipeline and insight documentation

---

## Data Preprocessing

Using a Jupyter Notebook, the dataset was:

- Cleaned and formatted (e.g., removing currency symbols, standardizing column names)
- Converted from text-based dates to proper `datetime` objects
- Enhanced with derived features like `year`, `month`, and `total_sales`
- Exported to a clean `.csv` file for Tableau use

---

## Python Analysis Highlights

- **Monthly sales trends** to identify seasonality
- **Top products** by total revenue
- **Salesperson performance** breakdown
- **Sales by country**

## Key Insights

**1. Top-Selling Product**

- _Smooth Sliky Salty_ generated the highest revenue at **$349,692**, followed by _50% Dark Bites_ and _White Choc_.

**2. Monthly Sales Peaks**

- Sales peaked in _January_ at **$896,105**, followed by _June ($865,144)_ and _July ($803,425)_.
- Indicates strong early-year demand, possibly post-holiday promotions.

**3. Top Regions by Revenue**

- _Australia_ led with **$1.14M**, followed by _UK ($1.05M)_ and _India ($1.05M)_.
- Reflects strong APAC and Commonwealth performance.

**4. Best Performing Salesperson**

- _Ches Bonnell_ was the top performer with **$320,901** in total sales.
- Useful for incentive or recognition programs.

**5. Average Revenue per Box**

- Each box sold generated an average of **$105.72**.
- Useful for pricing and bundling strategy evaluation.

---

## Tableau Dashboard

The final dashboard includes:

- A time-series line chart for monthly sales
- Bar charts showing top-selling products and top-performing regions
- A leaderboard for salesperson contributions
- An interactive filter for country, product, and salesperson

**[View the Dashboard](https://public.tableau.com/app/profile/ein.cagle/viz/GlobalChocolateSalesDashboard_17443257086610/GlobalChocolateSalesDashboard)**

---

## Files Included

- `Chocolate_Sales_Analysis_Fixed.ipynb` – Python notebook with analysis
- `cleaned_chocolate_sales.csv` – Export-ready file for Tableau
- `Chocolate Sales.csv` – Raw input dataset

---

## Key Takeaways

This project demonstrates how to transform raw sales data into actionable insights using Python and Tableau. It emphasizes clean design, clear storytelling, and a focus on business relevance.
