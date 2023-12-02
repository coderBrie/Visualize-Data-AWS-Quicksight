# Amazon Best Seller Data Visualization Mini Project

## Overview

This mini project involves visualizing data using Amazon QuickSight. The dataset used is the Amazon Best Seller dataset, which includes 1000 rows of real-life sample data. The dataset consists of a CSV file and a `manifest.json` file, which is used by QuickSight to access data from an S3 bucket.

## Steps

### 1. Setting up S3 Bucket

- Logged into AWS console and created an S3 bucket named `fawad-aws-miniproject`. <img src="Images/Create S3 Bucket.png" alt="S3 Bucket"> <br><br>
- Uploaded the CSV file and `manifest.json` file to the S3 bucket. <br> <br> <img src="Images/Upload in bucket.png" alt="S3 Bucket"> <br> <img src="Images/Upload csv file.png" alt="Upload csv"> <br> <img src="Images/upload manifest.png" alt="upload manifest"> 
- Ensured that the bucket name in the JSON file matches the created S3 bucket.
- Copied the S3 URL for future use in QuickSight. <br> <br> <img src="Images/Copy mainfest.png" alt="Copy mainfest">

### 2. QuickSight Setup

- Signed up for Amazon QuickSight with a free trial.
- Provided account name, email ID, and selected the S3 bucket (`fawad-aws-miniproject`) during the QuickSight setup. <br> <br> <img src="Images/Create Quicksight.png" alt="Create Quicksight"> <img src="Images/select bucket.png" alt="select bucket">
- Created a new dataset in QuickSight by navigating to Datasets -> New Dataset -> S3. <br> <br> <img src="Images/New Dataset.png" alt="New Dataset"> 
- Entered the data source name and pasted the copied URL of the `manifest.json` file.
- Connected to the dataset and clicked "Visualize."   <br> <br> <img src="Images/connect to datasource.png" alt="connect to datasource"> 

### 3. Visualization in QuickSight

- Selected the interactive sheet and created the visualization.
- Renamed the sheet to "Most Popular Brand." <br> <br> <img src="Images/Autogragh UI.png" alt="Autogragh UI"> 
- Dragged the field "brand" into the autograph. <br> <br> <img src="Images/Drag brands.png" alt="Drag brands">
- Sorted the data in descending order to visualize the most popular brands first. 
- Applied the changes to generate the graph.  <br> <br> <img src="Images/sort brands.png" alt="sort brands">

## Conclusion

The QuickSight interface now visualizes the graph, showcasing the popularity of Amazon brands from most popular to least popular.
<img src="Images/Most popular brand Output.png" alt="Most popular brand Output">

### Project Completion

The project is completed with the visualization of Amazon's most popular brands. The relevant code for connecting the dataset and generating the visualization in QuickSight is provided.

