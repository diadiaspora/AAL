# AAL Sales Analysis

## Project Overview

AAL, established in 2000, is a well-known clothing brand in Australia. The company has branches across various states, metropolises, and tier-1 and tier-2 cities, serving all age groups from kids to the elderly. Currently experiencing a surge in business, AAL is pursuing expansion opportunities and requires data-driven insights to inform investment and sales decisions.

This project focuses on analyzing **fourth-quarter sales data for AAL** to assist the head of Sales & Marketing (S&M) in identifying high-performing states and developing strategies for states with lower revenues.

---

## Problem Objective

- Identify states generating the **highest revenues**.
- Develop **sales programs** for states with lower revenues.
- Analyze sales data on a **state-by-state basis** to provide actionable insights.
- Perform **data wrangling, analysis, visualization, and report generation** to support decision-making.

---

## Dataset

The project uses the CSV file:

- `AusApparalSales4thQrt2020.csv` – contains sales data for the fourth quarter, including columns for sales, units, demographics (kids, women, men, seniors), and timestamps.

---

## Project Steps

### 1. Data Wrangling
- Ensure data is clean and free of missing or incorrect entries.
- Inspect data using `isna()` and `notna()`.
- Handle missing or incorrect data using suitable techniques (e.g., dropping nulls or filling values).
- Normalize data for analysis.
- Use `groupby()` for chunking or merging data as appropriate.

### 2. Data Analysis
- Perform descriptive statistics (mean, median, mode, standard deviation) on Sales and Units columns.
- Identify groups with highest and lowest sales.
- Generate **weekly, monthly, and quarterly reports**.
- Utilize libraries such as **NumPy**, **Pandas**, and **SciPy**.

### 3. Data Visualization
- Build a dashboard for S&M, including:
  - **State-wise sales analysis** for demographic groups (kids, women, men, seniors).
  - **Group-wise sales analysis** across states.
  - **Time-of-day analysis** to identify peak/off-peak sales periods.
- Ensure visualizations are **clear and actionable**.
- Include daily, weekly, monthly, and quarterly charts.
- Use **Seaborn** for statistical plots and distribution charts, and **box plots** for descriptive statistics.

### 4. Report Generation
- Use **JupyterLab Notebook** for integrating code, visualizations, and markdown explanations.
- Present results with **graphs, plots, and analysis**.
- Include **recommendations and rationale** for insights derived from analysis.

---

## Technologies Used

- **Python** – data analysis and visualization
- **Pandas & NumPy** – data manipulation and statistics
- **Seaborn & Matplotlib** – data visualization
- **SciPy** – statistical analysis
- **JupyterLab** – interactive report generation

---

## Project Structure

AAL_Sales_Analysis/
│
├── Data/
│ └── AusApparalSales4thQrt2020.csv
│
├── Notebooks/
│ └── aal_sales_analysis.ipynb
│
└── README.md

---

## How to Run

1. Clone the repository.
2. Open `aal_sales_analysis.ipynb` in **JupyterLab**.
3. Ensure the `Data/` folder contains `AusApparalSales4thQrt2020.csv`.
4. Execute cells sequentially to perform full analysis, visualization, and report generation.
