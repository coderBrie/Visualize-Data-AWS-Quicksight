# Amazon Best Seller Data Visualization Mini Project

## Overview

This mini project involves visualizing data using Amazon QuickSight. The dataset used is the Amazon Best Seller dataset, which includes 1000 rows of real-life sample data. The dataset consists of a CSV file and a `manifest.json` file, which is used by QuickSight to access data from an S3 bucket.

## Steps

### 1. Setting up S3 Bucket

- Logged into AWS console and created an S3 bucket named `fawad-aws-miniproject`.
- Uploaded the CSV file and `manifest.json` file to the S3 bucket.
- Ensured that the bucket name in the JSON file matches the created S3 bucket.
- Copied the S3 URL for future use in QuickSight.

### 2. QuickSight Setup

- Signed up for Amazon QuickSight with a free trial.
- Provided account name, email ID, and selected the S3 bucket (`fawad-aws-miniproject`) during the QuickSight setup.
- Created a new dataset in QuickSight by navigating to Datasets -> New Dataset -> S3.
- Entered the data source name and pasted the copied URL of the `manifest.json` file.
- Connected to the dataset and clicked "Visualize."

### 3. Visualization in QuickSight

- Selected the interactive sheet and created the visualization.
- Renamed the sheet to "Most Popular Brand."
- Dragged the field "brand" into the autograph.
- Sorted the data in descending order to visualize the most popular brands first.
- Applied the changes to generate the graph.

## Conclusion

The QuickSight interface now visualizes the graph, showcasing the popularity of Amazon brands from most popular to least popular.

### Project Completion

The project is completed with the visualization of Amazon's most popular brands. The relevant code for connecting the dataset and generating the visualization in QuickSight is provided below.

