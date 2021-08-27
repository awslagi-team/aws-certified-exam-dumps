Notes: Hi all, We’re sharing AWS Developer Associate (DVA-C01) Practice Exam Part 5 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Developer Associate Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \
For GCP: https://www.gcp-examquestions.com

181. A company’s website runs on an Amazon EC2 instance and uses Auto Scaling to scale the environment during peak times. Website users across the world are experiencing high latency due to static content on the EC2 instance, even during non-peak hours. Which combination of steps will resolve the latency issue? (Choose two.)

                A. Double the Auto Scaling group’s maximum number of servers.
                B. Host the application code on AWS Lambda.
                C. Scale vertically by resizing the EC2 instances.
                D. Create an Amazon CloudFront distribution to cache the static content.
                E. Store the application’s static content in Amazon S3.

Hint Answers: D E

182. A Developer is leveraging a Border Gateway Protocol (BGP)-based AWS VPN connection to connect from on-premises to Amazon EC2 instances in the Developer’s account. The Developer is able to access an EC2 instance in subnet A, but is unable to access an EC2 instance in subnet B in the same VPC. Which logs can the Developer use to verify whether the traffic is reaching subnet B?

                A. VPN logs
                B. BGP logs
                C. VPC Flow Logs
                D. AWS CloudTrail logs

Hint Answers: C

183. A Developer has created a new AWS IAM user that has s3 putObject permission to write to a specific Amazon S3 bucket. This S3 bucket uses server-side encryption with AWS KMS managed (SSE-KMS) as the default encryption. Using the access key and secret key of the IAM user, the application received an access denied error when calling the PutObject API. How can this issue be resolved?

                A. Update the policy of the IAM user to allow the s3 Encrypt action.
                B. Update the bucket policy of the S3 bucket to allow the IAM user to upload objects.
                C. Update the policy of the IAM user to allow the kms:GenerateDataKey action.
                D. Update the ACL of the S3 bucket to allow the IAM user to upload objects.

Hint Answers: C

184. A company has a web application that uses an Amazon Cognito user pool for authentication. The company wants to create a login page with the company logo. What should a Developer do to meet these requirements?

                A. Create a hosted user interface in Amazon Cognito and customize it with the company logo.
                B. Create a login page with the company logo and upload it to Amazon Cognito.
                C. Create a login page in Amazon API Gateway with the logo and save the link in Amazon Cognito.
                D. Upload the logo to the Amazon Cognito app settings and point to the logo on a custom login page

Hint Answers: D

185. A Developer wants the ability to roll back to a previous version of an AWS Lambda function in the event of errors caused by a new deployment. How can the Developer achieve this with MINIMAL impact on users?

                A. Change the application to use an alias that points to the current version. Deploy the new version of the code. Update the alias to use the newly deployed version. If too many errors are encountered, point the alias back to the previous version.
                B. Change the application to use an alias that points to the current version. Deploy the new version of the code. Update the alias to direct 10% of users to the newly deployed version. If too many errors are encountered, send 100% of traffic to the previous version.                 C. Do not make any changes to the application. Deploy the new version of the code. If too many errors are encountered, point the application back to the previous version using the version number in the Amazon Resource Name (ARN).
                D. Create three aliases: new, existing, and router. Point the existing alias to the current version. Have the router alias direct 100% of users to the existing alias. Update the application to use the router alias. Deploy the new version of the code. Point the new alias to this version. Update the router alias to direct 10% of users to the new alias. If too many errors are encountered, send 100% of traffic to the existing alias.

Hint Answers: B

186. A company is developing an application that will be accessed through the Amazon API Gateway REST API. Registered users should be the only ones who can access certain resources of this API. The token being used should expire automatically and needs to be refreshed periodically. How can a Developer meet these requirements?

                A. Create an Amazon Cognito identity pool, configure the Amazon Cognito Authorizer in API Gateway, and use the temporary credentials generated by the identity pool.
                B. Create and maintain a database record for each user with a corresponding token and use an AWS Lambda authorizer in API Gateway.
                C. Create an Amazon Cognito user pool, configure the Cognito Authorizer in API Gateway, and use the identity or access token.
                D. Create an IAM user for each API user, attach an invoke permissions policy to the API, and use an IAM authorizer in API Gateway.

Hint Answers: C

187. A Developer is working on a serverless project based in Java. Initial testing shows a cold start takes about 8 seconds on average for AWS Lambda functions. What should the Developer do to reduce the cold start time? (Choose two.)

                A. Add the Spring Framework to the project and enable dependency injection.
                B. Reduce the deployment package by including only needed modules from the AWS SDK for Java.
                C. Increase the memory allocation setting for the Lambda function.
                D. Increase the timeout setting for the Lambda function.
                E. Change the Lambda invocation mode from synchronous to asynchronous.

Hint Answers: B C

188. A Developer created a dashboard for an application using Amazon API Gateway, Amazon S3, AWS Lambda, and Amazon RDS. The Developer needs an authentication mechanism allowing a user to sign in and view the dashboard. It must be accessible from mobile applications, desktops, and tablets, and must remember user preferences across platforms. Which AWS service should the Developer use to support this authentication scenario?

                A. AWS KMS
                B. Amazon Cognito
                C. AWS Directory Service
                D. Amazon IAM

Hint Answers: B

189. A Developer has created an S3 bucket s3://mycoolapp and has enabled server across logging that points to the folder s3://mycoolapp/logs. The Developer moved 100 KB of Cascading Style Sheets (CSS) documents to the folder s3://mycoolapp/css, and then stopped work. When the developer came back a few days later, the bucket was 50 GB. What is the MOST likely cause of this situation?

                A. The CSS files were not compressed and S3 versioning was enabled.
                B. S3 replication was enabled on the bucket.
                C. Logging into the same bucket caused exponential log growth.
                D. An S3 lifecycle policy has moved the entire CSS file to S3 Infrequent Access.

Hint Answers: C

190. A Developer is creating an Auto Scaling group whose instances need to publish a custom metric to Amazon CloudWatch. Which method would be the MOST secure way to authenticate a CloudWatch PUT request?

                A. Create an IAM user with PutMetricData permission and put the user credentials in a private repository; have applications pull the credentials as needed.
                B. Create an IAM user with PutMetricData permission, and modify the Auto Scaling launch configuration to inject the user credentials into the instance user data.
                C. Modify the CloudWatch metric policies to allow the PutMetricData permission to instances from the Auto Scaling group.
                D. Create an IAM role with PutMetricData permission and modify the Auto Scaling launching configuration to launch instances using that role.

Hint Answers: D

191. A Developer is working on an application that tracks hundreds of millions of product reviews in an Amazon DynamoDB table. The records include the data elements shown in the table:

Name
Type
Description
reviewID
Number
16 digit UUID
starRating
Number
Integer 1-5 user rating
comment
String
User Comment String
productID
Number
Product ID being reviewed

Which field, when used as the partition key, would result in the MOST consistent performance using DynamoDB?

                A. starRating
                B. reviewID
                C. comment
                D. productID

Hint Answers: B

192. A Developer has written a serverless application using multiple AWS services. The business logic is written as a Lambda function which has dependencies on third-party libraries. The Lambda function endpoints will be exposed using Amazon API Gateway. The Lambda function will write the information to Amazon DynamoDB. The Developer is ready to deploy the application but must have the ability to rollback. How can this deployment be automated, based on these requirements?

                A. Deploy using Amazon Lambda API operations to create the Lambda function by providing a deployment package.
                B. Use an AWS CloudFormation template and use CloudFormation syntax to define the Lambda function resource in the template.
                C. Use syntax conforming to the Serverless Application Model in the AWS CloudFormation template to define the Lambda function resource.
                D. Create a bash script which uses AWS CLI to package and deploy the application

Hint Answers: C

193. What are the steps to using the AWS CLI to launch a templatized serverless application?

                A. Use AWS CloudFormation get-template then CloudFormation execute-change-set.
                B. Use AWS CloudFormation validate-template then CloudFormation create-change-set.
                C. Use AWS CloudFormation package then CloudFormation deploy.
                D. Use AWS CloudFormation create-stack then CloudFormation update-stack.

Hint Answers: C

194. A Developer is creating a web application that requires authentication, but also needs to support guest access to provide users limited access without having to authenticate. What service can provide support for the application to allow guest access?

                A. IAM temporary credentials using AWS STS.
                B. Amazon Directory Service
                C. Amazon Cognito with unauthenticated access enabled
                D. IAM with SAML integration

Hint Answers: C

195. An application takes 40 seconds to process instructions received in an Amazon SQS message. Assuming the SQS queue is configured with the default VisibilityTimeout value, what is the BEST way, upon receiving a message, to ensure that no other instances can retrieve a message that has already been processed or is currently being processed?

                A. Use the ChangeMessageVisibility API to increase the VisibilityTimeout, then use the DeleteMessage API to delete the message.
                B. Use the DeleteMessage API call to delete the message from the queue, then call DeleteQueue API to remove the queue.
                C. Use the ChangeMessageVisibility API to decrease the timeout value, then use the DeleteMessage API to delete the message.
                D. Use the DeleteMessageVisibility API to cancel the VisibilityTimeout, then use the DeleteMessage API to delete the message.

Hint Answers: A

196. A Developer has implemented a Lambda function that needs to add new customers to an RDS database that is expected to run hundreds of times per hour. The Lambda function is configured to use 512MB of RAM and is based on the following pseudo code:

def lambda_handler(event,context):
db = database.connect()
db.statement (` INSERT INTO Customers (CustomerName) VALUES (context.name)’)
db.close()

After testing the Lambda function, the Developer notices that the Lambda execution time is much longer than expected. What should the Developer do to improve performance?

                A. Increase the amount of RAM allocated to the Lambda function, which will increase the number of threads the Lambda can use.
                B. Increase the size of the RDS database to allow for an increased number of database connections each hour.
                C. Move the database connection and close statement out of the handler. Place the connection in the global space.
                D. Replace RDS with Amazon DynamoDB to implement control over the number of writes per second.

Hint Answers: C

197. A current architecture uses many Lambda functions invoking one another as a large state machine. The coordination of this state machine is legacy custom code that breaks easily. Which AWS Service can help refactor and manage the state machine?

                A. AWS Data Pipeline
                B. AWS SNS with AWS SQS
                C. Amazon Elastic MapReduce
                D. AWS Step Functions

Hint Answers: D

198. A Developer is asked to implement a caching layer in front of Amazon RDS. Cached content is expensive to regenerate in case of service failure. Which implementation below would work while maintaining maximum uptime?

                A. Implement Amazon ElastiCache Redis in Cluster Mode
                B. Install Redis on an Amazon EC2 instance.
                C. Implement Amazon ElastiCache Memcached.
                D. Migrate the database to Amazon Redshift.

Hint Answers: A

199. A current architecture uses many Lambda functions invoking one another as large state machine. The coordination of this state machine is legacy custom code that breaks easily. Which AWS Service can help refactor and manage the state machine?

                A. AWS Data Pipeline
                B. AWS SNS with AWS SQS
                C. Amazon Elastic MapReduce
                D. AWS Step Functions

Hint Answers: D

200. A large e-commerce site is being designed to deliver static objects from Amazon S3. The Amazon S3 bucket will server more than 300 GET requests per second. What should be done to optimize performance? (Choose two.)

                A. Integrate Amazon CloudFront with Amazon S3.
                B. Enable Amazon S3 cross-region replication.
                C. Delete expired Amazon S3 server log files.
                D. Configure Amazon S3 lifecycle rules.
                E. Randomize Amazon S3 key name prefixes.

Hint Answers: A E

201. A company is building a stock trading application that requires sub-millisecond latency in processing trading requests. Amazon DynamoDB is used to store all the trading data that is used to process each request. After load testing the application, the development team found that due to data retrieval times, the latency requirement is not satisfied. Because of sudden high spikes in the number of requests, DynamoDB read capacity has to be significantly over-provisioned to avoid throttling. What steps should be taken to meet latency requirements and reduce the cost of running the application?

                A. Add Global Secondary Indexes for trading data.
                B. Store trading data in Amazon S3 and use Transfer Acceleration.
                C. Add retries with exponential back-off for DynamoDB queries
                D. Use DynamoDB Accelerator to cache trading data.

Hint Answers: D

202. A Developer needs temporary access to resources in a second account. What is the MOST secure way to achieve this?

                A. Use the Amazon Cognito user pools to get short-lived credentials for the second account.
                B. Create a dedicated IAM access key for the second account, and send it by mail.
                C. Create a cross-account access role, and use sts:AssumeRole API to get short-lived credentials.
                D. Establish trust, and add an SSH key for the second account to the IAM user.

Hint Answers: C

203. An application reads data from an Amazon DynamoDB table. Several times a day, for a period of 15 seconds, the application receives multiple ProvisionedThroughputExceeded errors. How should this exception be handled?

                A. Create a new global secondary index for the table to help with the additional requests.
                B. Retry the failed read requests with exponential backoff.
                C. Immediately retry the failed read requests.
                D. Use the DynamoDB “UpdateItem” API to increase the provisioned throughput capacity of the table.

Hint Answers: B

204. A Developer has created a large Lambda function, and deployment is failing with the following error: ClientError: An error occurred (InvalidParameterValueException) when calling the CreateFunction operation: Unzipped size must be smaller than XXXXXXXXX bytes’, where XXXXXXXXX is the current Lambda limit What can the Developer do to fix this problem?

                A. Submit a limit increase request to AWS Support to increase the function to the size needed.
                B. Use a compression algorithm that is more efficient than ZIP.
                C. Break the function into multiple smaller Lambda functions.
                D. ZIP the ZIP file twice to compress it further.

Hint Answers: C

205. Given the source code for an AWS Lambda function in the local store.py containing a handler function called get_store and the following AWS CloudFormation template:

Transform: AWS::Serverless-2016-10-31
Resources:
StoreFunc:
Type: AWS::Serverless::Function
Properties:
Handler: store.get_store
Runtime: python3.6

What should be done to prepare the template so that it can be deployed using the AWS CLI command aws cloudformation deploy?

                A. Use aws cloudformation compile to base64 encode and embed the source file into a modified CloudFormation template.
                B. Use aws cloudformation package to upload the source code to an Amazon S3 bucket and produce a modified CloudFormation template.
                C. Use aws lambda zip to package the source file together with the CloudFormation template and deploy the resulting zip archive.
                D. Use aws serverless create-package to embed the source file directly into the existing CloudFormation template.

Hint Answers: B

206. An application stores images in an S3 bucket. Amazon S3 event notifications are used to trigger a Lambda function that resizes the images. Processing each image takes less than a second. How will AWS Lambda handle the additional traffic?

                A. Lambda will scale out to execute the requests concurrently.
                B. Lambda will handle the requests sequentially in the order received.
                C. Lambda will process multiple images in a single execution.
                D. Lambda will add more compute to each execution to reduce processing time.

Hint Answers: A

207. A company wants to implement a continuous integration for its workloads on AWS. The company wants to trigger unit test in its pipeline for commits-on its code repository, and wants to be notified of failure events in the pipeline. How can these requirements be met?

                A. Store the source code in AWS CodeCommit. Create a CodePipeline to automate unit testing. Use Amazon SNS to trigger notifications of failure events.
                B. Store the source code in GitHub. Create a CodePipeline to automate unit testing. Use Amazon SES to trigger notifications of failure events.
                C. Store the source code on GitHub. Create a CodePipeline to automate unit testing. Use Amazon CloudWatch to trigger notifications of failure events.
                D. Store the source code in AWS CodeCommit. Create a CodePipeline to automate unit testing. Use Amazon CloudWatch to trigger notification of failure events.

Hint Answers: A

208. A serverless application uses an API Gateway and AWS Lambda. Where should the Lambda function store its session information across function calls?

                A. In an Amazon DynamoDB table
                B. In an Amazon SQS queue
                C. In the local filesystem
                D. In an SQLite session table using –DSQLITE_ENABLE_SESSION

Hint Answers: A

209. A Developer has created a software package to be deployed on multiple EC2 instances using IAM roles. What actions could be performed to verify IAM access to get records from Amazon Kinesis Streams? (Choose two.)

                A. Use the AWS CLI to retrieve the IAM group.
                B. Query Amazon EC2 metadata for in-line IAM policies.
                C. Request a token from AWS STS, and perform a describe action.
                D. Perform a get action using the –-dry-run argument.
                E. Validate the IAM role policy with the IAM policy simulator.

Hint Answers: B,E

210. When writing a Lambda function, what is the benefit of instantiating AWS clients outside the scope of the handler?

                A. Legibility and stylistic convention
                B. Taking advantage of connection re-use
                C. Better error handling
                D. Creating a new instance per invocation

Hint Answers: B