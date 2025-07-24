# -Bitcoin-vs-Solana-Transaction-Trend-Visualization-2024-2025-

## Table of Content

 - [🧾 Procject Summary](#🧾Project-summary)
 - [🗃️ Data Source](#🗃️Data-source)
 - [🛠️Tools Used](#🛠️Tools-used)
 - [Import Data](#Import-Data)
 - [⚙️Steps](#⚙️Steps)
 - [Import Data](#Import-Data)
 - [Transform Data](#Transform-Data)
 - [Create Line Chart](Create-Line-Chart)
 - [📊 Result](#📊 Result)

### 🧾 Project Summary

This project visualizes and compares the daily transaction counts of two major blockchains—Bitcoin and Solana—from 2024 to 2025. The goal is to analyze trends in transaction activity over time using a line chart built in Power BI.

### 🗃️ Data Source

The dataset includes:
Date (daily granularity)
Bitcoin transaction counts
Solana transaction counts
Aggregated metrics:
Average Bitcoin transactions: 474.56K
Total Bitcoin transactions: 173M
Average Solana transactions: 336.36M
Total Solana transactions: 123B

### 🛠️ Tools Used

Power BI Desktop

Data processing with built-in Power BI tools

### ⚙️ Steps 

### Import Data

Load the dataset into Power BI (Excel, CSV, or database).

Ensure the date column is correctly typed as Date.

### Transform Data

Check and clean the data for missing values or inconsistencies.

Handling missing values

Aggregate the transaction counts by day, week, or month if necessary using Power BI’s "Group By" feature.

### Create Line Chart

Insert a Line and Clustered Column Chart or a Line Chart.

set:

X-axis: Date
Y-axis (Values):
Sum of Bitcoin Transaction Count
Sum of Solana Transaction Count
Legend: Blockchain names to distinguish the lines



4. Customize Chart

Apply custom colors for Bitcoin and Solana.

Format y-axis values in K (thousands) or bn (billions) for readability.
Add tooltips to show:

Total and average transaction counts

### 📊 Result

The final line chart displays a time-series comparison of the two blockchains, showing how transaction volume has evolved over time. It allows visual insights into:

Relative usage of Bitcoin vs Solana

Transaction trends and peaks

Differences in scale and performance
