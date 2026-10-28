# Diwali Sales Analysis

## Project Overview

The Diwali Sales Analysis project explores customer purchasing data using Python. The objective is to identify purchasing patterns across demographic groups, occupations, geographical regions, and product categories.

The project applies exploratory data analysis (EDA), data cleaning, aggregation, and visualization techniques to extract useful business insights.

## Objectives

- Inspect and clean the dataset.
- Analyse customer records by gender, age group, and marital status.
- Explore purchasing patterns across occupations.
- Compare purchase amounts across states and geographical zones.
- Identify frequently appearing products and important product categories.
- Visualize results using charts and summary tables.
- Develop data-driven business recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
diwali-sales-analysis/
├── data/
│   └── Diwali Sales Data.csv
├── notebooks/
│   └── diwali_sales_analysis.ipynb
├── outputs/
│   └── charts/
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

### 1. Clone or download the project

Open the project folder in Visual Studio Code.

### 2. Create a virtual environment

Run the following command in the terminal:

```bash
python3 -m venv .venv
```

### 3. Activate the virtual environment

**macOS/Linux:**

```bash
source .venv/bin/activate
```

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/diwali_sales_analysis.ipynb` and execute the cells in order.

## Analysis Performed

1. Dataset loading and inspection.
2. Missing-value and duplicate-record checks.
3. Data cleaning.
4. Gender analysis.
5. Age-group analysis.
6. Marital status analysis.
7. Occupation analysis.
8. State-wise and zone-wise analysis.
9. Product ID analysis.
10. Product category analysis.
11. Summary tables and visualizations.
12. Business recommendations.

## Business Applications

The analysis can help explore customer segments, regional purchasing patterns, and product category trends.

These findings may support customer segmentation, regional marketing, and further investigation of product demand.

## Limitations

- Findings depend on the quality and completeness of the supplied dataset.
- A record count does not necessarily represent a count of unique customers or unique orders.
- Recorded purchase amount is not the same as profit.
- Observed patterns do not establish causation.
- Recommendations should be validated before business implementation.

## Author

Add your name here.

## Learning Outcomes

This project demonstrates practical skills in:

- Python data analysis
- Data cleaning
- Exploratory data analysis
- Data aggregation using Pandas
- Data visualization
- Business insight generation
- Project documentation