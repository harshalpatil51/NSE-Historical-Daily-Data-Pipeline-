# NSE-Historical-Daily-Data-Pipeline-


🧾 Overview
This project demonstrates a simple end-to-end data pipeline using historical daily OHLCV data from NSE. The pipeline includes:

Loading data from a CSV file
Storing it in a PostgreSQL database
Retrieving and analyzing data using Python


📦 Dataset
Format: Parquet
Rows: ~200,000+
Columns: symbol, date, open, high, low, close, volume

* Setup PostgreSQL

Create a PostgreSQL database (e.g., nse_data)
Run sql_schema.sql to create necessary tables
Update connection details in the notebooks

* Run the Notebooks

Notebook 1: Load and preprocess Parquet data, store in PostgreSQL
Notebook 2: Query data from PostgreSQL and analyze

🔁 Pipeline Test

Add new yearly data to PostgreSQL
Ensure queries and dashboards reflect updated data automatically

✅ Evaluation Criteria

Correct data loading and storage
Efficient SQL queries
Indexing for performance
Pipeline modularity and update handling
Code clarity and documentation