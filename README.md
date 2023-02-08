# Amazon_Vine_Analysis
module 17

## Project Overview
### Purpose
The purpose of my analysis is to determine if there is any positivity bias in the reviews of Amazon's Vine program.
### Process
* I Extracted an Amazon Review dataset for watches, transformed the dataset into 4 DataFrames that I then loaded into their respective tables in pdAdmin.

  * Customers Table:
   
![customers_table](https://user-images.githubusercontent.com/115426070/217675969-de175b5c-61b4-4527-a619-cbc047a68d58.png)

  * Products Table:

![products_table](https://user-images.githubusercontent.com/115426070/217676002-33acebb8-f683-41d9-a574-374ed0de6a95.png)

  * Review ID Table:
  
![review_id_table](https://user-images.githubusercontent.com/115426070/217676027-edf6fe54-65ef-46be-bcf6-ae094c6d3212.png)

  * Vine Table:
  
![vine_table](https://user-images.githubusercontent.com/115426070/217676065-e7b3d9e1-de11-42e2-b738-7fa396be9d59.png)

* I then exported the vine_table that contained the data for the reviews to a csv file so I could convert it to a DataFrame and use that to perform analysis of Amazon's Vine Program.   
![vine_df](https://user-images.githubusercontent.com/115426070/217676116-2bbad509-3230-4f56-a506-b4942070c2cc.png)


## Results
### Evaluation of Vine and Non Vine Reviews for watches

* There are 47 total Vine reviews. 

![total_vine](https://user-images.githubusercontent.com/115426070/217676165-de8bdb64-8c60-4719-bd48-3328248c670d.png)

 
* There are 8362 total non-Vine reviews.

![total_non_vine](https://user-images.githubusercontent.com/115426070/217676226-451f4693-a187-4042-a07d-c4d912662c2e.png)


* There are 15 Vine reviews with 5 stars.

![vine_5star](https://user-images.githubusercontent.com/115426070/217676266-e07d4cff-a153-43de-8758-5ca2af0a67ef.png)


* There are 4332 non-Vine reviews with 5 stars.


![non_vine_5star](https://user-images.githubusercontent.com/115426070/217676283-d9fb6bf0-f654-449f-b56e-7335ba41446e.png)

* 31.91% of the Vine reviews were 5 stars.


 ![vine_percentage](https://user-images.githubusercontent.com/115426070/217676290-4c3a0e7c-f3a5-427b-acd4-d2bc2ac5e514.png)

* 51.81% of the non-Vine reviews were 5 stars.


![non_vine_percentage](https://user-images.githubusercontent.com/115426070/217676307-b8931e8f-957b-4174-9ff3-6f14ef0f76a3.png)

## Summary
### Evaluation of Bias
According to the analyzed data, the Vine program does not have any positivity bias.  This is because the percentage of non-Vine 5 star reviews (51.81%) is much higher than the percentage of Vine 5 star reviews (31.91%).  If there was a positivity bias for the Vine program, we would expect to see a higher percentage of Vine 5 star reviews.  

### Additional Analysis
One additional analysis we could do to further evaluate the positivity bias would be to analyze the 1 star reviews for both Vine and non-Vine reviews.  If there was a positivity bias, the Vine reviewers would be less likely to give the lowest review.  


