# Student Score ETL Pipeline

This is a beginner-friendly Azure Data Engineering project that demonstrates:
- Ingesting CSV data with Azure Data Factory
- Storing in Azure Data Lake Gen2
- Cleaning and transforming using Azure Databricks (PySpark)
- Writing clean data back to Data Lake

## 🛠 Technologies Used
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks (PySpark)
- Microsoft SQL Server (optional)
- GitHub

## 🧪 Dataset
Sample student scores with missing values in a CSV file.

## 🧱 Pipeline Steps
1. Upload raw CSV to Azure Data Lake
2. Use ADF to move data from `raw/` to `staging/`
3. Databricks reads `staging/`, cleans nulls, adds average score
4. Save final file to `processed/`

## 📸 Screenshots
Add ADF pipeline diagram here if available.

## 🚀 Output
Processed CSV with added "Average" column.
