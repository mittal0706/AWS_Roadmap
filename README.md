# AWS_Roadmap

- What is Cloud?
- Difference between IAAS, PAAS, SAAS?
- Why we Learn AWS Cloud?
- what is Region, availability zones and Edge Locations?

### What is the top 15 services for a developer?
- EC2 (Elastic Compute Cloud)
- VPC (Virtual private Cloud)
- S3 (Simple Storage service)
- Lambda
- Amazon RDS
- AWS DynamoDB
- AWS CloudWatch
- API Gateway
- EBS and EFS
- AWS SNS
- AWS SQS
- AWS Cloudfront
- AWS IAM
- LoadBalancing
- Autoscaling

## EC2 (Elastic Compute Cloud)

- Types of EC2 Instance?
- Instance Family?
- What is Reserverd Instance, Dedicated Host, Spot Instance, On-Demand?
- How to create windows Server?
- What is Security Group?
- What is user data? why we use user data?
- How to install webserver IIS and create webpage on windows server?
- What is AMI?
- Why we use key pair? What is the Difference between public key and private key? 
- What is the Difference between Snapshot and AMI?
- How to access EC2 machine? how many methods to access EC2 instance?

## EBS (Elastic Block Storage)

- What is Amazon EBS, and what is its primary purpose?
- What are the different types of EBS volumes available, and how do they differ in terms of performance and cost?
- How do you attach and detach EBS volumes to Amazon EC2 instances?
- What is the difference between EBS snapshots and AMI (Amazon Machine Image) backups?
- How can you resize an EBS volume, and what considerations should be taken into account?
- How does EBS encryption work, and why is it important for data security?
- What is EBS Provisioned IOPS, and when should you use it?
- How can you optimize EBS performance for your workload?

## EFS (Elastic File Storage)

- What is Amazon EFS, and what are its key features?
- How do you create and configure an EFS file system?
- What is the advantage of using EFS over EBS for shared access to files?
- How can you mount an EFS file system to multiple Amazon EC2 instances?
- What is the significance of EFS mount targets and availability zones?
- How does EFS provide high availability and durability?
- How can you control access to EFS file systems using security groups?
- What are the considerations for cost optimization when using EFS?

## VPC (Virtual Private Cloud)

- What is a VPC in AWS?
- What is the purpose of CIDR blocks in VPC?
- How can you connect your VPC to the internet?
- What is the difference between a public subnet and a private subnet?
- How do you control inbound and outbound traffic in a VPC?
- What is an internet gateway, and how is it used in VPC?
- What is the role of a NAT gateway in VPC?
- How can you establish connectivity between different VPCs?
- What are the benefits of using VPC endpoints?
- How does VPC peering work, and what are its limitations?

## S3

- What is Amazon S3, and what is its primary use case?
- What are S3 buckets, and how are they organized?
- How can you control access to S3 buckets and objects?
- What is the difference between S3 Standard, S3 Intelligent-Tiering, and S3 Glacier storage classes?
- How does S3 versioning work, and what are its benefits?
- What is the purpose of S3 server access logging?
- How can you configure event notifications for S3 objects?
- What is S3 Transfer Acceleration, and how does it improve upload and download speeds?
- How can you encrypt data stored in S3?
- What are S3 pre-signed URLs, and how are they used for temporary access to objects?

## Lambda

- What is AWS Lambda, and what is its purpose?
- How does Lambda function execution work?
- What are event sources and triggers in Lambda?
- How can you pass data to a Lambda function and retrieve the results?
- What is the difference between synchronous and asynchronous invocation of Lambda functions?
- How does Lambda pricing work?
- What are the available runtime environments in Lambda?
- How can you set up permissions and access control for Lambda functions?
- What are the benefits of using Lambda for serverless application development?
- How can you monitor and troubleshoot Lambda functions?

## Amazon RDS

- What is Amazon RDS, and why is it used?
- What are the different database engines supported by RDS?
- How can you create and manage database instances in RDS?
- What is the purpose of database backups in RDS?
- How can you scale your RDS database instance?
- What are read replicas, and how are they used for scaling and performance improvements?
- How can you secure access to RDS instances using security groups?
- What is the role of parameter groups in RDS, and how can you configure them?
- What is Multi-AZ deployment in RDS, and how does it provide high availability?
- How can you monitor and troubleshoot RDS instances?


## AWS DynamoDB

- What is Amazon DynamoDB, and why is it used?
- How is DynamoDB different from traditional relational databases?
- What are DynamoDB tables, and how are they organized?
- What is the purpose of primary keys in DynamoDB?
- How can you model and store data in DynamoDB?
- What are secondary indexes, and how do they enhance query flexibility?
- How does DynamoDB handle scaling and performance?
- What are read and write capacity units in DynamoDB?
- How can you configure and manage DynamoDB streams for capturing changes to the table?
- What are DynamoDB global tables, and how do they enable multi-region replication?

## AWS CloudWatch

- What is Amazon CloudWatch, and what are its primary use cases?
- How does CloudWatch collect and store metrics?
- What is the purpose of CloudWatch alarms, and how can you set them up?
- How can you collect and analyze logs using CloudWatch Logs?
- What are CloudWatch Events, and how can you use them for triggering automated actions?
- How can you create custom metrics in CloudWatch?
- What is the CloudWatch Agent, and how does it enable custom log collection and metric monitoring?
- How can you visualize metrics and logs using CloudWatch dashboards?
- What are the options for extending CloudWatch's capabilities through integration with other AWS services?
- How can you use CloudWatch for monitoring and troubleshooting your AWS resources and applications?

## API Gateway

- What is Amazon API Gateway, and what is its purpose?
- How does API Gateway facilitate the creation and management of APIs?
- What is a RESTful API, and how can you define resources and methods using API Gateway?
- How can you configure request and response mappings in API Gateway?
- What are the options for integrating API Gateway with backend services, such as AWS Lambda or Amazon DynamoDB?
- How can you enable caching to improve API performance in API Gateway?
- What are the available options for authentication and authorization in API Gateway?
- How can you deploy and manage different stages of your API in API Gateway?
- What are the monitoring and logging capabilities provided by API Gateway?
- How can you secure and protect your API endpoints in API Gateway?

## AWS SNS

- What is Amazon SNS, and what is its primary purpose?
- How does SNS use a publish-subscribe model for messaging?
- What are SNS topics, and how do they facilitate message distribution?
- How can you create and configure an SNS topic using the AWS Management Console or AWS CLI?
- What are SNS subscriptions, and how do they define endpoints or subscribers for receiving messages?
- What are the available protocols for delivering messages in SNS, and how do they differ?
- How can you send messages to an SNS topic using various protocols, such as HTTP/HTTPS, email, SMS, mobile push notifications, or Amazon SQS integration?
- How can you create different types of subscriptions, such as HTTP/S, email, SMS, or AWS Lambda?
- How does SNS handle message filtering based on attributes or message structure?
- What are SNS message attributes, and how can they be used for filtering and routing messages?

## AWS SQS

- What is Amazon SQS, and what is its primary purpose?
- How does SQS use a distributed queuing system to enable reliable message delivery?
- What are SQS queues, and how can you create and manage them?
- How can you send messages to an SQS queue, and what information can you include in a message?
- How can you receive messages from an SQS queue, and how does SQS handle message visibility and polling?
- What is the purpose of the visibility timeout, and how does it prevent multiple consumers from processing the same message simultaneously?
- How can you configure message retention in SQS, and what happens to messages that exceed the retention period?
- What are dead-letter queues in SQS, and how can they be used for handling failed or unprocessable messages?
- How can you control access to SQS queues using AWS Identity and Access Management (IAM) policies?
- What are the considerations for scaling and optimizing SQS for different use cases?

## AWS Cloudfront

- What is Amazon CloudFront, and what is its primary purpose?
- How does CloudFront use a global network of edge locations to deliver content with low latency and high data transfer speeds?
- What are CloudFront distributions, and how can you create and manage them?
- How can you configure CloudFront to work with different types of origin servers, such as Amazon S3 buckets, custom origin servers, or load balancers?
- What are the caching options available in CloudFront, and how can you control cache behavior for different types of content?
- How can you set up content routing in CloudFront using features like behavior rules and lambda@edge functions?
- What are CloudFront signed URLs and signed cookies, and how can you use them to control access to your content?
- How can you monitor and analyze the performance of your CloudFront distributions using CloudFront access logs and real-time metrics?
- What are the options for securing your CloudFront distributions using SSL/TLS certificates and AWS Identity and Access Management (IAM) policies?
- What are the considerations for cost optimization and scaling when using CloudFront for content delivery?

## AWS IAM

- What is AWS IAM, and what is its primary purpose?
- How does IAM help in managing access to AWS resources and maintaining security?
- What are IAM users, and how can you create, manage, and authenticate them?
- What are IAM groups, and how can you use them to simplify permission management?
- What is the purpose of IAM roles, and how can you grant permissions to entities outside of your AWS account using roles?
- What are IAM policies, and how do they define permissions and access rules?
- What is the difference between IAM policies and resource-based policies?
- How can you control access to AWS resources using IAM policies and permissions?
- How can you enable multi-factor authentication (MFA) for IAM users to enhance account security?
- What are the best practices for IAM security, including password policies, access keys, and least privilege principles?

## LoadBalancing

- What is load balancing, and what is its primary purpose?
- How does load balancing distribute incoming traffic across multiple servers or resources to optimize performance and ensure high availability?
- What are the different types of load balancers, such as hardware load balancers, software load balancers, or cloud load balancers?
- What are load balancing algorithms, and how do they determine how traffic is distributed?
- How can load balancers perform health checks on backend servers to ensure they are available and responsive?
- What are listeners in load balancing, and how do they define the protocols and ports for incoming traffic?
- What are target groups, and how do they group backend resources or servers for load balancing?
- How can load balancers handle SSL/TLS encryption and termination for secure connections?
- What is session persistence, and how can load balancers maintain sticky sessions or distribute sessions across multiple servers?
- What are the considerations for scaling and optimizing load balancing for different workloads and architectures?
Feel free to answer any or all of these questions to assess your understanding of load balancing concepts.

## Autoscaling

- What is autoscaling, and what is its primary purpose?
- How does autoscaling automatically adjust the number of resources, such as instances or servers, based on changes in demand or specified conditions?
- What are autoscaling groups, and how can you create and manage them?
- What are launch configurations, and how do they define the instance configuration and launch parameters for autoscaling?
- What are scaling policies, and how do they determine when and how to scale resources?
- How can autoscaling groups perform health checks on instances and automatically replace unhealthy instances?
- What is the cooldown period, and how does it prevent rapid scaling up or down during fluctuating demand?
- How can you define scaling triggers, such as CPU utilization or network traffic, to automatically scale resources?
- What are the considerations for scaling and optimizing autoscaling for different workloads and architectures?
- How can you monitor and track the performance and scaling activities of autoscaling groups?
