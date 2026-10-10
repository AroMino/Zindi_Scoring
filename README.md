# Zindi African Credit Scoring Challenge

This repository contains data, notebooks, and scripts for the African Credit Scoring Challenge on Zindi.

## Project Structure

- `Train.csv`: Training dataset containing customer loan records and default targets (0 or 1).
- `Test.csv`: Test dataset for which default predictions need to be made.
- `SampleSubmission.csv`: Example of the submission format.
- `economic_indicators.csv`: Additional economic indicators data.
- `VariableDefinitions.txt`: Descriptions of all features in the datasets.
- `Starter_Notebook_.ipynb`: Starter Jupyter notebook provided for the challenge.
- `exploration.ipynb`: Exploratory Data Analysis (EDA) and modeling notebook.
- `african-credit-scoring-challenge*.zip`: The original compressed dataset downloaded from Zindi.

## Objective

The goal is to predict whether a customer will default on a loan. The target variable is `target` (0 = no default, 1 = default).

## Features

The datasets include information such as:
- `Total_Amount` and `Total_Amount_to_Repay`
- `loan_type` and `duration`
- `New_versus_Repeat` customer indicator
- Demographic identifiers like `country_id`

For a complete list and description of the features, refer to `VariableDefinitions.txt`.
