# Spark Unified Analytics
## End to End Data life cycle on Databricks and Apache Spark
### Lending Club data cleaning and exploratory data analysis

- In this project I explored the lending club with spark distribution on databricks
- Understood the data, performed data plumbing tasks to improve the quality of the data
- Exploratory data analysis of lending club to unwrap the patterns (via spark SQL, spark dataframes and visualization)

### Airbnb data analysis

- In this project, mounted data from s3 to distributed databricks environment
- Addressed few real world data reading issues (read format vs data format)
- Load the data as tables on cluster in parquet format (columnar data store to save data on distributed cluster)
- Repartition the data from worker nodes into a single file write back to S3
- Data analysis, data tranformation and data aggregation (Complex SQL Queries)
- Loading the aggregated data on the cluster (parquet tables) for downstream utility

### Churn Analysis - End to end machine learning

- Exploratory Data Analysis of IBM churn data.
- Built a data pipeline to handle categorical and numerical feature transformation
- Feature engineering 
- Used various classification models on the data (logistic regression did better)
- Running through the classification task evaluation metrics
- Hyperparameter tuning to address overfitting



