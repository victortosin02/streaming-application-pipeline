# Data Engineering Streamfix Application Analysis Project by Victor Oladejo

## Overview

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured videos from Streamfix real time data.

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — I will be getting data in raw format, transforming this data into the proper format
3. Data lake — I will be getting data from multiple sources so I need centralized repo to store them
4. Scalability — As the size of our data increases, I need to make sure the system scales with it
5. Cloud — I can’t process vast amounts of data on my local computer so I need to use the cloud, in this case, I will use AWS
6. Reporting — Build a dashboard to get analytics of data

## Services we will be using
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.


https://www.kaggle.com/datasets/datasnaek/crackle

## Architecture Diagram
<img src="architecture.jpeg">
