# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program, which is a service that allows manufacturers and publishers to receive reviews for their products.
We use PySpark to perform the ETL process to extract a dataset that contains reviews of a specific product transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in our dataset.
The dataset analyzed in this challenge is reviews on Sports.

## Results
<img width="931" alt="Vine reviews" src="https://user-images.githubusercontent.com/77806210/192631454-608ba425-8d65-4803-8e21-08e1a94d250d.png">

- How many Vine reviews and non-Vine reviews were there?
Members of the paid Amazon Vine program are 334 and members of the non-paid amazon program are 61589. 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
As we can see in the total_5_Star-Reviews column, we can see that 139 vine reviews members were 5 stars and 32660 non-Vine reviews members were 5 stars
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
As we can see in the %_5_Star_To_Total, 41.62% of Vine reviews members were 5 stars and 53.03% of Non-vine reviews members were 5 stars. 

## Summary
There is no positivity bias for reviews in the Vine program.

As we can see from the ratings, 41.62% of Vine member reviews were 5 stars and 53.03% of non-Vine member reviews were 5 stars. Vine members have less 5 star reviews than non Vine members. We can say that Vine members are more critical when they review their products. 
In addition, we can analyze how much Vine members and non-Vine members spend on their product. 
