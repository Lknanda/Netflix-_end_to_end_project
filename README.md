# NETFLIX SHOWS AND MOVIES DATASET_EDA
The dataset consists of meta details about the movies and tv shows such as the title, director, and cast of the shows / movies. Details such as the release year, the rating, duration etc. As the first step, let's load the dataset, create some new features. In this kernel, I have analysed this dataset to find top insights and findings
Project Overview

This project demonstrates an end-to-end ELT (Extract, Load, Transform) workflow using a Netflix dataset.
The goal is to extract raw data, load it into a SQL database, transform it for analysis, and finally generate insights using Python.

# Dataset
The dataset contains information about Netflix titles, including:
Title|
Type (Movie/TV Show)|
Release year|
Date added|
Country|
Genre / Listed in|
Rating|
Duration|
Uploaded dataset: netflix_data.csv

# ELT Workflow 
Extract |
Pulled raw Netflix data from CSV |
Validated file format, column types, and missing values

# Load
Loaded the dataset into a relational SQL database (MySQL / PostgreSQL / SQLite).
Created staging tables for raw data.
Performed schema definition and constraints.



# Transformation completed using SQL + Python:

# 1.SQL Transformations
Cleaned null values and standardized date formats
Removed duplicates and invalid records
Split/normalized genre information
Extracted year, month, country and content attributes
Created analytics-friendly tables

# 2. Python Transformations
Used pandas for additional cleaning
Conducted EDA on content trends, genre distribution, and release patterns
Visualized insights using matplotlib / seaborn

# Key Insights
Distribution of movies vs TV shows
Most frequent genres
Content release trends across years
Country-wise production patterns
Rating categories and content duration trends

# Tech Stack
Python (pandas, matplotlib, seaborn) |
SQL (MySQL / PostgreSQL / SQLite) |
Jupyter Notebook

# CSV Data Source
📂 Project Structure
📦 Netflix-ELT-Project
│
├── netflix_data.csv
├── extract_load.sql
├── transform_queries.sql
├── analysis.ipynb
└── README.md
