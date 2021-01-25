# hackricex
Website made for HackRice X
Records information submitted by users through a form. Uses a REST API to trigger an AWS Lambda function which writes
the information to a DynamoDB table. Other Lambda functions periodically query the table and analyze the data. 
![app diagram]()
