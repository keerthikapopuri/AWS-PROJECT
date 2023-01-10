## AWS-PROJECT
#This project deploys AWS management to send a notified email to everyone in a respected group when a new file is uploaded into the bucket.

Step 1: Create a AWS account<br>
Step 2: Create a AWS S3 bucket with any specified name. I used here testinglambdasesproject<br>
Step 3: Create an IAM role with any name u desire. I used here is lambdasestesting. Add permissions of fullses acess,fulls3 acess,fullcloudwatch acess<br>
Step 4: Create Lambda Function. Name:lambdasestesting with python 3.9 and mapped the IAM role with this.<br>
Step 5: Now we are going to add trigger for the function specified. We are adding trigger of S3 bucket.<br>
Step 6: Then analyse the code here. Here we use boto3 module and give the respective mail id's and customize the body of the mail.<br>
Step 7: Before deploying the code, We first validate the email adress specified in code using Amazon SES.<br>
Step 8: Now, deploy the code and go to s3 bucket. Now, upload any dataset.<br>
Step 9: Go to the mail box and check the mail. u can also open cloudwatch and check the progress there.<br>

##THANK YOU FOR READING :)
