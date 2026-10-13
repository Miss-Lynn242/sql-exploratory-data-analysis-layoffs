# SQL Exploratory Data Analysis — Layoffs Dataset

## Project Overview

This guided project was completed as part of Alex The Analyst's Data Analyst Bootcamp. It focused on exploring a layoffs dataset using SQL and MySQL to examine patterns and trends across companies, industries, countries, years, months, and company stages.

## Tools Used

- SQL
- MySQL
- MySQL Workbench

## Analysis Performed

### 1. Company Layoffs

Used aggregate functions to examine the maximum number and percentage of employees laid off, as well as total layoffs by company. Examples from the analysis included 18,150 layoffs at Amazon and 12,000 at Google.

### 2. Layoff Date Range

Used `MIN()` and `MAX()` to examine the date range covered by the dataset, from 2020 to 2023.

### 3. Layoffs by Industry

Used `SUM()` to compare total layoffs across industries and identify the industries with the highest and lowest totals in the dataset.

### 4. Layoffs by Country

Compared total layoffs across countries using aggregate functions, identifying the countries with the highest and lowest totals in the dataset.

### 5. Layoffs by Year

Grouped layoffs by year and compared annual totals to identify the years with the highest and lowest numbers of layoffs in the dataset.

### 6. Layoffs by Company Stage

Compared total layoffs across company stages.

### 7. Rolling Layoff Totals by Month

Used a CTE and window functions with `ORDER BY` to calculate rolling totals and examine how layoffs accumulated over time across countries.

### 8. Ranking Companies by Annual Layoffs

Created the `Company_Year` and `Company_Year_Rank` CTEs and used `DENSE_RANK()` to rank companies according to their total layoffs in each year.

### 9. Company Rolling Totals

Used a CTE and window functions to examine the progression of layoffs for individual companies over time.

## SQL Concepts Practised

- Aggregate functions: `SUM()`, `MIN()`, and `MAX()`
- Common Table Expressions (CTEs)
- Window functions
- `DENSE_RANK()`
- `ORDER BY`
- Grouping and aggregation
- Rolling totals
- Ranking and trend analysis

## Key Learning

This project strengthened my practical SQL skills and helped me understand how to explore a dataset, compare values across different categories, rank results, and analyse trends over time.

## Project Type

**Guided Learning Project** — completed as part of Alex The Analyst's Data Analyst Bootcamp.
