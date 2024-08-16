# Recor ML

This project showcases the development of an article suggestion system using web analytics data and cloud-based machine learning. It employs a matrix factorization technique for collaborative filtering to propose relevant content to readers based on their browsing behavior.

## Project Synopsis

The project encompasses these main stages:

1. Web analytics data processing and preparation
2. Feature engineering to establish an article engagement metric
3. Training a recommendation algorithm using cloud-based ML tools
4. Applying the model to generate content suggestions

## Repository Contents

- `create_table.sql`: SQL code for preparing and transforming raw analytics data
- `train.sql`: SQL code for building the recommendation algorithm
- `predict.sql`: SQL code for producing recommendations with the trained model
- `bqml_ga360.ipynb`: Jupyter notebook detailing the complete process with explanations

## Key Aspects

- Uses session duration as an indicator of article interest
- Implements data scaling and normalization methods
- Leverages cloud-based matrix factorization capabilities
- Demonstrates large-scale data handling in a cloud environment

## Quick Start Guide

1. Confirm access to a cloud-based dataset containing Google Analytics information
2. Execute the SQL scripts in this sequence:
   - `create_table.sql`
   - `train.sql`
   - `predict.sql`
3. For a detailed walkthrough, refer to the `bqml_ga360.ipynb` notebook

## Requirements

- Google Cloud Platform account with BigQuery access
- Proficiency in SQL and BigQuery
- Foundational knowledge of recommendation systems and collaborative filtering

## Pricing Consideration

Training advanced matrix factorization models requires setting up a reservation (flex or regular) in BigQuery. On-demand pricing is not available for this model type.

## Contributions

We welcome forks of this repository and encourage pull requests for any enhancements or expansions to the project.
