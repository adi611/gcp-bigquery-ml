# Google Analytics Recommendation Model with BigQuery ML

This project demonstrates how to build a recommendation system using Google Analytics data and BigQuery ML. It implements a WALS (Weighted Alternating Least Squares) matrix factorization model for collaborative filtering to recommend newspaper articles to users based on their reading behavior.

## Project Overview

The project covers the following key steps:

1. Data preparation using Google Analytics data
2. Feature engineering to create a proxy for article ratings
3. Training a recommendation model using BigQuery ML
4. Making predictions and generating recommendations

## Files in this Repository

- `create_table.sql`: SQL script to prepare and transform the raw GA360 data
- `train.sql`: SQL script to train the recommendation model
- `predict.sql`: SQL script to generate recommendations using the trained model
- `bqml_ga360.ipynb`: Jupyter notebook containing the full workflow and explanations

## Key Features

- Uses session duration as a proxy for article ratings
- Implements data scaling and normalization techniques
- Utilizes BigQuery ML's matrix factorization capabilities
- Demonstrates how to handle large-scale data processing in BigQuery

## Getting Started

1. Ensure you have access to a BigQuery dataset with Google Analytics data
2. Run the scripts in the following order:
   - `create_table.sql`
   - `train.sql`
   - `predict.sql`
3. Alternatively, follow along with the `bqml_ga360.ipynb` notebook for a step-by-step guide

## Prerequisites

- Google Cloud Platform account with BigQuery access
- Familiarity with SQL and BigQuery
- Basic understanding of recommendation systems and collaborative filtering

## Note on BigQuery Pricing

Training matrix factorization models requires setting up a reservation (flex or regular) in BigQuery. On-demand pricing is not available for this type of model.

## Contributing

Feel free to fork this repository and submit pull requests with any improvements or extensions to the project.
