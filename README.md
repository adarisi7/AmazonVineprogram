# AmazonVineprogram

## Background
The purpose of this analysis was to extract an amazon dataset and analyze Amazon reviews written by members of the paid Amazon Vine program. Then I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in my dataset.

### Analysis
There were 261 vine reviews and 24040 non-vine reviews. There were 373988 five-star reviews and 292652 were paid and 81336 were unpaid. The percentage of five-star reviews is 52.98113442765081% and the percentage of non-five star reviews is 47.01886557234919%. 

#### Summary
There is definitely a positivity bias towards ratings. The big reason for this is because there are more five-star reviews in the entire dataset then there are not, at it is above 50%. Furthermore, most of these five-star reviews were paid, as it was 292652 out of 373988 which is 78%, so close to 80% of these reviewers are paid! Pandas can also be used to conduct this analysis. 

