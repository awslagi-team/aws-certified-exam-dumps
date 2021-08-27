Notes: Hi all, We’re sharing AWS Developer Associate (DVA-C01) Practice Exam Part 4 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Developer Associate Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \
For GCP: https://www.gcp-examquestions.com

151. A legacy service has an XML-based SOAP interface. The Developer wants to expose the functionality of the service to external clients with the Amazon API Gateway. Which technique will accomplish this?

                A. Create a RESTful API with the API Gateway; transform the incoming JSON into a valid XML message for the SOAP interface using mapping templates.
                B. Create a RESTful API with the API Gateway; pass the incoming JSON to the SOAP interface through an Application Load Balancer.
                C. Create a RESTful API with the API Gateway; pass the incoming XML to the SOAP interface through an Application Load Balancer.
                D. Create a RESTful API with the API Gateway; transform the incoming XML into a valid message for the SOAP interface using mapping templates.

152. A supplier is writing a new RESTful API for customers to query the status of orders. The customers requested the following API endpoint. http://www.supplierdomain.com/status/customerID Which of the following application designs meet the requirements? (Select two.)

                A. Amazon SQS; Amazon SNS
                B. Elastic Load Balancing; Amazon EC2
                C. Amazon ElastiCache; Amazon Elacticsearch Service
                D. Amazon API Gateway; AWS Lambda
                E. Amazon S3; Amazon CloudFront

153. A company developed a set of APIs that are being served through the Amazon API Gateway. The API calls need to be authenticated based on OpenID identity providers such as Amazon or Facebook. The APIs should allow access based on a custom authorization model. Which is the simplest and MOST secure design to use to build an authentication and authorization model for the APIs?

                A. Use Amazon Cognito user pools and a custom authorizer to authenticate and authorize users based on JSON Web Tokens.
                B. Build a OpenID token broker with Amazon and Facebook. Users will authenticate with these identity providers and pass the JSON Web Token to the API to authenticate each API call.
                C. Store user credentials in Amazon DynamoDB and have the application retrieve temporary credentials from AWS STS. Make API calls by passing user credentials to the APIs for authentication and authorization.
                D. Use Amazon RDS to store user credentials and pass them to the APIs for authentication and authorization.

154. A game stores user game data in an Amazon DynamoDB table. Individual users should not have access to other users’ game data. How can this be accomplished?

                A. Encrypt the game data with individual user keys.
                B. Restrict access to specific items based on certain primary key values.
                C. Stage data in SQS queues to inject metadata before accessing DynamoDB.
                D. Read records from DynamoDB and discard irrelevant data client-side.

155. A Developer is developing an application that manages financial transactions. To improve security, multi-factor authentication (MFA) will be required as part of the login protocol. What services can the Developer use to meet these requirements?

                A. Amazon DynamoDB to store MFA session data, and Amazon SNS to send MFA codes
                B. Amazon Cognito with MFA
                C. AWS Directory Service
                D. AWS IAM with MFA enabled

156. For a deployment using AWS CodeDeploy, what is the run order of the hooks for in-place deployments?

                A. Before Install -> Application Stop -> Application Start -> After Install
                B. Application Stop -> Before Install -> After Install -> Application Start
                C. Before Install -> Application Stop -> Validate Service -> Application Start
                D. Application Stop -> Before Install -> Validate Service -> Application Start

157. Amazon S3 has the following structure: S3://BUCKET/FOLDERNAME/FILENAME.zip Which S3 best practice would optimize performance with thousands of PUT request each second to a single bucket?

                A. Prefix folder names with user id; for example, s3://BUCKET/2013-FOLDERNAME/FILENAME.zip
                B. Prefix file names with timestamps; for example, s3://BUCKET/FOLDERNAME/2013-26-05-15-00- 00-FILENAME.zip
                C. Prefix file names with random hex hashes; for example, s3://BUCKET/FOLDERNAME/23a6- FILENAME.zip
                D. Prefix folder names with random hex hashes; for example, s3://BUCKET/23a6-FOLDERNAME/FILENAME.zip

158. A static website is hosted in an Amazon S3 bucket. Several HTML pages on the site use JavaScript to download images from another Amazon S3 bucket. These images are not displayed when users browse the site. What is the possible cause for the issue?

                A. The referenced Amazon S3 bucket is in another region.
                B. The images must be stored in the same Amazon S3 bucket.
                C. Port 80 must be opened on the security group in which the Amazon S3 bucket is located.
                D. Cross Origin Resource Sharing must be enabled on the Amazon S3 bucket.

159. A Developer has set up an Amazon Kinesis Stream with 4 shards to ingest a maximum of 2500 records per second. A Lambda function has been configured to process these records. In which order will these records be processed?

                A. Lambda will receive each record in the reverse order it was placed into the stream following a LIFO (last-in, first-out) method
                B. Lambda will receive each record in the exact order it was placed into the stream following a FIFO (first-in, first-out) method.
                C. Lambda will receive each record in the exact order it was placed into the shard following a FIFO (first-in, first-out) method. There is no guarantee of order across shards.                 D. The Developer can select FIFO, (first-in, first-out), LIFO (last-in, last-out), random, or request specific records using the getRecords API.

160. A Developer is creating an application that needs to locate the public IPv4 address of the Amazon EC2 instance on which it runs. How can the application locate this information?

                A. Get the instance metadata by retrieving http://169.254.169.254/latest/metadata/.
                B. Get the instance user data by retrieving http://169.254.169.254/latest/userdata/.
                C. Get the application to run IFCONFIG to get the public IP address.
                D. Get the application to run IPCONFIG to get the public IP address

161. An application under development is required to store hundreds of video files. The data must be encrypted within the application prior to storage, with a unique key for each video file. How should the Developer code the application?

                A. Use the KMS Encrypt API to encrypt the data. Store the encrypted data key and data.
                B. Use a cryptography library to generate an encryption key for the application. Use the encryption key to encrypt the data. Store the encrypted data.
                C. Use the KMS GenerateDataKey API to get a data key. Encrypt the data with the data key. Store the encrypted data key and data.
                D. Upload the data to an S3 bucket using server side-encryption with an AWS KMS key.

162. A Developer is writing a Linux-based application to run on AWS Elastic Beanstalk. Application requirements state that the application must maintain full capacity during updates while minimizing cost. Which type of Elastic Beanstalk deployment policy should the Developer specify for the environment?

                A. Immutable
                B. Rolling
                C. All at Once
                D. Rolling with additional batch

163. A Developer is creating a Lambda function and will be using external libraries that are not included in the standard Lambda libraries. What action would minimize the Lambda compute time consumed?

                A. Install the dependencies and external libraries at the beginning of the Lambda function.
                B. Create a Lambda deployment package that includes the external libraries.
                C. Copy the external libraries to Amazon S3, and reference the external libraries to the S3 location.
                D. Install the external libraries in Lambda to be available to all Lambda functions.

164. During non-peak hours, a Developer wants to minimize the execution time of a full Amazon DynamoDB table scan without affecting normal workloads. The workloads average half of the strongly consistent read capacity units during non-peak hours. How would the Developer optimize this scan?

                A. Use parallel scans while limiting the rate
                B. Use sequential scans
                C. Increase read capacity units during the scan operation
                D. Change consistency to eventually consistent during the scan operation

165. A Developer is writing transactions into a DynamoDB table called “SystemUpdates” that has 5 write capacity units. Which option has the highest read throughput?

                A. Eventually consistent reads of 5 read capacity units reading items that are 4 KB in size
                B. Strongly consistent reads of 5 read capacity units reading items that are 4 KB in size
                C. Eventually consistent reads of 15 read capacity units reading items that are 1 KB in size
                D. Strongly consistent reads of 15 read capacity units reading items that are 1 KB in size

166. A deployment package uses the AWS CLI to copy files into any S3 bucket in the account, using access keys stored in environment variables. The package is running on EC2 instances, and the instances have been modified to run with an assumed IAM role and a more restrictive policy that allows access to only one bucket. After the change, the Developer logs into the host and still has the ability to write into all of the S3 buckets in that account. What is the MOST likely cause of this situation?

                A. An IAM inline policy is being used on the IAM role
                B. An IAM managed policy is being used on the IAM role
                C. The AWS CLI is corrupt and needs to be reinstalled
                D. The AWS credential provider looks for instance profile credentials last

167. An application is designed to use Amazon SQS to manage messages from many independent senders. Each sender’s messages must be processed in the order they are received. Which SQS feature should be implemented by the Developer?

                A. Configure each sender with a unique MessageGroupId
                B. Enable MessageDeduplicationIds on the SQS queue
                C. Configure each message with unique MessageGroupIds.
                D. Enable ContentBasedDeduplication on the SQS queue

168. An application has hundreds of users. Each user may use multiple devices to access the application. The Developer wants to assign unique identifiers to these users regardless of the device they use. Which of the following methods should be used to obtain unique identifiers?

                A. Create a user table in Amazon DynamoDB as key-value pairs of users and their devices. Use these keys as unique identifiers.
                B. Use IAM-generated access key IDs for the users as the unique identifier, but do not store secret keys.
                C. Implement developer-authenticated identities by using Amazon Cognito, and get credentials for these identities.
                D. Assign IAM users and roles to the users. Use the unique IAM resource ID as the unique identifier.

169. A Developer created a Lambda function for a web application backend. When testing the Lambda function from the AWS Lambda console, the Developer can see that the function is being executed, but there is no log data being generated in Amazon CloudWatch Logs, even after several minutes. What could cause this situation?

                A. The Lambda function does not have any explicit log statements for the log data to send it to CloudWatch Logs.
                B. The Lambda function is missing CloudWatch Logs as a source trigger to send log data.
                C. The execution role for the Lambda function is missing permissions to write log data to the CloudWatch Logs.
                D. The Lambda function is missing a target CloudWatch Log group.

170. An Amazon RDS database instance is used by many applications to look up historical data. The query rate is relatively constant. When the historical data is updated each day, the resulting write traffic slows the read query performance and affects all application users. What can be done to eliminate the performance impact on application users?

                A. Make sure Amazon RDS is Multi-AZ so it can better absorb increased traffic.
                B. Create an RDS Read Replica and direct all read traffic to the replica.
                C. Implement Amazon ElastiCache in front of Amazon RDS to buffer the write traffic.
                D. Use Amazon DynamoDB instead of Amazon RDS to buffer the read traffic.

171. A Developer is trying to make API calls using SDK. The IAM user credentials used by the application require multi-factor authentication for all API calls. Which method the Developer use to access the multi-factor authentication protected API?

                A. GetFederationToken
                B. GetCallerIdentity
                C. GetSessionToken
                D. DecodeAutherizationMessage

172. A Developer is testing a Docker-based application that uses the AWS SDK to interact with Amazon DynamoDB. In the local development environment, the application has used IAM access keys. The application is now ready for deployment onto an ECS cluster. How should the application authenticate with AWS services in production?

                A. Configure an ECS task IAM role for the application to use
                B. Refactor the application to call AWS STS AssumeRole based on an instance role
                C. Configure AWS access key/secret access key environment variables with new credentials
                D. Configure the credentials file with a new access key/secret access key

173. An application is running on a cluster of Amazon EC2 instances. While trying to read objects stored within a single Amazon S3 bucket that are encrypted with server-side encryption with AWS KMS managed keys (SSE-KMS), the application receives the following error:

Service: AWSKMS; Status Code: 400; Error Code: ThrottlingException

Which combination of steps should be taken to prevent this failure? (Choose two.)

                A. Contact AWS Support to request an AWS KMS rate limit increase.
                B. Perform error retries with exponential backoff in the application code.
                C. Contact AWS Support to request a S3 rate limit increase.
                D. Import a customer master key (CMK) with a larger key size.
                E. Use more than one customer master key (CMK) to encrypt S3 data.

Hint Answers: C,D

174. A Developer has an e-commerce API hosted on Amazon ECS. Variable and spiking demand on the application is causing order processing to take too long. The application processes Amazon SQS queues. The ApproximateNumberOfMessagesVisible metric spikes at very high values throughout the day, which cause Amazon CloudWatch alarm breaches. Other ECS metrics for the API containers are well within limits. What can the Developer implement to improve performance while keeping costs low?

                A. Target tracking scaling policy
                B. Docker Swarm
                C. Service scheduler
                D. Step scaling policy

Hint Answers: D

175. A Developer wants to build an application that will allow new users to register and create new user accounts. The application must also allow users with social media accounts to log in using their social media credentials. Which AWS service or feature can be used to meet these requirements?

                A. AWS IAM
                B. Amazon Cognito identity pools
                C. Amazon Cognito user pools
                D. AWS Directory Service

Hint Answers: C

176. A company is developing a web application that allows its employees to upload a profile picture to a private Amazon S3 bucket. There is no size limit for the profile pictures, which should be displayed every time an employee logs in. For security reasons, the pictures cannot be publicly accessible. What is a viable long-term solution for this scenario?

                A. Generate a pre-signed URL when a picture is uploaded. Save the URL in an Amazon DynamoDB table. Return the URL to the browser when the employee logs in.
                B. Save the picture’s S3 key in an Amazon DynamoDB table. Create an Amazon S3 VPC endpoint to allow the employees to download pictures once they log in.
                C. Encode a picture using base64. Save the base64 string in an Amazon DB table. Allow the browser to retrieve the string and convert it to a picture.
                D. Save the picture’s S3 key in an Amazon DynamoDB table. Use a function to generate a presigned URL every time an employee logs in. Return the URL to the browser.

Hint Answers: B

177. A Developer is going to deploy an AWS Lambda function that requires significant CPU utilization. Which approach will MINIMIZE the average runtime of the function?

                A. Deploy the function into multiple AWS Regions.
                B. Deploy the function into multiple Availability Zones.
                C. Deploy the function using Lambda layers.
                D. Deploy the function with its memory allocation set to the maximum amount.

Hint Answers: C

178. A company has a legacy application that was migrated to a fleet of Amazon EC2 instances. The application stores data in a MySQL database that is currently installed on a single EC2 instance. The company has decided to migrate the database from the EC2 instance to MySQL on Amazon EDS. What should the Developer do to update the application to support data storage in Amazon RDS?

                A. Update the database connection parameters in the application to point to the new RDS instance.
                B. Add a script to the EC2 instance that implements an AWS SDK for requesting database credentials.
                C. Create a new EC2 instance with an IAM role that allows access to the new RDS database.
                D. Create an AWS Lambda function that will route traffic, from the EC2 instance to the RDS database.

Hint Answers: A

179. A Developer is working on an AWS Lambda function that accesses Amazon DynamoDB. The Lambda function must retrieve an item and update some of its attributes, or create the item if it does not exist. The Lambda function has access to the primary key. Which IAM permissions should the Developer request for the Lambda function to achieve this functionality?

                A. dynamodb:DeleteItem
                dynamodb:GetItem
                dynamodb:PutItem
                B. dynamodb:UpdateItem
                dynamodb:GetItem
                dynamodb:DescribeTable
                C. dynamodb:GetRecords
                dynamodb:PutItem
                dynamodb:UpdateTable
                D. dynamodb:UpdateItem
                dynamodb:GetItem
                dynamodb:PutItem

Hint Answers: D

180. A Developer is storing sensitive data generated by an application in Amazon S3. The Developer wants to encrypt the data at rest. A company policy requires an audit trail of when the master key was used and by whom. Which encryption option will meet these requirements?

                A. Server-side encryption with Amazon S3 managed keys (SSE-S3)
                B. Server-side encryption with AWS KMS managed keys (SSE-KMS)
                C. Server-side encryption with customer-provided keys (SSE-C)
                D. Server-side encryption with self-managed keys

Hint Answers: B