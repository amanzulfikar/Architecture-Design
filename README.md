# Solutions Architecture Projects
![SA 1](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/89bb8b36-c012-4d01-bb8b-3ddee2f91a6f)

Launched a Static Website (Project 1)- Created S3 buckets to host a static website. Generated a bucket policy to grant public read access. Implemented edits of websites’ index.html file using Notepad and saw edits mirrored on the website when uploaded. Set lifecycle policies & enabled cross-region replication to a destination bucket. Any uploaded edits to the index.html file were replicated to the destination bucket. 

![SA 2](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/564a5511-4d24-44e4-916e-de8e26923ff4)

Creating a Dynamic Website for the Cafe (Project 2)- Connected to the AWS Cloud9 IDE through an EC2 instance. Confirmed web server accessibility. Installed a web application on an EC2 instance that also uses AWS Systems Manager Parameter store. Troubleshooted website successfully by attaching appropriate IAM role to grant permission. Created an AMI and deployed the second copy of the web application to another AWS Region.

![SA 3](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/caf42e91-bb4c-45fb-8ab4-7b45cca47277)

Migrated a Database to Amazon RDS (Project 3)- Created an RDS database instance. Exported data from Maria database by using mysqldump. Connected a SQL client to an RDS database. Migrated data from MariaDB database that runs on an EC2 instance to an RDS database instance. Configured a web application to use the new RDS database instance for data storage. 

![SA 4](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/9b34ec09-6e86-4496-9ab6-bd7f69832f25)

Created a VPC Networking Environment for the Cafe website (Project 4)- Created a VPC that enabled to securely connect to private resources. Enabled private resources to connect to the internet. Created an additional layer of security in VPC to control traffic to and from private resources. 

![SA 5](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/ef8d9ce1-d70a-48d3-aeae-d438d8dd0497)

Created a VPC Peering Connection (Project 5)- Created a private VPC peering connection between two VPCs. Configured route tables to use the VPC peering connection. VPC peering connection was proven successful when the application showed data from the database. 

![SA 6](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/ad69380e-fdab-4aa9-bd9a-4e53a57f13cd)

Controlled AWS Account Access through IAM (Project 6)- Created IAM users and IAM groups. Associated IAM policies with IAM groups. Used AWS managed IAM policies to modify user access rights and observed the results. Used IAM Policy Simulator to observe the scope of the access. Observed what access rights different users are taking advantage of through the IAM Access Advisor feature. Created custom IAM policies by using the visual editor. 

![SA 7](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/8e70383b-14bf-4cca-b909-4c966011cb99)

Created a Scalable and Highly Available Environment for a Café (Project 7)- Inspected the VPC. Updated a network to work across multiple Availability Zones. Created an Application Load Balancer. Created a launch template and an Auto Scaling group. Tested load balancing and automatic scaling through putty. 

![SA 8](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/20a8913f-55e3-421f-923e-143caaaf5a5e)

Automating Infrastructure Deployment (Project 8)- Deployed a VPC networking layer by using an AWS CloudFormation template. Deployed an application layer by using an AWS CloudFormation template. Used Git to invoke AWS CodePipeline, and to create or update stacks from templates that are stored in AWS CodeCommit. Duplicated network and application resources to another AWS Region by using AWS CloudFormation. 

![SA 9](https://github.com/amanzulfikar/Architecture-Design/assets/171962956/f459362b-a41b-45d5-9a75-41a088f512c1)

Streaming Dynamic Content using Amazon CloudFront (Project 9)- Created multiple bit-rate versions of a given source media file using Amazon Elastic Transcoder. Used Amazon CloudFront to deliver the dynamic multi bit-rate stream created by Amazon Elastic Transcoder. 
