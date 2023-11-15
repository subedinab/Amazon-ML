# Women's Clothing Reviews Dataset Analysis

## Project Overview

This project involves ingesting, transforming, and analyzing the Women's Clothing Reviews dataset using AWS data stack services. The main steps include:

1. **Ingest and Transform Dataset:**
   - List the dataset files in the public S3 bucket.
   - Copy the data locally to the notebook.
   - Load and preview the data using Pandas.
   - Transform the data to create a new CSV file with selected columns.

2. **Register Dataset for Querying and Visualization:**
   - Register the transformed dataset into an S3-backed database table for querying.
   - Use AWS Glue and Amazon Athena to register and query the dataset.

3. **Data Analysis with AWS Data Wrangler:**
   - Analyze the dataset using AWS Data Wrangler.
   - Plot visuals to extract insights from the dataset.

## Project Structure

The project is organized into the following sections:

1. **Ingest and Transform Dataset:**
   - **File:** `01_ingest_transform.ipynb`
   - **Description:** This notebook includes code to list, copy, and transform the dataset.

2. **Register Dataset for Querying and Visualization:**
   - **File:** `02_register_dataset.ipynb`
   - **Description:** This notebook demonstrates how to register the dataset in the AWS Glue Catalog.

3. **Data Analysis with AWS Data Wrangler:**
   - **File:** `03_data_analysis.ipynb`
   - **Description:** This notebook showcases data analysis using AWS Data Wrangler.

4. **Additional Files:**
   - `womens_clothing_ecommerce_reviews.csv`: Original dataset.
   - `womens_clothing_ecommerce_reviews_transformed.csv`: Transformed dataset.
   - `README.md`: Project documentation.

## Running the Notebooks

To run the notebooks, follow these steps:

1. Open `01_ingest_transform.ipynb` and execute the cells to ingest and transform the dataset.
2. Open `02_register_dataset.ipynb` and execute the cells to register the dataset in the AWS Glue Catalog.
3. Open `03_data_analysis.ipynb` and execute the cells for data analysis.

## Dependencies

Ensure you have the necessary dependencies installed, including the AWS CLI, Pandas, AWS Data Wrangler, and Boto3. You can install them using:

```bash
pip install pandas awswrangler boto3
