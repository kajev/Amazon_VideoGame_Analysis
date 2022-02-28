# Amazon_Vine_Analysis
Using AWS and Pgadmin4 to do an analysis on vine data

## Objective of this analysis:
#### Deliverable 1: Perform ETL on Amazon Product Reviews
  - Using your knowledge of the cloud ETL process, you’ll create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets (Links to an external site.), and extract the dataset into a DataFrame. You'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, you'll upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.
#### Deliverable 2: Determine Bias of Vine Reviews
  - Using your knowledge of PySpark, Pandas, or SQL, you’ll determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, you'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews
#### Overall, the end goal is to perform ETL on data and then deterine if paying for a Vine review increases your 5-star review.

### Results
  - Why do so many programs decide to not pay for reviews when it seems helpful overall?
  - There is an increase of about 13% more 5-star ratings
  - Do they actually get more visitors after paying for program reviews
### Summary
  - There is significant bias as the paid reviews only account for 0.2% of all programs( vine_number / vine_number + no_vine_number)
