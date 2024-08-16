# Recor ML

This project demonstrates the creation of a content recommendation system using web analytics data and cloud-based machine learning. It implements a matrix factorization approach for collaborative filtering to suggest relevant articles to users based on their reading patterns.

## Project Overview

The project covers these key phases:

1. Analytics data preparation and processing
2. Feature engineering to create an article engagement metric
3. Training a recommendation model using cloud-based ML tools
4. Generating predictions and applying recommendations

## Repository Contents

- `data_transform.sql`: SQL script for preparing and transforming raw analytics data
- `model_build.sql`: SQL script for training the recommendation model
- `recommendation_gen.sql`: SQL script for producing recommendations using the trained model
- `recor_ml_workflow.ipynb`: Jupyter notebook containing the complete process with explanations

## Key Features

- Leverages session duration as a proxy for article engagement
- Applies data normalization and scaling techniques
- Utilizes cloud-based matrix factorization capabilities
- Demonstrates handling of large-scale data in a cloud environment

## Getting Started

1. Ensure access to a cloud-based dataset with web analytics information
2. Execute the SQL scripts in this order:
   - `data_transform.sql`
   - `model_build.sql`
   - `recommendation_gen.sql`
3. Alternatively, follow the `recor_ml_workflow.ipynb` notebook for a step-by-step guide

## Prerequisites

- Cloud platform account with appropriate database access
- Proficiency in SQL and cloud-based data processing
- Basic understanding of recommendation systems and collaborative filtering

## Note on Computational Resources

Training advanced matrix factorization models may require setting up specific computational resources. Standard on-demand pricing might not be available for this model type.

## Contributing

We welcome forks of this repository and encourage pull requests for any improvements or extensions to the project.
