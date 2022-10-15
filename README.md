# Amazon_Vine_Analysis

## Overview/Purpose of Project

The Amazon Vine program is a paid service available to manufacturers and publishers that incentivises Amazon Vine members with products to provide required reviews. The task of this challenge was to analyze product reviews and investigate if the Vine program actually creates bias, granting businesses that pay for the service better reviews.

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, we’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. One of the datasets for toys is used perform ETL and load data in various tables in Postgres.

In another deliverable, performed analysis to figure out if there is bias toward favorable reviews from Vine members in dataset.

## Results Analysis and Challenges

Below are the results for the analysis performed on Deliverable 2:

![image](https://github.com/hemalis/Amazon_Vine_Analysis/blob/main/images/image.png?raw=true)

- Paid Total reviews: 1,266
- Paid 5-star reviews: 432
- Unpaid Total reviews: 61,849
- Unpaid 5-star reviews: 29,950
- % of Paid 5-star Reviews: 34.12322274881517%
- % of Unpaid 5-star Reviews: 48.42438842988569%

There are 1,266 paid reviews and 432 were 5-star reviews out of them.
There are 61,849 unpaid reviews and 29,950 out of them were 5-star.

## Summary

There is no bias visible in toys related reviews. There are ~34% 5-star reviews with Vine program compared ~48%.

There is certainly more analysis needed to come to comclusion on this.

1. Adding more data for other categories will provide more concrete analysis.
2. Adding 4-star reviews to the mix in analysis can be also helpful as paid reviewers might be giving 4-star to no have obvious bias on the reviews and get filtered by Amazon.
