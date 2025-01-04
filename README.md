# Netflix_Analysis_Quicksight
This is a documentation of the dashboard that I have prepared with the help of Quicksight a Business Intelligence tool provided by AWS

# Steps for creating a dashboard using AWS Quicksight
  1. Create an AWS Account, If you already have an account, log into the account. (**Remember not to use the root account, Always go with the least privileges)
  2. We will upload the netlfix_title.csv and manifest.json to the S3 Bucket. (**Provide a unique name to the S3 Bucket as AWS searches the name globally)
     ![image](https://github.com/user-attachments/assets/39570f1f-8c3a-4782-8b9e-f750bc1e3523)
  3. Now we will create an account with AWS Quicksight.
  4.
     (I) Click on New Analysis --> Dataset --> Upload the .csv file (** This is one of the methods)\
    (II) Click on New Analysis --> S3 Bucket --> Write the dataset name and add the URI of the mainfest.json we uploaded in the s3 bucket or the manifest.json.
  5. After the dataset has been added, you have been provided with the dashboard creation window, try playing with the data and create the charts and graphs as required.

![image](https://github.com/user-attachments/assets/03a37dc0-617f-4ac3-a9de-25484587eb6d)


