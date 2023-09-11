# Data Cleaning and Analysis for Eat Safe, Love Magazine  

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Introduction
This repository contains the code and analysis for a data project undertaken for Eat Safe, Love magazine. The project involved cleaning and analyzing food hygiene ratings data from the UK Food Standards Agency to help the magazine's journalists and food critics identify establishments for future articles.

## Data Cleaning
### Part 1: Database Setup
Imported the provided data from the `establishments.json` file into a MongoDB database named `uk_food and` a collection named `establishments`.
Utilized PyMongo and Pretty Print (pprint) libraries for data manipulation.
Confirmed the successful import of data and set up the database for analysis.

### Part 2: Updating the Database
Added a new halal restaurant, "Penang Flavours," to the database as requested.
Found and updated the BusinessTypeID for "Restaurant/Cafe/Canteen."
Removed establishments within the Dover Local Authority as per the magazine's request.
Converted latitude and longitude values from strings to decimal numbers using `update_many`.

## Exploratory Analysis
### Part 3: Answering Magazine's Questions
Explored the dataset to answer specific questions posed by Eat Safe, Love magazine.
Utilized count_documents, pprint, and Pandas DataFrames for analysis.
Findings

## Key Findings
Identified establishments with a hygiene score equal to 20.

![image](https://github.com/nancygmz/nosql-challenge/blob/main/readme_pictures/Question_1.png)

Discovered establishments in London with a RatingValue greater than or equal to 4.

![image](https://github.com/nancygmz/nosql-challenge/blob/main/readme_pictures/question_2.png)

Determined the top 5 establishments with a RatingValue of '5,' sorted by the lowest hygiene score and proximity to "Penang Flavours."

![image](https://github.com/nancygmz/nosql-challenge/blob/main/readme_pictures/question_3.png)

Calculated the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.

![image](https://github.com/nancygmz/nosql-challenge/blob/main/readme_pictures/Screenshot%202023-09-11%20191611.png)

## Conclusion
This project demonstrates the data cleaning and analysis process performed on the UK Food Standards Agency's hygiene ratings data. The findings provide valuable insights for Eat Safe, Love magazine to select locations for future articles. For detailed code and analysis, please refer to the Jupyter notebooks in this repository.
