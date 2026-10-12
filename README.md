# Pre-Launch Market Intelligence System

An AI-powered product and market intelligence system focused on India.

## Objective

Analyze product, pricing, customer, demand, competition, consumer-interest,
seasonality, events, demographic, economic, technology, distribution, and
regulatory factors to support product-launch planning and market analysis.

## V1 Scope

- India-focused market analysis
- Historical category-month demand analysis
- Product and competition feature engineering
- Consumer-interest and seasonality analysis
- Data quality checks and master-dataset preparation
- Future scenario analysis, subject to data availability

## Factor Status

- Factors 1–13: data preparation and feature work at varying stages
- Factor 14 — Marketing & Distribution: template only; data collection pending
- Factor 15 — Social/Cultural/Influencer: paused and excluded from V1 master data
- Factor 16 — Tax/Tariff/Regulation: reference data requires verification

## Current Dataset

The current category-month master dataset contains 72 records across
three product categories and 24 months (2023–2024).

This dataset is exploratory. Its small size is not sufficient by itself to
claim reliable product-launch success probabilities or generalizable
production-grade predictions.

## Repository Structure

- `notebooks/` — reviewed project notebook
- `01_Raw_Data/` — local raw data, excluded from Git
- `02_Cleaned_Data/` — local cleaned data, excluded from Git
- `03_Feature_Engineered/` — local feature datasets, excluded from Git
- `04_Master_Dataset/` — generated master datasets, excluded from Git

## Setup

The current notebook was developed for Google Colab and Google Drive.
Upload the required source datasets to the expected Colab paths and configure
the project base directory before running the pipeline.

Install the Python dependencies listed in `requirements.txt`.

## Data and Privacy

Raw data, generated datasets, model artifacts, credentials, and environment
files must not be committed to this repository. Review dataset licensing and
source attribution before redistributing any data.

## Status

Data preparation and repository setup are in progress. Model training has
not been approved yet.
