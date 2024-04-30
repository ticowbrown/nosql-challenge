# NoSQL Challenge

## Overview
  This ReadMe document outlines the tasks completed for Eat Safe, Love, a food magazine, to evaluate food hygiene ratings data. 
The evaluation aims to assist journalists and food critics in focusing future articles on establishments across the United Kingdom.

## Part 1: Database and Jupyter Notebook Set Up
* Imported data from establishments.json into the MongoDB database named uk_food, with the collection establishments.
* Confirmed database setup by listing databases and collections, and displayed a document from the establishments collection.
## Part 2: Update the Database
*  Added information for a new halal restaurant, "Penang Flavours," to the database.
*  Updated the new restaurant with the appropriate BusinessTypeID.
*  Removed establishments within the Dover Local Authority from the database.
*  Converted latitude, longitude, and RatingValue data types.
## Part 3: Exploratory Analysis
*  Explored the database to answer specific questions provided by Eat Safe, Love regarding hygiene scores, rating values, and establishment locations.
   1. There are 41 establishments with a hygiene score equal to 20.
   2. There are 33 establishments with a rating value equal or greater than 4.
   3. The top 5 establishments with the highest rating value are:
      1.  Volunteer
      2.  Plumstead Manor Nursery
      3.  Atlantic Fish Bar
      4.  Iceland
      5.  Howe and Co Fish and Chips - Van 17
    4. There are 55 local authority areas with a count of of establishments with a hygiene score of 0.   

