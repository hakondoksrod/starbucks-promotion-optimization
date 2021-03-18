# Starbucks promotion optimization
This project is made as a part of the Udacity Data Scientist Nanodegree Program. The project has been used by Starbucks as a take home assignment for job candidates. The contents of the data is explained in more detail inside the notebook (Starbucks.ipynb)

## Table of Contents:
- [Installation](#installation)
- [File descriptions](#file-descriptions)
- [Project Summary](#project-summary)

## Installation
The project should run without issues using Python 3. The project was created using an Anaconda installation. If you are using this, make sure to install the following packages:
- xgboost
- imblearn

## File descriptions
- Starbucks.ipynb - notebook file containing the project code
- test_results.py - script to display results of optimization strategy
- Test.csv - file with the test portion of the dataset
- training.csv - file with the training portion of the dataset

## Project Summary
The data for this prject consists of about 120,000 data points split in a 2:1 ratio among training and test files. In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion.

The goal is to maximize the following metrics:
- Incremental Response Rate(IRR)
--IRR shows how many more customers purchased the product with the promotion, as compared to if they didn't receive the promotion
- Net Incremental Revenue (NIR)
--NIR shows the net revenue of the promotion after deducting the cost of distributing the promotion
