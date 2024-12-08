# Mini-Project

The dataset order data analysis from kaggle is unzipped and the data clenaing process such as renaming data , renaming columns , remvoing null or missing values. Then the data is pushed into cloud database from python by using psycopg2 package . Before pushing the dataframe it is split into two dataframes. Two tables are created in the database and then the data is pushed from python.The host name of postgres , username , password,host,database values are given and they are connected. Then pushed by sqlalchemy and create engine package. This create engine package connects postgres to the cloud server database.

After pushing the dataframes into two tables the given queries are executed successfully and queries for my own questions are run successfully.
