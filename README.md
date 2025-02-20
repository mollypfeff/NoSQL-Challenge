# NoSQL-Challenge
This repository contains my submission for the Module 12 Challenge due on 1/21. All of the work present has been created by myself, Molly Pfefferkorn. My instructor, Dr. Carl Arrington, provided troubleshooting feedback during the designated office hours of this class. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
-------------
This project involved analyzing food hygiene ratings from the UK Food Standards Agency for Eat Safe, Love, a (fictional) food magazine. The task was divided into three parts: setting up a MongoDB database to store and manage the data, updating the database with a new halal restaurant ("Penang Flavours"), and performing exploratory data analysis to answer specific questions. 

The database was set up using the mongoimport command to import the data, followed by ensuring the data was loaded correctly with queries using PyMongo. 

Updates to the database included adding a new restaurant, Penang Flavours, updating its details, and removing all establishments from Dover. Data cleaning was performed by converting string values for latitude, longitude, and ratings into appropriate numeric formats. 

The analysis focused on answering questions such as identifying establishments with specific hygiene scores, finding high-rated establishments in London, locating the top 5 highest-rated restaurants near Penang Flavours, and aggregating data on hygiene scores of 0 across local authority areas. MongoDB queries and aggregation pipelines were used for these tasks, and the results were displayed using Pandas DataFrames.
