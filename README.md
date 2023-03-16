# Amazon_Vine_Analysis

## Overview
This project involved using Google CoLab, AWS, and SQL in order to analyze a set of data from Amazon Reviews from the Amazon Vine program.  I chose to use the "Movies" dataset to base my analysis on. This dataset was uploaded and transformed.  Four new data frames were created and then uploaded into SQL. 

## Results
After transforming my data, I created four new data frames and uploaded them into SQL, as shown below:

Customers Table:

![customers](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/customers.png)

Products Table:

![products](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/products.png)

Reviews Table:

![reviews](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/reviews.png)

Vine Table:

![vine](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/vine.png)

Questions:
**-How many Vine reviews and non-Vine reviews were there?**

Surpisingly, with the dataset I chose to use, there were no vine reviews.

![no vine](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/no_vine.png)

There were 380604 reviews that were not with vine.

![vinereviews](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/vine_review.png)

**-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

When filtering among verified purchases, I found that 2288 verified purchases were 5 stars and 10043 non-verfied purchases wer 5 stars.

**-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**

When filtering using "verified purchase" I saw that 64% of verified purchases were 5-stars.

![paid](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/verified.png)

Additionally, 60% of nonverified purchases were 5 stars.

![not_paid](https://github.com/heatherhutchinson211/Amazon_Vine_Analysis/blob/main/not%20verified.png)

## Summary

Since my dataset did not have any vine reviews it is hard to say whether or not vine reviews would be biased.  However, if I were to chose a different dataset, I could further my analysis by comparing items with and without vine reviews to the helpful votes count. 
