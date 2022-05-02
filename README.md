# Module 16 Challenge - Big Data
- Perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
- Use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 
- Write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Purpose: 
I need to analyze Amazon Revies on Video Games using the following link:
**https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz**
I have to figure out if there are any positive reviews bias by Amazon Vine users compared to the non-program reviews.

- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

## Results: 
pgAdming Table:



1. How many Vine reviews and non-Vine reviews were there?

There are 9,454 vine reviews.

* Image1

There are 28,467 no vine reviews.

* Image2

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There are 3,607 5 stars vine reviews and 11,141 5 stars no vine reviews.

* Image3

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The percentage of reviews of 5 stars vine reviews is 61.69% and the percentage of 5 star no vine reviews is 64.3%.

* Image3

## Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

Reviwing the results we can see that the percentage for 5 stars vine reviews and 5 stars no vine reviews are pretty close. 
The difference between those is of only 2.61%, so we can state the there is no differece. 
I then conclude there is no positive bias for any type of reviews.
Further analisys is needed in order to figure out any bias, like performing the same analysis but for 4 stars, 3 stars, 2 stars and even 1 star reviews.

