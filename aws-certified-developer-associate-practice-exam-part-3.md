Notes: Hi all, We’re sharing AWS Developer Associate (DVA-C01) Practice Exam Part 3 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Developer Associate Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \ 
For GCP: https://www.gcp-examquestions.com

120. An on-premises application is implemented using a Linux, Apache, MySQL and PHP (LAMP) stack. The Developer wants to run this application in AWS. Which of the following sets of AWS services can be used to run this stack?

	A. Amazon API Gateway, Amazon S3
	B. AWS Lambda, Amazon DynamoDB
	C. Amazon EC2, Amazon Aurora
	D. Amazon Cognito, Amazon RDS
	E. Amazon ECS, Amazon EBS

121. A gaming company is developing a mobile game application for iOS® and Android® platforms. This mobile game securely stores user data locally on the device. The company wants to allow users to use multiple device for the game, which requires user data synchronization across device. Which service should be used to synchronize user data across devices without the need to create a backend application?

	A. AWS Lambda
	B. Amazon S3
	C. Amazon DynamoDB
	D. Amazon Cognito

122. A Developer must trigger an AWS Lambda function based on the item lifecycle activity in an Amazon DynamoDB table. How can the Developer create the solution?

	A. Enable a DynamoDB stream that publishes an Amazon SNS message. Trigger the Lambda function synchronously from the SNS message.
	B. Enable a DynamoDB stream that publishes an SNS message. Trigger the Lambda function asynchronously from the SNS message.
	C. Enable a DynamoDB stream, and trigger the Lambda function synchronously from the stream.
	D. Enable a DynamoDB stream, and trigger the Lambda function asynchronously from the stream

123. An on-premises legacy application is caching data files locally and writing shared images to local disks. What is necessary to allow for horizontal scaling when migrating the application to AWS?

	A. Modify the application to have both shared images and caching data written to Amazon EBS.
	B. Modify the application to read and write cache data on Amazon S3, and also store shared images on S3.
	C. Modify the application to use Amazon S3 for serving shared images; cache data can then be written to local disks.
	D. Modify the application to read and write cache data on Amazon S3, while continuing to write shared images to local disks.

124. After installing the AWS CLI, a Developer tries to run the command aws configure but receives the following error: Error: aws: command not found What is the most likely cause of this error?

	A. The aws executable is not in the PATH environment variable.
	B. Access to the aws executable has been denied to the installer.
	C. Incorrect AWS credentials were provided.
	D. The aws script does not have an executable file mode.

125. A Developer will be using the AWS CLI on a local development server to manage AWS services. What can be done to ensure that the CLI uses the Developer’s IAM permissions when making commands?

	A. Specify the Developer’s IAM access key ID and secret access key as parameters for each CLI command.
	B. Run the aws configure CLI command, and provide the Developer’s IAM access key ID and secret access key.
	C. Specify the Developer’s IAM user name and password as parameters for each CLI command.
	D. Use the Developer’s IAM role when making the CLI command.

126. A Developer needs to use AWS X-Ray to monitor an application that is deployed on EC2 instances. What steps have to be executed to perform the monitoring?

	A. Deploy the X-Ray SDK with the application and use X-Ray annotation.
	B. Install the X-Ray daemon and instrument the application code.
	C. Install the X-Ray daemon and configure it to forward data to Amazon CloudWatch Events.
	D. Deploy the X-Ray SDK with the application and instrument the application code.

127. An application is real-time processing millions of events that are received through an API. What service could be used to allow multiple consumers to process the data concurrently and MOST cost-effectively?

	A. Amazon SNS with fanout to an SQS queue for each application
	B. Amazon SNS with fanout to an SQS FIFO (first-in, first-out) queue for each application
	C. Amazon Kinesis Firehose
	D. Amazon Kinesis Streams

128. A Developer is creating a mobile application with a limited budget. The solution requires a scalable service that will enable customers to sign up and authenticate into the mobile application while using the organization’s current SAML 2.0 identity provider. Which AWS service should be used to meet these requirements?

	A. AWS Lambda
	B. Amazon Cognito
	C. AWS IAM
	D. Amazon EC2

129. The Developer for a retail company must integrate a fraud detection solution into the order processing solution. The fraud detection solution takes between ten and thirty minutes to verify an order. At peak, the web site can receive one hundred orders per minute. What is the most scalable method to add the fraud detection solution to the order processing pipeline?

	A. Add all new orders to an Amazon SQS queue. Configure a fleet of 10 EC2 instances spanning multiple AZs with the fraud detection solution installed on them to pull orders from this queue. Update the order with a pass or fails status.
	B. Add all new orders to an SQS queue. Configure an Auto Scaling group that uses the queue depth metric as its unit of scale to launch a dynamically-sized fleet of EC2 instances spanning multiple AZs with the fraud detection solution installed on them to pull orders from this queue. Update the order with a pass or fails status.
	C. Add all new orders to an Amazon Kinesis Stream. Subscribe a Lambda function to automatically read batches of records from the Kinesis Stream. The Lambda function includes the fraud detection software and will update the order with a pass or fail status.
	D. Write all new orders to Amazon DynamoDB. Configure DynamoDB Streams to include all new orders. Subscribe a Lambda function to automatically read batches of records from the Kinesis Stream. The Lambda function includes the fraud detection software and will update the order with a pass or fail status.

130. A Lambda function is packaged for deployment to multiple environments, including development,test, production, etc. Each environment has unique set of resources such as databases, etc. How can the Lambda function use the resources for the current environment?

	A. Apply tags to the Lambda functions.
	B. Hardcore resources in the source code.
	C. Use environment variables for the Lambda functions.
	D. Use separate function for development and production

131. When a Developer tries to run an AWS CodeBuild project, it raises an error because the length of all environment variables exceeds the limit for the combined maximum of characters. What is the recommended solution?

	A. Add the export LC_ALL=“en_US.utf8” command to the pre_build section to ensure POSIX localization.
	B. Use Amazon Cognito to store key-value pairs for large numbers of environment variables.
	C. Update the settings for the build project to use an Amazon S3 bucket for large numbers of environment variables.
	D. Use AWS Systems Manager Parameter Store to store large numbers of environment variables.

132. A company needs to encrypt data at rest, but it wants to leverage an AWS managed service using its own master key Which of the following AWS service can be used to meet these requirements?

	A. SSE with Amazon S3
	B. SSE with AWS KMS
	C. Client-side encryption
	D. AWS IAM roles and policies

133. A company is developing a new online game that will run on top of Amazon ECS. Four distinct Amazon ECS services will be part of the architecture, each requiring specific permissions to various AWS services. The company wants to optimize the use of the underlying Amazon EC2 instances by bin packing the containers based on memory reservation. Which configuration would allow the Development team to meet these requirements MOST securely?

	A. Create a new Identity and Access Management (IAM) instance profile containing the required permissions for the various ECS services, then associate that instance role with the underlying EC2 instances.
	B. Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then configure each ECS service to reference the associated IAM role.
	C. Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then, create an IAM group and configure the ECS cluster to reference that group.
	D. Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then configure each ECS task definition to reference the associated IAM role.

134. An application running on EC2 instances is storing data in an S3 bucket. Security policy mandates that all data must be encrypted in transit. How can the Developer ensure that all traffic to the S3 bucket is encrypted?

	A. Install certificates on the EC2 instances.
	B. Create a bucket policy that allows traffic where SecureTransport is true.
	C. Create an HTTPS redirect on the EC2 instances.
	D. Create a bucket policy that denies traffic where SecureTransport is false.

135. A Developer uses AWS CodeDeploy to automate application deployment that connects to an external MySQL database. The Developer wants to securely access the encrypted secrets, such as API keys and database passwords. Which of the following solutions would involve the LEAST administrative effort?

	A. Save the secrets in Amazon S3 with AWS KMS server-side encryption, and use a signed URL to access them by using the IAM role from Amazon EC2 instances.
	B. Use the instance metadata to store the secrets and to programmatically access the secrets from EC2 instances.
	C. Use the Amazon DynamoDB client-side encryption library to save the secrets in DynamoDB and to programmatically access the secrets from EC2 instances.
	D. Use AWS SSM Parameter Store to store the secrets and to programmatically access them by using the IAM role from EC2 instances

136. A set of APIs are exposed to customers using the Amazon API Gateway. These APIs have caching enabled on the API Gateway. Customers have asked for an option to invalidate this cache for each of the APIs. What action can be taken to allow API customers to invalidate the API Cache?

	A. Ask customers to use AWS credentials to call the InvalidateCache API.
	B. Ask customers to invoke an AWS API endpoint which invalidates the cache.
	C. Ask customers to pass an HTTP header called Cache-Control:max-age=0.
	D. Ask customers to add a query string parameter called “INVALIDATE_CACHE” when making an API call.

137. A Developer must repeatedly and consistently deploy a serverless RESTful API on AWS. Which techniques will work? (Choose two.)

	A. Define a Swagger file. Use AWS Elastic Beanstalk to deploy the Swagger file.
	B. Define a Swagger file. Use AWS CodeDeploy to deploy the Swagger file.
	C. Deploy a SAM template with an inline Swagger definition.
	D. Define a Swagger file. Deploy a SAM template that references the Swagger file.
	E. Define an inline Swagger definition in a Lambda function. Invoke the Lambda function

138. A Developer has been asked to build a real-time dashboard web application to visualize the key prefixes and storage size of objects in Amazon S3 buckets. Amazon DynamoDB will be used to store the Amazon S3 metadata. What is the optimal and MOST cost-effective design to ensure that the real-time dashboard is kept up to date with the state of the objects in the Amazon S3 buckets?

	A. Use an Amazon CloudWatch event backed by an AWS Lambda function. Issue an Amazon S3 API call to get a list of all Amazon S3 objects and persist the metadata within DynamoDB. Have the web application poll the DynamoDB table to reflect this change.
	B. Use Amazon S3 Event Notification backed by a Lambda function to persist the metadata into DynamoDB. Have the web application poll the DynamoDB table to reflect this change.
	C. Run a cron job within an Amazon EC2 instance to list all objects within Amazon S3 and persist the metadata into DynamoDB. Have the web application poll the DynamoDB table to reflect this change.
	D. Create a new Amazon EMR cluster to get all the metadata about Amazon S3 objects; persist the metadata into DynamoDB. Have the web application poll the DynamoDB table to reflect this change.

139. A customer wants to deploy its source code on an AWS Elastic Beanstalk environment. The customer needs to perform deployment with minimal outage and should only use existing instances to retain application access log. What deployment policy would satisfy these requirements?

	A. Rolling
	B. All at once
	C. Rolling with an additional batch
	D. Immutable

140. A Developer must re-implement the business logic for an order fulfilment system. The business logic has to make requests to multiple vendors to decide where to purchase an item. The whole process can take up to a week to complete. What is the MOST efficient and SIMPLEST way to implement a system that meets these requirements?

	A. Use AWS Step Functions to execute parallel Lambda functions, and join the results.
	B. Create an AWS SQS for each vendor, poll the queue from a worker instance, and join the results.
	C. Use AWS Lambda to asynchronously call a Lambda function for each vendor, and join the results.
	D. Use Amazon CloudWatch Events to orchestrate the Lambda functions.

141. An existing serverless application processes uploaded image files. The process currently uses a single Lambda function that takes an image file, performs the processing, and stores the file in Amazon S3. Users of the application now require thumbnail generation of the images. Users want to avoid any impact to the time it takes to perform the image uploads. How can thumbnail generation be added to the application, meeting user requirements while minimizing changes to existing code?

	A. Change the existing Lambda function handling the uploads to create thumbnails at the time of upload. Have the function store both the image and thumbnail in Amazon S3.
	B. Create a second Lambda function that handles thumbnail generation and storage. Change the existing Lambda function to invoke it asynchronously.
	C. Create an S3 event notification with a Lambda function destination. Create a new Lambda function to generate and store thumbnails.
	D. Create an S3 event notification to an SQS Queue. Create a scheduled Lambda function that processes the queue, and generates and stores thumbnails.

142. Where should the appspec.yml file be placed in order for AWS CodeDeploy to work?

	A. In the root of the application source code directory structure
	B. In the bin folder along with all the compiled code
	C. In an S3 bucket
	D. In the same folder as the application configuration files

143. The release process workflow of an application requires a manual approval before the code is deployed into the production environment. What is the BEST way to achieve this using AWS CodePipeline?

	A. Use multiple pipelines to allow approval
	B. Use an approval action in a stage
	C. Disable the stage transition to allow manual approval
	D. Disable a stage just prior the deployment stage

144. An application overwrites an object in Amazon S3, and then immediately reads the same object. Why would the application sometimes retrieve the old version of the object?

	A. S3 overwrite PUTS are eventually consistent, so the application may read the old object.
	B. The application needs to add extra metadata to label the latest version when uploading to Amazon S3.
	C. All S3 PUTS are eventually consistent, so the application may read the old object.
	D. The application needs to explicitly specify the latest version when retrieving the object.

145. An organization must store thousands of sensitive audio and video files in an Amazon S3 bucket. Organizational security policies require that all data written to this bucket be encrypted. How can compliance with this policy be ensured?

	A. Use AWS Lambda to send notifications to the security team if unencrypted objects are pun in the bucket.
	B. Configure an Amazon S3 bucket policy to prevent the upload of objects that do not contain the xamz-server-side-encryption header.
	C. Create an Amazon CloudWatch event rule to verify that all objects stored in the Amazon S3 bucket are encrypted.
	D. Configure an Amazon S3 bucket policy to prevent the upload of objects that contain the x-amzserver-side-encryption header.

146. A company has written a Java AWS Lambda function to be triggered whenever a user uploads an image to an Amazon S3 bucket. The function converts the original image to several different formats and then copies the resulting images to another Amazon S3 bucket. The Developers find that no images are being copied to the second Amazon S3 bucket. They have tested the code on an Amazon EC2 instance with 1GB of RAM, and it takes an average of 500 seconds to complete. What is the MOST likely cause of the problem?

	A. The Lambda function has insufficient memory and needs to be increased to 1 GB to match the Amazon EC2 instance
	B. Files need to be copied to the same Amazon S3 bucket for processing, so the second bucket needs to be deleted.
	C. Lambda functions have a maximum execution limit of 300 seconds, therefore the function is not complete.
	D. There is a problem with the Java runtime for Lambda, and the function needs to be converted to node.js

147. A company is using Amazon API Gateway to manage access to a set of microservices implemented as AWS Lambda functions. Following a bug report, the company makes a minor breaking change to one of the APIs. In order to avoid impacting existing clients when the new API is deployed, the company wants to allow clients six months to migrate from v1 to v2. Which approach should the Developer use to handle this change?

	A. Update the underlying Lambda function and provide clients with the new Lambda invocation URL.
	B. Use API Gateway to automatically propagate the change to clients, specifying 180 days in the phased deployment parameter.
	C. Use API Gateway to deploy a new stage named v2 to the API and provide users with its URL.
	D. Update the underlying Lambda function, create an Amazon CloudFront distribution with the updated Lambda function as its origin.

148. A Developer wants to use AWS X-Ray to trace a user request end-to-end throughput the software stack. The Developer made the necessary changes in the application, tested it, and found that the application is able to send the traces to AWS X-Ray. However, when the application is deployed to an EC2 instance, the traces are not available. Which of the following could create this situation? (Select two.)

	A. The traces are reaching X-Ray, but the Developer does not have access to view the records.
	B. The X-Ray daemon is not installed on the EC2 instance.
	C. The X-Ray endpoint specified in the application configuration is incorrect.
	D. The instance role does not have “xray:BatchGetTraces” and “xray:GetTraceGraph” permissions.
	E. The instance role does not have “xray:PutTraceSegments” and “xray:PutTelemetryRecords” permissions

149. A web application is using Amazon Kinesis Streams for clickstream data that may not be consumed for up to 12 hours. How can the Developer implement encryption at rest for data within the Kinesis Streams?

	A. Enable SSL connections to Kinesis
	B. Use Amazon Kinesis Consumer Library
	C. Encrypt the data once it is at rest with a Lambda function
	D. Enable server-side encryption in Kinesis Streams

150. A company is using AWS CodeBuild to compile a website from source code stored in AWS CodeCommit. A recent change to the source code has resulted in the CodeBuild project being unable to successfully compile the website. How should the Developer identify the cause of the failures?

	A. Modify the buildspec.yml file to include steps to send the output of build commands to Amazon CloudWatch.
	B. Use a custom Docker image that includes the AWS X-Ray agent in the AWS CodeBuild project configuration.
	C. Check the build logs of the failed phase in the last build attempt in the AWS CodeBuild project build history.
	D. Manually re-run the build process on a local machine so that the output can be visualized.
