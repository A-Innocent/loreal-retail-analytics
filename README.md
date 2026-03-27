# L'Oréal Retail Analytics Dashboard

A production-grade BI solution built on the Sephora skincare dataset, 
demonstrating end-to-end analytics engineering from raw data to 
AI-powered insights.

## Project Overview
This project simulates an enterprise retail analytics dashboard for 
L'Oréal's skincare portfolio, combining Python data engineering, 
Power BI development, and Claude AI integration to deliver 
actionable business intelligence.

## Tech Stack
- **Python** (pandas) — data ingestion, cleaning, aggregation
- **Power BI** — dashboard development, DAX measures, RLS security
- **Claude API** (Anthropic) — AI-generated narrative insights
- **GitHub** — version control and documentation

## Dataset
Sephora Products and Skincare Reviews — Kaggle  
1,094,411 customer reviews across 27 product categories and 1,100+ brands

## Dashboard Pages
1. **Executive Overview** — KPI cards, category volume, average ratings
2. **Brand Intelligence** — Top 10 brands, price vs rating scatter, 
   recommendation rates
3. **Customer & Skin Type Analysis** — Ratings and engagement by skin type
4. **Category Trends** — Review volume and rating trends 2008–2023
5. **AI Insights** — Claude-generated narrative analysis by topic

## Security Implementation
- PII pseudonymization on customer identifiers
- Dynamic Row-Level Security (ABAC) with DAX
- Parameterized API key management mapped to Azure Key Vault pattern

## Notebooks
| Notebook | Description |
|----------|-------------|
| `01_data_prep.ipynb` | Data ingestion, cleaning, and master table creation |
| `02_aggregations.ipynb` | Aggregated summary tables for Power BI |
| `03_ai_insights.ipynb` | Claude API integration for AI narrative generation |

## Author
Alantz Innocent  
[LinkedIn](https://linkedin.com/in/ainnocent) | 
[GitHub](https://github.com/A-Innocent)
