# aws-terminologies

1. **AWS RDS** : This is a relational database service offered by aws which operates on databases that use SQL ( for eg: MySQL, PostgreSQL, MariaDB, Aurora). This services focuses on automatically backing up, dupicating, and auto scaling of the data.
2. **Aurora** : This is a fully functional database that is compatible with MySQL and PostgreSQL, and can be run on RDS. This is a fully managed DB that automates read replica and write replicas creation, it supports auto scaling and offers an automatic failover mechanism.
3. **AWS Codebuild** : This is a Continuous Integration platform that compiles the code, runs tests and produces production ready software packages. (like Jenkins)
4. **AWS CodePipeline** : This is a Continuous Deployment service that automates the build, tests and deployment of code. Code can be pipelined to either test or production environment.
5. **Block Storage** : This is used to store data in fixed size blocks that don't follow any hierarchial or directory like structure. These are usually used in SANs (Storage Area Networks) and allow multiple servers to access the blocks at the same time (shared access) as if the blocks are a part of a that server's own hard disk. Each block has a unique address that allows the server to access and (or) modify it.
6. **Object Storage** : This type of storage divides a file into multiple objects (having variable sizes) with each having a unique identifier. Each objects consist of data, along with metadata. They are stored in flat namespaces and are highly scalable.

# Storage Services:
 1. S3 : Scalable, Object Storage 
 2. EBS : For having block storage associated with EC2 instances. offers low latency and cost effectiveness.
 3. EFS: Offers file storage for EC2.
 4. S3 Glacier : Low cost cloud data archival service (like a data vault) that offfers fast retrieval, highly secure and durable.

# Load Balancers and Target groups: 
 **Load balancers are given the task of efficienctly dividing the network traffic or resources across multiple servers that are part of that network. This ensures that all the servers remain active (unless there’s some hardware issue).**
 
 
