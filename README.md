# Movies-ETL
## Project Overview
The client requests to keep the  dataset updated on a daily basis.
The automated pipeline that should be created will take in new data, perform the appropriate transformations, and load the data into existing tables. 
 In this sense, the original code should be refactored to create one function that takes in the data sources used (Wikipedia data, Kaggle metadata, and the MovieLens rating data), and performs the ETL process by adding the data to a PostgreSQL database.