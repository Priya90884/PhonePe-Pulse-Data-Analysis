# PhonePe Pulse Data Analysis | Python

**Exploring India's Digital Payment Trends (2018–2021) Using Python and Pandas**

## 📌 Project Overview

This project analyzes the PhonePe Pulse dataset to explore digital payment trends across Indian states and districts from 2018 to 2021.

The objective was to understand transaction behavior, regional payment patterns, average transaction value (ATV), mobile device adoption, and app engagement through data analysis and visualization.

Using Python and Pandas, I explored multiple datasets, validated data quality, compared regional transaction totals, and identified patterns that help explain the growth and distribution of digital payments across India.

## 🎯 Project Objectives

- Analyze digital payment trends across states and districts.
- Compare transaction volumes and values across regions and years.
- Calculate Average Transaction Value (ATV) to understand regional differences in transaction behavior.
- Examine mobile device brand adoption across states.
- Explore app usage trends through quarterly app-open data.
- Validate data consistency before drawing business conclusions.
- Communicate findings through clear and meaningful visualizations.

## 🛠️ Tools and Technologies

- **Python** — data analysis and processing
- **Pandas** — data loading, data manipulation, aggregation, and validation
- **Excel** — source data format
- **Matplotlib / Seaborn** — include if these libraries were used for your visualizations
- **Jupyter Notebook** — include if this was your actual development environment

## 📂 Dataset Description

The project uses multiple sheets containing PhonePe Pulse data:

| Dataset | Purpose |
|---|---|
| State-level transactions | Analyze transaction trends by state and year |
| District-level transactions | Compare transaction activity across districts |
| Transaction type | Examine transaction categories |
| Device brand data | Explore registered device and brand adoption |
| District population | Support regional and demographic comparisons |
| App-open data | Analyze app usage trends over time |

**Period covered:** 2018–2021

## 🔄 Project Workflow

### 1. Data Loading and Exploration

- Loaded the multi-sheet Excel dataset using Pandas.
- Examined each dataset separately to understand its structure and columns.
- Reviewed data types, missing values, and the available geographic and time dimensions.

### 2. Data Quality Validation

- Checked columns across datasets for missing values.
- Observed that missing values were below 0.3% in the reported checks.
- Aggregated district-level transactions and compared them with state-level totals.
- Confirmed that the totals matched for the comparisons performed.

These checks helped establish confidence in the consistency of the data before analysis.

### 3. Transaction Trend Analysis

- Grouped transaction data by state and year.
- Compared regional transaction activity to identify higher- and lower-volume regions.
- Examined transaction volume and value patterns over the study period.

### 4. Average Transaction Value (ATV)

Calculated Average Transaction Value to compare the average value of transactions across states.

**Formula:**

`ATV = Total Transaction Value / Total Number of Transactions`

The analysis identified Ladakh and the Andaman & Nicobar Islands among the regions with high average transaction values in the comparisons performed.

This illustrates why transaction volume and average transaction value should be analyzed separately: regions with fewer transactions can still have higher average transaction values.

### 5. Device Adoption Analysis

- Examined registered phone brands across states.
- Identified the most commonly registered phone brand in each state.
- Used bar-chart visualizations to compare device adoption patterns.

### 6. App Usage Analysis

- Examined app-open activity over time.
- Compared quarterly usage patterns for selected states.
- Used line-chart visualizations to identify changes in app engagement.

## 📊 Key Findings

- **Data consistency:** District-level transaction totals matched the corresponding state-level totals in the validation performed.
- **Low missingness:** Missing values were below 0.3% in the reported data quality checks.
- **Regional variation:** Transaction activity differed across states and districts.
- **ATV differences:** Ladakh and the Andaman & Nicobar Islands showed high average transaction values in the analysis.
- **Device adoption:** Phone brand registration patterns varied across states.
- **App engagement:** Quarterly app-open trends provided an additional perspective on digital payment app usage beyond transaction counts.

*Note: Findings are based on the analyzed dataset and comparisons performed; they should not be interpreted as proof of causation.*

## 💡 Skills Demonstrated

- Multi-sheet Excel data handling
- Exploratory Data Analysis (EDA)
- Data quality assessment and validation
- Missing-value analysis
- Data aggregation using Pandas
- Grouping and regional comparisons
- KPI calculation and interpretation
- Trend analysis
- Data visualization
- Analytical storytelling

## 📁 Repository Structure

```text
PhonePe-Pulse-Data-Analysis/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── PhonePe_Pulse_Analysis.ipynb
│
├── images/
│   └── dashboard-preview.png
│
└── README.md
```

*This is a suggested structure. Update the filenames and folders to match the files actually present in your repository. Do not upload restricted or unnecessarily large raw datasets.*

## 🚀 How to Explore the Project

1. Open the Jupyter Notebook in the `notebooks` folder.
2. Review the data-loading and exploration steps.
3. Follow the data quality checks and aggregation logic.
4. Explore the transaction, ATV, device adoption, and app usage analyses.
5. Review the visualizations and findings.

If you run the notebook locally, install the required libraries and update the dataset paths to match your local folder structure.

Example:

```bash
pip install pandas openpyxl matplotlib seaborn jupyter
```

Only install the visualization libraries required by your actual notebook.

## 📷 Project Preview

Add screenshots of your actual analysis and visualizations to the `images` folder, then display them here.

Example Markdown:

```markdown
![PhonePe Transaction Analysis](images/dashboard-preview.png)
```

Replace the example filename with the actual image filename in your repository.

## 📌 Conclusion

This project demonstrates how Python and Pandas can be used to explore large, multi-dimensional digital payment datasets, validate data consistency, compare regional trends, and communicate findings through visual analysis.

It strengthened my practical understanding of data cleaning, aggregation, KPI calculation, trend analysis, and evidence-based interpretation—skills relevant to an entry-level Data Analyst role.

---

**Project Focus:** Digital Payments | Exploratory Data Analysis | Regional Trends | Data Quality

**Author:** Priya Kumari
