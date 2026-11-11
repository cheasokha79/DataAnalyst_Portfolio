# Retail Sales and Profitability Analysis

A Python and Power BI portfolio project examining sales and profitability across products, discounts, customers, regions, and time. The notebook combines data inspection with exploratory analysis, then translates the results into evidence-based findings and management follow-up questions.

## Business questions

- How did sales and profit vary across product categories?
- Which sub-categories generated the most profit or loss?
- How were discounts associated with profit?

The notebook also explores customer, regional, shipping, and monthly performance, including data quality checks and a documented reporting cutoff.

## Project contents

```text
Project1_Retail_Sales/
├── data/
│   ├── SampleSuperstore.csv
│   ├── sample_-_superstore.xls
│   └── cleaned_retail_sales_data.csv
├── notebooks/
│   ├── 01_Data_Inspection.ipynb
│   └── portfolio_charts.png
├── PowerBI/
│   └── retail_sales_dashboard.pbix
└── readme.md
```

## Notebook walkthrough

Open [`notebooks/01_Data_Inspection.ipynb`](notebooks/01_Data_Inspection.ipynb) to review the end-to-end work. It includes:

1. Dataset structure, completeness, duplicates, data types, and date validation
2. Sales and profit summaries by category and sub-category
3. Profitability patterns across discount levels, with product-level follow-up
4. Additional customer, segment, regional, monthly, and shipping analyses
5. Data validation, interpretation notes, and management recommendations

The discount analysis describes associations in the observed transactions. It does not establish that discounts alone caused a profit outcome. Similarly, performance comparisons should be interpreted alongside the reporting period and data limitations documented in the notebook.

## Run the notebook

1. Install Python and Jupyter Notebook or JupyterLab.
2. Install the core Python dependencies:

   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Launch Jupyter from the `Project1_Retail_Sales` directory.
4. Open `notebooks/01_Data_Inspection.ipynb` and run the cells from top to bottom.

The notebook loads `../data/SampleSuperstore.csv`, so keep the folder structure intact. Some cells save chart output to the notebook folder.

## Companion deliverables

- [`PowerBI/retail_sales_dashboard.pbix`](PowerBI/retail_sales_dashboard.pbix) — interactive dashboard for Power BI Desktop.
- [`Data Analyst_portfolio_Project_1.pptx`](Data%20Analyst_portfolio_Project_1.pptx) — project presentation.
- [`data/cleaned_retail_sales_data.csv`](data/cleaned_retail_sales_data.csv) — prepared dataset supplied with the project.
- [`notebooks/portfolio_charts.png`](notebooks/portfolio_charts.png) — exported chart image.

## Tools

Python · pandas · Matplotlib · Jupyter Notebook · Power BI Desktop

