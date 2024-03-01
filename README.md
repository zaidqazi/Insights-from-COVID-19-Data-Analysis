# SQL Data Exploration README

## Overview

This repository contains SQL code for exploring COVID-19 data and cleaning Nashville Housing data. The SQL queries demonstrate various techniques including joins, common table expressions (CTEs), temporary tables, window functions, aggregate functions, creating views, and converting data types.

## COVID-19 Data Exploration

### Initial Data Exploration

- **Description**: Retrieves COVID-19 data from the `CovidDeaths` table and filters out records where continent information is available.
  
### Total Cases vs Total Deaths

- **Description**: Calculates the percentage of deaths relative to total cases for locations containing "states" in their name.

### Total Cases vs Population

- **Description**: Calculates the percentage of population infected with COVID-19 for each location.

### Countries with Highest Infection Rate

- **Description**: Identifies countries with the highest infection rates relative to their population.

### Countries with Highest Death Count per Population

- **Description**: Identifies countries with the highest death counts per population.

### Continent-wise Analysis

- **Description**: Analyzes continents with the highest death counts per population.

### Global Numbers

- **Description**: Provides global statistics on total cases, total deaths, and death percentage.

### Vaccination Analysis

- **Description**: Calculates the percentage of population vaccinated against COVID-19.

### Views

- **Description**: Creates a view to store data for later visualizations.

## Nashville Housing Data Cleaning

### Standardize Date Format

- **Description**: Standardizes the date format in the Nashville Housing dataset.

### Populate Property Address Data

- **Description**: Populates missing property addresses by joining the dataset with itself based on ParcelID.

### Split Address into Individual Columns

- **Description**: Splits the address into separate columns for Address, City, and State.

### Change Yes/No to Y/N in "Sold as Vacant" Field

- **Description**: Converts Y/N values in the "Sold as Vacant" field to Yes/No.

### Remove Duplicates

- **Description**: Removes duplicate records from the Nashville Housing dataset.

### Delete Unused Columns

- **Description**: Deletes unused columns from the Nashville Housing dataset.

## Note
- Some queries may involve specific database schema and might need modification to work with different datasets.
