# COVID-19-ETL
A Python ETL pipeline that fetches, cleans, and stores Italy's COVID-19 confirmed cases data into a SQLite database for easy analysis.

This project is a simple Python ETL (Extract, Transform, Load) pipeline that fetches COVID-19 confirmed case data for Italy from a public API, cleans and transforms the data, then stores it into a local SQLite database.

## Features
- Fetches daily COVID-19 case data via REST API
- Cleans and normalizes data using pandas
- Stores data into SQLite database for easy querying
- Prints summary of recent confirmed cases

## Requirements
- Python 3.7+
- Packages: `requests`, `pandas`

## Installation
```bash
pip install requests pandas
