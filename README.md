# Telecom Customers Data Warehouse (Sample)

This repository contains a **Databricks PySpark project** that demonstrates:
- Downloading and importing data from **Kaggle** into Databricks
- Cleaning file names and column names
- Managing table naming conventions using a configurable `DataProductConfig` class
- Writing data to Unity Catalog tables in predefined schemas (`data_sources`, `data_products`, `analytics_products`)

## Dataset

I used the sample dataset **World Telecom Subscriptions** from Kaggle:  
[https://www.kaggle.com/datasets/taniaj/world-telecommunications-data  ](https://www.kaggle.com/datasets/taniaj/world-telecommunications-data)

This dataset contains subscription statistics for various telecom services across countries and years.
