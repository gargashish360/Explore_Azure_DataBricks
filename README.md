# Explore_Delta_Lake.ipynb:
This notebook show the manipulation done on products dataset, using Azure Databricks and Delta Lake Capabilities.It first saves the raw data into delta live tables format and then do manipulations over. Delta lake has capabilties to perform ACID transactions and maintain logs for each transaction.

# Data_Processing_Pipeline.ipynb:
Contains the code to process the covid data and get its aggregated enriched form and saved in format of delta live tables. We can run this script as an ETL pipeline such as:
--> In Delta Live Tables tab within Azure Databricks workspace select Create Pipeline.
--> Fill the relevant metadata for pipeline and specify the location where the final table data in delta live table format will be stored.
--> Select Create and then Start.
