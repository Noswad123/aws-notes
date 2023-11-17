# Amazon Instance Store
- [instance store](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)
- provides temporary block-level storage for an Amazon EC2 instance.
- An instance store is disk storage that is physically attached to the host computer for an EC2 instance, and therefore has the same lifespan as the instance.
- When the instance is terminated, you lose any data in the instance store.

# AWS Elastic Disaster Recovery
- saves costs by removing idle recovery site resources
- recovery application within minutes
- unified process to test, recover, and failback a wide range of applications
- Automate configuring your environment
- based on launching infrastructure in a separate region
- Objectives
	- Recovery Point Objective
	- Recovery Time Objective
# Amazon Elastic Block Store
- [Amazon Elastic Block Store (Amazon EBS)](https://aws.amazon.com/ebs) 
- Block-level storage volumes that behave like physical hard drives
- service that provides block-level storage volumes you can use with Amazon EC2 instances.
- If you stop an EC2 instance, all the data on the attached EBS volume remains available.
- breaks files into small components
	- great for updates to big files
	- complex for reads and writes
- volumes attach to EC2 instance
- availability zone level resource
- doesn't automatically scale
- Types
	- SSD-backed volumes
		- optimized for transactional workloads
		- performance attribute is IOPS?
	- HDD-backed volumes
		- optimized for large streams
 - [EBS snapshot](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html)
	 - incremental backup.
		 - the first backup taken of a volume copies all the data.
		 - For subsequent backups, only the blocks of data that have changed since the most recent snapshot are saved.

# [[Amazon Simple Storage Service]] (S3)

# Amazon Elastic File System (EFS)
- regional resource
- multiple instances reading and writing simultaneously
- linux file system
- automatically scales

# Amazon Fsx
- performant files system
- [Amazon FsX docs](https://aws.amazon.com/fsx/)

# [[Amazon Database]]

# Amazon Managed Blockchain

[**Amazon Managed Blockchain**](https://aws.amazon.com/managed-blockchain) is a service that you can use to create and manage blockchain networks with open-source frameworks. 
# Amazon Quantum ledger database
[**Amazon Quantum Ledger Database (Amazon QLDB)**](https://aws.amazon.com/qldb) is a ledger database service. 

# Amazon Elasticache
[**Amazon ElastiCache**](https://aws.amazon.com/elasticache) is a service that adds caching layers on top of your databases to help improve the read times of common requests. 
# Amazon DynamoDB accelerator
[**Amazon DynamoDB Accelerator (DAX)**](https://aws.amazon.com/dynamodb/dax/) is an in-memory cache for DynamoDB. 
