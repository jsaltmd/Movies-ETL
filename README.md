# Movies-ETL

### Background
A series of datasets were created for Amazing Prime and they love and wants to keep it updated on a daily basis. An automated pipeline was created that takes in new data, performs the appropriate transformations, and loads the data into existing tables. The codes from the previous dataset was refactored to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.