# 📊 SunCoast Retail Visual Analysis

## 📌 Overview

This project is a **data visualization and exploratory analysis** of the retail company, *SunCoast Retail*. It demonstrates how to use **Matplotlib** and Python to transform raw data into meaningful visual insights.

The program generates realistic datasets for **sales performance and customer behavior**, then visualizes trends, relationships, and distributions to support business decision-making.

---

## Features

### Data Simulation

* Generates **quarterly sales data (2022–2023)** across:

  * Multiple locations (Tampa, Miami, Orlando, Jacksonville)
  * Product categories (Electronics, Clothing, etc.)
* Simulates **customer demographics and purchase behavior**
* Incorporates:

  * Seasonal trends (Q4 spikes, Q1 dips)
  * Location and category performance differences
  * Advertising spend and growth trends

---

### Visual Analytics

#### Time Series Analysis

* Quarterly sales trends over time
* Sales comparisons across locations

#### Categorical Analysis

* Product category performance by location
* Sales composition (stacked bar charts)

#### Relationship Analysis

* Advertising spend vs. sales (scatter plot + trendline)
* Advertising efficiency over time

#### Distribution Analysis

* Customer age distribution (histograms)
* Purchase behavior by age group (box plots)

#### Sales Distribution

* Purchase amount distribution
* Sales breakdown by pricing tiers (pie chart)

#### Market Share Analysis

* Sales share by category
* Sales distribution by location

#### Dashboard

* Combined multi-plot dashboard summarizing key insights

---

## Key Concepts Demonstrated

* Data visualization with **Matplotlib**
* Time series analysis
* Comparative and categorical plotting
* Distribution and statistical visualization
* Business storytelling through data

---

## Technologies Used

* **Python**
* **Pandas** – Data handling
* **NumPy** – Data simulation
* **Matplotlib** – Visualization

---

## How to Run

1. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib
   ```

2. Run the script:

   ```bash
   python main.py
   ```

3. Output:

   * Multiple charts and visualizations displayed via matplotlib
   * Console will print key business insights

---

## Example Insights

* Sales show **consistent growth** with strong **Q4 seasonal spikes**
* **Miami** is the top-performing location; **Jacksonville** underperforms
* **Electronics** dominate as the highest revenue-generating category
* Advertising has a **positive but diminishing return** on sales
* Customer preferences vary significantly by **age group**
* Most purchases fall in the **mid-range tier**, with premium yielding higher value per sale

---

## Business Recommendations

* Invest more in **high-performing categories** like Electronics
* Optimize **advertising spend** to avoid diminishing returns
* Use **targeted marketing** based on customer demographics
* Develop strategies to improve **underperforming locations**

---

## Project Structure

```id="structure-001"
├── main.py        # Main visualization script
├── README.md      # Project documentation
```

---

## Notes

* All data is **synthetically generated** for learning purposes
* Random seed ensures **reproducibility**
* Designed for **educational use in data visualization and analytics**

---

## Purpose

This project highlights how visualization can:

* Reveal hidden patterns in data
* Communicate insights clearly
* Support data-driven business decisions

---
---
