# GRIND SALES PRICING PROJECT (2023-2025)

## Project Overview
The objective of this analysis is to assess the decline in profit margins across the product portfolio, driven primarily by rising Cost of Goods Sold (COGS), tariffs, and other cost pressures. Using order data from 2023 to 2025, the analysis aims to evaluate portfolio performance and support pricing strategy decisions.
* Task:
  * Identify all products with a Gross Margin % (GMP) below 30% in Q3 2025.
  * Create a dashboard showing Year-over-Year GMP, Revenue by Category, Product and Region.
  * Provide clear, data-backed recommendations on which items require a price increase or discontinuation.

## Data Sources & Ingestion
* Built a modern SQL Server data warehouse using a Medallion Architecture, from raw CSV ingestion into Bronze, Silver, and Gold layers via Stored Procedures to deliver business-ready data.
<img width="13720" height="7510" alt="High Architector" src="https://github.com/user-attachments/assets/b4f5f864-891f-43bb-84a6-ae5922d5d5a3" />

## Executive Summary & Recommendations 
* Key Finding: Identified six key products consistently failed to meet the 30% Gross Margin threshold.
* Strategic Action: Recommended a tiered pricing strategy: discontinuing low-value merchandise and implementing price adjustments on high-volume essentials to restore profitability.
* Full Report: [View Presentation Slides](https://drive.google.com/file/d/1EHqgQH0TWGbQ2QZPB0_NwDP5WAjYpHe2/view?usp=sharing)

## Dash Board: 

<img width="1056" height="593" alt="image" src="https://github.com/user-attachments/assets/e2095ae3-0348-4140-a93f-201aaf65b541" />

<img width="1057" height="593" alt="image" src="https://github.com/user-attachments/assets/09c4913b-febe-48d5-a831-807e29d8c331" />


## Tool: 
* SQL Server: For designing the database schema, loading raw CSVs, and creating Views for Power BI integration.
* Power BI: For calculating profit metrics and designing the final dashboard.
<img width="2742" height="1299" alt="SQLdrawio" src="https://github.com/user-attachments/assets/2d7d99d7-5a8b-4f5f-a73a-8ba0eb0a4796" />
