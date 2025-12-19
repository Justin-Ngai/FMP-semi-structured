# Ingestion and Staging of Financial Text Data

This project ingests financial text data from **Financial Modeling Prep** (news articles) and **Alpha Vantage** (earnings call transcripts).

The goal is to build an ingestion and staging layer that organizes raw, semi-structured text data into a medallion-style layout for downstream analysis.

## Scope

This project focuses on:
- ingesting text data using AWS Lambda and scheduled jobs
- staging semi-structured text data in AWS SageMaker Lakehouse
- organizing text into an event based schema to support analyzing corporate actions
