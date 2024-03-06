# AWS-Snowflake-integration-project

Firstly make the file ready by cleanisng and making basic transformations using AWS tools( I used lambda and glue) and put it in the S3 bucket. Didn't mention this step as the main focus of this project is to integrate AWS with Snowflake
This project is a simple integration of aws and snowflake

step 1 :  create an AWS bucket

step 2 :  create a role choosing AWS service as role type and Use case category as Snowflake

step 3 :  give following permissoions "AmazonS3ReadOnlyAccess", review and create role

step 4 :  create storage integration following the queries file and give STORAGE_AWS_ROLE_ARN

step 5 :  Give STORAGE_AWS_IAM_USER_ARN and STORAGE_AWS_EXTERNAL_ID in Trust relationships

step 6 :  Create external stage in Snowflake following the queries file

step 7 :  Copy Data from external stage(S3) to Snowflake

step 8 :  Visualize the data from the Snowflake Dashboards option by writing queries samples provided in queries file

