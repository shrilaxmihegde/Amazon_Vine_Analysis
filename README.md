# Amazon_Vine_Analysis

# Overview of the analysis:

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
Companies that will pay a fee to Amazon and may provide free products to Vine  In order to determine if there is any bias towards favorable reviews from Vine members vs. non-members, we need to identify the percentage of 5 star ratings to total rating. As part of this exercise, we were asked to choose from 50 datasets to extract, transform and load into a dataframe in order to complete our analysis. Throughout this analysis, we use:
 This datasets and use ***PySpark*** to perform the ***ETL*** process to extract the dataset, transform the data, connect to an *** AWS***  ***RDS*** instance, and load the transformed data into pgAdmin.

# Purpose :

1. Define big data and describe the challenges associated with it.

2. Define Hadoop and name the main elements of its ecosystem.

3. Explain how MapReduce processes data.

4. Define Spark and explain how it processes data.

5. Describe how NLP collects and analyzes text data.

6. Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.

7. Complete an analysis of an Amazon customer review.

# Results :
1. How many Vine reviews and non-Vine reviews were there?

   a. Total number of vine( paid) reviews - 969.

![Totalpaidreviews)](/Resources/Total_paid_reviews.png) 

    
   b. Total non-vine (unpaid) reviews - 43,745

![Totalunpaidreviews)](/Resources/Total_unpaid_reviews.png) 

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

   a. Total vine reviews  430 of 5 star.
 
![Lottest)](/Resources/paid_5_star_reviews.png)

   b. Non vine reviews of 5 star - 19,233

![Unpaid_fivestar)](/Resources/Unpaid_fivestar.png) 

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

   a.Total percentage of vine reviews were 5 star - 44.3 %

![percentage_paid_reviews)](/Resources/percentage_paid_reviews.png)


   b. Non-Vine  reviews were 5 star - 43.97%.

![unpaid_percentage)](/Resources/unpaid_percentage.png)
 
# Summary :

1. Totally 44.3% of paid memebers gave 5 star rating and 43.9% non paid members gave 5 star rating in their reviews. As both the data points are very close to each other, it do not look like there is any positivity bias for reviews in the Vine program.

2. We can perform this same analysis on whole data set. Because, in some cases, review readers may not vote it as helpful or unhelpful. So, if cover them as well, then we get a bigger sample of data set. Ofcourse, it can skew the results. But it is worth a shot to take.




