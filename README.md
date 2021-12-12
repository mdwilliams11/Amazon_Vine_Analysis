# Amazon_Vine_Analysis
Module 16 AWS ETL

## Overview of Analysis
In this module I used PySpark within Google Colaboratory to retrieve data from AWS and analyze the Amazon Vine program. The Vine program pays customers a small amount to write reviews for a product that they purchased. Using a dataset of over 3 million reviews on electronics sold on Amazon I analyzed the proportion of 5-star reviews among both Vine reviews and non-Vine reviews to see if the payment had any noticable affect on how highly a product was rated. 


## Results

 How many Vine reviews and non-Vine reviews were there?
* 3093869 total reviews, 58554 reviews with 20 or more total votes on it, and 50753 reviews with 20+ votes that are more than 50% helpful
* Of those 50753 reviews, 1080 were Vine reviews and 49673 were non-Vine reviews

 How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* 545 5-Star Vine reviews
* 23043 5-Star non-Vine reviews

 What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* % of 5-star reviews for vine: 42.04%
* % of 5-star reviews for non-vine: 46.39%


Here are the 4 tables from pgAdmin
![Any_title](https://raw.githubusercontent.com/mdwilliams11/Amazon_Vine_Analysis/main/image_name.png)

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Amazon_Vine_Analysis/main/image_name.png)

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Amazon_Vine_Analysis/main/image_name.png)

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Amazon_Vine_Analysis/main/image_name.png)


## Summary
The proportion of 5-star reviews for Vine reviewers is slightly lower than that of the non-Vine reviewers. Vine reviewers don't appear incentivized to leave better reviews than their non-Vine counterparts. In fact, the lower proportions of 5-star reviews might indicate that the Vine program has a negative affect on reviews.

