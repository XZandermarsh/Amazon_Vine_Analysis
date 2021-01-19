# Amazon_Vine_Analysis
## Overview
* This analysis was performed to evaluate if the number of 5 star reviews on Amazon products is higher for paid vine users compared to unpaid users. This would indicate a bias in those reviews thay may need to be taken into account. This analysis was applied specifically to the "Furniture" category of Amazon reviews.

## Results
### How many Vine reviews and non-Vine reviews were there?
* After filtering out the reviews with low total votes (<20) or generally unhelpful (<50% helpful votes), there were 136 Vine reviews, and 18019 non-Vine reviews for the "Furniture" category.

![alt text](https://github.com/XZandermarsh/Amazon_Vine_Analysis/blob/main/paid_vine_df_Screenshot.png "Vine reviews")
![alt text](https://github.com/XZandermarsh/Amazon_Vine_Analysis/blob/main/unpaid_vine_df_Screenshot.png "non-Vine reviews")

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* Of the 136 Vine reviews, 74 were 5-star. Of the 18019 non-Vine reviews, 8482 were 5-star.

### What percentage of vine reviews were 5-stars? What percentage of non-Vine reviews were 5-stars?
* 5-star review percentage was 54.4% for Vine reviews, but only 47.1% for non-Vine reviews.

![alt text](https://github.com/XZandermarsh/Amazon_Vine_Analysis/blob/main/analysis_Screenshot.png "Analysis")

## Summary
* In the furniture category, it is clear that there is a positive bias for reviews in the Vine program, since there is a significantly higher percentage of 5-star reviews when compared to reviews from non-Vine users. An additional analysis could be performed to compare the percentage of "low" review scores for Vine reviews and non-Vine reviews (<=2 stars).
