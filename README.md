# Amazon_Vine_Analysis

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

![customers_table](https://user-images.githubusercontent.com/95668609/166179202-365df257-bf76-4847-b7a0-b1528751d3af.png)

![products_table](https://user-images.githubusercontent.com/95668609/166179208-f3a44b94-e043-4e12-b605-1630b48e224f.png)

![review_id_table](https://user-images.githubusercontent.com/95668609/166179217-c677511d-6fdf-4d12-b340-a0ecf52252e4.png)

![vine_table](https://user-images.githubusercontent.com/95668609/166179226-4d11fd34-99b0-45cc-a5c2-8ae0e8488cdd.png)


1. How many Vine reviews and non-Vine reviews were there?

There are 9,454 vine reviews.

* Image1
![Image#1](https://user-images.githubusercontent.com/95668609/166179238-91ad7b82-1725-4d3a-9056-64b678a24b0c.png)


There are 28,467 no vine reviews.

* Image2
![Image#2](https://user-images.githubusercontent.com/95668609/166179252-fbb7ef73-b599-41d0-926f-5b51f8627ae4.png)


2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There are 3,607 5 stars vine reviews and 11,141 5 stars no vine reviews.

* Image3
![Image#3](https://user-images.githubusercontent.com/95668609/166179256-48f834bc-5f35-41c4-a6b7-d4c85a2a268d.png)


3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The percentage of reviews of 5 stars vine reviews is 61.69% and the percentage of 5 star no vine reviews is 64.3%.

* Image3
![Image#3](https://user-images.githubusercontent.com/95668609/166179263-f2be1ea5-cd3a-446f-9cff-9acf1e0d443b.png)


## Summary: 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

Reviwing the results we can see that the percentage for 5 stars vine reviews and 5 stars no vine reviews are pretty close. 
The difference between those is of only 2.61%, so we can state the there is no differece. 
I then conclude there is no positive bias for any type of reviews.
Further analisys is needed in order to figure out any bias, like performing the same analysis but for 4 stars, 3 stars, 2 stars and even 1 star reviews.

