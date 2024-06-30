## This repository demonstrates an ELT (Extract, Load, Transform) workflow utilizing AWS S3 and Glue

### Project Goals:

- Data Ingestion: Populate an S3 bucket with raw data.
- ETL Job Creation: Develop an ETL job using AWS Glue to transform the raw data.
- Data Processing: Apply transformations within the ETL job to prepare the data for analysis.
- Data Loading: Load the processed data into a separate S3 bucket for further use.
-- Data Catalog Management: Utilize AWS Glue crawlers to automatically discover and populate the Data Catalog with schema information.
