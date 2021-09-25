# Amazon_Vine_Analysis
## Overview of the analysis:
To analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
## Results:

### Perform ETL on Amazon Product Reviews

 In cloud ETL process,  an AWS RDS database is created with tables in pgAdmin and the dataset is extracted into a DataFrame and transformed into four separate DataFrames that match the table schema in pgAdmin. Data is uploaded  into the appropriate tables and queries are run in pgAdmin to confirm that the data has been uploaded.
![summary](https://user-images.githubusercontent.com/84524153/134749273-e873d01e-22e7-4fbe-9f9b-ba4e8a25d971.png)

#### Customers table
![customer](https://user-images.githubusercontent.com/84524153/134749289-a2d358c2-cbde-41ba-999f-c7117e0e91cd.png)

![customer1](https://user-images.githubusercontent.com/84524153/134749291-2cffd8ef-d8d2-4514-b7f8-fbfdad8817a8.png)

#### Products table
![products](https://user-images.githubusercontent.com/84524153/134749296-5954b1b6-2ddd-48e4-bba6-9273600eb867.png)

![products1](https://user-images.githubusercontent.com/84524153/134749298-2a391f03-31b0-46fb-ac2c-de9c45fcc209.png)

#### Review Id table
![review_id](https://user-images.githubusercontent.com/84524153/134749312-35c25222-849b-4de5-aa73-3248f777d487.png)

![review_id1](https://user-images.githubusercontent.com/84524153/134749315-5f7c51ad-af14-4c26-8e2d-50f027f7db27.png)

#### Vine table
![vine_table](https://user-images.githubusercontent.com/84524153/134749323-15db4c43-995b-43a7-9268-1d0d47781227.png)

![vine_table1](https://user-images.githubusercontent.com/84524153/134749328-da772e1c-04ab-4a56-8fac-f2acca71a014.png)


### Determine Bias of Vine Reviews
![review](https://user-images.githubusercontent.com/84524153/134742201-d8489892-c3a5-482e-b5ca-81cd98d3efdd.png) 

##### - How many Vine reviews and non-Vine reviews were there?

![totalcount](https://user-images.githubusercontent.com/84524153/134751145-fa0a3f43-6cde-4c38-baa1-a949dcf1f24b.png)

##### - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![5star](https://user-images.githubusercontent.com/84524153/134751383-8b9143f6-a1af-4972-879d-7a256667134b.png)

##### - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![percentage](https://user-images.githubusercontent.com/84524153/134751019-17725bd7-1f11-430d-9639-71090b44ec43.png)

## Summary: 
##### Vine reviews (Paid) and non-Vine reviews (Unpaid)
![vine](https://user-images.githubusercontent.com/84524153/134742213-e7b61c40-b696-4f9b-8ea1-6b8594159980.png)

There is negligible percentage of vine reviews and so it is safe to say there is no bias towards reviews and having a paid Vine reviews makes almost no difference in the percentage of 5-star reviews.

- Additional analysis
