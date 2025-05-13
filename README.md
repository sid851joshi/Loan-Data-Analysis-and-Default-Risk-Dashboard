# Loan Data Analysis Dashboard

This project presents an interactive Power BI dashboard focused on analyzing loan data to uncover insights about borrower behavior, loan performance, and default risk across various demographics.

## 📊 Project Overview

The goal of this project is to help financial institutions understand patterns in loan issuance and default using visual analytics. The dashboard includes dynamic visuals segmented by employment type, age group, education level, credit score, and marital status.

Key insights include:
- Loan amounts by loan purpose (Home, Auto, Business, etc.)
- Default rates by employment type and year
- Average loan by age group and credit score
- Number of loans by education level
- YOY (Year-over-Year) changes in loan disbursement and defaults

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **Power BI Dataflow** (for cloud-based ETL and dataset reuse)
- **Microsoft SQL Server** (as the primary data source)

## 💡 Why Use Power BI Dataflow?

Power BI Dataflow provides several benefits:
- **Centralized ETL logic**: Reuse data prep steps across multiple reports.
- **Scalability**: Better performance and incremental refresh options.
- **Automation**: Schedule refreshes for up-to-date insights.
- **Governance & Reusability**: Share consistent datasets across dashboards.

## 🔌 Data Source

The underlying dataset is stored in **Microsoft SQL Server** and imported into Power BI using **DirectQuery and Dataflows** for efficient access and transformation.
But I provided the excel sheet of dataset so You can simply use it by loading that excel file into your power bi.

## 📈 Use Cases

- Risk assessment and monitoring
- Strategic loan product planning
- Customer segmentation
- Credit policy analysis

