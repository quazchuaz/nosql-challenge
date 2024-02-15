# nosql-challenge
Evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Part 1 - Setup and update database
Initally set up the database by importing the relevant json file. Within the UK Foods database, and establishments collection, added a new document for 'Penang Flavours'. Finally, removed all documents with the Dover Local Authority from the collection.

## Part 2 - Exploratory Analysis
Queries were run to answer a number of questions regarding the dataset. These were:

1. Which establishments have a hygiene score equal to 20 (first 6 rows below)?
![image](https://github.com/quazchuaz/nosql-challenge/assets/135037270/9fe3dc41-07df-483f-844b-b69d54a0cc9f)

3. Which establishments in London have a RatingValue greater than or equal to 4 (first 6 rows below)?
![image](https://github.com/quazchuaz/nosql-challenge/assets/135037270/0749a107-395c-42f2-a5c9-7e51caabafdb)
   
5. What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
6. ![image](https://github.com/quazchuaz/nosql-challenge/assets/135037270/bb43115c-74c4-4c5c-afa8-027759121e2f)

7. How many establishments in each Local Authority area have a hygiene score of 0 (first 10 rows below)?
![image](https://github.com/quazchuaz/nosql-challenge/assets/135037270/cf97f88f-c799-440f-ba53-c1f264666902)
