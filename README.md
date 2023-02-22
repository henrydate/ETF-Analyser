# Visual Data Analysis of Suspicious Transactions via SQL


## Background

Fraud is prevalent these days, whether you are a small taco shop or a large international business. While there are emerging technologies that employ machine learning and artificial intelligence to detect fraud, many instances of fraud detection still require strong data analytics to find abnormal charges.

In this repo I have used SQL to analyze historical credit card transactions and consumption patterns in order to identify possible fraudulent transactions. The following tasks have been completed:

1. Data Modeling: Define a database model to store the credit card transactions data and create a new PostgreSQL database using your model.

2. Data Engineering: Create a database schema on PostgreSQL and populate your database from the CSV files provided.

3. Data Analysis: Analyze the data to identify possible fraudulent transactions.

---

## The Process

### Data Modeling

I have created an entity relationship diagram (ERD) based on the CSV files. You can view the ERD file in the ERD notebook.

### Data Engineering

Using the database model as a blueprint I have created a database schema for each of the tables and relationships. After creating the database schema, I imported the data from the corresponding CSV files.

### Data Analysis

It's time to identify fraudulent transactions. In this part of the repo, I have analyzed the data and then created a report to present the findings. The report answers the following questions:

* How can we isolate (or group) the transactions of each cardholder?

* Considering the time period 7:00 a.m. to 9:00 a.m. What are the top 100 highest transactions during this time period?

* Are there any fraudulent or anomalous transactions?

* Why might there be fraudulent transactions during this time frame?

* Some fraudsters hack a credit card by making several small payments (generally less than \\$2.00), which are typically ignored by cardholders. Is there any evidence to suggest that a credit card has been hacked? Explain your rationale.

* What are the top 5 merchants prone to being hacked using small transactions?


### Visual Data Analysis 

I have performed a visual data analysis of fraudulent transactions using Pandas, hvPlot, and SQLAlchemy to create the visualizations. The answers to these questions is within visual_data_analysis.ipynb

## Contributors
> Email: Henrydate1@gmail.com |
> [GitHub](https://github.com/henrydate) |
> [LinkedIn](https://www.linkedin.com/in/henry-date-9356351a4/)

---
