Task Statement 3.6: Identify AWS storage services

Here are the study notes for AWS storage services relevant to the AWS Certified Cloud Practitioner certification in tabular format:

| **Service**                     | **Description**                                                                                                          | **Key Features**                                                                                         | **Examples/Use Cases**                                      |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Amazon S3 (Simple Storage Service)** | Scalable object storage for a wide range of data types and use cases                                                  | - Virtually unlimited storage<br>- Data durability of 99.999999999%<br>- Access control options<br>- Lifecycle policies | - Backup and restore<br>- Data lakes<br>- Static website hosting |
| **Amazon EBS (Elastic Block Store)** | Block storage for use with Amazon EC2                                                                                  | - Persistent storage<br>- Low-latency performance<br>- Snapshots for data backup                          | - Database storage<br>- File systems<br>- Enterprise applications |
| **Amazon EFS (Elastic File System)** | Scalable file storage for use with Amazon EC2                                                                           | - Fully managed<br>- Scalable<br>- NFS protocol support<br>- Pay-for-use                                   | - Content management<br>- File storage<br>- Big data and analytics |
| **Amazon Glacier**              | Secure, durable, and low-cost storage service for data archiving and long-term backup                                     | - Low-cost archival storage<br>- Retrieval options: expedited, standard, bulk<br>- High durability        | - Archival storage<br>- Compliance archives<br>- Long-term backup |
| **AWS Storage Gateway**         | Hybrid storage service that enables on-premises applications to seamlessly use AWS cloud storage                          | - File, volume, and tape gateways<br>- Cached and stored volumes<br>- Backup integration                   | - Hybrid cloud storage<br>- Backup and restore<br>- Disaster recovery |
| **Amazon S3 Glacier Deep Archive** | Lowest-cost storage class for long-term data retention and digital preservation                                         | - Lowest-cost storage<br>- Retrieval within 12 hours                                                      | - Long-term backups<br>- Digital preservation<br>- Compliance archives |
| **AWS Snowball**                | Data transfer service to move large amounts of data into and out of AWS                                                   | - Physical device for data transfer<br>- Secure and fast transfer<br>- Edge computing capabilities         | - Data migration<br>- Disaster recovery<br>- Edge computing |
| **AWS Snowmobile**              | Exabyte-scale data transfer service                                                                                       | - Transfer up to 100PB per Snowmobile<br>- Secure and fast transfer                                        | - Large-scale data migration<br>- Data center shutdown<br>- Disaster recovery |
| **Amazon FSx**                  | Fully managed file systems optimized for a variety of use cases                                                           | - **Amazon FSx for Windows File Server**: Fully managed Windows file system<br>- **Amazon FSx for Lustre**: High-performance file system | - Windows-based applications<br>- High-performance computing<br>- Machine learning |
| **AWS Backup**                  | Centralized backup service to automate and manage backups across AWS services                                             | - Centralized backup management<br>- Automated backup scheduling<br>- Compliance and auditing capabilities | - Backup automation<br>- Compliance and auditing<br>- Disaster recovery |
| **Amazon S3 Transfer Acceleration** | Accelerates uploads to S3 using AWS edge locations                                                                      | - Faster uploads using CloudFront's globally distributed edge locations                                    | - Large file uploads<br>- Global data transfer<br>- Media uploads |

### Summary

- **Amazon S3**:
  - Object storage with virtually unlimited capacity and high durability.
  - Ideal for backup, data lakes, and static website hosting.

- **Amazon EBS**:
  - Block storage for EC2 instances with persistent storage and low-latency performance.
  - Suitable for database storage, file systems, and enterprise applications.

- **Amazon EFS**:
  - Scalable file storage for EC2 instances supporting the NFS protocol.
  - Used for content management, file storage, and big data analytics.

- **Amazon Glacier**:
  - Low-cost archival storage with multiple retrieval options.
  - Suitable for archival storage, compliance archives, and long-term backup.

- **AWS Storage Gateway**:
  - Hybrid storage service enabling on-premises applications to use AWS cloud storage.
  - Used for hybrid cloud storage, backup and restore, and disaster recovery.

- **Amazon S3 Glacier Deep Archive**:
  - Lowest-cost storage class for long-term data retention.
  - Ideal for long-term backups, digital preservation, and compliance archives.

- **AWS Snowball**:
  - Data transfer service for moving large amounts of data to and from AWS.
  - Used for data migration, disaster recovery, and edge computing.

- **AWS Snowmobile**:
  - Exabyte-scale data transfer service for extremely large data migrations.
  - Suitable for large-scale data migration, data center shutdowns, and disaster recovery.

- **Amazon FSx**:
  - Managed file systems optimized for specific use cases.
  - Includes FSx for Windows File Server and FSx for Lustre, suitable for Windows-based applications and high-performance computing.

- **AWS Backup**:
  - Centralized service for automating and managing backups across AWS services.
  - Ideal for backup automation, compliance, and disaster recovery.

- **Amazon S3 Transfer Acceleration**:
  - Accelerates uploads to S3 using AWS edge locations for faster data transfer.
  - Used for large file uploads, global data transfer, and media uploads.
 
Here are the study notes for the specified skills for the AWS Certified Cloud Practitioner certification in tabular format:

| **Skill**                                      | **Description**                                                                                             | **Key Points**                                                                                     | **Examples/Use Cases**                                      |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Identifying the uses for object storage**    | Understanding the applications of object storage services in AWS                                            | - Store unstructured data<br>- Scalable and durable<br>- Accessible via HTTP/S                      | - Backup and restore<br>- Data lakes<br>- Static website hosting |
| **Recognizing the differences in Amazon S3 storage classes** | Knowing the different storage classes within Amazon S3 and their uses                                        | - **S3 Standard**: Frequently accessed data<br>- **S3 Standard-IA**: Infrequently accessed data<br>- **S3 One Zone-IA**: Infrequently accessed data, single AZ<br>- **S3 Intelligent-Tiering**: Automatically moves data to the most cost-effective access tier<br>- **S3 Glacier**: Archival storage<br>- **S3 Glacier Deep Archive**: Long-term archival storage | - **S3 Standard**: Active data, content distribution<br>- **S3 Standard-IA**: Backup, disaster recovery<br>- **S3 Glacier**: Long-term backups, archives |
| **Identifying block storage solutions**        | Recognizing block storage solutions available in AWS                                                        | - **Amazon EBS**: Persistent block storage for EC2 instances<br>- **Instance Store**: Temporary block storage | - **Amazon EBS**: Database storage, file systems<br>- **Instance Store**: Cache, temporary data |
| **Identifying file services**                  | Knowing the different file storage services in AWS                                                          | - **Amazon EFS**: Scalable file storage for EC2 instances<br>- **Amazon FSx**: Managed file systems for Windows and Lustre | - **Amazon EFS**: Content management, big data<br>- **Amazon FSx for Windows File Server**: Windows-based applications<br>- **Amazon FSx for Lustre**: High-performance computing |
| **Identifying cached file systems**            | Understanding hybrid storage solutions that cache on-premises data                                           | - **AWS Storage Gateway**: File, volume, and tape gateways<br>- Cached volumes provide low-latency access to frequently accessed data | - Hybrid cloud storage<br>- Backup and restore<br>- Disaster recovery |
| **Understanding use cases for lifecycle policies** | Knowing when to use lifecycle policies to manage the lifecycle of objects in S3                              | - Transition objects to different storage classes<br>- Automate deletion of objects<br>- Reduce storage costs | - Transition data to Glacier for long-term storage<br>- Automatically delete old log files |
| **Understanding use cases for AWS Backup**     | Recognizing the benefits of using AWS Backup to manage and automate backups                                  | - Centralized backup management<br>- Automated backup scheduling<br>- Compliance and auditing capabilities | - Backup automation<br>- Compliance and auditing<br>- Disaster recovery |

### Summary

- **Uses for object storage**:
  - **Amazon S3**: Used for storing unstructured data, providing scalable and durable storage that is accessible via HTTP/S.
  - Common use cases include backup and restore, data lakes, and static website hosting.

- **Amazon S3 storage classes**:
  - **S3 Standard**: For frequently accessed data.
  - **S3 Standard-IA**: For infrequently accessed data but requires rapid access when needed.
  - **S3 One Zone-IA**: For infrequently accessed data stored in a single Availability Zone.
  - **S3 Intelligent-Tiering**: Automatically moves data to the most cost-effective access tier.
  - **S3 Glacier**: For archival storage with various retrieval options.
  - **S3 Glacier Deep Archive**: For long-term archival storage.

- **Block storage solutions**:
  - **Amazon EBS**: Provides persistent block storage for EC2 instances, suitable for databases and file systems.
  - **Instance Store**: Provides temporary block storage that is ideal for cache and temporary data.

- **File services**:
  - **Amazon EFS**: Provides scalable file storage for EC2 instances, suitable for content management and big data.
  - **Amazon FSx**:
    - **Amazon FSx for Windows File Server**: Fully managed file storage for Windows applications.
    - **Amazon FSx for Lustre**: High-performance file system for compute-intensive workloads.

- **Cached file systems**:
  - **AWS Storage Gateway**: Provides hybrid storage solutions with file, volume, and tape gateways. Cached volumes offer low-latency access to frequently accessed data.

- **Lifecycle policies**:
  - Used to manage the lifecycle of objects in S3 by transitioning objects to different storage classes or automating deletion to reduce storage costs.

- **AWS Backup**:
  - Provides centralized backup management, automated backup scheduling, and compliance and auditing capabilities.
  - Useful for backup automation, compliance, and disaster recovery.
