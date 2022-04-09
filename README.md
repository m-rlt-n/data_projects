# data_projects

## Overview

This repository exists to publicly showcase examples from my data engineering work. The vast majority of my work is housed in private repositories, as it is completed for clients of [Brocade Studio](https://www.brocade.studio), or for [TropicSport](https://www.tropicsport.com).

## Files

`ecom_record_linkage.ipynb`: script used to link customers across platforms for ecom company using Shopify and Amazon. 

Outputs
-  a table of orders by linked customers for retargeting, 
-  descriptive statistics about repeat behaviors for management

`employees_by_role_and_year.ipynb`: script used to create a table of employees with a record for each fiscal year in which they held a given position.

Outputs
- "employees_by_role_by_year" table in a MySQL database

`shopify_orders.ipynb`: script used with Crontab to pull order data into DB on daily basis.

Outputs
- daily updates to orders table in shopify schema
