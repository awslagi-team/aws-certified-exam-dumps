Notes: Hi all, We’re sharing AWS Developer Associate (DVA-C01) Practice Exam Part 1 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Developer Associate Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \ 
For GCP: https://www.gcp-examquestions.com

1. A company wants to implement authentication for its new REST service using Amazon API Gateway. To authenticate the calls, each request must include HTTP headers with a client ID and user ID. These credentials must be compared to authentication data in an Amazon DynamoDB table. What MUST the company do to implement this authentication in API Gateway?

        A. Implement an AWS Lambda authorizer that references the DynamoDB authentication table
        B. Create a model that requires the credentials, then grant API Gateway access to the authentication table
        C. Modify the integration requests to require the credentials, then grant API Gateway access to the authentication table
        D. Implement an Amazon Cognito authorizer that references the DynamoDB authentication table

Answer: A

2. A company is creating a REST service using an Amazon API Gateway with AWS Lambda integration. The service run different versions for testing purposes. What would be the BEST way to accomplish this?

        A. Use an x-Version header to denote which version is being called and pass that header to the Lambda function(s)
        B. Create an API Gateway Lambda authorizer to route API clients to the correct API version
        C. Create an API Gateway resource policy to isolate versions and provide context to the Lambda function(s)
        D. Deploy the API versions as unique stages with unique endpoints and use stage variables to provide further context

Answer: D

3. A Developer is storing documents in Amazon S3 that will require encryption at rest. The encryption keys must be rotated annually, at least. What is the easiest way to achieve this?

        A. Encrypt the data before sending it to Amazon S3
        B. Import a custom key into AWS KMS with annual rotation enabled
        C. Use AWS KMS with automatic key rotation
        D. Export a key from AWS KMS to encrypt the data

Answer: C

4. When developing an AWS Lambda function that processes Amazon Kinesis Data Streams, Administrators within the company must receive a notice that includes the processed data. How should the Developer write the function to send processed data to the Administrators?

        A. Separate the Lambda handler from the core logic
        B. Use Amazon CloudWatch Events to send the processed data
        C. Publish the processed data to an Amazon SNS topic
        D. Push the processed data to Amazon SQS

Answer: C

5. A Developer is writing a REST service that will add items to a shopping list. The service is built on Amazon API Gateway with AWS Lambda integrations. The shopping list items are send as query string parameters in the method request. How should the Developer convert the query string parameters to arguments for the Lambda function?

        A. Enable request validation
        B. Include the Amazon Resource Name (ARN) of the Lambda function
        C. Change the integration type
        D. Create a mapping template

Answer: D

6. A Development team would like to migrate their existing application code from a GitHub repository to AWS CodeCommit. What needs to be created before they can migrate a cloned repository to CodeCommit over HTTPS?

        A. A GitHub secure authentication token
        B. A public and private SSH key file
        C. A set of Git credentials generated from IAM
        D. An Amazon EC2 IAM role with CodeCommit permissions

Answer: C

7. A Developer must encrypt a 100-GB object using AWS KMS. What is the BEST approach?

        A. Make an Encrypt API call to encrypt the plaintext data as ciphertext using a customer master key (CMK)
        B. Make an Encrypt API call to encrypt the plaintext data as ciphertext using a customer master key (CMK) with imported key material
        C. Make an GenerateDataKey API call that returns a plaintext key and an encrypted copy of a data key. Use a plaintext key to encrypt the data
        D. Make an GenerateDataKeyWithoutPlaintext API call that returns an encrypted copy of a data key. Use an encrypted key to encrypt the data

Answer: C

8. A team of Developers must migrate an application running inside an AWS Elastic Beanstalk environment from a Classic Load Balancer to an Application Load Balancer. Which steps should be taken to accomplish the task using the AWS Management Console?

        A. 1. Update the application code in the existing deployment. 2. Select a new load balancer type before running the deployment.3. Deploy the new version of the application code to the environment.
        B. 1. Create a new environment with the same configurations except for the load balancer type. 2. Deploy the same application version as used in the original environment.3. Run the swap-environment-cnames action.
        C. 1. Clone the existing environment, changing the associated load balancer type. 2. Deploy the same application version as used in the original environment. 3. Run the swap-environment-cnames action.
        D. 1. Edit the environment definitions in the existing deployment. 2. Change the associated load balancer type according to the requirements. 3. Rebuild the environment with the new load balancer type.

Answer: B

9. A Development team wants to instrument their code to provide more detailed information to AWS X-Ray than simple outgoing and incoming requests. This will generate large amounts of data, so the Development team wants to implement indexing so they can filter the data. What should the Development team do to achieve this?

        A. Add annotations to the segment document and the code
        B. Add metadata to the segment document and the code
        C. Configure the necessary X-Ray environment variables
        D. Install required plugins for the appropriate AWS SDK

Answer: A

10. A Developer created a new AWS account and must create a scalable AWS Lambda function that meets the following requirements for concurrent execution: Average execution time of 100 seconds 50 requests per second Which step must be taken prior to deployment to prevent errors?

        A. Implement dead-letter queues to capture invocation errors
        B. Add an event source from Amazon API Gateway to the Lambda function
        C. Implement error handling within the application code
        D. Contact AWS Support to increase the concurrent execution limits

Answer: D

11. A company is using continuous integration and continuous delivery systems. A Developer now needs to automate a software package deployment to both Amazon EC2 instances and virtual servers running on-premises. Which AWS service should be used to accomplish this?

        A. AWS CodePipeline
        B. AWS CodeBuild
        C. AWS Elastic Beanstalk
        D. AWS CodeDeploy

Answer: D

12. A company needs a version control system for collaborative software development. Features of the system must include the following: Support for batches of changes across multiple files Parallel branching Version tracking Which AWS service will meet these requirements?

        A. AWS CodePipeline
        B. Amazon S3
        C. AWS Code Build
        D. AWS CodeCommit

Answer: D

13. A company runs an e-commerce website that uses Amazon DynamoDB where pricing for items is dynamically updated in real time. At any given time, multiple updates may occur simultaneously for pricing information on a particular product. This is causing the original editor’s changes to be overwritten without a proper review process. Which DynamoDB write option should be selected to prevent this overwriting?

        A. Concurrent writes
        B. Conditional writes
        C. Atomic writes
        D. Batch writes

Answer: B

14. An Amazon DynamoDB table uses a Global Secondary Index (GSI) to support read queries. The primary table is write-heavy, whereas the GSI is used for read operations. Looking at Amazon CloudWatch metrics, the Developer notices that write operations to the primary table are throttled frequently under heavy write activity. However, write capacity units to the primary table are available and not fully consumed. Why is the table being throttled?

        A. The GSI write capacity units are under provisioned
        B. There are not enough read capacity units on the primary table
        C. Amazon DynamoDB Streams is not enabled on the table
        D. A large write operation is being performed against another table

Answer: A

15. A Developer is building a three-tier web application that should be able to handle a minimum of 5000 requests per minute. Requirements state that the web tier should be completely stateless while the application maintains session state for the users. How can session data be externalized, keeping latency at the LOWEST possible value?

        A. Create an Amazon RDS instance, then implement session handling at the application level to leverage a database inside the RDS database instance for session data storage
        B. Implement a shared file system solution across the underlying Amazon EC2 instances, then implement session handling at the application level to leverage the shared file system for session data storage
        C. Create an Amazon ElastiCache, Memcached cluster, then implement session handling at the application level to leverage the cluster for session data storage
        D. Create an Amazon DynamoDB table, then implement session handling at the application level to leverage the table for session data storage

Answer: C

16. An application is being developed to audit several AWS accounts. The application will run in Account A and must access AWS services in Accounts B and C. What is the MOST secure way to allow the application to call AWS services in each audited account?

        A. Configure cross-account roles in each audited account. Write code in Account a that assumes those roles
        B. Use S3 cross-region replication to communicate among accounts, with Amazon S3 event notifications to trigger Lambda functions
        C. Deploy an application in each audited account with its own role. Have Account A authenticate with the application
        D. Create an IAM user with an access key in each audited account. Write code in Account A that uses those access keys

Answer: A

17. A Developer has been asked to create an AWS Lambda function that is triggered any time updates are made to items in an Amazon DynamoDB table. The function has been created, and appropriate permissions have been added to the Lambda execution role. Amazon DynamoDB streams have been enabled for the table, but the function is still not being triggered. Which option would enable DynamoDB table updates to trigger the Lambda function?

        A. Change the StreamViewType parameter value to NEW_AND_OLD_IMAGES for the DynamoDB table
        B. Configure event source mapping for the Lambda function
        C. Map an Amazon SNS topic to the DynamoDB streams
        D. increase the maximum execution time (timeout) setting of the Lambda function

Answer: B

18. A company needs to ingest terabytes of data each hour from thousands of sources that are delivered almost continually throughout the day. The volume of messages generated varies over the course of the day. Messages must be delivered in real time for fraud detection and live operational dashboards. Which approach will meet these requirements?

        A. Send the messages to an Amazon SQS queue, then process the messages by using a fleet of Amazon EC2 instances
        B. Use the Amazon S3 API to write messages to an S3 bucket, then process the messages by using Amazon Redshift
        C. Use AWS Data Pipeline to automate the movement and transformation of data
        D. Use Amazon Kinesis Data Streams with Kinesis Client Library to ingest and deliver messages

Answer: D

19. A company is running a Docker application on Amazon ECS. The application must scale based on user load in the last 15 seconds. How should a Developer instrument the code so that the requirement can be met?

        A. Create a high-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 30 seconds
        B. Create a high-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 5 seconds
        C. Create a standard-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 30 seconds
        D. Create a standard-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 5 seconds

Answer: B D

20. A Developer wants to upload data to Amazon S3 and must encrypt the data in transit. Which of the following solutions will accomplish this task? (Choose two.)

        A. Set up hardware VPN tunnels to a VPC and access S3 through a VPC endpoint
        B. Set up Client-Side Encryption with an AWS KMS-Managed Customer Master Key
        C. Set up Server-Side Encryption with AWS KMS-Managed Keys
        D. Transfer the data over an SSL connection
        E. Set up Server-Side Encryption with S3-Managed Keys

Answer: B D

21. A Developer is trying to deploy a serverless application using AWS CodeDeploy. The application was updated and needs to be redeployed. What file does the Developer need to update to push that change through CodeDeploy?

        A. dockerrun.aws.json
        B. buildspec.yml
        C. appspec.yml
        D. ebextensions.config

Answer: C

22. An AWS Lambda function must access an external site by using a regularly rotated user name and password. These items must be kept securely and cannot be stored in the function code. What combination of AWS services can be used to accomplish this? (Choose two.)

        A. AWS Certificate Manager (ACM)
        B. AWS Systems Manager Parameter Store
        C. AWS Trusted Advisor
        D. AWS KMS
        E. Amazon GuardDuty

Answer: B D

23. A Developer is building a web application that uses Amazon API Gateway to expose an AWS Lambda function to process requests from clients. During testing, the Developer notices that the API Gateway times out even though the Lambda function finishes under the set time limit. Which of the following API Gateway metrics in Amazon CloudWatch can help the Developer troubleshoot the issue? (Choose two.)

        A. CacheHitCount
        B. IntegrationLatency
        C. CacheMissCount
        D. Latency
        E. Count

Answer: B C

24. A Developer is working on an application that handles 10MB documents that contain highly sensitive data. The application will use AWS KMS to perform client-side encryption. What steps must be followed?

        A. Invoke the Encrypt API passing the plaintext data that must be encrypted, then reference the customer managed key ARN in the KeyId parameter
        B. Invoke the GenerateRandom API to get a data encryption key, then use the data encryption key to encrypt the data
        C. Invoke the GenerateDataKey API to retrieve the encrypted version of the data encryption key to encrypt the data
        D. Invoke the GenerateDataKey API to retrieve the plaintext version of the data encryption key to encrypt the data

Answer: D

25. An application deployed on AWS Elastic Beanstalk experiences increased error rates during deployments of new application versions, resulting in service degradation for users. The Development team believes that this is because of the reduction in capacity during the deployment steps. The team would like to change the deployment policy configuration of the environment to an option that maintains full capacity during deployment while using the existing instances. Which deployment policy will meet these requirements while using the existing instances?

        A. All at once
        B. Rolling
        C. Rolling with additional batch
        D. Immutable

Answer: C

26. An application writes items to an Amazon DynamoDB table. As the application scales to thousands of instances, calls to the DynamoDB API generate occasional ThrottlingException errors. The application is coded in a language incompatible with the AWS SDK. How should the error be handled?

        A. Add exponential backoff to the application logic
        B. Use Amazon SQS as an API message bus
        C. Pass API calls through Amazon API Gateway
        D. Send the items to DynamoDB through Amazon Kinesis Data Firehose

Answer: A

27. A company is running an application built on AWS Lambda functions. One Lambda function has performance issues when it has to download a 50MB file from the Internet in every execution. This function is called multiple times a second. What solution would give the BEST performance increase?

        A. Cache the file in the /tmp directory
        B. Increase the Lambda maximum execution time
        C. Put an Elastic Load Balancer in front of the Lambda function
        D. Cache the file in Amazon S3

Answer: A

28. A company needs to distribute firmware updates to its customers around the world. Which service will allow easy and secure control of the access to the downloads at the lowest cost?

        A. Use Amazon CloudFront with signed URLs for Amazon S3
        B. Create a dedicated Amazon CloudFront Distribution for each customer
        C. Use Amazon CloudFront with AWS Lambda@Edge
        D. Use Amazon API Gateway and AWS Lambda to control access to an S3 bucket

Answer: A

29. A Developer has a stateful web server on-premises that is being migrated to AWS. The Developer must have greater elasticity in the new design. How should the Developer re-factor the application to make it more elastic? (Choose two.)

        A. Use pessimistic concurrency on Amazon DynamoDB
        B. Use Amazon CloudFront with an Auto Scaling group
        C. Use Amazon CloudFront with an AWS Web Application Firewall
        D. Store session state data in an Amazon DynamoDB table
        E. Use an ELB with an Auto Scaling group

Answer: D E

30. A Developer is creating a template that uses AWS CloudFormation to deploy an application. This application is serverless and uses Amazon API Gateway, Amazon DynamoDB, and AWS Lambda. Which tool should the Developer use to define simplified syntax for expressing serverless resources?

        A. CloudFormation serverless intrinsic functions
        B. AWS serverless express
        C. An AWS serverless application model
        D. A CloudFormation serverless plugin

Answer: C

31. An e-commerce web application that shares session state on-premises is being migrated to AWS. The application must be fault tolerant, natively highly scalable, and any service interruption should not affect the user experience. What is the best option to store the session state?

        A. Store the session state in Amazon ElastiCache
        B. Store the session state in Amazon CloudFront
        C. Store the session state in Amazon S3
        D. Enable session stickiness using elastic load balancers

Answer: A

32. A Developer wants to debug an application by searching and filtering log data. The application logs are stored in Amazon CloudWatch Logs. The Developer creates a new metric filter to count exceptions in the application logs. However, no results are returned from the logs. What is the reason that no filtered results are being returned?

        A. A setup of the Amazon CloudWatch interface VPC endpoint is required for filtering the CloudWatch Logs in the VPC
        B. CloudWatch Logs only publishes metric data for events that happen after the filter is created
        C. The log group for CloudWatch Logs should be first streamed to Amazon Elasticsearch Service before metric filtering returns the results
        D. Metric data points for logs groups can be filtered only after they are exported to an Amazon S3 bucket

Answer: B

33. A Developer must analyze performance issues with production-distributed applications written as AWS Lambda functions. These distributed Lambda applications invoke other components that make up the applications. How should the Developer identify and troubleshoot the root cause of the performance issues in production?

        A. Add logging statements to the Lambda functions, then use Amazon CloudWatch to view the logs.
        B. Use AWS Cloud Trail and then examine the logs
        C. Use AWS X-Ray, then examine the segments and errors
        D. Run Amazon Inspector agents and then analyze performance

Answer: C

34. A Developer is investigating an issue whereby certain requests are passing through an Amazon API Gateway endpoint /MyAPI, but the requests do not reach the AWS Lambda function backing /MyAPI. The Developer found that a second Lambda function sometimes runs at maximum concurrency allowed for the given AWS account. How can the Developer address this issue?

        A. Manually reduce the concurrent execution limit at the account level
        B. Add another API Gateway stage for /MyAPI, and shard the requests
        C. Configure the second Lambda functions concurrency execution limit
        D. Reduce the throttling limits in the API Gateway /MyAPI endpoint

Answer: C

35. A company is using Amazon RDS MySQL instances for its application database tier and Apache Tomcat servers for its web tier. Most of the database queries from web applications are repeated read requests. Use of which AWS service would increase in performance by adding in-memory store for repeated read queries?

        A. Amazon RDS Multi-AZ
        B. Amazon SQS
        C. Amazon ElastiCache
        D. Amazon RDS read replica

Answer: C

36. To include objects defined by the AWS Serverless Application Model (SAM) in an AWS CloudFormation template, in addition to Resources, what section MUST be included in the document root?

        A. Conditions
        B. Globals
        C. Transform
        D. Properties

Answer: C

37. A Developer is making changes to a custom application that is currently using AWS Elastic Beanstalk. After the Developer completes the changes, what solutions will update the Elastic Beanstalk environment with the new application version? (Choose two.)

        A. Package the application code into a .zip file, and upload, then deploy the packaged application from the AWS Management Console
        B. Package the application code into a .tar file, create a new application version from the AWS Management Console, then update the environment by using AWS CLI
        C. Package the application code into a .tar file, and upload and deploy the packaged application from the AWS Management Console
        D. Package the application code into a .zip file, create a new application version from the packaged application by using AWS CLI, then update the environment by using AWS CLI
        E. Package the application code into a .zip file, create a new application version from the AWS Management Console, then rebuild the environment by using AWS CLI

Answer: A D

38. A Developer created configuration specifications for an AWS Elastic Beanstalk application in a file named healthcheckurl.yaml in the .ebextensions/directory of their application source bundle. The file contains the following:

        A. Convert the file to JSON format.
        B. Rename the file to a .config extension.
        C. Change the configuration section from options_settings to resources.
        D. Change the namespace of the option settings to a custom namespace.

Answer: B

39. A company is migrating a single-server, on-premises web application to AWS. The company intends to use multiple servers behind an Elastic Load Balancer (ELB) to balance the load, and will also store session data in memory on the web server. The company does not want to lose that session data if a server fails or goes offline, and it wants to minimize user’s downtime. Where should the company move session data to MOST effectively reduce downtime and make users’ session data more fault tolerant?

        A. An Amazon ElastiCache for Redis cluster
        B. A second Amazon EBS volume
        C. The web server’s primary disk
        D. An Amazon EC2 instance dedicated to session data

Answer: A

40. A Developer is building a mobile application and needs any update to user profile data to be pushed to all devices accessing the specific identity. The Developer does not want to manage a back end to maintain the user profile data. What is the MOST efficient way for the Developer to achieve these requirements using Amazon Cognito?

        A. Use Cognito federated identities.
        B. Use a Cognito user pool.
        C. Use Cognito Sync.
        D. Use Cognito events.

Answer: C

41. A Developer has created a Lambda function and is finding that the function is taking longer to complete than expected. After some debugging, the Developer has discovered that increasing compute capacity would improve performance. How can the Developer increase the Lambda compute resources?

        A. Run on a larger instance size with more compute capacity.
        B. Increase the maximum execution time.
        C. Specify a larger compute capacity when calling the Lambda function.
        D. Increase the allocated memory for the Lambda function.

Answer: D

42. A Developer is writing a mobile application that allows users to view images from an S3 bucket. The users must be able to log in with their Amazon login, as well as Facebook and/or Google accounts. How can the Developer provide this authentication functionality?

        A. Use Amazon Cognito with web identity federation.
        B. Use Amazon Cognito with SAML-based identity federation.
        C. Use AWS IAM Access/Secret keys in the application code to allow Get* on the S3 bucket.
        D. Use AWS STS AssumeRole in the application code and assume a role with Get* permissions on the S3 bucket.

Answer: A

43. A company maintains a REST service using Amazon API Gateway and the API Gateway native API key validation. The company recently launched a new registration page, which allows users to sign up for the service. The registration page creates a new API key using CreateApiKey and sends the new key to the user. When the user attempts to call the API using this key, the user receives a 403 Forbidden error. Existing users are unaffected and can still call the API. What code updates will grant these new users access to the API?

        A. The createDeployment method must be called so the API can be redeployed to include the newly created API key.
        B. The updateAuthorizer method must be called to update the API’s authorizer to include the newly created API key.
        C. The importApiKeys method must be called to import all newly created API keys into the current stage of the API.
        D. The createUsagePlanKey method must be called to associate the newly created API key with the correct usage plan.

Answer: C

44. A company has an application that logs all information to Amazon S3. Whenever there is a new log file, an AWS Lambda function is invoked to process the log files. The code works, gathering all of the necessary information. However, when checking the Lambda function logs, duplicate entries with the same request ID are found. What is causing the duplicate entries?

        A. The S3 bucket name was specified incorrectly.
        B. The Lambda function failed, and the Lambda service retired the invocation with a delay.
        C. There was an S3 outage, which caused duplicate entries of the sale log file.
        D. The application stopped intermittently and then resumed.

Answer: B

45. A nightly batch job loads 1 million new records into a DynamoDB table. The records are only needed for one hour, and the table needs to be empty by the next night’s batch job. Which is the MOST efficient and cost-effective method to provide an empty table?

        A. Use DeleteItem using a Condition Expression.
        B. Use BatchWriteItem to empty all of the rows.
        C. Write a recursive function that scans and calls out DeleteItem.
        D. Create and then delete the table after the task has completed.

Answer: D

46. A Developer wants access to make the log data of an application running on an EC2 instance available to systems administrators. Which of the following enables monitoring of this metric in Amazon CloudWatch?

        A. Retrieve the log data from CloudWatch using the GetMetricData API call
        B. Retrieve the log data from AWS CloudTrail using the LookupEvents API call.
        C. Launch a new EC2 instance, configure Amazon CloudWatch Events, and then install the application.
        D. Install the Amazon CloudWatch Logs agent on the EC2 instance that the application is running on.

Answer: D

47. A Development team has pushed out 10 applications running on several Amazon EC2 instances. The Operations team is asking for a graphical representation of one key performance metric for each application. These metrics should be available on one screen for easy monitoring. Which steps should the Developer take to accomplish this using Amazon CloudWatch?

        A. Create a custom namespace with a unique metric name for each application.
        B. Create a custom dimension with a unique metric name for each application.
        C. Create a custom event with a unique metric name for each application.
        D. Create a custom alarm with a unique metric name for each application.

Answer: A

48. A Developer is creating a serverless website with content that includes HTML files, images, videos, and JavaScript (client-side scripts). Which combination of services should the Developer use to create the website?

        A. Amazon S3 and Amazon CloudFront
        B. Amazon EC2 and Amazon ElastiCache
        C. Amazon ECS and Redis
        D. AWS Lambda and Amazon API Gateway

Answer: A

49. A company is providing services to many downstream consumers. Each consumer may connect to one or more services. This has resulted in a complex architecture that is difficult to manage and does not scale well. The company needs a single interface to manage these services to consumers. Which AWS service should be used to refactor this architecture?

        A. AWS Lambda
        B. AWS X-Ray
        C. Amazon SQS
        D. Amazon API Gateway

Answer: D

50. A company uses Amazon DynamoDB for managing and tracking orders. The DynamoDB table is partitioned based on the order date. The company receives a huge increase in orders during a sales event, causing DynamoDB writes to throttle, and the consumed throughput is far below the provisioned throughput. According to AWS best practices, how can this issue be resolved with MINIMAL costs?

        A. Create a new DynamoDB table for every order date.
        B. Increase the read and write capacity units of the DynamoDB table.
        C. Add a random number suffix to the partition key values.
        D. Add a global secondary index to the DynamoDB table.

Answer: C

51. A company has three different environments: Development, QA, and Production. The company wants to deploy its code first in the Development environment, then QA, and then Production. Which AWS service can be used to meet this requirement?

        A. Use AWS CodeCommit to create multiple repositories to deploy the application.
        B. Use AWS CodeBuild to create, configure, and deploy multiple build application projects.
        C. Use AWS Data Pipeline to create multiple data pipeline provisions to deploy the application.
        D. Use AWS CodeDeploy to create multiple deployment groups.

Answer: D

52. A company is creating an application that will require users to access AWS services and allow them to reset their own passwords. Which of the following would allow the company to manage users and authorization while allowing users to reset their own passwords?

        A. Amazon Cognito identity pools and AWS STS
        B. Amazon Cognito identity pools and AWS IAM
        C. Amazon Cognito user pools and AWS KMS
        D. Amazon Cognito user pools and identity pools

Answer: D

53. An application that runs on an Amazon EC2 instance needs to access and make API calls to multiple AWS services. What is the MOST secure way to provide access to the AWS services with MINIMAL management overhead?

        A. Use AWS KMS to store and retrieve credentials.
        B. Use EC2 instance profiles.
        C. Use AWS root user to make requests to the application.
        D. Store and retrieve credentials from AWS CodeCommit.

Answer: B

54. In a multi-container Docker environment in AWS Elastic Beanstalk, what is required to configure container instances in the environment?

        A. An Amazon ECS task definition
        B. An Amazon ECS cluster
        C. A Docker in an application package
        D. A CLI for Elastic Beanstalk

Answer: A

55. A Development team currently supports an application that uses an in-memory store to save accumulated game results. Individual results are stored in a database. As part of migrating to AWS, the team needs to use automatic scaling. The team knows this will yield inconsistent results. Where should the team store these accumulated game results to BEST allow for consistent results without impacting performance?

        A. Amazon S3
        B. Amazon RDS
        C. Amazon ElastiCache
        D. Amazon Kinesis
Answer: C

56. A company has a multi-tiered web application on AWS. During a recent spike in traffic, one of the primary relational databases on Amazon RDS could not serve all the traffic. Some read queries for repeatedly accessed items failed, so users received error messages. What can be done to minimize the impact on database read queries MOST efficiently during future traffic spikes?

        A. Use Amazon S3 to cache database query results
        B. Use Amazon RDS as a custom origin for Amazon CloudFront.
        C. Use local storage and memory on Amazon EC2 instances to cache data.
        D. Use Amazon ElastiCache in front of the primary database to cache data.

Answer: D

57. A company has a website that is developed in PHP and WordPress and is launched using AWS Elastic Beanstalk. There is a new version of the website that needs to be deployed in the Elastic Beanstalk environment. The company cannot tolerate having the website offline if an update fails. Deployments must have minimal impact and rollback as soon as possible. What deployment method should be used?

        A. All at once
        B. Rolling
        C. Snapshots
        D. Immutable

Answer: D

58. A company maintains an application responsible for processing several thousand external callbacks each day. The company’s System administrators want to know how many callbacks are being received on a rolling basis, and they want this data available for 10 days. The company also wants the ability to issue automated alerts if the number of callbacks exceeds the defined thresholds. What is the MOST cost-effective way to address the need to track and alert on these statistics?

        A. Push callback data to an Amazon RDS database that can be queried to show historical data and to alert on exceeded thresholds.
        B. Push callback data to AWS X-Ray and use AWS Lambda to query, display, and alert on exceeded thresholds.
        C. Push callback data to Amazon Kinesis Data Streams and invoke an AWS Lambda function that stores data in Amazon DynamoDB and sends the required alerts.
        D. Push callback data to Amazon CloudWatch as a custom metric and use the CloudWatch alerting mechanisms to alert System Administrators

Answer: D

59. A Developer is creating an AWS Lambda function to process a stream of data from an Amazon Kinesis Data Stream. When the Lambda function parses the data and encounters a missing field, it exits the function with an error. The function is generating duplicate records from the Kinesis stream. When the Developer looks at the stream output without the Lambda function, there are no duplicate records. What is the reason for the duplicates?

        A. The Lambda function did not advance the Kinesis stream pointer to the next record after the error.
        B. The Lambda event source used asynchronous invocation, resulting in duplicate records.
        C. The Lambda function did not handle the error, and the Lambda service attempted to reprocess the data.
        D. The Lambda function is not keeping up with the amount of data coming from the stream.

Answer: C

60. A Developer must build an application that uses Amazon DynamoDB. The requirements state that items being stored in the DynamoDB table will be 7KB in size and that reads must be strongly consistent. The maximum read rate is 3 items per second, and the maximum write rate is 10 items per second. How should the Developer size the DynamoDB table to meet these requirements?

        A. Read: 3 read capacity units Write: 70 write capacity units
        B. Read: 6 read capacity units Write: 70 write capacity units
        C. Read: 6 read capacity units Write: 10 write capacity units
        D. Read: 3 read capacity units Write: 10 write capacity units

Answer: B