# Credit Card Approval Prediction

## Overview

This project aims to predict credit card approval status based on applicant data using classification algorithms. By utilizing personal information and credit history, the model determines the likelihood of credit card approval. The dataset consists of two parts: `credit_record` and `application_record`, which are merged using a common `ID` to create a unified dataset for prediction.

## Key Features

- **Dataset Merging**: Merged two datasets (`application_record` and `credit_record`) using the `ID` column to create a unified dataset.
- **Class Mapping**: Credit score categories are mapped to two main classes:
  - **Approved**: `C`, `X` (Mapped to `0`)
  - **Not Approved**: `0`, `1`, `2`, `3`, `4`, `5` (Mapped to `1`)
- **Pipeline Implementation**: Includes data cleaning, preprocessing, model training, and evaluation.
- **Prediction**: Utilizes machine learning algorithms to predict the approval status based on applicant data.

## Dataset

The dataset consists of two parts:
- `application_record`: Contains application details.
- `credit_record`: Contains credit score records.

The datasets are merged by the `ID` column to form a unified dataset for prediction.
