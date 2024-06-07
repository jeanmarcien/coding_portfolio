# Python Projects

## <u>Project 1<u>
### CleanLife: A Data Cleaning Project for Life Insurance Policies
The Life Insurance Data Cleaning Project aims to clean and standardize a messy dataset related to life insurance policies. The dataset includes fields such as policy ID, policy holder's name, age, date of birth, email, phone, address, policy amount, policy term, policy start date, policy status, and beneficiary name, initially containing numerous issues like missing values, inconsistent formats, and invalid data entries. The cleaning process involves handling missing values by filling or dropping them, correcting data types, standardizing data formats, removing duplicates, and validating data to ensure accuracy and consistency. By following these steps, the project transforms the dataset into a clean, reliable, and analysis-ready format, serving as a practical guide for preparing messy datasets for data analysis or machine learning tasks.

<u>Programming Language Used<u>: Python

[Code and Descriptions](https://github.com/jeanmarcien/cleanlife/tree/main)

## <u>Project 2<u>
The project involves retrieving Premier League data from an API and storing it in an SQLite database. The script starts by sending a GET request to the API using specific headers that include an API key. Upon successful retrieval of the data (status code 200), it proceeds to set up a local SQLite database. Within the database, it creates two tables: "teams" and "stats". The "teams" table stores information about each team, such as their name, logo, and abbreviation, while the "stats" table holds various statistics including wins, losses, ties, games played, goals for, goals against, points, rank, and goal difference. The data is extracted from the API response and inserted into the respective tables. Finally, the changes are committed, and the database connection is closed. If the API request fails, an error message with the status code is printed.

<u>Programming Language Used<u>: Python, SQL

[Code and Descriptions](https://github.com/jeanmarcien/premier_league_table_season_2022-2023)
