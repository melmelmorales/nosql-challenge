# Data-Driven Delights: Serving Up the Best in Culinary Critique
Melissa Morales

# Overview

The UK Food Standards Agency assesses a range of establishments across the country, providing them with food hygiene ratings. This project involves analyzing the ratings data to assist journalists at "Eat Safe, Love" and food critics in identifying key areas for future articles.

The assignment focuses on working with non-relational documents, employing the PyMongo library to interface with MongoDB databases using Python. MongoDB, a document-oriented database, offers greater flexibility compared to structured SQL databases, making it suitable for both small-scale and large-scale data projects.

# Method

This project followed a three-part methodology:

**Database and Jupyter Notebook Setup:** Initially, a MongoDB database was established, and a Jupyter notebook was configured. Ratings data for food establishments, provided in a JSON format, was imported into the MongoDB database. Subsequent analyses were conducted to guide editorial decisions for the food magazine.

**Database Updates:** The PyMongo library was utilized to manage the database, facilitating essential CRUD (Create, Read, Update, Delete) operations to ensure the data remained current and relevant.

**Exploratory Analysis:** Advanced queries were executed to extract documents from the MongoDB database, and aggregation pipelines were employed to perform in-depth analyses on the data.

# Exploratory Analysis

## Which establishments have a hygiene score equal to 20?

Number of rows in the DataFrame: 41

## Which establishments in London have a RatingValue greater than or equal to 4?

Number of documents in the result: 33

## What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

The top 5 establishments are "The Pizza Spot", "Towes (Premier) Convenience Score, Lullingstone Castle, High Firs, and Swanley Kindergarten Pre-School.

## How many establishments in each Local Authority area have a hygiene score of 0?

| Local Authority | Count |
| ------------- |:-------------:|
| Thanet | 1130 |
| Greenwich | 882 |
| Maidstone | 713 |
| Newham | 711 |
|	Swale |	686 |
|	Chelmsford |	680 |
|	Medway	| 672 |
|	Bexley |	607 |
|	Southend-On-Sea	| 586 |
|	Tendring |	542 |
