# Amazon_Vine_Analysis
## Overview

In this project, analyzing “Shoes” dataset of Amazon reviews written by members of the paid Amazon Vine program and examining if there is any bias toward favorable reviews from Vine members in our dataset using PySpark to perform the ETL process, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

## Result
•	Total of 1088895 reviews (where there are 20 or more total votes) were analyzed and 594035 were five-star reviews.

![plot](“images/total_and_total5star.png”)

•	439 reviews were Vine reviews and rest 1078456 were Non-Vine reviews.

![plot](“images/vine_non_vine.png”)

From total of 594035 five-star reviews 
•	221 were paid five-star reviews which is 0.04% of total reviews. 
•	593814 were unpaid five-star reviews which is 99.96% of total reviews. 

![plot](“images/five_star_review_percentage.png”)
 
## Summary: 
Analysis indicates that there might be positivity bias for reviews in the vine program. (221 of 439 paid reviews were five-star reviews.)
One additional analysis that we could conduct is to include all data rather than focusing on data with 20 or more total votes. I suspect that excluding the portion of data will not provide accurate insight into biases of being within this program. 


