# Amazon_Vine_Analysis

## Overview of the analysis: 

The purpose of this analysis is to determine if there is a bias amongst Amazon Vine memebers reviewing office products.  The tools used are PySpark, AWS, and Postgres.

## Results: 

### How many Vine reviews and non-Vine reviews were there?

- 969 reviews were from Vine members
- 43,745 reviews were not from Vine members

![image](https://user-images.githubusercontent.com/80642682/128655191-05d14759-d22a-4263-97fd-77d1afaa0876.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- Out of  969 reviews from Vine members, there are 430 5-star reviews
- Out of the 43,745 reviews not from Vine members, there are 19,233 5-star reviews

![image](https://user-images.githubusercontent.com/80642682/128655451-6ebfc4d2-6bf9-4c9c-b726-d60823cdc058.png)

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- About 44% of reviews by Vine members were 5 stars
- About 44% of reviews by non-Vine members were 5 stars

![image](https://user-images.githubusercontent.com/80642682/128655553-7c7b5552-d2d6-488d-bbf7-fa2e4356f430.png)


## Summary: 

When comparing the percentage of reviews that are 5 stars from Vine members to non-Vine members, it can be concluded that there is no bias.  The percentages are approximately the same.  To further investigate if there is any bias is to see how 1 star reviews from Vine members compare to non-Vine members.
