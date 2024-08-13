# Eat Safe, Love - UK Food Standards Analysis

## Project Overview
This project is part of a data analysis task for a food magazine, *Eat Safe, Love*. The UK Food Standards Agency provides food hygiene ratings for various establishments across the United Kingdom. This project involves setting up a NoSQL database, performing updates, and conducting exploratory data analysis to help the magazine’s journalists and food critics focus on key areas for their articles.

## Project Structure
- **Part 1: Database and Jupyter Notebook Set Up**
  - Import the data from `establishments.json` into a MongoDB database named `uk_food`.
  - Create an instance of MongoClient.
  - Confirm that the data has been loaded correctly by listing the databases and collections, and displaying a sample document.

- **Part 2: Update the Database**
  - Add a new restaurant, "Penang Flavours", to the database.
  - Update the new restaurant with the correct `BusinessTypeID`.
  - Remove all establishments located in Dover.
  - Convert string values for latitude, longitude, and `RatingValue` to their appropriate numeric types.

- **Part 3: Exploratory Analysis**
  - Answer key questions posed by the magazine editors using MongoDB queries:
    - Identify establishments with a hygiene score of 20.
    - Find establishments in London with a `RatingValue` greater than or equal to 4.
    - List the top 5 establishments near "Penang Flavours" with a `RatingValue` of 5, sorted by the lowest hygiene score.
    - Determine the number of establishments in each Local Authority area with a hygiene score of 0.
