# Data Engineering Project using SSIS

## Overview
This project demonstrates an end-to-end ETL pipeline built using SQL Server Integration Services (SSIS). It integrates multiple data sources, applies data transformations, and loads clean data into a structured format.

## Features
- Data Integration (XML, CSV, REST API)
- ETL Pipeline Development
- Data Cleaning & Transformation
- Slowly Changing Dimension (SCD Type 6)
- Incremental Load
- Data Versioning
- Data Aggregation

## Tasks

### Task 1: Data Integration
- Combined XML, CSV, and API data
- Standardized schema
- Cleaned missing and invalid values

### Task 2: SCD Type 6
- Implemented historical + current tracking
- Used incremental load
- Custom logic without built-in SCD component

### Task 3: Data Versioning
- Version tracking per run
- Active flag handling
- Multi-day logic

### Task 4: Trade Aggregation
- Processed trading data
- Applied business rules
- Generated trader summary metrics

## Tools & Technologies
- SSIS
- SQL Server
- Visual Studio

## Project Structure
- ssis-packages/: SSIS package files (.dtsx)
- sql/: SQL scripts
- data-samples/: sample input data
- screenshots/: pipeline visuals
