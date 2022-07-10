# Amazon_Vine_Analysis
## Background
Using PySpark, perform the ETL process to extract an Amazon reviews dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, using PySpark determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Results
* There were 35 Vine reviews and 4957 non-Vine reviews.
* 18 of the Vine reviews were rated 5 stars. 1963 of the non-Vine reviews were 5-star reviews.
* 51% percentage of Vine reviews are 5-star. 40% percentage of non-Vine reviews are 5-star.

![Screen Shot 2022-07-09 at 10 17 36 PM](https://user-images.githubusercontent.com/101379969/178132326-b9e13e4a-53c2-423e-88a5-cc53ca1c1d25.png)
![Screen Shot 2022-07-09 at 10 17 23 PM](https://user-images.githubusercontent.com/101379969/178132322-210fee37-7f90-4870-8ed0-39f8abbb7e52.png)

## Summary
Comparing the percentages for Vine and non-Vine reviews, we see that Vine reviews are more likely to be given a 5-star review. The increased likelihood that a Vine review will give a 5-star review shows that there is a positive bias for reviews in the Vine program. An additional analysis we can make is to confirm if the trend continues with 4-star reviews or, if Vine or non-vine 5-star reviews resulted in more 'helpful review' votes to potentiall show if the review influenced shoppers.
