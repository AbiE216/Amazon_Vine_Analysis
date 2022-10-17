# Amazon_Vine_Analysis
## Overview 
This project was intended to examine reviews from amazon, perform ETL through Google Colab, gain familiarity with Amazon Web Servers and moving data between these into PostgreSQL.
### Purpose
To examine Amazon reviews to determine if there is a difference between paid reviews and non-paid reviews, both in comparison to the total number of reviews and the total number of 5 star reviews. 

## Results
1 a. The total number of Vine reviews: 285
  b. The total number of Non-Vine reviews: 31,545
2 a. Vine reviews that were 5 stars: 163
  b. Non-Vine reviews that were 5 stars: 14,614
3 a. Percentage of Vine reviews that were 5 stars: 1.1%
  b. Percentage of Non-Vine reviews that are 5 stars: 98.9%
  
## Reviews 
From these numbers, with 285 total vine reviews, and 163 of them being 5 stars, this would be 57% of Vine reviews at 5 stars, compared to 14,614 5 star reviews that are non-Vine compared to a toal of 31,545 non-Vine total reviews, leaving a 46% of reviews at 5 stars. There is about a 10% difference between the two. This could very well be significant, and it linear regression could likely be applied here to truly determine how much of an effect it has on it. The biggest caveat, is that the number of Vine reviews is pretty minimal compared to total reviews so the skew might be significantly less. The way to determine this, would be an additional test to see if certain products are more likely to have vine reviews, if so the skew is likely more pronounced on those items, compared to the others. 
