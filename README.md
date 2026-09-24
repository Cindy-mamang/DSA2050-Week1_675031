#  Retail Data Analysis & Business Intelligence Project

> A comprehensive data-driven exploration of retail transactions, designed to uncover key performance indicators, regional market trends, and product category dynamics.

---

##  Project Overview
Welcome to the **Retail Performance Analysis** repository! This project dives deep into a rich dataset of **300 retail transactions** to extract actionable insights[cite: 1]. By analyzing revenue streams across multiple product categories and geographical regions, this project provides a clear framework for data-backed business decision-making.

---

##  Key Performance Indicators (KPIs)
At a glance, the portfolio's core transaction metrics highlight strong market activity:
* **Total Revenue:** KES 3,206,450 — *The cumulative financial value of all recorded orders[cite: 1].*
* **Total Transactions:** 300 orders processed (`OrderID`)[cite: 1].
* **Average Transaction Value:** KES 10,688.17 — *The average customer spend per transaction[cite: 1].*

---

##  Performance Breakdown

###  Revenue by Product Category
| Category | Revenue (KES) | Performance Insight |
| :--- | :--- | :--- |
| **Electronics** | 934,500[cite: 1] | Top-performing revenue driver[cite: 1] |
| **Personal Care** | 931,800[cite: 1] | A close second in total sales[cite: 1] |
| **Home & Office** | 917,900[cite: 1] | Strong, steady mid-to-high tier contributor |
| **Accessories** | 422,250[cite: 1] | Developing category with growth potential[cite: 1] |

###  Regional Distribution
The market footprint demonstrates a healthy, balanced nationwide spread:
* **Kisumu:** KES 878,050[cite: 1]
* **Mombasa:** KES 793,400[cite: 1]
* **Nakuru:** KES 777,050[cite: 1]
* **Nairobi:** KES 757,950[cite: 1]

---

##  Project Structure
```text
├── data/
│   └── retail_dataset.csv     # Raw transaction records
├── scripts/
│   └── analysis_script.R      # Data processing and KPI generation
└── README.md                  # Project documentation
🛠️ Prerequisites
Before running the analysis scripts, ensure your environment meets the following requirements:

Software: R (version 4.0 or higher) or Python (version 3.8 or higher).

Libraries:

For R: tidyverse, dplyr, ggplot2

For Python: pandas, numpy, matplotlib

Data File: Ensure retail_dataset.csv is correctly placed inside the data/ directory.

 Usage Guidelines
Clone or Download the repository to your local machine.

Open your preferred data analysis workspace (RStudio or Jupyter Notebook).

Load the Dataset by setting your working directory and reading the CSV file:

R Example: retail_data <- read.csv("data/retail_dataset.csv")

Python Example: df = pd.read_csv("data/retail_dataset.csv")

Execute the Scripts sequentially to compute KPIs, aggregate totals by region and category, and reproduce the analytical reports