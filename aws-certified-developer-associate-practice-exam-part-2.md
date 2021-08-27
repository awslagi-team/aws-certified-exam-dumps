Notes: Hi all, We’re sharing AWS Developer Associate (DVA-C01) Practice Exam Part 2 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Developer Associate Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \
For GCP: https://www.gcp-examquestions.com

61. An AWS Lambda function must read data from an Amazon RDS MySQL database in a VPC and also reach a public endpoint over the internet to get additional data. Which steps must be taken to allow the function to access both the RDS resource and the public endpoint? (Select TWO.)

		A. Modify the default configuration for the Lambda function to associate it with an Amazon VPC private subnet.
		B. Modify the default network access control list to allow outbound traffic.
		C. Add a NAT Gateway to the VPC.
		D. Modify the default configuration of the Lambda function to associate it with a VPC public subnet.
		E. Add an environmental variable to the Lambda function to allow outbound internet access.

Answer: A C

62. A Developer writes an AWS Lambda function and uploads the code in a .ZIP file to Amazon S3. The Developer makes changes to the code and uploads a new .ZIP file to Amazon S3. However, Lambda executes the earlier code. How can the Developer fix this in the LEAST disruptive way?

		A. Create another Lambda function and specify the new .ZIP file.
		B. Call the update-function-code API.
		C. Remove the earlier .ZIP file first, then add the new .ZIP file.
		D. Call the create-alias API.

Answer: B

63. A company is developing an application that will run on several Amazon EC2 instances in an Auto Scaling group and can access a database running on Amazon EC2. The application needs to store secrets required to connect to the database. The application must allow for periodic secret rotation, and there should be no changes to the application when a secret changes. What is the SAFEST way to meet these requirements?

		A. Associate an IAM role to the EC2 instance where the application is running with permission to access the database.
		B. Use AWS Systems Manager Parameter Store with the SecureString data type to store secrets.
		C. Configure the application to store secrets in Amazon S3 object metadata.
		D. Hard code the database secrets in the application code itself.

Answer: A

64. A Developer needs to design an application running on AWS that will be used to consume Amazon SQS messages that range from 1 KB up to 1GB in size. How should the Amazon SQS messages be managed?

		A. Use Amazon S3 and the Amazon SQS CLI.
		B. Use Amazon S3 and the Amazon SQS Extended Client Library for Java.
		C. Use Amazon EBS and the Amazon SQS CLI.
		D. Use Amazon EFS and the Amazon SQS CLI.

Answer: A

65. A Developer has been asked to make changes to the source code of an AWS Lambda function. The function is managed using an AWS CloudFormation template. The template is configured to load the source code from an Amazon S3 bucket. The Developer manually created a .ZIP file deployment package containing the changes and put the file into the correct location on Amazon S3. When the function is invoked, the code changes have not been applied. What step is required to update the function with the changes?

		A. Delete the .ZIP file on S3, and re-upload by using a different object key name.
		B. Update the CloudFormation stack with the correct values for the function code properties S3Bucket, S3Key, or S3ObjectVersion.
		C. Ensure that the function source code is base64-encoded before uploading the deployment package to S3.
		D. Modify the execution role of the Lambda function to allow S3 access permission to the deployment package .ZIP file.

Answer: A

66. An AWS Elastic Beanstalk application needs to be deployed in multiple regions and requires a different Amazon Machine Image (AMI) in each region. Which AWS CloudFormation template key can be used to specify the correct AMI for each region?

		A. Parameters
		B. Outputs
		C. Mappings
		D. Resources

Answer: C

67. A Developer is designing a new application that uses Amazon S3. To satisfy compliance requirements, the Developer must encrypt the data at rest. How can the Developer accomplish this?

		A. Use s3:x-amz-acl as a condition in the S3 bucket policy.
		B. Use Amazon RDS with default encryption.
		C. Use aws:SecureTransport as a condition in the S3 bucket policy.
		D. Turn on S3 default encryption for the S3 bucket.

Answer: D

68. A Developer wants to enable AWS X-Ray for a secure application that runs in an Amazon ECS environment. What combination of steps will enable X-Ray? (Select THREE.)

		A. Create a Docker image that runs the X-Ray daemon.
		B. Add instrumentation to the application code for X-Ray.
		C. Install the X-Ray daemon on the underlying EC2 instance.
		D. Configure and use an IAM EC2 instance role.
		E. Register the application with X-Ray.
		E. Configure and use an IAM role for tasks.

Answer: A E F

69. A Developer must deploy a new AWS Lambda function using an AWS CloudFormation template. Which procedures will deploy a Lambda function? (Select TWO.)

		A. Upload the code to an AWS CodeCommit repository, then add a reference to it in an AWS::Lambda::Function resource in the template.
		B. Create an AWS::Lambda::Function resource in the template, then write the code directly inside the CloudFormation template.
		C. Upload a .ZIP file containing the function code to Amazon S3, then add a reference to it in an AWS::Lambda::Function resource in the template.
		D. Upload a .ZIP file to AWS CloudFormation containing the function code, then add a reference to it in an AWS::Lambda::Function resource in the template.
		E. Upload the function code to a private Git repository, then add a reference to it in an AWS::Lambda::Function resource in the template.

Answer: A B

70. A Developer has published an update to an application that is served to a global user base using Amazon CloudFront. After deploying the application, users are not able to see the updated changes. How can the Developer resolve this issue?

		A. Remove the origin from the CloudFront configuration and add it again.
		B. Disable forwarding of query strings and request headers from the CloudFront distribution configuration.
		C. Invalidate all the application objects from the edge caches.
		D. Disable the CloudFront distribution and enable it again to update all the edge locations.

Answer: C

71. A Developer wants to find a list of items in a global secondary index from an Amazon DynamoDB table. Which DynamoDB API call can the Developer use in order to consume the LEAST number of read capacity units?

		A. Scan operation using eventually-consistent reads
		B. Query operation using strongly-consistent reads
		C. Query operation using eventually-consistent reads
		D. Scan operation using strongly-consistent reads

Answer: C

72. An AWS Lambda function generates a 3MB JSON file and then uploads it to an Amazon S3 bucket daily. The file contains sensitive information, so the Developer must ensure that it is encrypted before uploading to the bucket. Which of the following modifications should the Developer make to ensure that the data is encrypted before uploading it to the bucket?

		A. Use the default AWS KMS customer master key for S3 in the Lambda function code.
		B. Use the S3 managed key and call the GenerateDataKey API to encrypt the file.
		C. Use the GenerateDateKey API, then use that data key to encrypt the file in the Lambda function code.
		D. Use a custom KMS customer master key created for S3 in the Lambda function code.

Answer: C

73. A company needs to secure its existing website running behind an Elastic Load Balancer. The website’s Amazon EC2 instances are CPU-constrained. What should be done to secure the website while not increasing the CPU load on the EC2 web servers? (Select TWO.)

		A. Configure an Elastic Load Balancer with SSL pass-through.
		B. Configure SSL certificates on an Elastic Load Balancer.
		C. Configure an Elastic Load Balancer with a Loadable Storage System.
		D. Install SSL certificates on the EC2 instances.
		E. Configure an Elastic Load Balancer with SSL termination.

Answer: B E

74. How should custom libraries be utilized in AWS Lambda?

		A. Host the library on Amazon S3 and reference to it from the Lambda function.
		B. Install the library locally and upload a ZIP file of the Lambda function.
		C. Import the necessary Lambda blueprint when creating the function.
		D. Modify the function runtime to include the necessary library.

Answer: B

75. In a move toward using microservices, a company’s Management team has asked all Development teams to build their services so that API requests depend only on that service’s data store. One team is building a Payments service which has its own database; the service needs data that originates in the Accounts database. Both are using Amazon DynamoDB. What approach will result in the simplest, decoupled, and reliable method to get near-real time updates from the Accounts database?

		A. Use Amazon Glue to perform frequent ETL updates from the Accounts database to the Payments database.
		B. Use Amazon ElastiCache in Payments, with the cache updated by triggers in the Accounts database.
		C. Use Amazon Kinesis Data Firehouse to deliver all changes from the Accounts database to the Payments database.
		D. Use Amazon DynamoDB Streams to deliver all changes from the Accounts database to the Payments database.

Answer: D

76. A Developer is designing a fault-tolerant environment where client sessions will be saved. How can the Developer ensure that no sessions are lost if an Amazon EC2 instance fails?

		A. Use sticky sessions with an Elastic Load Balancer target group.
		B. Use Amazon SQS to save session data.
		C. Use Amazon DynamoDB to perform scalable session handling.
		D. Use Elastic Load Balancer connection draining to stop sending requests to failing instances.

Answer: C

77. A Developer is writing an imaging micro service on AWS Lambda. The service is dependent on several libraries that are not available in the Lambda runtime environment. Which strategy should the Developer follow to create the Lambda deployment package?

		A. Create a ZIP file with the source code and all dependent libraries.
		B. Create a ZIP file with the source code and a script that installs the dependent libraries at runtime.
		C. Create a ZIP file with the source code. Stage the dependent libraries on an Amazon S3 bucket indicated by the Lambda environment variable LD_LIBRARY_PATH
		D. Create a ZIP file with the source code and a buildspec.yaml file that installs the dependent libraries on AWS Lambda.

Answer: A

78. A Developer is writing a serverless application that requires that an AWS Lambda function be invoked every 10 minutes. What is an automated and serverless way to trigger the function?

		A. Deploy an Amazon EC2 instance based on Linux, and edit its /etc/crontab file by adding a command to periodically invoke the Lambda function.
		B. Configure an environment variable named PERIOD for the Lambda function. Set the value to 600.
		C. Create an Amazon CloudWatch Events rule that triggers on a regular schedule to invoke the Lambda function.
		D. Create an Amazon SNS topic that has a subscription to the Lambda function with a 600-second timer

Answer: C

79. A company needs a fully-managed source control service that will work in AWS. The service must ensure that revision control synchronizes multiple distributed repositories by exchanging sets of changes peer-to-peer. All users need to work productively even when not connected to a network. Which source control service should be used?

		A. Subversion
		B. AWS CodeBuild
		C. AWS CodeCommit
		D. AWS CodeStar

Answer: C

80. An application running on Amazon EC2 instances must access objects within an Amaon S3 busket that are encrypted using server-side encryption using AWS KMS encryption keys (SSEKMS). The application must have access to the customer master key (CMK) to decrypt the objects. Which combination of steps will grant the application access? (Select TWO.)

		A. Write an S3 bucket policy that grants the bucket access to the key.
		B. Grant access to the key in the IAM EC2 role attached to the application’s EC2 instances.
		C. Write a key policy that enables IAM policies to grant access to the key.
		D. Grant access to the key in the S3 bucket’s ACL
		E. Create a Systems Manager parameter that exposes the KMS key to the EC2 instances

Answer: B E

81. A Developer is creating a mobile application that will not require users to log in. What is the MOST efficient method to grant users access to AWS resources?

		A. Use an identity provider to securely authenticate with the application.
		B. Create an AWS Lambda function to create an IAM user when a user accesses the application.
		C. Create credentials using AWS KMS and apply these credentials to users when using the application.
		D. Use Amazon Cognito to associate unauthenticated users with an IAM role that has limited access to resources.

Answer: D

82. A company is building an application to track athlete performance using an Amazon DynamoDB table. Each item in the table is identified by a partition key (user_id) and a sort key (sport_name). The table design is shown below: A Developer is asked to write a leaderboard application to display the top performers (user_id) based on the score for each sport_name. What process will allow the Developer to extract results MOST efficiently from the DynamoDB table?

		A. Use a DynamoDB query operation with the key attributes of user_id and sport_name and order the results based on the score attribute.
		B. Create a global secondary index with a partition key of sport_name and a sort key of score, and get the results
		C. Use a DynamoDB scan operation to retrieve scores and user_id based on sport_name, and order the results based on the score attribute.
		D. Create a local secondary index with a primary key of sport_name and a sort key of score and get the results based on the score attribute.

Answer: B

83. A company recently migrated its web, application and NoSQL database tiers to AWS. The company is using Auto Scaling to scale the web and application tiers. More than 95 percent of the Amazon DynamoDB requests are repeated read-requests. How can the DynamoDB NoSQL tier be scaled up to cache these repeated requests?

		A. Amazon EMR
		B. Amazon DynamoDB Accelerator
		C. Amazon SQS
		D. Amazon CloudFront

Answer: B

84. A company has multiple Developers located across the globe who are updating code incrementally for a development project. When Developers upload code concurrently, internet connectivity is slow and it is taking a long time to upload code for deployment in AWS Elastic Beanstalk. Which step will result in minimized upload and deployment time with the LEAST amount of administrative effort?

		A. Allow the Developers to upload the code to an Amazon S3 bucket, and deploy it directly to Elastic Beanstalk.
		B. Allow the Developers to upload the code to a central FTP server to deploy the application to Elastic Beanstalk.
		C. Create an AWS CodeCommit repository, allow the Developers to commit code to it, and then directly deploy the code to Elastic Beanstalk.
		D. Create a code repository on an Amazon EC2 instance so that all Developers can update the code, and deploy the application from the instance to Elastic Beanstalk.

Answer: C

85. What does an Amazon SQS delay queue accomplish?

		A. Messages are hidden for a configurable amount of time when they are first added to the queue.
		B. Messages are hidden for a configurable amount of time after they are consumed from the queue.
		C. The consumer can poll the queue for a configurable amount of time before retrieving a message.
		D. Message cannot be deleted for a configurable amount of time after they are consumed from the queue.

Answer: A

86. A Developer is using AWS CLI, but when running list commands on a large number of resources, it is timing out. What can be done to avoid this time-out?

		A. Use pagination
		B. Use shorthand syntax
		C. Use parameter values
		D. Use quoting strings

Answer: A

87. A Development team is working on a case management solution that allows medical claims to be processed and reviewed. Users log in to provide information related to their medical and financial situations. As part of the application, sensitive documents such as medical records, medical imaging, bank statements, and receipts are uploaded to Amazon S3. All documents must be securely transmitted and stored. All access to the documents must be recorded for auditing. What is the MOST secure approach?

		A. Use S3 default encryption using Advanced Encryption Standard-256 (AES-256) on the destination bucket.
		B. Use Amazon Cognito for authorization and authentication to ensure the security of the application and documents.
		C. Use AWS Lambda to encrypt and decrypt objects as they are placed into the S3 bucket.
		D. Use client-side encryption/decryption with Amazon S3 and AWS KMS.

Answer: D

88. An application uses Amazon Kinesis Data Streams to ingest and process large streams of data records in real time. Amazon EC2 instances consume and process the data from the shards of the Kinesis data stream by using Amazon Kinesis Client Library (KCL). The application handles the failure scenarios and does not require standby workers. The application reports that a specific shard is receiving more data than expected. To adapt to the changes in the rate of data flow, the “hot” shard is resharded. Assuming that the initial number of shards in the Kinesis data stream is 4, and after resharding the number of shards increased to 6, what is the maximum number of EC2 instances that can be deployed to process data from all the shards?

		A. 12
		B. 6
		C. 4
		D. 1

Answer: B

89. Where can PortMapping be defined when launching containers in Amazon ECS?

		A. Security groups
		B. Amazon Elastic Container Registry (Amzon ECR)
		C. Container agent
		D. Task definition

Answer: D

90. A stock market monitoring application uses Amazon Kinesis for data ingestion. During simulated tests of peak data rates, the Kinesis stream cannot keep up with the incoming data. What step will allow Kinesis to accommodate the traffic during peak hours?

		A. Install the Kinesis Producer Library (KPL) for ingesting data into the stream.
		B. Reduce the data retention period to allow for more data ingestion using DecreaseStreamRetentionPeriod.
		C. Increase the shard count of the stream using UpdateShardCount.
		D. Ingest multiple records into the stream in a single call using PutRecords.

Answer: A

91. While developing an application that runs on Amazon EC2 in an Amazon VPC, a Developer identifies the need for centralized storage of application-level logs. Which AWS service can be used to securely store these logs?

		A. Amazon EC2 VPC Flow Logs
		B. Amazon CloudWatch Logs
		C. Amazon CloudSearch
		D. AWS CloudTrail

Answer: B

92. An organization is storing large files in Amazon S3, and is writing a web application to display meta-data about the files to end-users. Based on the metadata a user selects an object to download. The organization needs a mechanism to index the files and provide single-digit millisecond latency retrieval for the metadata. What AWS service should be used to accomplish this?

		A. Amazon DynamoDB
		B. Amazon EC2
		C. AWS Lambda
		D. Amazon RDS

Answer: A

93. An on-premises application makes repeated calls to store files to Amazon S3. As usage of the application has increased, “LimitExceeded” errors are being logged. What should be changed to fix this error?

		A. Implement exponential backoffs in the application.
		B. Load balance the application to multiple servers.
		C. Move the application to Amazon EC2.
		D. Add a one second delay to each API call.

Answer: A

94. A Developer wants to encrypt new objects that are being uploaded to an Amazon S3 bucket by an application. There must be an audit trail of who has used the key during this process. There should be no change to the performance of the application. Which type of encryption meets these requirements?

		A. Server-side encryption using S3-managed keys
		B. Server-side encryption with AWS KMS-managed keys
		C. Client-side encryption with a client-side symmetric master key
		D. Client-side encryption with AWS KMS-managed keys

Answer: B

95. A company has an AWS CloudFormation template that is stored as a single file. The template is able to launch and create a full infrastructure stack. Which best practice would increase the maintainability of the template?

		A. Use nested stacks for common template patterns.
		B. Embed credentials to prevent typos.
		C. Remove mappings to decrease the number of variables.
		D. Use AWS::Include to reference publicly-hosted template files.

Answer: A

96. The upload of a 15 GB object to Amazon S3 fails. The error message reads: “Your proposed upload exceeds the maximum allowed object size.” What technique will allow the Developer to upload this object?

		A. Upload the object using the multi-part upload API.
		B. Upload the object over an AWS Direct Connect connection.
		C. Contact AWS Support to increase the object size limit.
		D. Upload the object to another AWS region.

Answer: A

97. An application is expected to process many files. Each file takes four minutes to process each AWS Lambda invocation. The Lambda function does not return any important data. What is the fastest way to process all the files?

		A. First split the files to make them smaller, then process with synchronous RequestResponse Lambda invocations.
		B. Make synchronous RequestResponse Lambda invocations and process the files one by one.
		C. Make asynchronous Event Lambda invocations and process the files in parallel.
		D. First join all the files, then process it all at once with an asynchronous Event Lambda invocation.

Answer: C

98. A company caches session information for a web application in an Amazon DynamoDB table. The company wants an automated way to delete old items from the table. What is the simplest way to do this?

		A. Write a script that deletes old records; schedule the scripts as a cron job on an Amazon EC2 instance.
		B. Add an attribute with the expiration time; enable the Time To Live feature based on that attribute.
		C. Each day, create a new table to hold session data; delete the previous day’s table.
		D. Add an attribute with the expiration time; name the attribute ItemExpiration.

Answer: B

99. AWS CodeBuild builds code for an application, creates the Docker image, pushes the image to Amazon Elastic Container Registry (Amazon ECR), and tags the image with a unique identifier. If the Developers already have AWS CLI configured on their workstations, how can the Docker images be pulled to the workstations?

		A. Run the following: docker pull REPOSITORY URI : TAG
		B. Run the output of the following: aws ecr get-login and then run: docker pull REPOSITORY URI : TAG
		C. Run the following: aws ecr get-login and then run: docker pull REPOSITORY URI : TAG
		D. Run the output of the following: aws ecr get-download-url-for-layer and then run: docker pull REPOSITORY URI : TAG

Answer: B

100. Queries to an Amazon DynamoDB table are consuming a large amount of read capacity. The table has a significant number of large attributes. The application does not need all of the attribute data. How can DynamoDB costs be minimized while maximizing application performance?

    A. Batch all the writes, and perform the write operations when no or few reads are being performed.
    B. Create a global secondary index with a minimum set of projected attributes.
    C. Implement exponential backoffs in the application.
    D. Load balance the reads to the table using an Application Load Balancer

Answer: B

101. An application is running on an EC2 instance. The Developer wants to store an application metric in Amazon CloudWatch. What is the best practice for implementing this requirement?

    A. Use the PUT Object API call to send data to an S3 bucket. Use an event notification to invoke a Lambda function to publish data to CloudWatch.
    B. Publish the metric data to an Amazon Kinesis Stream using a PutRecord API call. Subscribe a Lambda function that publishes data to CloudWatch.
    C. Use the CloudWatch PutMetricData API call to submit a custom metric to CloudWatch. Provide the required credentials to enable the API call.
    D. Use the CloudWatch PutMetricData API call to submit a custom metric to CloudWatch. Launch the EC2 instance with the required IAM role to enable the API call

Answer: D

102. A company needs a new REST API that can return information about the contents of an Amazon S3 bucket, such as a count of the objects stored in it. The company has decided that the new API should be written as a microservice using AWS Lambda and Amazon API Gateway. How should the Developer ensure that the microservice has the necessary access to the Amazon S3 bucket, while adhering to security best practices?

    A. Create an IAM user that has permissions to access the Amazon S3 bucket, and store the IAM user credentials in the Lambda function source code.
    B. Create an IAM role that has permissions to access the Amazon S3 bucket and assign it to the Lambda function as its execution role.
    C. Create an Amazon S3 bucket policy that specifies the Lambda service as its principal and assign it to the Amazon S3 bucket.
    D. Create an IAM role, attach the AmazonS3FullAccess managed policy to it, and assign the role to the Lambda function as its execution role

Answer: B

103. A web application is designed to allow new users to create accounts using their email addresses. The application will store attributes for each user, and is expecting millions of user to sign up. What should the Developer implement to achieve the design goals?

    A. Amazon Cognito user pools
    B. AWS Mobile Hub user data storage
    C. Amazon Cognito Sync
    D. AWS Mobile Hub cloud logic

Answer: A

104. An application is using Amazon DynamoDB as its data store, and should be able to read 100 items per second as strongly consistent reads. Each item is 5 KB in size. To what value should the table’s provisioned read throughput be set?

    A. 50 read capacity units
    B. 100 read capacity units
    C. 200 read capacity units
    D. 500 read capacity units

Answer: C

105. An organization is using Amazon CloudFront to ensure that its users experience low-latency access to its web application. The organization has identified a need to encrypt all traffic between users and CloudFront, and all traffic between CloudFront and the web application. How can these requirements be met? (Choose two.)

    A. Use AWS KMS to encrypt traffic between CloudFront and the web application.
    B. Set the Origin Protocol Policy to “HTTPS Only”.
    C. Set Origin’s HTTP Port to 443.
    D. Set the Viewer Protocol Policy to “HTTPS Only” or “Redirect HTTP to HTTPS”.
    E. Enable the CloudFront option Restrict Viewer Access.

Answer: B D

106. An application uses Lambda functions to extract metadata from files uploaded to an S3 bucket; the metadata is stored in Amazon DynamoDB. The application starts behaving unexpectedly, and the Developer wants to examine the logs of the Lambda function code for errors. Based on this system configuration, where would the Developer find the logs?

    A. Amazon S3
    B. AWS CloudTrail
    C. Amazon CloudWatch
    D. Amazon DynamoDB

Answer: C

107. A Developer has developed a web application and wants to deploy it quickly on a Tomcat server on AWS. The Developer wants to avoid having to manage the underlying infrastructure. What is the easiest way to deploy the application, based on these requirements?

    A. AWS CloudFormation
    B. AWS Elastic Beanstalk
    C. Amazon S3
    D. AWS CodePipeline

Answer: B

108. A Developer is creating a Lambda function that will generate and export a file. The function requires 100 MB of temporary storage for temporary files while executing. These files will not be needed after the function is complete. How can the Developer MOST efficiently handle the temporary files?

    A. Store the files in EBS and delete the files at the end of the Lambda function.
    B. Copy the files to EFS and delete the files at the end of the Lambda function.
    C. Store the files in the /tmp directory and delete the files at the end of the Lambda function.
    D. Copy the files to an S3 bucket with a lifecycle policy to delete the files.

Answer: C

109. An application runs on multiple EC2 instances behind an ELB. Where is the session data best written so that it can be served reliably across multiple requests?

    A. Write data to Amazon ElastiCache
    B. Write data to Amazon Elastic Block Store.
    C. Write data to Amazon EC2 Instance Store.
    D. Write data to the root filesystem.

Answer: A

110. A company is migrating from a monolithic architecture to a microservices-based architecture. The Developers need to refactor the application so that the many microservices can asynchronously communicate with each other without impacting performance. Use of which managed AWS services will enable asynchronous message passing? (Choose two.)

    A. Amazon SQS
    B. Amazon Cognito
    C. Amazon Kinesis
    D. Amazon SNS
    E. Amazon ElastiCache

Answer: A D

111. An application running on an Amazon Linux EC2 instance needs to manage the AWS infrastructure. How can the EC2 instance be configured to make AWS API calls securely?

    A. Sign the AWS CLI command using the signature version 4 process.
    B. Run the aws configure AWS CLI command and specify the access key id and secret access key.
    C. Specify a role for the EC2 instance with the necessary privileges.
    D. Pass the access key id and secret access key as parameters for each AWS CLI command.

Answer: C

112. The development team is working on an API that will be served from Amazon API gateway. The API will be served from three environments: development, test, and production. The API Gateway is configured to use 237 GB of cache in all three stages. Which is the MOST cost-efficient deployment strategy?

    A. Create a single API Gateway with all three stages.
    B. Create three API Gateways, one for each stage in a single AWS account.
    C. Create an API Gateway in three separate AWS accounts.
    D. Enable the cache for development and test environments only when needed.

Answer: D

113. According to best practice, how should access keys be managed in AWS? (Choose two.)

    A. Use the same access key in all applications for consistency.
    B. Delete all access keys for the account root user.
    C. Leave unused access keys in the account for tracking purposes.
    D. Embed and encrypt access keys in code for continuous deployment.
    E. Use Amazon IAM roles instead of access keys where possible.

Answer: B E

114. A development team is using AWS Elastic Beanstalk to deploy a two-tier application that consists of a load-balanced web tier and an Amazon RDS database tier in production. The team would like to separate the RDS instance from the Elastic Beanstalk. How can this be accomplished?

    A. Use the Elastic Beanstalk CLI to disassociate the database.
    B. Use the AWS CLI to disassociate the database.
    C. Change the deployment policy to disassociate the database.
    D. Recreate a new Elastic Beanstalk environment without Amazon RDS.

Answer: D

115. An application needs to use the IP address of the client in its processing. The application has been moved into AWS and has been placed behind an Application Load Balancer (ALB). However, all the client IP addresses now appear to be the same. The application must maintain the ability to scale horizontally. Based on this scenario, what is the MOST cost-effective solution to this problem?

    A. Remove the application from the ALB. Delete the ALB and change Amazon Route 53 to direct traffic to the instance running the application.
    B. Remove the application from the ALB. Create a Classic Load Balancer in its place. Direct traffic to the application using the HTTP protocol.
    C. Alter the application code to inspect the X-Forwarded-For header. Ensure that the code can work properly if a list of IP addresses is passed in the header.
    D. Alter the application code to inspect a custom header. Alter the client code to pass the IP address in the custom header.

Answer: C

116. A website’s page load times are gradually increasing as more users access the system at the same time. Analysis indicates that a user profile is being loaded from a database in all the web pages being visited by each user and this is increasing the database load and the page load latency. To address this issue the Developer decides to cache the user profile data. Which caching strategy will address this situation MOST efficiently?

    A. Create a new Amazon EC2 Instance and run a NoSQL database on it. Cache the profile data within this database using the write-through caching strategy.
    B. Create an Amazon ElastiCache cluster to cache the user profile data. Use a cache-aside caching strategy.
    C. Use a dedicated Amazon RDS instance for caching profile data. Use a write-through caching strategy.
    D. Create an ElastiCache cluster to cache the user profile data. Use a write-through caching strategy.

Answer: B

117. A social media company is using Amazon Cognito in order to synchronize profiles across different mobile devices, to enable end users to have a seamless experience. Which of the following configurations can be used to silently notify users whenever an update is available on all other devices?

    A. Modify the user pool to include all the devices which keep them in sync.
    B. Use the SyncCallback interface to receive notifications on the application.
    C. Use an Amazon Cognito stream to analyze the data and push the notifications.
    D. Use the push synchronization feature with the appropriate IAM role.

Answer: D

118. A company is using AWS CodePipeline to deliver one of its applications. The delivery pipeline is triggered by changes to the master branch of an AWS CodeCommit repository and uses AWS CodeBuild to implement the test and build stages of the process and AWS CodeDeploy to deploy the application. The pipeline has been operating successfully for several months and there have been no modifications. Following a recent change to the application’s source code, AWS CodeDeploy has not deployed the updates application as expected. What are the possible causes? (Choose two.)

    A. The change was not made in the master branch of the AWS CodeCommit repository 
    B. One of the earlier stages in the pipeline failed and the pipeline has terminated.
    C. One of the Amazon EC2 instances in the company’s AWS CodePipeline cluster is inactive.
    D. The AWS CodePipeline is incorrectly configured and is not executing AWS CodeDeploy.
    E. AWS CodePipeline does not have permissions to access AWS CodeCommit.

Answer: A

119. An application displays a status dashboard. The status is updated by 1 KB messages from an SQS queue. Although the status changes infrequently, the Developer must minimize the time between the message arrival in the queue and the dashboard update. What technique provides the shortest delay in updating the dashboard?

    A. Retrieve the messages from the queue using long polling every 20 seconds.
    B. Reduce the size of the messages by compressing them before sending.
    C. Retrieve the messages from the queue using short polling every 10 seconds.
    D. Reduce the size of each message payload by sending it in two parts

Answer: A

120. An on-premises application is implemented using a Linux, Apache, MySQL and PHP (LAMP) stack. The Developer wants to run this application in AWS. Which of the following sets of AWS services can be used to run this stack?

    A. Amazon API Gateway, Amazon S3
    B. AWS Lambda, Amazon DynamoDB
    C. Amazon EC2, Amazon Aurora
    D. Amazon Cognito, Amazon RDS
    E. Amazon ECS, Amazon EBS

Answer: C
