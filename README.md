# Customer Churn Capstone – Part 2: RFM Segmentation & Retention Strategy

## Project Overview

This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) framework. Customers are grouped into meaningful segments based on their purchasing behavior and engagement patterns.

## Dataset

The analysis uses customer behavioral and transaction data provided in the D2C Churn Capstone dataset.

## Methodology

### Recency (R)

Measures how recently a customer interacted or purchased.

### Frequency (F)

Measures how often a customer purchased during the observation period.

### Monetary (M)

Measures total customer spending during the observation period.

Customers were scored using RFM metrics and assigned to business-friendly segments.

## Customer Segments

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk
* Lost Customers

## Key Findings

* Champions show the lowest churn rate and highest monetary value.
* Lost Customers exhibit the highest churn risk.
* At Risk customers show declining engagement and require intervention.
* Loyal Customers generate consistent revenue and should be retained.
* Potential Loyalists can be nurtured into high-value customers.

## Repository Structure

* 02_RFM_Segmentation.ipynb
* customer_segments.csv
* retention_strategy.md
* requirements.txt
* Visualisations/

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open the notebook:
   jupyter notebook 02_RFM_Segmentation.ipynb

3. Run all cells to reproduce the analysis.
