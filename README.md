# Ingestion and Staging for Financial Texts

This project gets financial texts (news articles from Financial Modeling Prep, earnings transcripts from Alpha Vantage). 
__

The purpose of this project is to build a production-ready medallion architecture that extracts alpha signals from Financial Modeling Prep (FMP) news articles. During the development, I learn about:
- Various ingestion methods (already built with Lambda, comparing with Airflow)
- Developing with AWS SageMaker Lakehouse and calling data agents. How this compares to Microsoft Fabric and Databricks - both of which I'm certified for.
- Reorganizing data for a semantic layer that financial analysts can query from

Financial Modeling Prep was chosen because it's used by reputable companies, such as Citadel and Harvard. News articles were chosen because they're webpages (semi-structured data), which are harder to standardize on than tabular data.
