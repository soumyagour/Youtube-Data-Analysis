# Data Engineering YOUTUBE Analysis Project
# Overview:
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

# Project Goals:
1. Data Ingestion - Ingested data from multiple sources.
2. ETL system- transforming data into proper format from raw format.
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them.
4. Scailibility- as data size increases we need of make sure our system scales with it.
5. Cloud- We are using here AWS cloud service.
6. Reporting- Build a dashboard to get answers to the question we asked earlier.

# Services used:
1. AWS IAM- this is identity access management service which enables us to manage access to AWS services and resources securely.
2. Amazon S3- Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
3. AWS Glue- AWS Glue is a serverless data integration service that makes data preparation simpler, faster, and cheaper.
4. AWS Lambda- Lambda is a computing service that allows programmers to run code without creating or managing servers.
5. AWS Athena- Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL.
6. QuickSight- Amazon Quicksight is a business analytics service provided by AWS. It provides easy to use tools to build visualizations, perform ad-hoc analysis, get   business insights from the data and share the results with others.

# Dataset used:
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.
