Ingestion and Staging of Financial Text Data

This project ingests financial text data from two sources:
	•	news articles from Financial Modeling Prep
	•	earnings call transcripts from Alpha Vantage

The goal is to build a clean, production-style ingestion and staging layer using a medallion-style layout. The work focuses on making raw, semi-structured text data reliable, traceable, and easy to transform downstream.

Along the way, this project explores:
	•	event-driven ingestion with AWS Lambda and scheduled jobs, and how this compares to Airflow
	•	staging and organization of text data in AWS SageMaker Lakehouse, with comparisons to Microsoft Fabric and Databricks
	•	restructuring raw text into consistent schemas that support a simple semantic layer for analysis

Financial Modeling Prep and Alpha Vantage were chosen because they are widely used data providers and expose realistic constraints such as API limits, missing data, and inconsistent structures—issues that matter in real ingestion pipelines.
