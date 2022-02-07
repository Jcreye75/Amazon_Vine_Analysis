# Amazon_Vine_Analysis

## Overview of the analysis:
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## What Its being Created
This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis

## Resources
- Software: Git version 2.33.0.windows.2, Visual Studio 1.62.2, Google Colab Notebook, PgAdmin 4 5.7

## Deliverable 1

1. The Database for the Challenge was created:

![1_0_Database](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/1_0_Database.png)

2. The Database crewated uoin AWS, was connected to PgAdmin

![1_1_DB2Pgadmin](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/1_1_DB2Pgadmin.png)

3. Using Google Colan Notebook, the.ipynb file was created to execute the code on it.
![1_2_ColabR2U](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/1_2_ColabR2U.png)

4. Four tables were created on PgAdmin

![2_0_Query2Tables](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/2_0_Query2Tables.png)

5. From the selected Amazon DB (Video Games), customers Dataframe was created with the columns needed.

![2_1_Customers](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/2_1_Customers.png)

6. From the selected Amazon DB (Video Games), products Dataframe was created with the columns needed.

![2_2_Products](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/2_2_Products.png)

7. From the selected Amazon DB (Video Games), review id Dataframe was created with the columns needed.

![2_3_Reviewid](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/2_3_Reviewid.png)

8. From the selected Amazon DB (Video Games), vine Dataframe was created with the columns needed.

![2_4_Vine](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/2_4_Vine.png)

9. Customer dataframe loaded into the appropiate pgAdmin table

![3_1_Customers_Table](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_1_Customers_Table.png)

10. Products dataframe loaded into the appropiate pgAdmin table

![3_2_Products_Table](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_2_Products_Table.png)

11. Review id dataframe loaded into the appropiate pgAdmin table

![3_3_Reviewid_Table](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_3_Reviewid_Table.png)

12. Vine dataframe loaded into the appropiate pgAdmin table

![3_4_Vine_Table](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

## Deliverable 2
1. DataFrame was created for the vine_table data using PySpark method.

![D2_0_Dataframe](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

2. The data is filtered to create a DataFrame where there are 20 or more total votes.

![D2_1_DFfilteredg20](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

3. The data is filtered to create a DataFrame where the percentage of helpful_votes is equal to or greater than 50%.

![D2_2_DFfilteredg50P](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

4. The data is filtered to create a DataFrame where there is a Vine review. 

![D2_3_DFfilteredPaid](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

5. The data is filtered to create a DataFrame where there isn’t a Vine review.

![D2_4_DFfilteredunPaid](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

6. The total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews are calculated for all Vine and non-Vine reviews.
![D2_5_PaidunPaid](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

## Deliverable 3

### Overview of the analysis: 

The analysis is done to practice the following:
- Define big data and describe the challenges associated with it.
- Define Hadoop and name the main elements of its ecosystem.
- Explain how MapReduce processes data.
- Define Spark and explain how it processes data.
- Describe how NLP collects and analyzes text data.
- Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
- Complete an analysis of an Amazon customer review.

Using the Amazon Video games data, and objectives above, what found is the following:

### Results

- How many Vine reviews and non-Vine reviews were there?

![D3_1](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

- How many Vine reviews were 5 stars?

![D3_2](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

- How many non-Vine reviews were 5 stars?

![D3_3](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

- What percentage of Vine reviews were 5 stars? 

![D3_4](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)

- What percentage of non-Vine reviews were 5 stars?

![D3_5](https://github.com/Jcreye75/Amazon_Vine_Analysis/blob/9771894c4e2aa76bd68708ffa376fcfbf7040ba5/Resources/3_4_Vine_Table.png)


### Summary: 

Paid 5-stars Vine reviews represent the 50%. Unpaid 5stars reviews represent 30%, therefre both whos that data are biased.



