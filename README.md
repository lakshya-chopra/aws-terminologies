# benefits
faster time to market
scalability and flexibility
cost savings
better collaboration
advanced security
data loss prevention

# disadvantage
risk of vendor lock-in
less control over underlying cloud insfra
concerns about security risks like data privacy and online threats
integration complexity with exisiting systems
unforseen costs and unexpected expenses

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

# Load Balancers: 
 **Load balancers are given the task of efficienctly dividing the network traffic or resources across multiple servers that are part of that network. This ensures that all the servers remain active (unless there’s some hardware issue).**

 **Security groups** : A security group controls the traffic that is allowed to reach and leave the resources that it is associated with. For example, after you associate a security group with an EC2 instance, it controls the inbound and outbound traffic for the instance. When you create a VPC, it comes with a default security group. (acts as a firewall)

# Network Services
VPC : own isolated environment in a public cloud
Domain Name Service - Route 53

public subnet : can receive traffic from outerworld
private subnet : cannot receive traffic from outerworld but may or may not send traffic to outerworld
![Screenshot from 2023-11-26 17-59-50](https://github.com/KRIISHSHARMA/AWS/assets/86760658/a6881e65-16b5-4e2f-8480-973fee9344f6)

- public subnet : can receive traffic from outerworld 
- private subnet : cannot receive traffic from outerworld but may or may not send traffic to outerworld

![Screenshot from 2023-11-26 18-03-33](https://github.com/KRIISHSHARMA/AWS/assets/86760658/dee853ad-6c86-4238-98ec-ba7ba60b7831)
![Screenshot from 2023-11-26 18-05-39](https://github.com/KRIISHSHARMA/AWS/assets/86760658/0e807497-f6ce-484e-82c0-40f1bcd83c45)


![Screenshot from 2023-11-26 13-40-57](https://github.com/KRIISHSHARMA/AWS/assets/86760658/3dcafdd0-84f9-4ecd-9843-e6ea71061a3f)
![Screenshot from 2023-11-26 13-46-08](https://github.com/KRIISHSHARMA/AWS/assets/86760658/2ba98aae-9871-40a1-89a9-3bbcaa961fdc)
![Screenshot from 2023-11-26 13-47-33](https://github.com/KRIISHSHARMA/AWS/assets/86760658/a7b8c06a-c163-4b80-a052-d433928260ff)
![Screenshot from 2023-11-26 13-57-52](https://github.com/KRIISHSHARMA/AWS/assets/86760658/86722cee-9cc8-47be-9e62-a4f6fb8dc842)
![Screenshot from 2023-11-26 13-59-20](https://github.com/KRIISHSHARMA/AWS/assets/86760658/2edee858-bceb-49da-8c19-d87403bf0582)
