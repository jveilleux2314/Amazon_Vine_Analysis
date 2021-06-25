# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program:

I evaluated a set of data pertaining to Amazon reviews of Digital Ebooks purchased. 

### Purpose

The purpose of this was to see how many helpful reviews are genuine or based off the Vine program that pays customers to leave 5 star reviews. 

## Process

- [x] Here I seperated the ebooks that have over 20 reviews from the rest.

<img width="807" alt="over 20 votes" src="https://user-images.githubusercontent.com/78769464/123469348-8e1e9600-d5b8-11eb-9eb3-7a1a242d206b.png">

- [x] The helpful votes and the total votes were used to calculate the percentage of helpful votes.

<img width="804" alt="Helpful Percent" src="https://user-images.githubusercontent.com/78769464/123469367-9545a400-d5b8-11eb-98cf-60da06cd2ecb.png">


- [x] I filtered the dataset to only view the ebooks with 50% and over helpful reviews.

<img width="806" alt="over 50%" src="https://user-images.githubusercontent.com/78769464/123469381-98d92b00-d5b8-11eb-98b1-5e027e2c4ca5.png">

- [x] Finally - I compared the over 50% helpful reviews table to the amount of Vine program Ebooks (customers that were paid for their reviews vs those who were not)

<img width="886" alt="Y vs N - VINE" src="https://user-images.githubusercontent.com/78769464/123469751-13a24600-d5b9-11eb-8128-b1fe84846e60.png">


## Results:

- **How many Vine reviews and non-Vine reviews were there?**

There were no Vine reviews in my set of Ebook purchases- with a total of 65,149 reviews over 50% voted helpful.

- **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

There were 24,673 reviews that were non-Vine 5 star reviews.

- **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**

38% of non-Vine reviews were 5 star reviews.


## Summary:

Based on the numbers caluculated I would say there is no bias based off the Vine program, considering none of the reviews over 50% voted helpful were actually paid to leave the review. With further evaluation - I beleive evaluating the verified purchases over the total would be more accurate. 


<img width="779" alt="verified 5 star" src="https://user-images.githubusercontent.com/78769464/123470839-8fe95900-d5ba-11eb-9dc4-533107d62bd1.png">

16,231 out of 45,482 verified purchases were 5 star reviews - Although this is not a huge difference from the 38% calcuated previously, I do beleive at 36% - it is more accurate. 
