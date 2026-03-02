# Overview
Think of workflow orchestration as an orchestra with different instruments and a conductor

In our case

Kestra is the conductor and will make use of the different tools (code, cloud, database) and apply and use them to use them in whenever and wherever it sees fit.

Scheduled and Event Driven triggers

Kestra creates a workflow orchestration using a yaml file as a configuration.

# ETL vs. ELT

Extract Transform Load vs Extract Load Transform

## ETL

In our case, we were extracting the data from csvs on web. Transforming the data by adding file name and unique ids, then merge into final destination in postgres database.

## ELT

Load massive dataset into cloud, then transform using power of cloud. Use BigQuery to interact with yellow dataset.


The benefits of ELT is that we can utilize the power of the cloud, (cloud computing usually is a lot more powerful compared to local machines.)
