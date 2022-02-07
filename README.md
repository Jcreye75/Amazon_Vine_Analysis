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

![1_0_Database]()

2. The Database crewated uoin AWS, was connected to PgAdmin

![1_1_DB2Pgadmin]()

3. Using Google Colan Notebook, the.ipynb file was created to execute the code on it.
![1_2_ColabR2U]()

4. Four tables were created on PgAdmin

![2_0_Query2Tables]()

5. From the selected Amazon DB (Video Games), customers Dataframe was created with the columns needed.

![2_1_Customers]()

6. From the selected Amazon DB (Video Games), products Dataframe was created with the columns needed.

![2_2_Products]()

7. From the selected Amazon DB (Video Games), review id Dataframe was created with the columns needed.

![2_3_Reviewid]()

8. From the selected Amazon DB (Video Games), vine Dataframe was created with the columns needed.

![2_4_Vine]()

9. Customer dataframe loaded into the appropiate pgAdmin table

![3_1_Customers_Table]()

10. Products dataframe loaded into the appropiate pgAdmin table

![3_2_Products_Table]()

11. Review id dataframe loaded into the appropiate pgAdmin table

![3_3_Reviewid_Table]()

12. Vine dataframe loaded into the appropiate pgAdmin table

![3_4_Vine_Table]()

