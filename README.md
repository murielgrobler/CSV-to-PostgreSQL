# CSV-to-PostgreSQL
The goal of this project is to transfer the information in a CSV file into a PostgreSQL database and analyse this
As a sample project we'll be using Python to create a mathematical model to predict energy consumption based on 
weather conditions. 

We will be using psycopg2 and handling the data in Python. Please note that you will need a working PostgreSQL
database to complete this exercise. This directory contains two .csv files and the python script for importing 
them into the PostgreSQL tables. 

In order to run the script, do the following:
1. Create a PostgreSQL database called "austin_weather_energy"
2. Create a user for the database
3. Download the two .csv files to a directory on your computer
4. Run the two Python files "Austin Energy to SQL.ipynb" and "Austin Weather csv to SQL.ipynb" (remember to change location specific details and user information)

The two database tables you've created can now be used to make predictions about energy costs. The notebook
"Analyzing weather energy data from SQL" was created for this.

