Notes: Hi all, We’re sharing AWS Database Specialty (DBS-C01) Practice Exam Part 3 will familiarize you with types of questions you may encounter on the certification exam and help you determine your readiness or if you need more preparation and/or experience. Successful completion of the practice exam does not guarantee you will pass the certification exam as the actual exam is longer and covers a wider range of topics. We highly recommend you should take AWS Database Specialty Guarantee Part because it include actual exam questions and highlighted answers are collected in our exam. It will help you pass exam in easier way. For the rest and actual exam questions please follow us on our website.

For AWS: https://www.awslagi.com \ 
For GCP: https://www.gcp-examquestions.com

21. A company maintains several databases using Amazon RDS for MySQL and PostgreSQL. Each RDS database generates log files with retention periods set to their default values. The company has now mandated that database logs be maintained for up to 90 days in a centralized repository to facilitate real-time and after-the-fact analyses. What should a Database Specialist do to meet these requirements with minimal effort?

        A. Create an AWS Lambda function to pull logs from the RDS databases and consolidate the log files in an Amazon S3 bucket. Set a lifecycle policy to expire the objects after 90 days.
        B. Modify the RDS databases to publish log to Amazon CloudWatch Logs. Change the log retention policy for each log group to expire the events after 90 days.
        C. Write a stored procedure in each RDS database to download the logs and consolidate the log files in an Amazon S3 bucket. Set a lifecycle policy to expire the objects after 90 days.
        D. Create an AWS Lambda function to download the logs from the RDS databases and publish the logs to Amazon CloudWatch Logs. Change the log retention policy for the log group to expire the events after 90 days.

Answer: B

22. A Database Specialist is setting up a new Amazon Aurora DB cluster with one primary instance and three Aurora Replicas for a highly intensive, business-critical application. The Aurora DB cluster has one medium-sized primary instance, one large-sized replica, and two medium sized replicas. The Database Specialist did not assign a promotion tier to the replicas. In the event of a primary failure, what will occur?

        A. Aurora will promote an Aurora Replica that is of the same size as the primary instance
        B. Aurora will promote an arbitrary Aurora Replica
        C. Aurora will promote the largest-sized Aurora Replica
        D. Aurora will not promote an Aurora Replica

Answer: C

23. A company is running its line of business applications on AWS, which uses Amazon RDS for MySQL at the persistent data store. The company wants to minimize downtime when it migrates the database to Amazon Aurora. Which migration method should a Database Specialist use?

        A. Take a snapshot of the RDS for MySQL DB instance and create a new Aurora DB cluster with the option to migrate snapshots.
        B. Make a backup of the RDS for MySQL DB instance using the mysqldump utility, create a new Aurora DB cluster, and restore the backup.
        C. Create an Aurora Replica from the RDS for MySQL DB instance and promote the Aurora DB cluster.
        D. Create a clone of the RDS for MySQL DB instance and promote the Aurora DB cluster.

Answer: C

24. The Security team for a finance company was notified of an internal security breach that happened 3 weeks ago. A Database Specialist must start producing audit logs out of the production Amazon Aurora PostgreSQL cluster for the Security team to use for monitoring and alerting. The Security team is required to perform real-time alerting and monitoring outside the Aurora DB cluster and wants to have the cluster push encrypted files to the chosen solution. Which approach will meet these requirements?

        A. Use pg_audit to generate audit logs and send the logs to the Security team.
        B. Use AWS CloudTrail to audit the DB cluster and the Security team will get data from Amazon S3.
        C. Set up database activity streams and connect the data stream from Amazon Kinesis to consumer applications.
        D. Turn on verbose logging and set up a schedule for the logs to be dumped out for the Security team.

Answer: C

25. A company is using Amazon RDS for MySQL to redesign its business application. A Database Specialist has noticed that the Development team is restoring their MySQL database multiple times a day when Developers make mistakes in their schema updates. The Developers sometimes need to wait hours to the restores to complete. Multiple team members are working on the project, making it difficult to find the correct restore point for each mistake. Which approach should the Database Specialist take to reduce downtime?

        A. Deploy multiple read replicas and have the team members make changes to separate replica instances
        B. Migrate to Amazon RDS for SQL Server, take a snapshot, and restore from the snapshot
        C. Migrate to Amazon Aurora MySQL and enable the Aurora Backtrack feature
        D. Enable the Amazon RDS for MySQL Backtrack feature

Answer: C

26. A media company is using Amazon RDS for PostgreSQL to store user data. The RDS DB instance currently has a publicly accessible setting enabled and is hosted in a public subnet. Following a recent AWS Well-Architected Framework review, a Database Specialist was given new security requirements. Only certain on-premises corporate network IPs should connect to the DB instance.
Connectivity is allowed from the corporate network only. Which combination of steps does the Database Specialist need to take to meet these new requirements? (Choose three.)

        A. Modify the pg_hba.conf file. Add the required corporate network IPs and remove the unwanted IPs.
        B. Modify the associated security group. Add the required corporate network IPs and remove the unwanted IPs.
        C. Move the DB instance to a private subnet using AWS DMS.
        D. Enable VPC peering between the application host running on the corporate network and the VPC associated with the DB instance.
        E. Disable the publicly accessible setting.
        F. Connect to the DB instance using private IPs and a VPN.

Answer: B E F

27. A company is about to launch a new product, and test databases must be re-created from production data. The company runs its production databases on an Amazon Aurora MySQL DB cluster. A Database Specialist needs to deploy a solution to create these test databases as quickly as possible with the least amount of administrative effort. What should the Database Specialist do to meet these requirements?

        A. Restore a snapshot from the production cluster into test clusters
        B. Create logical dumps of the production cluster and restore them into new test clusters
        C. Use database cloning to create clones of the production cluster
        D. Add an additional read replica to the production cluster and use that node for testing

Answer: C

28. A company with branch offices in Portland, New York, and Singapore has a three-tier web application that leverages a shared database. The database runs on Amazon RDS for MySQL and is hosted in the us-west-2 Region. The application has a distributed front end deployed in the us-west-2, ap-southeast-1, and us- east-2 Regions. This front end is used as a dashboard for Sales Managers in each branch office to see current sales statistics. There are complaints that the dashboard performs more slowly in the Singapore location than it does in Portland or New York. A solution is needed to provide consistent performance for all users in each location. Which set of actions will meet these requirements?

        A. Take a snapshot of the instance in the us-west-2 Region. Create a new instance from the snapshot in the ap-southeast-1 Region. Reconfigure the ap- southeast-1 front-end dashboard to access this instance.
        B. Create an RDS read replica in the ap-southeast-1 Region from the primary RDS DB instance in the us-west-2 Region. Reconfigure the ap-southeast-1 front- end dashboard to access this instance.
        C. Create a new RDS instance in the ap-southeast-1 Region. Use AWS DMS and change data capture (CDC) to update the new instance in the ap-southeast-1 Region. Reconfigure the ap-southeast-1 front-end dashboard to access this instance.
        D. Create an RDS read replica in the us-west-2 Region where the primary instance resides. Create a read replica in the ap-southeast-1 Region from the read replica located on the us-west-2 Region. Reconfigure the ap-southeast-1 front-end dashboard to access this instance.

Answer: D

29. A company wants to migrate its existing on-premises Oracle database to Amazon Aurora PostgreSQL. The migration must be completed with minimal downtime using AWS DMS. A Database Specialist must validate that the data was migrated accurately from the source to the target before the cutover. The migration must have minimal impact on the performance of the source database. Which approach will MOST effectively meet these requirements?

        A. Use the AWS Schema Conversion Tool (AWS SCT) to convert source Oracle database schemas to the target Aurora DB cluster. Verify the datatype of the columns.
        B. Use the table metrics of the AWS DMS task created for migrating the data to verify the statistics for the tables being migrated and to verify that the data definition language (DDL) statements are completed.
        C. Enable the AWS Schema Conversion Tool (AWS SCT) pre migration validation and review the pre migration checklist to make sure there are no issues with the conversion.
        D. Enable AWS DMS data validation on the task so the AWS DMS task compares the source and target records, and reports any mismatches.

Answer: D

30. A company is planning to close for several days. A Database Specialist needs to stop all applications along with the DB instances to ensure employees do not have access to the systems during this time. All databases are running on Amazon RDS for MySQL. The Database Specialist wrote and executed a script to stop all the DB instances. When reviewing the logs, the Database Specialist found that Amazon RDS DB instances with read replicas did not stop. How should the Database Specialist edit the script to fix this issue?

        A. Stop the source instances before stopping their read replicas
        B. Delete each read replica before stopping its corresponding source instance
        C. Stop the read replicas before stopping their source instances
        D. Use the AWS CLI to stop each read replica and source instance at the same

Answer: B

31. A global digital advertising company captures browsing metadata to contextually display relevant images, pages, and links to targeted users. A single page load can generate multiple events that need to be stored individually. The maximum size of an event is 200 KB and the average size is 10 KB. Each page load must query the user’s browsing history to provide targeting recommendations. The advertising company expects over 1 billion page visits per day from users in the United States, Europe, Hong Kong, and India. The structure of the metadata varies depending on the event. Additionally, the browsing metadata must be written and read with very low latency to ensure a good viewing experience for the users.
Which database solution meets these requirements?

        A. Amazon DocumentDB
        B. Amazon RDS Multi-AZ deployment
        C. Amazon DynamoDB global table
        D. Amazon Aurora Global Database

Answer: C

32. A Database Specialist modified an existing parameter group currently associated with a production Amazon RDS for SQL Server Multi-AZ DB instance. The change is associated with a static parameter type, which controls the number of user connections allowed on the most critical RDS SQL Server DB instance for the company. This change has been approved for a specific maintenance window to help minimize the impact on users. How should the Database Specialist apply the parameter group change for the DB instance?

        A. Select the option to apply the change immediately
        B. Allow the preconfigured RDS maintenance window for the given DB instance to control when the change is applied
        C. Apply the change manually by rebooting the DB instance during the approved maintenance window
        D. Reboot the secondary Multi-AZ DB instance

Answer: C

33. A Database Specialist is designing a new database infrastructure for a ride hailing application. The application data includes a ride tracking system that stores GPS coordinates for all rides. Real-time statistics and metadata lookups must be performed with high throughput and microsecond latency. The database should be fault tolerant with minimal operational overhead and development effort. Which solution meets these requirements in the MOST efficient way?

        A. Use Amazon RDS for MySQL as the database and use Amazon ElastiCache
        B. Use Amazon DynamoDB as the database and use DynamoDB Accelerator
        C. Use Amazon Aurora MySQL as the database and use Aurora’s buffer cache
        D. Use Amazon DynamoDB as the database and use Amazon API Gateway

Answer: B

34. A company is using an Amazon Aurora PostgreSQL DB cluster with an xlarge primary instance master and two large Aurora Replicas for high availability and read-only workload scaling. A failover event occurs and application performance is poor for several minutes. During this time, application servers in all Availability Zones are healthy and responding normally. What should the company do to eliminate this application performance issue?

        A. Configure both of the Aurora Replicas to the same instance class as the primary DB instance. Enable cache coherence on the DB cluster, set the primary DB instance failover priority to tier-0, and assign a failover priority of tier-1 to the replicas.
        B. Deploy an AWS Lambda function that calls the DescribeDBInstances action to establish which instance has failed, and then use the PromoteReadReplica operation to promote one Aurora Replica to be the primary DB instance. Configure an Amazon RDS event subscription to send a notification to an Amazon SNS topic to which the Lambda function is subscribed.
        C. Configure one Aurora Replica to have the same instance class as the primary DB instance. Implement Aurora PostgreSQL DB cluster cache management. Set the failover priority to tier-0 for the primary DB instance and one replica with the same instance class. Set the failover priority to tier-1 for the other replicas.
        D. Configure both Aurora Replicas to have the same instance class as the primary DB instance. Implement Aurora PostgreSQL DB cluster cache management. Set the failover priority to tier-0 for the primary DB instance and to tier-1 for the replicas.

Answer: C

35. A company has a database monitoring solution that uses Amazon CloudWatch for its Amazon RDS for SQL Server environment. The cause of a recent spike in CPU utilization was not determined using the standard metrics that were collected. The CPU spike caused the application to perform poorly, impacting users. A Database Specialist needs to determine what caused the CPU spike. Which combination of steps should be taken to provide more visibility into the processes and queries running during an increase in CPU load? (Choose two.)

        A. Enable Amazon CloudWatch Events and view the incoming T-SQL statements causing the CPU to spike.
        B. Enable Enhanced Monitoring metrics to view CPU utilization at the RDS SQL Server DB instance level.
        C. Implement a caching layer to help with repeated queries on the RDS SQL Server DB instance.
        D. Use Amazon QuickSight to view the SQL statement being run.
        E. Enable Amazon RDS Performance Insights to view the database load and filter the load by waits, SQL statements, hosts, or users.

Answer: B E

36. A company is using Amazon with Aurora Replicas for read-only workload scaling. A Database Specialist needs to split up two read-only applications so each application always connects to a dedicated replica. The Database Specialist wants to implement load balancing and high availability for the read-only applications. Which solution meets these requirements?

        A. Use a specific instance endpoint for each replica and add the instance endpoint to each read-only application connection string.
        B. Use reader endpoints for both the read-only workload applications.
        C. Use a reader endpoint for one read-only application and use an instance endpoint for the other read-only application.
        D. Use custom endpoints for the two read-only applications.

Answer: D

37. An online gaming company is planning to launch a new game with Amazon DynamoDB as its data store. The database should be designated to support the following use cases:
– Update scores in real time whenever a player is playing the game.
– Retrieve a player’s score details for a specific game session.
– A Database Specialist decides to implement a DynamoDB table.
– Each player has a unique user_id and each game has a unique game_id.
Which choice of keys is recommended for the DynamoDB table?

        A. Create a global secondary index with game_id as the partition key
        B. Create a global secondary index with user_id as the partition key
        C. Create a composite primary key with game_id as the partition key and user_id as the sort key
        D. Create a composite primary key with user_id as the partition key and game_id as the sort key

Answer: D

38. A Database Specialist migrated an existing production MySQL database from on-premises to an Amazon RDS for MySQL DB instance. However, after the migration, the database needed to be encrypted at rest using AWS KMS. Due to the size of the database, reloading, the data into an encrypted database would be too time-consuming, so it is not an option. How should the Database Specialist satisfy this new requirement?

        A. Create a snapshot of the unencrypted RDS DB instance. Create an encrypted copy of the unencrypted snapshot. Restore the encrypted snapshot copy.
        B. Modify the RDS DB instance. Enable the AWS KMS encryption option that leverages the AWS CLI.
        C. Restore an unencrypted snapshot into a MySQL RDS DB instance that is encrypted.
        D. Create an encrypted read replica of the RDS DB instance. Promote it the master.

Answer: A

39. A Database Specialist is planning to create a read replica of an existing Amazon RDS for MySQL Multi-AZ DB instance. When using the AWS Management Console to conduct this task, the Database Specialist discovers that the source RDS DB instance does not appear in the read replica source selection box, so the read replica cannot be created. What is the most likely reason for this?

        A. The source DB instance has to be converted to Single-AZ first to create a read replica from it.
        B. Enhanced Monitoring is not enabled on the source DB instance.
        C. The minor MySQL version in the source DB instance does not support read replicas.
        D. Automated backups are not enabled on the source DB instance.

Answer: D

40. A Database Specialist has migrated an on-premises Oracle database to Amazon Aurora PostgreSQL. The schema and the data have been migrated successfully. The on-premises database server was also being used to run database maintenance cron jobs written in Python to perform tasks including data purging and generating data exports. The logs for these jobs show that, most of the time, the jobs completed within 5 minutes, but a few jobs took up to 10 minutes to complete. These maintenance jobs need to be set up for Aurora PostgreSQL. How can the Database Specialist schedule these jobs so the setup requires minimal maintenance and provides high availability?

        A. Create cron jobs on an Amazon EC2 instance to run the maintenance jobs following the required schedule.
        B. Connect to the Aurora host and create cron jobs to run the maintenance jobs following the required schedule.
        C. Create AWS Lambda functions to run the maintenance jobs and schedule them with Amazon CloudWatch Events.
        D. Create the maintenance job using the Amazon CloudWatch job scheduling plugin.

Answer: C