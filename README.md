# Amazon_Vine_Analysis
module 17

## Project Overview
### Purpose
The purpose of my analysis is to determine if there is any positivty bias in the reviews of Amazon's Vine program.
### Process
* I Extracted an Amazon Review dataset for watches, transformed the dataset into 4 DataFrames that I then loaded into their respective tables in pdAdmin.

(insert table images)

* I then exported the vine_table that contained the data for the reviews to a csv file so I could perform analysis of Amazon's Vine Program.   

(vine_df image)



## Results
### Evaluation of Vine and Non Vine Reviews for watches

* There are 47 total Vine reviews. 

 
* There are 8362 non-Vine reviews.



* There are 15 Vine reviews with 5 stars.



* There are 4332 non-Vine reviews with 5 stars.



* 31.91% of the Vine reviews were 5 stars.


 
* 51.81% of the non-Vine reviews were 5 stars.

(images)

## Summary
### Evaluation of Bias
According to the analyzed data, the Vine program does not have any positivity bias.  This is because the percentage of non-Vine 5 star reviews (51.81%) is much higher than the percentage of Vine 5 star reviews (31.91%).  If there was a positivity bias for the Vine program, we would expect to see a higher percentage of Vine 5 star reviews.  

### Additional Analysis
One additional analysis we could do to further evaluate the positivity bias would be to analyze the 1 star reviews for both Vine and non-Vine reviews.  If there was a positivity bias, the Vine reviewers would be less likely to give the lowest review.  


