# Amazon Vine Analysis

## Overview
This analysis uses Amazon S3 data containing 4864249 reviews of products in the "toys" category on Amazon Shopping. This data has been manipulated with Spark and Google Colaboratory to gain insights on the difference in rating behavior between users that participate in the Vine program, and those who do not.

## Results

![image](https://user-images.githubusercontent.com/93882635/160252098-04892b7a-f787-404e-94d1-c8aa5d1bfc8f.png)

After filtering for reviews with 20 or more votes, and at least 50% helpful votes, the dataframe contained 1266 Vine reviews and 62026 non-vine reviews.
Out of the Vine reviews, 432 had a five star rating, which equals 34% of the Vine reviews. Out of the non-Vine reviews, 29982 had a five star rating, which equals 48% of the non-Vine reviews.

## Summary
Based on the data chosen for this assignment, it seems that users of the Vine program are less likely to give a product a rating of five stars.

It would be interesting to also look at the percentages of one star reviews left by Vine and non-Vine users. This would provide insight on whether the diffence in voting behavior is limited to five star reviews, or whether there is a larger degree of polarization among non-Vine users compared to Vine users.
