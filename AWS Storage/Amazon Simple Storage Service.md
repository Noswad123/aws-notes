- Store data as objects
	- store objects in buckets
	- Can store files this way
- upload a maximum object size of 5TB
- Version objects
- Write once read many (WORM)
- web enabled
- regionally distributed
- serverless
- [**Amazon Simple Storage Service (Amazon S3)**](https://aws.amazon.com/s3/) 

# Storage classes
 [a range of storage classes](https://aws.amazon.com/s3/storage-classes)

Amazon S3 standard
- designed for frequently accessed data
- stores data in a minimum of 3 availability Zones
- high availability for objects

Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA)
- stores data in a single availability zone
- lower storage price than Amazon S3 Standard-IA
- stored in a single availability Zone
- you may want to save costs for storage
- easily reproduce data in the event of an availability zone failure

Amazon S3 Intelligent-Tiering
- Ideal for data with unknown or changing access patterns
- Requires a small monthly monitoring and automation fee per object

Amazon Glacier Flexible retrieval
- Low-cost storage designed for data archiving
- Able to retrieve objects within a few minutes to hours

Amazon Glacier instant Retrieval
- Works well for archived data that requires immediate access
- Can retrieve objects within a few milliseconds

Amazon S3 Glacier Deep Archive
- Lowest-cost object storage class ideal for archiving
- Able to retrieve objects within 12 hours
- supports long-term retention and digital preservation for data that might be accessed once or twice in a year.

Amazon S3 Outposts
- Creates S3 buckets on Amazon S3 Outposts
- Makes it easier to retrieve, store, and access data on AWS Outposts

# Encryption
- S3 uses server-side encryption
- client-side encryption