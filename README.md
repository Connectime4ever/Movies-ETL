# Movies-ETL
## Project Overview
The client requests to keep the  dataset updated on a daily basis.
The automated pipeline that should be created will take in new data, perform the appropriate transformations, and load the data into existing tables. 
 In this sense, the original code should be refactored to create one function that takes in the data sources used (Wikipedia data, Kaggle metadata, and the MovieLens rating data), and performs the ETL process by adding the data to a PostgreSQL database.

## Results
#### ***ETL Function to Read Three Data Files***
![D1](https://github.com/Connectime4ever/Movies-ETL/blob/main/D1.png)
![df11](https://github.com/Connectime4ever/Movies-ETL/blob/main/df11.png)
![df12](https://github.com/Connectime4ever/Movies-ETL/blob/main/df12.png)
![df13](https://github.com/Connectime4ever/Movies-ETL/blob/main/df13.png)
#### ***Extract and Transform the Wikipedia Data***
![df21](https://github.com/Connectime4ever/Movies-ETL/blob/main/df21.png)
![df22](https://github.com/Connectime4ever/Movies-ETL/blob/main/df22.png)
#### ***Extract and Transform Kaggle Data***
![df31](https://github.com/Connectime4ever/Movies-ETL/blob/main/df31.png)
![df32](https://github.com/Connectime4ever/Movies-ETL/blob/main/df32.png)
#### ***Create the Movie Database***
![movies_query](https://github.com/Connectime4ever/Movies-ETL/blob/main/Resources/movies_query.png.png)
![ratings_query](https://github.com/Connectime4ever/Movies-ETL/blob/main/Resources/ratings_query.png.png)