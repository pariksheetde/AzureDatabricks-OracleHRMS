Data Engineering Oracle HRMS by Pariksheet De
Overview
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured Oracle Human Resource data

Project Goals
Data Ingestion — Build a mechanism to ingest data from ADLS
ETL System — We are getting data in raw format, transforming this data into the proper format
Data lake — We will be getting data from multiple sources so we need centralized repo to store them
Scalability — As the size of our data increases, we need to make sure our system scales with it
Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use Azure Databricks

Services we will be using
Amazon S3: Azure ADLS is an object storage service that provides manufacturing scalability, data availability, security, and performance.
Storage IAM: This is nothing but identity and access management which enables us to manage access to Azure Databricks services and resources securely.
Azure Databricks: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
Unity Catalog: 
Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

Architecture Diagram


