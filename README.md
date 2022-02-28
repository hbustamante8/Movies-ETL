# Movies-ETL

## Project Overview

Amazing Prime video team would like to develop an algorithm to predict which low budget movie releasing soon will become popular so Amazing Prime can buy the streaming rights at a bargain. The goal of the project is to provide a clean dataset of movie data so that individuals can use in a hackathon that Amazing Prime is sponsoring. This project will create an automated pipeline that takes in new data from Wikipedia, Kaggle metadata, and the MovieLens rating data. The project performs the extract, transform, and loads the data into an existing PostgreSQL database. The following is an outline of what the python scripts do.


1. Write an ETL functions that reads the three different data files
2. Extract and transform the Wikipedia data
3. Extract and transform the Kaggle and rating data
4. Load the data to a PostgreSQL Movies Database via SQLAlchemy modules 


## Resources

* Software used: Python 3, Anaconda Navigator, Jupyter Notebook,PostegreSQL, pgAdmin


## Outcome

* This is a snapshot of what the movies table looks like within pgAdmin 4 after completing the extract,transform, and load.

![image](https://user-images.githubusercontent.com/96553992/155865474-6f93a2c3-41f9-46f4-be6d-ca274c353c99.png)


## Summary 

The ETL function created collects and cleans the data from the three different data sources (Wikipedia JSON, Kaggle csv, and ratings csv. The function merges the data and loads it into PostgreSQL database. Now the tables within the database can be used by the hackathon participants to conduct their analysis.
