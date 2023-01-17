# Crowdfunding-ETL
## Overview
We were asked to assist Britta and her boss in breaking down information presented to us both as a csv and excel file throughout this module. We were asked to incorporate SQL and execute multiple queries in order to obtain the information her boss was seeking.

## Resources

Data : crowdfunding.xlsx, backer_info.csv

Primary Software : Python, Pandas, Jupyter Notebook, PostgreSQL 15, pgAdmin4, JSON

## Challenge Results

We performed quite a few steps in order to have the data be readable in the SQL database, using pandas we sorted the information into new columns with distinct columns names to better format the information using the string replace method.

We also seperated the columns in order to set primary and foreign keys for the table to be able to relate to one another once we ran the queries listed below with their outputs

Query: 

<img width="590" alt="Screenshot 2023-01-17 at 1 43 22 PM" src="https://user-images.githubusercontent.com/114188120/212984270-c46ead55-a9d4-4974-b85e-2cdaef148327.png">

Output:

<img width="834" alt="Screenshot 2023-01-17 at 1 46 57 PM" src="https://user-images.githubusercontent.com/114188120/212984941-8bd1fe7b-b340-4d75-ab09-63833f8dd759.png">


Query:

<img width="586" alt="Screenshot 2023-01-17 at 1 47 57 PM" src="https://user-images.githubusercontent.com/114188120/212985157-830f3bed-7b5e-40af-8401-b54f596d2423.png">

Output:

<img width="993" alt="Screenshot 2023-01-17 at 1 49 15 PM" src="https://user-images.githubusercontent.com/114188120/212985495-52fac547-d7a3-4c2f-9306-2d0daab95c80.png">

## Summary

By running these queries this should allow Britta and her boss to pass along infomration for each of these projects in order to locate backers that have not pledged to these "live" projects as well as to locate and let backers know how far from the goal or each individual has left on their pledge.

