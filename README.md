# RFM Analysis

## Overview
This repository contains scripts and notebooks for performing RFM analysis on customer transaction data. RFM analysis is a technique used in marketing and customer segmentation to categorize customers based on their transactional behavior.

## Dataset

The data used in this project is sourced from the **Online Retail II Data Set** available on Kaggle, provided by the ML Repository. This dataset contains transactional data from an online retail store over a period of approximately two years (from December 2009 to December 2011). It includes sales made to customers who are primarily wholesalers.

### Dataset Information:
- **Source**: [Online Retail II Data Set](https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository)
- **Provider**: ML Repository on Kaggle
- **Content**: The dataset consists of the following columns:
  - `InvoiceNo`: Invoice number (unique identifier for each transaction).
  - `StockCode`: Product code (unique identifier for each product).
  - `Description`: Product description.
  - `Quantity`: Quantity of each product per transaction.
  - `InvoiceDate`: Date and time of the transaction.
  - `UnitPrice`: Price per unit of the product.
  - `CustomerID`: Unique identifier for each customer.
  - `Country`: Country where the customer resides.

### Visualization:
This dataset is used for performing RFM (Recency, Frequency, Monetary) analysis and customer segmentation. The data has been preprocessed to handle missing values and outliers where applicable, and it is used to derive insights into customer purchasing behavior and patterns. The Tableau Visualization can be found here: [Tableau Visualization](https://public.tableau.com/app/profile/ashnair/viz/RFMAnalysis_17183097564710/RFMAnalysisDashboard?publish=yes)
