# Amazon_Vine_Analysis

## Overview

This analysis examines Amazon reviews written by members of the paid Amazon Vine program and compares them to reviews left by non-members of the program. Using big data sets I examined real-life reviews of Toys left on Amazon. I used Pyspark to perform ETL, connected to an AWS RDS database and loaded the data to pgadmin. Next, I used Pandas to determine bias toward favorable reviews from Vine members. 

## Results
![Screen Shot 2021-10-02 at 4 15 10 PM](https://user-images.githubusercontent.com/84756166/135730770-e1cda053-f559-40b8-878a-f0e85ef87779.png)

### Stats
* How many Vine reviews and non-Vine reviews were there?
* In total, there were 32,441 Vine sponsored reviews and and 38,033 non sponsored reviews.

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* 14,551 Vine-sponsored 5-star reviews
* 16,734 non-sponsored 5-star reviews

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* Vine-sponsored = ~45%
* non-sponsored = ~44%


## Summary 
<img width="995" alt="Screen Shot 2021-10-02 at 4 23 40 PM" src="https://user-images.githubusercontent.com/84756166/135730865-98713e11-29dd-45d0-b1d2-c0712caf2c18.png">

<img width="1006" alt="Screen Shot 2021-10-02 at 4 23 46 PM" src="https://user-images.githubusercontent.com/84756166/135730866-d06b3383-005d-44a5-b54e-9016788b552e.png">

There is no positivity bias found for Vine sponsored reviews. The data comparison shows a similar population of reviews for Vine and non-Vine reviews, as well as a similar percentage of review positivity. Vine sponsored reviews score just one percent higher than non-Vine reviews for positivity ratio. 

### Additional Testing
Additionally, I could find the aggregate average star-rating of both vine-sponsered and non-sponsored reviews and compare the results.
