## This repository demonstrates an ELT (Extract, Load, Transform) workflow utilizing AWS S3 and Glue

### Project Goals:

- Data Ingestion: Populate an S3 bucket with raw data.
- ETL Job Creation: Develop an ETL job using AWS Glue to transform the raw data.
- Data Processing: Apply transformations within the ETL job to prepare the data for analysis.
- Data Loading: Load the processed data into a separate S3 bucket for further use.
- Data Catalog Management: Utilize AWS Glue crawlers to automatically discover and populate the Data Catalog with schema information.


## Setup on aws 
### Steps to Create an AWS S3 Bucket for Raw and Processed Data
- Here are the steps, with proper grammar, to create an AWS S3 bucket named data-pipeline-s3-glue that will store both raw and processed data:
1. Log in to your AWS Management Console.
Navigate to the S3 service. You can search for "S3" in the search bar or find it under the "Storage" category.
Click on the "Create bucket" button.
2. In the "Bucket name" field, enter "data-pipeline-s3-glue".
3. Choose a region closest to where you access the data most frequently.
4. (Optional) Configure additional settings for the bucket as needed. You can leave the defaults for most initial setups.
Click on the "Create" button.
- This will create an S3 bucket named data-pipeline-s3-glue within your AWS account.
- You can then use this bucket to store both your raw and processed data files.
