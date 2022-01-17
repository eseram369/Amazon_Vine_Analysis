# Amazon_Vine_Analysis

## Analysis Overview
### This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Results
### Total number of reviews
- Vine reviews

![Vine reviews](https://user-images.githubusercontent.com/90746609/149728532-dac7bb30-a138-4042-b687-172d851092e3.jpg)


- Non Vine reviews

![Non-Vine reviews](https://user-images.githubusercontent.com/90746609/149728711-38870b9e-a1c4-4084-b36d-e946d6bf2264.jpg)


### Total number of 5-star reviews
-Vine reviews

![Vine reviews5](https://user-images.githubusercontent.com/90746609/149728569-8cf928ad-0ed9-4e3a-ad7c-8ee8c8fd2e21.jpg)

-Non Vine reviews
![non Vine reviews 5](https://user-images.githubusercontent.com/90746609/149728681-5e39b2a4-5a30-4f2e-96a5-fe925f177d1c.jpg)


### Percentage of 5-star reviews
-Vine reviews

![Vine reviews percemtage](https://user-images.githubusercontent.com/90746609/149728620-ea0dde62-1f51-47af-a0c2-c64bc41688d8.jpg)


-Non Vine reviews

![nonVine reviewspercantage](https://user-images.githubusercontent.com/90746609/149728662-ae0a4891-798b-4ae0-aba8-6cd58ece72b8.jpg)


## Summary
### 51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
