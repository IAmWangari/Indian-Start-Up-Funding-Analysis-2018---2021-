# Indian-Start-Up-Funding-Analysis (2018-2021)
This repository contains an in-depth analysis of the Indian startup ecosystem as the analysis aim to explores various elements of Indian startups.
Table of Contents
Overview
Dataset Description
Data Collection and Sources
Data Cleaning and Preparation
Columns Description
Usage Instructions
Insights and Key Findings
References

1. Overview

This dataset provides a comprehensive overview of start-up funding in India from 2018 to 2021. It includes data on funding amounts, investors, sectors, and the geographical distribution of start-up funding. This dataset is intended for analysts, researchers, and entrepreneurs interested in exploring trends and insights in the Indian start-up ecosystem.

2. Dataset Description

File Name: cleaned_combined_dataset.csv
Format: CSV
Size: [Add the size here]
Number of Rows: [Add the number of rows]
Number of Columns: [Add the number of columns]

3. Data Collection and Sources

The dataset is compiled from various public and private sources, mainly Crunchbase, a platform for finding business information about private and public companies.

4. Data Cleaning and Preparation

To ensure data quality and consistency, the following steps were taken:
Missing Values: Missing data points were filled using appropriate techniques, such as forward filling.
Data Standardization: Ensured consistent formatting for textual data.
Outlier Removal: Removed extreme outliers in the funding amount to prevent skewed analysis.
Column Standardization: Unified the format for critical columns like ‘HeadQuarter’ to simplify analysis.

5. Columns Description

Here’s a brief overview of each column:
Column Name         	Description
Start-up Name	        Name of the start-up.
Sector	                Business sector or industry the start-up belongs to.
Amount($)	            Funding amount received in USD.
HeadQuarter	            City where the start-up is headquartered.
Investor Name	        Name of the primary investor.
Year	                Year in which the funding was received.
Stage	                Funding stage (e.g., Seed, Series A).
Funding Type	        Type of funding (e.g., Equity, Debt).
Number of Investments	Total number of investments received by the start-up.

6. Usage Instructions

Loading the Data: Use Python libraries like pandas to load and explore the dataset.
Exploring Data: Use descriptive statistics and visualizations to explore trends and patterns.
Analyzing Trends: Perform analysis to find trends over the years, sector-specific funding patterns, and regional distribution.

7. Insights and Key Findings

Funding Growth: There was a steady increase in start-up funding from 2018 to 2021.
Sector Leaders: Fintech and Healthcare received the highest funding.
Regional Hotspots: Bangalore and Mumbai were the top cities for start-up funding.
Investment Stages: Early-stage funding was more prevalent, but significant funds were directed towards later stages.

8. References

Crunchbase: crunchbase.com
Azubi Africa: azubiafrica.com

