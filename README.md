### Financial Data Analysis

## Overview

This project analyzes financial data from two datasets: Balance_Sheet.xlsx and Income_Statement.xlsx. The goal is to compute and evaluate key financial ratios and provide insights into different industry types based on these ratios.

## Datasets
Balance_Sheet.xlsx: Contains balance sheet information for various companies.
Columns:
Company: Company ticker name.
Year: Year of the financial data.
comp_type: Industry type (tech, fmcg, real_est).
Additional columns related to balance sheet metrics such as Total Liab, Total Stockholder Equity, etc.
Income_Statement.xlsx: Contains income statement information for the same set of companies.
Columns:
Company: Company ticker name.
Year: Year of the financial data.
comp_type: Industry type (tech, fmcg, real_est).
Additional columns related to income statement metrics such as Gross Profit, Total Revenue, etc.
Analysis

The analysis involves the following steps:

## Load Data:
Import the datasets using Pandas.
## Merge Data:
Combine the balance sheet and income statement datasets on common columns (Company, comp_type, Year).
## Calculate Ratios:
Leverage Ratio: Ratio of Total Liabilities to Total Stockholder Equity.
## Profitability Ratio: Ratio of Gross Profit to Total Revenue.
## Compute Insights:
Identify the industry type with the lowest average profitability ratio.
Identify the industry type with the highest average leverage ratio.
Analyze the relationship between leverage and profitability for real estate companies.
