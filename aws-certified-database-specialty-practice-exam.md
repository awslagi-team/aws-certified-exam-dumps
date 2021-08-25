Notes: Hi all, We’re sharing AWS Database Specialty (DBS-C01) Practice Exam Part 1 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Database Specialty Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \ 
For GCP: https://www.gcp-examquestions.com

1. A company’s compliance requirements mandate regular backup of all their production databases. What should a Database Specialist consider when creating backups for DynamoDB tables? (Select three)

        A. To delete backups marked with a “Backup type’ of AWS using the DynamoDB console, you need to have full access permissions on DynamoDB resources.
        B. All API and console actions of DynamoDB backup and restore are captured and recorded in AWS CloudTrail.
        C. When you restore a table, you only use the provisioned Read Capacity Units (RCUs) of the table and Write Capacity Units (WCUs) remain untouched.
        D. IAM policies as well as encryption settings have to be manually setup for the restored table.
        E. DynamoDB backup will preserve the Provisioned Read and Write capacities, Local Secondary Indexes (LSIs) and billing mode of the backed-up table.
        F. Auto-scaling policies, AWS Identity and Access Management (IAM) policies have to be manually setup for the restored table.

Answer: B E F

10. A health-care company has just migrated its IT infrastructure from the on-premises data-center to AWS Cloud. The company is using Aurora MySQL DB cluster as its data store and the HIPAA compliance guidelines mandate that the company must produce audit logs from the production Amazon Aurora MySQL cluster and push the encrypted logs into a third-party compliance management application. The solution should allow the security team to carry out real-time alerting and monitoring outside the Aurora DB cluster. As a Database Specialist, which approach will you recommend to meet these requirements?

        A. Activate Aurora Event Notifications and then push the notifications into a compliance management application via Kinesis Data Streams.
        B. Set up AWS CloudTrail to capture the audit logs for the DB cluster and the security team can ingest the data from Amazon S3 into the compliance management application.
        C. Activate database activity streams and then push the streams into a compliance management application via Kinesis Data Streams.
        D. Enable Aurora Enhanced Monitoring and then push the metrics into a compliance management application via AWS Lambda.

Answer: C

11. A sports analytics firm uses AWS DynamoDB to store information about user’s favorite sports teams and allows the information to be searchable from their home page. There is a daily requirement that all 10 million records in the table should be deleted then re-loaded at 3:00 AM each night. Which option is an efficient way to delete with minimal costs?

        A. Scan and delete items using batch mode.
        B. Delete then re-create the table.
        C. Scan and delete items individually.
        D. Use the purge table option.

Answer: B

12. You are a database administrator for an IT company that recently moved its production application to AWS and migrated data from PostGreSQL to AWS DynamoDB. You are adding new tables to AWS DynamoDB and need to allow your application to query your data by the primary key and an alternate key. This option must be added at the outset when you are first creating tables, otherwise, changes cannot be done once the table is created. As a Database Specialist, which of the following actions would you suggest?

        A. Create an LSI.
        B. Migrate away from DynamoDB.
        C. Create a GSI.
        D. Create DynamoDB Streams.

Answer: A

13. A global CRM company uses Amazon RDS for MySQL DB cluster for its flagship application but it is running into performance issues despite using Read Replicas. The company has hired you as an AWS Certified Database Specialist to address these performance-related challenges on an urgent basis without moving away from the underlying relational database schema. The company has branch offices across the world and it needs the solution to work on a global scale. Which of the following will you recommend as the MOST cost-effective and high-performance solution?

        A. Use Amazon Aurora Global Database to enable fast local reads with low latency in each region.
        B. Spin up a Redshift cluster in each AWS region. Migrate the existing data into Redshift clusters.
        C. Spin up EC2 instances in each AWS region, install MySQL databases and migrate the existing data into these new databases.
        D. Use Amazon DynamoDB Global Tables to provide fast, local, read and write performance in each region.

Answer: A

14. A big data analytics company wants to process loT data from the field devices of an agricultural sciences company. The database team at the analytics company is designing a new database infrastructure for capturing this loT data. The database should be resilient with minimal operational overhead and require the least development effort. The application includes a device tracking system that stores the GPS data for all devices. Real-time loT data, as well as metadata lookups, must be performed with high throughput and microsecond latency. As a Database Specialist, which of the following options would you recommend as the MOST efficient solution for these requirements?

        A. Use DocumentDB as the database with API Gateway.
        B. Use DynamoDB as the database with DynamoDB Accelerator (DAX).
        C. Use Aurora MySQL as the database with Aurora cluster cache.
        D. Use RDS MySQL as the database with ElastiCache.

Answer: B

15. The database administration team at a gaming company is planning to create a Read Replica of an existing Amazon RDS for PostGreSQL Multi-AZ DB instance. However, while using the AWS Management Console to set up the Read Replica, the Team Lead discovers that the source RDS DB instance does not show in the Read Replica source field. As a Database Specialist, which of the following would you recommend as a solution for this issue?

        A. Enable database cloning on the source RDS DB instance.
        B. Enable Enhanced Monitoring on the source RDS DB instance.
        C. Enable database replication on the source RDS DB instance.
        D. Enable automatic backups on the source RDS DB instance.

Answer: D

16. You are a Database Specialist working for an analytics company. You have been tasked with building a reporting application that includes dashboards for data visualization. You are provisioning your AWS DynamoDB table and need to perform 10 strongly consistent reads per second of 8 KB in size each. How many Read Capacity Units (RCUs) are needed?

        A. 20
        B. 10
        C. 40
        D. 5

Answer: A

17. A Silicon Valley based startup is experimenting with DynamoDB in its new test environment. The database team has discovered that some of the write operations have been overwriting existing items which have that specific primary key. This has corrupted their data leading to data discrepancies. As a Database Specialist, which DynamoDB write option would you select to prevent this kind of overwriting?

        A. Conditional writes
        B. Atomic Counters
        C. Batch writes
        D. Use Scan operation

Answer: A

18. As part of its disaster recovery testing. an IT company would like to simulate an Availability Zone failure for its RDS for MySQL Multi-AZ DB instance. The testing team wants to record how the application reacts during the DB instance failover activity. The company does not want to make any configuration or code changes for this testing. As a Database Specialist, which of the following solutions would you outline for the company to test this use-case in the SHORTEST time?

        A. Use the RDS SQL injection query to simulate the primary instance failure.
        B. Use the RDS fault injection query to simulate the primary instance failure.
        C. Initiate a manual failover of the RDS DB primary instance by terminating the instance.
        D. Initiate a manual failover of the RDS DB primary instance by using reboot with failover.

Answer: D

19. An ed-tech company is doing pre-launch testing for its new product. The company runs its production database on an Aurora MySQL DB cluster and the performance testing team wants access to multiple test databases that must be re-created from production data. The company has hired an AWS Certified Database Specialist to deploy a solution to create test databases quickly with the LEAST required effort for database administration. What should the Database Specialist do to address this use-case?

        A. Use database cloning to create multiple clones of the production. DB and use each clone as a test DB.
        B. Create additional Read Replicas of the Aurora MySQL production DB and use the Read Replicas for testing by promoting each Replica to be its own independent standalone instance.
        C. Enable database Backtracking on the production DB and let the testing team use the production DB.
        D. Take a backup of the Aurora MySQL DB instance using the mysqidump utility, create multiple new test DB instances and restore each test DB from the backup.

Answer: A

2. The database administration team at a major health-care company uses Multi-Availability Zone (Multi-AZ) deployment for its RDS MySQL DB cluster to automate its database replication and augment data durability. The database administration team has scheduled a maintenance window for a database engine level upgrade for the next weekend. As an AWS Certified Database Specialist, which of the following would you identify as the correct outcome during the maintenance window?

        A. Any database engine level upgrade for an RDS DB instance with Multi-AZ deployment triggers the standby DB instance to be upgraded which is then followed by the upgrade of the primary DB instance. This does not cause any downtime for the duration of the upgrade.
        B. Any database engine level upgrade for an RDS DB instance with Multi-AZ deployment triggers both the primary and standby DB instances to be upgraded at the same time. However, this does not cause any downtime until the upgrade is complete.
        C. Any database engine level upgrade for an RDS DB instance with Multi-AZ deployment triggers the primary DB instance to be upgraded which is then followed by the upgrade of the standby DB instance. This does not cause any downtime for the duration of the upgrade.
        D. Any database engine level upgrade for an RDS DB instance with Muiti-AZ deployment triggers both the primary and standby DB instances to be upgraded at the same time. This causes downtime until the upgrade is complete.

Answer: D

20. The development team at an e-commerce company manages 5 Amazon EC2 instances that make read-heavy database requests to the Amazon RDS for PostgreSQL DB instance. As a Database Specialist, you have been asked to make the database instance resilient from a disaster recovery perspective. Which of the following features will help you prepare for database disaster recovery? (Select two)

        A. Use cross-Region Read Replicas.
        B. Use RDS Provisioned IOPS (SSD) Storage in place of General Purpose (SSD) Storage.
        C. Enable the automated backup feature of Amazon RDS in a multi-AZ deployment that creates backups across multiple Regions.
        D. Enable the automated backup feature of Amazon RDS in a multi-AZ deployment that creates backups in a single AWS Region.
        E. Use database cloning feature of the RDS DB cluster.

Answer: A D

21. The engineering team at a Big Data Analytics company has set up a workflow to ingest the clickstream data into the raw zone of the S3 data lake. The team wants to run some SQL based data sanity checks on the raw zone of the data lake. The company has hired you as an AWS Certified Database Specialist to build a serverless solution that involves the least amount of development effort so that is cost-effective and easy to maintain. Which of the following solutions would you build for this use-case?

        A. Load the incremental raw zone data into RDS on an hourly basis and run the SQL based sanity checks.
        B. Load the incremental raw zone data into DynamoDB on an hourly basis and run the SQL based sanity checks.
        C. Use Athena to run SQL based analytics against S3 data.
        D. Load the incremental raw zone data into Redshift on an hourly basis and run the SQL based sanity checks.

Answer: C

22. A global e-commerce company has just migrated its technology infrastructure from the on-premises data center to AWS Cloud. The database management team at the e-commerce company wants to deploy an Online Transactional Processing (OLTP) application with support for relational queries which will have unpredictable spikes in the usage pattern that they do not know in advance. As a Database Specialist, which of the following database solutions would you recommend for this use-case?

        A. DynamoDB with On-Demand Capacity.
        B. Aurora Serverless.
        C. Aurora Global Database.
        D. DynamoDB with Provisioned Capacity and Auto Scaling.

Answer: B

23. A gaming company maintains a staging environment for its flagship application which uses a DynamoDB table to keep track of gaming history for the players. This data needs to be kept for only a week and then it can be deleted. The IT manager has noticed that the table has several months of data in the table. The company wants to implement a cost-effective solution to keep only the latest week’s data in the table. Which of the following solutions requires the MINIMUM development effort and on-going maintenance?

        A. Add a new attribute in the table to track the expiration time and set up a Glue job to delete items that are more than a week old.
        B. Add a created_at attribute in the table and then use a cron job on EC2 instance to invoke a Python script daily. The script deletes items older than a week on the basis of this attribute.
        C. Add a new attribute in the table to track the expiration time and enable time to live (TTL) on the table.
        D. Add a created_at attribute in the table and then use a CloudWatch Events rule to invoke a Lambda function daily. The Lambda function deletes items older than a week on the basis of this attribute.

Answer: C

24. An analytics company is looking to migrate its RDS PostGreSQL DB instance to Aurora PostGreSQL DB cluster. The company wants the fastest possible solution with minimum downtime and least effort for the migration of its current database which is 2TB in size. As a Database Specialist, which of the following solutions would you recommend for this use-case?

        A. Use AWS Database Migration Service (AWS DMS) to migrate the RDS PostGreSQL DB instance to Aurora PostGreSQL DB cluster.
        B. Create a DB snapshot for the Aurora PostgreSQL DB instance and then migrate data directly from this DB snapshot to the Aurora PostgreSQL DB cluster.
        C. Create an Aurora PostgreSQL Read Replica of the PostgreSQL DB instance and migrate data to the Aurora PostgreSQL DB cluster using this Read Replica. Promote the replica when the replication lag is zero.
        D. Use AWS Glue to create an ETL job for the data migration from RDS PostGreSQL DB instance to Aurora PostGreSQL DB cluster.

Answer: D

25. Due to the COVID-19 pandemic, a large retail company is planning to close operations for a month. The technology team at the company needs to stop all applications along with all the RDS PostGreSQL DB instances to ensure employees do not have access to the systems during this time. The Team Lead has written and executed a script to stop all the RDS PostGreSQL DB instances. However, while reviewing the logs, the Team Lead finds that the RDS PostGreSQL DB instances with Read Replicas did not stop. As an AWS Certified Database Specialist, how would you modify the script to fix this issue?

        A. Stop all Read Replicas before stopping the primary RDS DB instance.
        B. Use a schedule based CloudWatch Events rule to stop the Read Replicas and the primary RDS DB instance at the same time.
        C. Stop the primary RDS DB instance before stopping all Read Replicas.
        D. Delete all Read Replicas before stopping the corresponding primary RDS DB instance.

Answer: D

26. The technology team at a Wall Street trading firm uses DynamoDB to facilitate high- frequency trading where multiple trades can try and update an item at the same time. As a Database Specialist, which of the following actions would you recommend to make sure that only the last updated value of any item is used in the application?

        A. Use ConsistentRead – true while doing Getitem operation for any item.
        B. Use ConsistentRead – true while doing Putitem operation for any item.
        C. Use ConsistentRead – true while doing Updateltem operation for any item.
        D. Use ConsistentRead – false while doing Putitem operation for any item.

Answer: A

27. An IT company has a three-year contract with a health-care provider. The contract states that monthly database backups must be retained for the duration of the contract for compliance purposes. Currently. the limit for backup retention for automated backups on Amazon Relational Database Service (RDS) does not meet your requirements. Which of the following solutions can help you meet your requirements?

        A. Enable RDS Multi-AZ.
        B. Enable RDS automatic backups.
        C. Create a schedule based CloudWatch Events rule that invokes an AWS Lambda function that further triggers the database snapshot.
        D. Enable RDS Read replicas.

Answer: C

28. An IT company manages its technology infrastructure on the AWS Cloud. The Database administration team at the company wants to migrate its RDS MySQL database to Aurora MySQL database. As a Database Specialist, which of the following solutions would you suggest so that it does not require any custom development and there is minimum downtime when the company migrates the database?

        A. Create a clone of the RDS MySQL DB instance and then promote the clone into a standalone Aurora DB cluster.
        B. Create a DB snapshot of the RDS MySQL DB and then migrate this snapshot to create an Aurora MySQL DB cluster.
        C. Use AWS Glue to create an ETL job to migrate the RDS MySQL database to Aurora MySQL database.
        D. Create an Aurora Replica from the RDS MySQL DB instance and then promote the Replica into a standalone Aurora DB cluster.

Answer: D

29. A financial services company has recently transitioned its technology infrastructure from the on-premises data center to AWS Cloud. The security team at the company is evaluating the security features offered by RDS MySQL. You have been hired as an AWS Certified Database Specialist to provide guidance on RDS MySQL security offerings. Which of the following statements would you identify as correct for the given use-case? (Select three)

        A. You can map multiple IAM users or roles to the same database user account.
        B. IAM database authentication tokens are generated using AWS access keys. These Authentication tokens do not expire once they are generated. They need to be manually expired by the application after using them.
        C. All data transmitted to and from RDS DB instance for IAM Database Authentication is encrypted using KMS service.
        D. IAM database authentication should only be used if your application requires no more than 200 new connections per second.
        E. If your application is running on Amazon Elastic Compute Cloud (Amazon EC2). then you can use EC2 instance profile credentials to access the database.
        F. IAM user/role and database user hold a one to one relationship. That is, each IAM user or role need a separate database user account mapped to their IAM account for access to the RDS MySQL database.

Answer: A D E

3. A database administrator is provisioning a DynamoDB table for an e-commerce application. The development team has given a requirement of 500 Write Capacity Units and 5000 Read Capacity Units for this DynamoDB table. The database administrator is planning to allocate 50GB of space to this table. How many partitions will be created in the table for this requirement?

        A. 3 partitions
        B. 8 partitions
        C. 6 partitions
        D. 5 partitions

Answer: D

30. An analytics company uses Aurora MySQL DB cluster for running online transaction processing (OLTP) transactions all through the day as well as running a reporting workload at certain times of the day. The reporting workload amounts to just 20% of the OLTP workload. A 10-node cluster is sufficient to meet the entire workload. The company wants to optimize the cluster size so that it pays the minimum charges while still maintaining a sufficient number of nodes to support any changes in the overall workload. As a Database Specialist, which of the following would you recommend as the MOST cost-optimal solution with minimum configuration changes?

        A. Use Aurora Auto Scaling to enable your Aurora DB cluster to handle variations in workload by provisioning Aurora Multi-AZ instances.
        B. Create two separate DB clusters use one for OLTP workload and the other for reporting workload. Use AWS DMS to replicate data between the two clusters.
        C. Use Aurora Auto Scaling to enable your Aurora DB cluster to handle variations in workload by provisioning Aurora Replicas.
        D. Use CloudWatch alarm to stop all the nodes of the DB cluster during times of minimal workload. The cluster can be restarted again if the workload goes above a pre-defined threshold.

Answer: C

31. An advertising technology company is looking at moving their on-premises infrastructure to AWS Cloud. Their flagship application uses a massive PostgreSQL database and the database administration team would like to retain control over managing the patches, version upgrades for the database, and consistent performance with high IOPS. The team wants to install the database on an EC2 instance with the optimal storage type on the attached EBS volume. As a Database Specialist, which of the following configurations would you suggest to the database administration team?

        A. Amazon EC2 with EBS volume of Throughput Optimized HDD (st1) type.
        B. Amazon EC2 with EBS volume of Provisioned IOPS SSD (io1) type.
        C. Amazon EC2 with EBS volume of cold HDD (sc1) type.
        D. Amazon EC2 with EBS volume of General Purpose SSD (gp2) type.

Answer: B

32. An Internet-of-Things (IoT) solutions company is looking to migrate its on-premises infrastructure into the AWS Cloud. The database management team is looking for a fully managed NoSQL persistent data store with in-memory caching to maintain low latency that is critical for real-time scenarios such as video streaming and interactive content. The team is well versed with the expected access patterns for the underlying database and expects the number of concurrent users to touch up to a million so the database should be able to scale elastically. As a Database Specialist, which of the following AWS services would you recommend for this use-case?

        A. DocumentDB
        B. RDS
        C. DynamoDB
        D. ElastiCache

Answer: C

33. The technology team at a retail organization is running batch workloads on AWS Cloud. The team has embedded RDS database connection strings within each web server hosting the flagship application. After failing a security audit, the team is looking at a different approach to store the database secrets securely and automatically rotate the database credentials. As a Database Specialist, which of the following solutions would you recommend to meet this requirement?

        A. Secrets Manager
        B. KMS
        C. Systems Manager
        D. SSM Parameter Store

Answer: A

34. A gaming company is using RDS MySQL DB to re-engineer its flagship application. The development team needs to restore its MySQL database whenever a developer makes a mistake in the schema updates. As a result, the entire development team needs to wait hours for the DB restore to complete. The issue is further compounded as multiple team members are collaborating on the same project, thereby making it hard to find the right restore point for each mistake. As a Database Specialist, which of the following solutions would you recommend to reduce the downtime during the development phase?

        A. Enable the RDS for MySQL Clone feature and then the developers can make changes to their own cloned instances.
        B. Enable the RDS for MySQL Backtrack feature and then the developers can backtrack to a pre-defined checkpoint.
        C. Set up multiple read replicas and then the developers can make changes to their own promoted replica instances.
        D. Migrate to Amazon Aurora MySQL and enable the Aurora Backtrack feature.

Answer: C

35. A Silicon Valley based unicorn startup is moving its IT operations from an on-premises data center to AWS Cloud. The database team at the startup is evaluating the Multi-AZ and Read Replica capabilities of RDS MySQL vs Aurora MySQL before they implement the solution in their production environment. The startup has hired you as an AWS Certified Database Specialist to provide a detailed report on this technical requirement. Which of the following would you identify as correct regarding the given use-case? (Select three)

        A. Database engine version upgrades happen on primary for Aurora MySQL whereas all instances are updated together for RDS MySQL.
        B. The primary and standby DB instances are upgraded at the same time for RDS MySQL Multi-AZ. All instances are upgraded at the same time for Aurora MySQL.
        C. Multi-AZ deployments for RDS MySQL follow synchronous replication whereas Multi-AZ deployments for Aurora MySQL follow asynchronous replication.
        D. Multi-AZ deployments for Aurora MySQL follow synchronous replication whereas Multi-AZ deployments for RDS MySQL follow asynchronous replication.
        E. Read Replicas can be manually promoted to a standalone database instance for RDS MySQL whereas Read Replicas for Aurora MySQL can be promoted to the primary instance.
        F. Read Replicas can be manually promoted to a standalone database instance for Aurora MySQL whereas Read Replicas for RDS MySQL can be promoted to the primary instance.

Answer: B C E

36. A financial services company uses AWS Cloud to manage its technology infrastructure. The company has deployed its consumer-focused web-application on EC2 based web servers and uses RDS PostGreSQL DB as the data store. The PostGreSQL DB is set up in a private subnet that allows inbound traffic from selected EC2 instances. The DB also uses AWS KMS for encrypting data at rest. As a Database Specialist, which of the following steps would you suggest to facilitate secure access to the database?

        A. Create a new Network Access Control List (NACL) that blocks SSH from the entire EC2 subnet into the DB.
        B. Create a new security group that blocks SSH from the selected EC2 instances into the DB
        C. Use IAM authentication to access the DB instead of the database user’s access credentials.
        D. Configure RDS to use SSL for data in transit.

Answer: D

37. The database management team at a Big Data consultancy is working on the Disaster Recovery (DR) plans for a Redshift cluster deployed in the us-east-1 Region. The existing cluster is encrypted via AWS KMS and the team wants to copy the Redshift snapshots to another Region to meet the DR requirements. As a Database Specialist, which of the following solutions would you suggest to address the given use-case?

        A. Create a snapshot copy grant in the source Region for a KMS key in the source Region. Configure Redshift cross-Region snapshots in the destination Region.
        B. Create a snapshot copy grant in the destination Region for a KMS key in the destination Region. Configure Redshift cross-Region snapshots in the source Region.
        C. Create an IAM role in destination Region with access to the KMS key in the source Region Create a snapshot copy grant in the destination Region for this KMS key in the source Region Configure Redshift cross-Region snapshots in the source Region.
        D. Create a snapshot copy grant in the destination Region for a KMS key in the destination Region Configure Redshift cross-Region replication in the source Region.

Answer: B

38. An analytics company is using an Aurora DB cluster with Read Replicas for specialized read-only workloads. The database administration team at the company needs to spin up three read-only reporting applications for the Sales, HR and Finance departments at the company. Each application needs to connect to its own set of dedicated Read Replicas. The company has hired you as an AWS Certified Database Specialist to implement a load balanced and highly available solution for this reporting application. Which of the following options would you recommend for this use-case?

        A. Create three reader endpoints and use one reader endpoint for each of the read-only reporting applications.
        B. Use one custom endpoint for all three read-only reporting applications.
        C. Use one reader endpoint for all three read-only reporting applications.
        D. Create three custom endpoints and use one custom endpoint for each of the read-only reporting applications.

Answer: D

39. A Database Specialist is working on modeling data for a DynamoDB production database. To address certain access patterns for the application, he is in the process of creating secondary indexes. Which of the following options should the database specialist consider for these requirements? (Select three)

        A. A Global Secondary Index contains a selection of attributes from the base table which are organized by a primary key that is different from that of the table.
        B. A Local Secondary Index maintains an alternate primary key for a given partition key value
        C. For greater query or scan flexibility. you can create up to twenty Local Secondary Indexes per table.
        D. If the writes are throttled on the Global Secondary Indexes, then the main table will be throttled, even though the Write Capacity Units on the main tables are fine.
        E. Applications that need to perform many kinds of queries, using a variety of different attributes for their query criteria should use Global Secondary Indexes.
        F. Global secondary indexes support both data models eventually consistent or strongly consistent reads.

Answer: A D E

4. A CRM company uses a two-tier architecture with application servers in the public subnet and an RDS based database in a private subnet. The database management team is able to use a bastion host in the public subnet to log in to MySQL and run queries from the bastion host. However, end-users are reporting application errors. Upon inspecting application logs, the database team notices several “could not connect to server: connection timed out” error messages. As a Database Specialist, which of the following would you identify as the root cause behind this issue?

        A. The security group configuration for the application servers does not have the correct rules to allow inbound connections from the DB instance.
        B. The database user credentials (username and password) configured for the application are incorrect.
        C. The database user credentials (username and password) configured for the application do not have the required privilege for the given database.
        D. The security group configuration for the DB instance does not have the correct rules to allow inbound connections from the application servers.

Answer: D

40. The data analytics team at a multi-national retail company has been running ad-hoc queries on Oracle and PostgreSQL services on Amazon RDS to prepare daily reports for senior management. To facilitate the data analytics reporting. the database administration team now wants to replicate this data with high availability and consolidate these databases into a petabyte-scale data warehouse by streaming data to Amazon Redshift. As a Database Specialist, which of the following would you recommend as the MOST resource-efficient solution that requires the LEAST amount of development time without the need to manage the underlying infrastructure?

        A. Use AWS EMR to replicate the data from the databases into Amazon Redshift.
        B. Use AWS Database Migration Service to replicate the data from the databases into Amazon Redshift.
        C. Use Amazon Kinesis Data Streams to replicate the data from the databases into Amazon Redshift.
        D. Use AWS Glue to replicate the data from the databases into Amazon Redshift.

Answer: B

41. As part of a new release, the DevOps team at an IT company executed a database migration script that ended up breaking the application because the script had a bug that deleted several records from one of the main tables. An AWS Certified Database Specialist was brought in to assess the event that happened about 8 hours ago. The Specialist noted that the Aurora DB cluster had the “Backtrack” feature enabled with a 24 hour backtrack window. In addition, the DevOps team had also taken a manual DB cluster snapshot as well as cloned the DB cluster before the release. Which of the following solutions can be used to return the affected database to the correct state within the LEAST amount of time and MINIMUM data loss?

        A. Backtrack the DB cluster to a point in time just before the release.
        B. Restore the DB cluster using the pre-release manual snapshot to a new DB cluster and update the application configuration to use the new DB cluster.
        C. Use the cloned DB cluster with the Backtrack feature enabled and then rewind the cloned cluster to a point in time just before the release. Return the affected database to the correct state by copying the deleted records from the cloned database to the original database
        D. Restore the DB cluster using the point in time recovery method to a new DB cluster. Return the affected database to the correct state by copying the deleted rows from the recovered database to the original database.

Answer: C

42. An ad-tech company runs a leading ad targeting platform that captures various kinds of marketing data such as user profiles, user events, clicks, and visited links. The company is looking to migrate its IT infrastructure from the on-premises data center to AWS Cloud. The technical requirements for the advertising platform mandate a high request rate (millions of requests per second). low predictable latency and high reliability. The company also needs to deploy this ad targeting platform in more than one AWS Regions. The maximum size of an event is 200 KB and the average size is 10 KB. The structure of the incoming data varies depending on the event. As a Database Specialist, which of the following database solutions would you recommend to address these requirements?

        A. DynamoDB Global Tables.
        B. DocumentDB.
        C. Aurora Serverless.
        D. Aurora Global Database.

Answer: A

43. The DevOps team at an IT company created an AWS CloudFormation stack with an RDS DB instance. An intern has accidentally deleted the stack and most of the recent data has been lost. You have been hired as an AWS Certified Database Specialist to configure RDS settings to the CloudFormation template to mitigate such accidental instance data loss in the future. Which of the following settings will address this use-case? (Select three)

        A. Configure Multi-AZ to True.
        B. Configure DeletionPolicy to Retain.
        C. Configure Read Replica to True.
        D. Enable Termination Protection section of the CloudFormation stack via the AWS Management Console.
        E. Enable Deletion Protection section of the CloudFormation stack via the AWS Management Console.
        F. Configure DeleteAutomatedBackups to False.

Answer: B D F

44. A media company has recently migrated their technology infrastructure to AWS Cloud. The database team is centralizing database access credentials to align with IAM based authentication. Which of the following AWS database engines can be configured with IAM Database Authentication?

        A. RDS SQL Server
        B. RDS MySQL
        C. RDS Oracle
        D. RDS Maria DB
        E. RDS PostGreSQL

Answer: B E

45. The database team at an e-commerce company wants to connect to the RDS PostGreSQL Multi-AZ DB instance using Secure Socket Layer or Transport Layer Security (SSL/TLS). The Team Lead has set the value of the static parameter rds.force_ssl as 1 in the custom parameter group currently associated with the production RDS PostGreSQL Multi-AZ DB instance. This change has been approved for a specific maintenance window to help minimize the impact on users. As a Database Specialist, which of the following steps would you recommend to apply the parameter group change for the given use-case?

        A. Propagate the parameter group update manually by rebooting the DB instance during the approved maintenance window.
        B. Use the “Apply Immediately” setting to enforce the parameter update.
        C. Let the approved maintenance window automatically apply the change for the static parameter.
        D. Go to the AWS RDS console and reboot the instance immediately.

Answer: A

46. A social networking application supports the transfer of gift vouchers between users. When a user reaches a certain number of followers on the application, that user earns a gift voucher that can be redeemed or transferred to another user. The database administration team wants to ensure that this transfer is captured in the database such that the records for both users are either written successfully with the new gift vouchers or the status quo is maintained. As a Database Specialist, which of the following solutions would you recommend as the best-fit options to meet the given requirements? (Select two)

        A. Complete both operations on RDS MySQL in a single transaction block.
        B. Complete both operations on Amazon RedShift in a single transaction block.
        C. Use the DynamoDB transactional read and write APIs on the table items as a single, all-or-nothing operation.
        D. Use the Amazon Athena transactional read and write APIs on the table items as a single, all-or-nothing operation.
        E. Perform DynamoDB read and write operations with ConsistentRead parameter set to true.

Answer: A C

47. A multi-national company has just floated their latest security policy. As per this policy. data needs to be stored in encrypted form only. The company uses different Amazon RDS solutions for their various products. As a Database Specialist, you are roped in to facilitate the learning of RDS encryption features and configurations. Which of the following statements would you identify as correct for the given context? (Select three)

        A. You can enable encryption for an Amazon RDS DB instance when you create it or when you pull it down for maintenance Encryption settings cannot be changed when the database is up and running.
        B. An unencrypted RDS DB instance will only result in unencrypted Read Replicas. You can’t have an encrypted Read Replica of an unencrypted DB instance.
        C. You can restore an unencrypted Aurora DB cluster snapshot to an encrypted Aurora DB cluster.
        D. You can restore an unencrypted backup or snapshot of an Amazon RDS DB instance to an encrypted DB instance by specifying the KMS key identifier.
        E. Since Read Replica of an Amazon RDS encrypted instance is also encrypted using the same key as the primary DB instance creating Read Replicas in a different Region is not possible.
        F. To copy an encrypted snapshot from one AWS Region to another, you must specify the KMS key identifier of the destination AWS Region.

Answer: B C F

48. The database management team at a leading gaming company is evaluating multiple in-memory data stores with the ability to power its on-demand, live leaderboard. The company’s leaderboard requires high availability, low latency. and real-time processing to deliver customizable user data for the community of users working out together virtually from the comfort of their home. As a Database Specialist, which of the following solutions would you recommend?(Select two)

        A. Develop the leaderboard using DynamoDB with DynamoDB. Accelerator (DAX) as it meets the in-memory, high availability, low latency requirements.
        B. Develop the leaderboard using ElastiCache Redis as it meets the in-memory, high availability, low latency requirements.
        C. Develop the leaderboard using DynamoDB as it meets the in-memory, high availability, low latency requirements.
        D. Develop the leaderboard using AWS Neptune as it meets the in-memory, high availability, low latency requirements.
        E. Develop the leaderboard using RDS Aurora as it meets the in-memory, high availability, low latency requirements.

Answer: A B

49. The database administration team at a leading social media company uses Amazon MySQL RDS DB cluster because it simplifies much of the time-consuming administrative tasks typically associated with databases. The team uses Multi-Availability Zone (Multi-AZ) deployment to further automate its database replication and augment data durability. The current cluster configuration also uses Read Replicas. An intern has joined the team and wants to understand the replication capabilities for Multi-AZ as well as Read Replicas for the given RDS cluster. As a Database Specialist, which of the following capabilities would you identify as correct for the given database?

        A. Multi-AZ follows asynchronous replication and spans at least two Availability Zones within a single region. Read Replicas follow synchronous replication and can be within an Availability Zone Cross-AZ or Cross-Region.
        B. Multi-AZ follows asynchronous replication and spans one Availability Zone within a single region. Read Replicas follow synchronous replication and can be within an Availability Zone, Cross-AZ or Cross-Region.
        C. Multi-AZ follows synchronous replication and spans at least two Availability Zones within a single region. Read Replicas follow asynchronous replication and can be within an Availability Zone Cross-AZ, or Cross-Region.
        D. Multi-AZ follows asynchronous replication and spans at least two Availability Zones within a single region. Read Replicas follow asynchronous replication and can be within an Availability Zone Cross-AZ or Cross-Region.

Answer: C

5. An in-home fitness company has recently transitioned to AWS Cloud from its on-premises data center. The CTO at the company wants to augment the existing application by adding a leaderboard that uses a complex proprietary algorithm based on the participating user’s health metrics to identify the top users on a real-time basis. The technical requirements mandate high elasticity. low latency. and real-time processing to deliver customizable rider data for the community of users riding together virtually from the comfort of their home. The leaderboard would be accessed by millions of users simultaneously. As a Database Specialist, which of the following options would you enlist to advocate for using ElastiCache for the given requirements? (Select two)

        A. Use ElastiCache to run highly complex JOIN queries.
        B. Use ElastiCache to improve performance of compute-intensive workloads.
        C. Use ElastiCache to improve latency and throughput for read-heavy application workloads.
        D. Use ElastiCache to improve latency and throughput for write-heavy application workloads
        E. Use ElastiCache to improve performance of Extract-Transform-Load (ETL)workloads.

Answer: B C

50. The database team at an e-commerce company has been grappling with an issue on its Amazon Aurora MySQL DB cluster where the Read Replicas are lagging behind the master node with a huge deficit. On further investigation, the team has come across the error message “Read Replica has fallen behind the master too much. Restarting MySQL”. As a Database Specialist, what steps and configuration checks will you undertake to resolve the issue? (Select two)

        A. A sudden surge of write activity in an already write-heavy production cluster can cause an overload on the writer DB instance. You can visualize this by using Amazon CloudWatch, where you observe sudden bursts of the DMLThroughput DDLThroughput and Queries metrics.
        B. Check all instances in the cluster have the same specification A reader node should not have a weaker DB instance class configuration than that of a writer DB instance.
        C. The Amazon Aurora DB instance is undergoing instance recovery or failover, forcing the Read Replica to act as Primary node and this resulted in a restart of the Read Replica.
        D. The storage volume that Read Replica is connected to could have crashed.
        E. An instance in Aurora clusters might have run out of cluster volume and forced a restart on Read Replica.

Answer: A B

51. Ahead of the upcoming holiday sale season, a group of database administrators at an e-commerce company is analyzing performance issues for an RDS for PostgreSQL DB instance and is reviewing related metrics. The group wants to understand the database wait events in more detail. As a Database Specialist, which of the following steps would you suggest for the given use-case?

        A. Use the Trusted Advisor dashboard to analyze the wait events.
        B. Enable Amazon RDS Performance Insights and review the appropriate dashboard to analyze the wait events.
        C. Configure the database logs to be pushed to Amazon CloudWatch Logs for detailed analysis for the wait events.
        D. Use Amazon RDS Enhanced Monitoring to analyze the wait events.

Answer: B

52. A multi-national retail company uses separate AWS accounts for their business units. The finance team has an encrypted snapshot of an Amazon Relational Database Service (Amazon RDS) instance that uses the default AWS Key Management Service (AWS KMS) key. The finance team wants to share the encrypted snapshot with their Audit team that uses another AWS account. As a Database Specialist, which of the following solutions would you recommend to address the given use-case?

        A. Add the target account to the default AWS KMS key. Copy the snapshot using the customer managed key. and then share the snapshot with the target account Copy the shared DB snapshot from the target account.
        B. Add the target account to the default AWS KMS key. Copy the snapshot using the default AWS KMS key, and then share the snapshot with the target account.
        C. Copy the shared DB snapshot from the target account Add the target account to a customer managed key. Copy the snapshot using the default AWS KMS key. and then share the snapshot with the target account.
        D. Copy the shared DB snapshot from the target account Add the target account to a customer managed key. Copy the snapshot using the customer managed key. and then share the snapshot with the target account Copy the shared DB snapshot from the target account.

Answer: D

53. A retail company recently migrated its IT infrastructure from the on-premises data center to AWS Cloud. After a security review by an external auditor, the CTO at the company has mandated that the RDS for PostGreSQL DB cluster should be encrypted at rest using AWS KMS. Due to the high volume of data, it is not possible to develop a custom Extract Transform Load (ETL) solution to reload the data into another encrypted database because of the time constraints involved in developing Testing and deploying the ETL solution. As a Database Specialist, which of the following solutions would you recommend to address the given use-case?

        A. Create a snapshot of the unencrypted RDS DB instance. Create an encrypted snapshot via an encrypted copy of the unencrypted snapshot Restore this new encrypted snapshot into a new DB instance.
        B. Create an encrypted Read Replica of the RDS DB instance and then promote the Read Replica to its own standalone DB instance.
        C. Use AWS CLI to activate the AWS KMS encryption setting on the existing RDS DB instance
        D. Create a snapshot of the unencrypted RDS DB instance Create an encrypted snapshot via an encrypted copy of the unencrypted snapshot Restore this new encrypted snapshot into the existing DB instance.

Answer: A

54. A multi-national retail company uses Amazon Aurora DB cluster as its primary database service. The company has now deployed 5 multi-AZ Read Replicas to increase the read throughput and for use as failover target. The replicas have been assigned the following failover priority tiers and corresponding sizes are given in parentheses: tier-1 (8TB). tier-1 (16TB). tier-10 (16TB). tier-15 (8TB). tier-15 (16TB). In the event of a failover, Amazon Aurora will promote which of the following Read Replicas?

        A. Tier-10 (16TB)
        B. Tier-1 (8TB)
        C. Tier-15 (16TB)
        D. Tier-1 (16TB)

Answer: A

55. The database administration team at an e-commerce company is doing a root-cause analysis for a recent spike in CPU utilization for an RDS MySQL DB instance that caused the application to perform poorly. The standard metrics available in Amazon CloudWatch are not enough to guide the investigation. The company has hired you as an AWS Certified Database Specialist to determine what caused the CPU spike. Which of the following steps would you recommend to provide more details about the underlying processes and queries resulting in an increase in the CPU load? (Select two)

        A. Use Amazon Athena to analyze the SQL statements being run on the RDS instance
        B. Enable RDS Performance Insights and review the appropriate dashboard to visualize the database load and filter the load by waits, SQL statements, hosts or users.
        C. Implement ElastiCache in front of the RDS DB instance to reduce the CPU load on the RDS instance.
        D. Activate Amazon CloudWatch Events and review the event data that has the SQL statements behind the CPU spikes.
        E. Activate Enhanced Monitoring to view CPU utilization information for the RDS MySQL DB instance.

Answer: B E

56. A social media company is setting up an Aurora DB cluster with one primary instance and four Aurora Replicas for its flagship application. The Aurora DB cluster has one medium-sized primary instance, one large-sized Replica, one small-sized Replica and two medium-sized Replicas. The database administrator has not assigned a promotion tier to the Replicas. In case the primary instance fails, which of the following events will occur?

        A. One of the medium-sized Aurora Replicas will be chosen randomly for promotion.
        B. The small-sized Aurora Replica will be promoted.
        C. The large-sized Aurora Replica will be promoted.
        D. None of the Replicas will be promoted and Aurora will spin up a new primary instance.

Answer: C

57. An e-commerce application is facing user experience issues with users reporting frequent sign-in requests from the application. The application is currently hosted on multiple EC2 instances. The development team has identified the root cause as unhealthy servers causing session data to be lost. The Lead Developer has asked the database management team to implement a distributed in-memory cache-based session management solution. As a Database Specialist, which of the following solutions would you recommend?

        A. Use Elasticache for distributed in-memory cache based session management.
        B. Use RDS for distributed in-memory cache based session management.
        C. Use DynamoDB for distributed in-memory cache based session management.
        D. Continue with application-based sticky sessions.

Answer: A

58. A health-care startup wants to leverage ElastiCache for Redis in cluster mode to enhance the performance and scalability of its existing two-tier application architecture. The ElastiCache cluster is configured to listen on port 6379. The company has hired you as an AWS Certified Database Specialist to make sure that the cache data is secure and protected from unauthorized access so that the solution is HIPAA compliant. Which of the following steps would address the given use-case? (Select three)

        A. Create the cluster with auth-token parameter and make sure that the parameter is included in all subsequent commands to the cluster.
        B. Enable CloudTrail to monitor the API Calls for the ElastiCache cluster.
        C. Configure the security group for the ElastiCache cluster with the required rules to allow outbound traffic to the cluster’s clients on port 6379.
        D. Configure the security group for the ElastiCache cluster with the required rules to allow inbound traffic from the cluster itself as well as from the cluster’s clients on port 6379.
        E. Configure the ElastiCache cluster to have both in-transit as well as at-rest encryption.
        F. Enable CloudWatch Logs to monitor the security credentials for the ElastiCache cluster.

Answer: A D E

59. An IT company is using AWS DMS to migrate its Amazon RDS for Oracle DB instance configured in a VPC in the us-east-1 Region to another VPC in the us-west-1 Region. As a Database Specialist, where would you place the DMS replication instance for the MOST optimal performance?

        A. Create the replication instance in the same Region and VPC as the target DB instance.
        B. Create the replication instance in the same Availability Zone and VPC as the source DB instance.
        C. Create the replication instance in the same Availability Zone and VPC as the target DB instance.
        D. Create the replication instance in the same Region and VPC as the source DB instance.

Answer: C

6. An advertising technology startup in Silicon Valley captures browsing metadata to contextually display relevant images, pages, and links to targeted users. A single page load can generate multiple events that need to be stored individually. Each page load must query the user’s browsing history to provide targeting recommendations. The startup expects over 1 billion page visits per day. The startup now wants to add a caching layer to support high read volumes. As a Database Specialist, which of the following AWS services would you recommend as a caching layer for this use-case? (Select two)

        A. Elasticsearch
        B. ElastiCache
        C. RDS
        D. DynamoDB Accelerator (DAX)
        E. Redshift

Answer: B D

60. A global CRM company has recently migrated its technology infrastructure from its on-premises data center to AWS Cloud. The database administration team has provisioned an RDS PostGreSQL DB cluster for the company’s flagship CRM application. An analytics workload also runs on the same database which publishes near real-time reports for the senior management of the company. When the analytics workload runs, it slows down the CRM application as well, resulting in bad user experience. As a Database Specialist, which of the following would you recommend as the MOST cost-optimal solution to fix this issue?

        A. Enable Multi-AZ for the RDS database and run the analytics workload on the standby database.
        B. For Disaster Recovery purposes, create a Read Replica in another Region as the Master database and point the analytics workload there.
        C. Create a Read Replica in the same Region as the Master database and point the analytics workload there.
        D. Migrate the analytics application to AWS Lambda.

Answer: C

61. A media company is planning to move their on-premises database to Amazon RDS. As part of disaster recovery planning. the team is looking into the various database backup options available with RDS. As a Database Specialist, you have been roped in to understand and weigh-in on the RDS automated backups and snapshot features. Which of the following statements would you identify as correct for the given context? (Select three)

        A. Disabling automatic backups for a DB instance deletes all existing automated backups for the instance.
        B. DB Snapshots can be created with the AWS Management Console, CreateDBSnapshot API, or create-db-snapshot command.
        C. The total number of automated backups and manual snapshots put together, should not exceed 100 per Region.
        D. The default backup retention period is one day if you create the DB instance using the Amazon RDS API.
        E. DB Snapshots can be created with the AWS Management Console and create-db-snapshot command only.
        F. When a DB instance is deleted manually created DB snapshots as well as automated backups are deleted.

Answer: A B D

62. A Database Specialist is working on the throughput capacity of a newly provisioned table in Amazon DynamoDB. The database specialist has provisioned 20 Read Capacity Units for the table. Which of the following options represents the correct throughput that the table will support for the various read modes?

        A. Read throughput of 80KB/sec with strong consistency. Read throughput of 160KB/sec with eventual consistency. Transactionalread throughput of 40KB/sec.
        B. Read throughput of 80KB/sec with strong consistency. Read throughput of 160KB/sec with eventual consistency. Transactional read throughput of 320KB/sec.
        C. Read throughput of 40KB/sec with strong consistency. Read throughput of 80KB/sec with eventual consistency. Transactional read throughput of 120KB/sec.
        D. Read throughput of 40KB/sec with strong consistency. Read throughput of 80KB/sec with eventual consistency. Transactional read throughput of 60KB/sec.

Answer: A

63. A retail company is migrating its infrastructure from the on-premises data-center to AWS Cloud. The company wants to deploy its two-tier application with the EC2 instance based web servers in a public subnet and PostGreSQL RDS based database layer in a private subnet. The company wants to ensure that the database access credentials used by the web servers are handled securely as well as these credentials are changed every 90 days in an automated way using an off-the-shelf solution. As a Database Specialist, which of the following solutions would you recommend for the given use-case?

        A. Store the database access credentials in an SSE-S3 encrypted text file on S3. Configure the application web servers to retrieve the credentials from S3 on system boot Write custom code to change the database access credentials stored on the encrypted file after 90 days.
        B. Store the database access credentials as the EC2 instance user data. Configure the application web servers to retrieve the credentials from the user data while bootstrapping. Write custom code to change the database access credentials stored in the user data after 90 days.
        C. Store the database access credentials in a KMS encrypted text file on EFS. Configure the application web servers to retrieve the credentials from EFS on system boot Write custom code to change the database access credentials stored on the encrypted file after 90 days
        D. Use AWS Secrets Manager to store the database access credentials with the rotation interval configured to 90 days. Set up the application web servers to retrieve the credentials from the Secrets Manager.

Answer: D

64. A multi-national retail company is planning to move their on-premises database to Amazon RDS. As an AWS Certified Database Specialist, you have been roped in to understand and weigh-in on the replication features of RDS. Which of the following statements would you identify as correct for the given context? (Select two)

        A. If you delete an Amazon RDS for MySQL DB Instance that has Read Replicas, all Read Replicas will be promoted to standalone DB Instances.
        B. Amazon RDS for MySQL allows you to create a second-tier read replica from an existing first-tier Read Replica.
        C. Amazon RDS for PostgreSQL allows you to create a second-tier Read Replica from an existing first-tier Read Replica.
        D. You can configure RDS source DB instance as a Multi-AZ deployment to avoid I/O suspension that occurs when a Read Replica is initiated.
        E. When running an RDS DB instance as a Multi-AZ deployment the standby DB can be used for read or write operations.

Answer: B D

65. A health-care company has just migrated its IT infrastructure from the on-premises data-center to AWS Cloud. The company is using Aurora PostGreSQL DB cluster as its data store and the CTO at the company now wants to build the caching layer of the current architecture for its PostGreSQL DB cluster. He wants the caching layer to have replication and archival support built into the architecture. Most importantly, the solution needs to be end-to-end HIPAA compliant. Which of the following AWS service offers the capabilities required for the engineering of the caching layer?

        A. DocumentDB
        B. DynamoDB Accelerator (DAX)
        C. ElastiCache for Redis
        D. ElastiCache for Memcached

Answer: C

7. A multi-national retail company wants to migrate its on-premises Oracle database to Aurora MySQL. The company has hired an AWS Certified Database Specialist to carry out the migration with minimal downtime using AWS DMS. The company has mandated that the migration must have minimal impact on the performance of the source database and the Database Specialist must validate that the data was migrated accurately from the source to the target before the cutover. Which of the following solutions will MOST effectively address this use-case?

        A. Configure DMS premigration assessment on the migration task so the assessment can compare the source and target data and report any mismatches.
        B. Use AWS Schema Conversion Tool for the migration task so it can compare the source and target data and report any mismatches.
        C. Configure DMS data validation on the migration task so it can compare the source and target data for the DMS task and report any mismatches.
        D. Use the table metrics of the DMS task to verify the statistics for tables being migrated including the DDL statements completed.

Answer: C

8. As a Database Specialist, you have been asked to implement a disaster recovery strategy for all the Amazon RDS databases that a company owns. Which of the following points do you need to consider for creating a robust recovery plan (Select three)?

        A. Automated backups are limited to a single AWS Region while manual snapshots and Read Replicas are supported across multiple Regions.
        B. Recovery time objective (RTO). expressed in hours, represents how much data you could lose when a disaster happens.
        C. You can share automated Amazon RDS snapshots with up to 20 AWS accounts.
        D. Database snapshots are user-initiated backups of your complete DB instance that serve as full backups. These snapshots can be copied and shared to different Regions and accounts.
        E. Recovery time objective (RTO) represents the number of hours it takes, to return the Amazon RDS database to a working state after a disaster.
        F. Similar to an Amazon RDS Multi-AZ configuration, failover to a Read Replica is an automated process that requires no manual intervention after initial configurations.

Answer: A D E

9. A data analytics company wants to deploy a global IoT solution in multiple AWS Regions. The company wants to store loT data in DynamoDB tables in each Region as per the user’s geographic location. The DevOps team at the company wants an automated solution that can deploy the database along with the rest of the application with an identical configuration in new Regions as per the business requirement. The solution should also propagate configuration updates across all Regions. As a Database Specialist, which of the following options would you recommend to address the given use-case?

        A. Create DynamoDB tables using the AWS Console in multiple Regions and create a detailed guide for future updates to the deployment.
        B. Create DynamoDB global tables via AWS CLI.
        C. Create a CloudFormation template and deploy the template to multiple Regions via a stack set.
        D. Use a CloudFormation template to deploy the solution to multiple Regions.

Answer: C