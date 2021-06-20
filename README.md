# Amazon_Vine_Analysis

## Overview of Analysis
This assignment analyzes Amazon Vine program and determines if there is a bias toward favorable reviews. Analysis uses PySpark to perform ETL process to extract and transform data, connect to AWS, and load data into pgADdmin and analyze data.

## Results:
- there were 94 vine reviews and 40471 non-vine reviews
- 48 of vine reviews were 5 star
- 15663 of non-Vine reviews were 5 star
- that means 51.1% of vine reviews were 5 stars while 38.7 of non-vine reviews were 5 stars.

## Summary
There appears to be bias of paid reviews as they tend to have more 5-star ratings than non-paid reviews. Non-paid reviews may be more honest and genuine. Further analysis needs to be done to determine bias. One could offer weight 1-2-3-4-5 star reviews and determine if paid reviews tend to overrall have higher reviews than non-paid reviews, not just in 5-stars.
