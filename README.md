# Datacamp Project: Modeling Car Insurance Claim Outcomes

## Overview
Insurance companies need to optimize their pricing strategies and accurately predict the likelihood of claims to stay competitive. In many jurisdictions, car insurance is mandatory for driving, ensuring a vast market. This project, initiated by On the Road Car Insurance, aims to develop a predictive model to determine whether a customer will file a claim during their policy period. Due to limited expertise in machine learning deployment and monitoring, the focus is on identifying the single most predictive feature for claim occurrence, using model accuracy as the performance metric.

## Dataset
The dataset provided by On the Road Car Insurance is contained in a CSV file named `car_insurance.csv`. The file includes several columns, each representing different attributes of customers and their insurance policies. Below is a table describing each column in detail:

| Column Name        | Description                            |
|--------------------|----------------------------------------|
| `customer_id`      | Unique identifier for the customer     |
| `age`              | Age of the customer                    |
| `vehicle_type`     | Type of vehicle insured                |
| `policy_start`     | Start date of the insurance policy     |
| `policy_end`       | End date of the insurance policy       |
| `annual_premium`   | Annual cost of the insurance policy    |
| `claim_history`    | Number of claims made in the past      |
| `credit_score`     | Credit score of the customer           |
| `outcome`          | 1 if a claim was made, 0 otherwise     |

