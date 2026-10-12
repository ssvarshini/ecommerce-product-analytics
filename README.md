# E-commerce Product Analytics & Conversion Analysis

## Overview

This project analyses approximately **42.45 million e-commerce events** from October 2019 to explore customer behaviour, product performance, and purchasing patterns. Using Python, SQL, statistical analysis, and Tableau, the project turns raw event data into insights to support data-driven business decisions.

## Objectives

* Analyse customer engagement and purchasing behaviour.
* Compare product category, brand, and price-band performance.
* Investigate relationships between product prices and customer activity.
* Identify potential gaps between product views, cart additions, and purchases.
* Communicate findings through visualisations and a Tableau dashboard.

## Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **SQL:** SQLite
* **Visualisation:** Tableau
* **Analysis:** Exploratory data analysis and statistical testing

## Dataset

Source: [eCommerce Behavior Data from Multi-Category Store — Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)

The dataset contains product views, cart additions, purchases, timestamps, product details, and customer activity. The raw dataset is not included in this repository due to its large file size.

## Workflow

1. **Data Cleaning:** Inspected data quality, handled selected missing values, and engineered analytical features.
2. **Exploratory Analysis:** Examined event distributions, customer activity, and time-based patterns.
3. **Product Analysis:** Compared category, brand, and price-band performance.
4. **Statistical Analysis:** Investigated price differences across event types and associations between prices and product activity.
5. **SQL & Tableau:** Queried product performance and developed visual reports to communicate findings.

## Key Findings

* Product views accounted for the largest share of recorded events.
* Customer activity patterns varied across times and event types.
* Customer segmentation revealed different levels of browsing, cart, and purchase activity.
* Price and product performance analyses revealed associations worth further investigation.

## Limitations

The analysis covers October 2019 only. Duplicate records were retained, and the SQL analysis uses the first one million rows rather than the full dataset. Findings are exploratory and do not establish causation.
