# Customer Credit Card Clustering

This repository contains code and data for performing K-means clustering on a customer credit card information dataset (https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data). The goal is to group customers based on their behaviour and identify patterns or segments within the customer base.

## Dataset

The dataset used for this analysis consists of the following variables:

- `SI_No`: Customer Serial Identification Number (unique)
- `Customer Key`: Customer Reference Key (unique)
- `AvgCreditLimit`: Average Credit Card Limit for the Customer
- `Total_Credit_Cards`: Total Credit Cards Owned by the Customer
- `Total_visits_bank`: Total Number of Bank Visits by the Customer
- `Total_visits_online`: Total Visits Online by the Bank Customer
- `Total_calls_made`: Total Calls Made by the Customer to the Bank

## Methodology

The K-means clustering algorithm was applied to the dataset using SAS Enterprise Miner. K-means is an unsupervised machine learning algorithm that partitions the data into K clusters based on the similarity of observations within each cluster. The algorithm iteratively assigns observations to clusters and updates the cluster centroids until convergence.

## Usage

SAS Enterprise Miner 15.2 version


## Results

The clustering analysis resulted in 3 distinct customer segments based on their characteristics. [LowCreditHighVolumeCallCustomers, FrequentBankVisitors, TopCreditOnlineCustomers]


