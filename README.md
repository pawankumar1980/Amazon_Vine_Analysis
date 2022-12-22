# Amazon_Vine_Analysis

## Project Overview

In this project, we analyze the Amazon Vine program for US Video Games data and tried to determine if there is a bias toward favourable reviews from Vine members.

The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

## Results

<img width="1440" alt="Screen Shot 2022-12-22 at 00 07 14" src="https://user-images.githubusercontent.com/111800568/209061504-55c5ebd4-3b67-499c-92e5-f5a0202e54c8.png">

 - There were a total of 94 Vine reviews.
 - There were a total of 40,471 non-Vine reviews.
 - There were a total of 48 Vine 5-star reviews.
 - There were a total of 15,663 non-Vine 5-star reviews.
 - 51% of the Vine reviews were 5-star.
 - 38.7% of the non-Vine reviews were 5-star.

## Summary

In conclusion, the vine program is not worth it for the video game category. As can be seen, only a few helpful reviews made part of it (a total of 94), and only around half were 5-star rated (51%). Like the unpaid reviews, less than 40% were 5-star rated (38.7%). Even though the percentages may be misleading as the volume of reviews in the vine and non-vine programs vary, this is a sign that the vine program is not very popular in this category. We might not want to pay for it as it does not incentivize people to write better reviews.

The above information suggests that customers do not feel a positivity bias for leaving good reviews in the paid program as there are so few and not so many well-rated. Nevertheless, if we analyze further, we could calculate the mean of the star ratings on each program's reviews to see if there is a significant incentive.
