# nosql-challenge

UK Food Standards Agency Data Analysis

Project Overview

This project involves evaluating food hygiene ratings from the UK Food Standards Agency. The objective is to assist the editors of the food magazine Eat Safe, 'analyzing establishments' data to guide their food critics and journalists.

Project Sections

Part 1: Database and Jupyter Notebook Setup

Import the dataset establishments.json into MongoDB.

Use UK_food as the database name and establishments as the collection name.

Verify successful import by listing databases and collections.

Retrieve and display a sample document.

Part 2: Database Updates

Add a new restaurant, Penang Flavours, which is pending a rating.

Retrieve the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new entry accordingly.

Remove establishments under the "Dover" Local Authority.

Convert improperly stored numerical values to their correct data types:

Convert latitude and longitude to decimals.

Convert RatingValue to integers, handling non-numeric values.

Part 3: Exploratory Analysis

Perform data queries to answer key questions:

Identify establishments with a hygiene score of 20.

Find establishments in London with a RatingValue of 4 or more.

Locate the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to Penang Flavours.

Determine the number of establishments with a hygiene score of 0 in each Local Authority and list the top 10.

Tools and Technologies Used

MongoDB: NoSQL database for storing and querying the data.

PyMongo: Python library for interacting with MongoDB.

Jupyter Notebook: For executing data queries and analysis.

Pandas: Data manipulation and transformation for structured analysis.

Pretty Print (pprint): For better readability of JSON data.

Setup and Execution

Install MongoDB and start the service.

Import the dataset:

Open the provided Jupyter Notebook (NoSQL_setup_starter.ipynb) and execute the cells in order.

Perform database modifications and queries as outlined in the notebook.

