# Movies-ETL


## Overview 

The purpose of this project was to create an automated pipeline that takes in new data, transforms the data into a clean/readable format with the relavant information, and loads the data into Postgres SQL tables. 

## ETL Test Function

For this step I refactored the code from the module to write an ETL function to read the 3 data files we were using for this project (movies metadata and ratings from Kaggle, along with Wikipedia movies). 

## ETL Wiki Movies

For this part in the project I refactored the code & updated the function to preform the Extract and Transform steps for the Wikipedia data. 

## ETL Kaggle Data

For this part in the project I refactored the code & updated the function to preform the Extract and Transform steps for the Kaggle data. 

## ETL Create Database 

For this part of the project I refactored the code to preform the Extract and Transform steps for the Kaggle and Wikipedia data, along with create a connection to SQL and create 2 table with the clean data, that also replaces the tables if they already exist so the database can be consistently updated. 