Task Statement 3.4: Identify AWS database services

Here are the study notes for AWS database services and database migration relevant to the AWS Certified Cloud Practitioner certification in tabular format:

| **Topic**                      | **Description**                                                                                                                         | **Key Points**                                                                                     | **Examples/Use Cases**                                     |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| **Amazon RDS (Relational Database Service)** | Managed relational database service that supports multiple database engines (e.g., MySQL, PostgreSQL, Oracle, SQL Server)          | - Automated backups<br>- Multi-AZ deployments<br>- Read replicas<br>- Automated patching and updates | - Web and mobile applications<br>- E-commerce platforms<br>- Enterprise applications |
| **Amazon Aurora**             | MySQL and PostgreSQL-compatible relational database engine built for the cloud                                                          | - High performance and availability<br>- Up to 5x throughput of MySQL<br>- Up to 3x throughput of PostgreSQL<br>- Serverless option (Aurora Serverless) | - High-traffic applications<br>- SaaS applications<br>- Enterprise-grade applications |
| **Amazon DynamoDB**           | Fully managed NoSQL database service                                                                                                   | - Key-value and document database<br>- Single-digit millisecond latency<br>- Built-in security, backup, and restore | - Real-time bidding<br>- Gaming<br>- IoT applications |
| **Amazon Redshift**           | Fully managed data warehouse service                                                                                                   | - Columnar storage<br>- Massively parallel processing (MPP)<br>- Integration with BI tools | - Data warehousing<br>- Big data analytics<br>- Reporting and dashboarding |
| **Amazon ElastiCache**        | Managed in-memory caching service for Redis and Memcached                                                                              | - Sub-millisecond latency<br>- Supports Redis and Memcached<br>- Scalable and secure | - Caching web application data<br>- Session management<br>- Real-time analytics |
| **Amazon Neptune**            | Fully managed graph database service                                                                                                   | - Supports both Property Graph and RDF graph models<br>- Optimized for storing and querying highly connected data | - Social networking<br>- Recommendation engines<br>- Fraud detection |
| **Amazon DocumentDB**         | Managed document database service that is compatible with MongoDB                                                                      | - Scalable and fully managed<br>- High availability with multiple replicas<br>- Full MongoDB compatibility | - Content management<br>- Mobile applications<br>- Catalogs |
| **AWS Database Migration Service (DMS)** | Service for migrating databases to AWS                                                                                             | - Supports homogeneous and heterogeneous migrations<br>- Minimal downtime during migration<br>- Continuous data replication | - Migrating on-premises databases to AWS<br>- Database consolidation<br>- Data synchronization |
| **Amazon Timestream**         | Fully managed time series database service                                                                                             | - Built for IoT and operational applications<br>- Ingests, stores, and analyzes time series data<br>- Scales automatically | - IoT applications<br>- DevOps monitoring<br>- Industrial telemetry |
| **Amazon QLDB (Quantum Ledger Database)** | Fully managed ledger database                                                                                                      | - Immutable and cryptographically verifiable transaction log<br>- High availability and durability<br>- Serverless | - Systems of record<br>- Supply chain management<br>- Financial transactions |

### Summary

- **Amazon RDS**:
  - Supports multiple relational database engines (e.g., MySQL, PostgreSQL).
  - Features automated backups, Multi-AZ deployments, and read replicas.

- **Amazon Aurora**:
  - MySQL and PostgreSQL-compatible, high performance.
  - Aurora Serverless for on-demand automatic scaling.

- **Amazon DynamoDB**:
  - Managed NoSQL database, key-value and document store.
  - Single-digit millisecond latency, scalable and secure.

- **Amazon Redshift**:
  - Managed data warehouse, supports columnar storage and MPP.
  - Integrates with BI tools for data analytics and reporting.

- **Amazon ElastiCache**:
  - Managed in-memory caching service, supports Redis and Memcached.
  - Provides sub-millisecond latency for caching and real-time analytics.

- **Amazon Neptune**:
  - Managed graph database, supports Property Graph and RDF models.
  - Optimized for storing and querying highly connected data.

- **Amazon DocumentDB**:
  - Managed document database, compatible with MongoDB.
  - Scalable, high availability, and fully managed.

- **AWS Database Migration Service (DMS)**:
  - Migrates databases to AWS with minimal downtime.
  - Supports continuous data replication and both homogeneous and heterogeneous migrations.

- **Amazon Timestream**:
  - Managed time series database for IoT and operational applications.
  - Ingests, stores, and analyzes time series data, automatically scales.

- **Amazon QLDB**:
  - Managed ledger database with an immutable and verifiable transaction log.
  - Ideal for systems of record, supply chain, and financial transactions.
 
    Here are the study notes for the specified skills for the AWS Certified Cloud Practitioner certification in tabular format:

| **Skill**                                     | **Description**                                                                                              | **Key Points**                                                                                      | **Examples/Use Cases**                                      |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Deciding when to use EC2 hosted databases or AWS managed databases** | Understanding when to choose between self-managed EC2-hosted databases and AWS managed database services        | **EC2 Hosted Databases**: Full control over configuration and management<br>**AWS Managed Databases**: Automated backups, patching, scaling, and high availability | **EC2 Hosted**: Custom database setups, unsupported database engines<br>**AWS Managed**: Reduced operational overhead, enhanced security, built-in high availability |
| **Identifying relational databases**          | Recognizing AWS services that offer relational database management                                             | **Amazon RDS**: Supports MySQL, PostgreSQL, Oracle, SQL Server, MariaDB<br>**Amazon Aurora**: MySQL and PostgreSQL compatible, high performance | - Web and mobile applications<br>- E-commerce platforms<br>- Enterprise applications |
| **Identifying NoSQL databases**               | Recognizing AWS services that provide NoSQL database solutions                                                 | **Amazon DynamoDB**: Key-value and document database, single-digit millisecond latency<br>**Amazon DocumentDB**: Managed MongoDB-compatible database | - Real-time bidding<br>- Gaming<br>- IoT applications<br>- Content management<br>- Mobile applications |
| **Identifying memory-based databases**        | Recognizing AWS services that offer in-memory caching and database solutions                                   | **Amazon ElastiCache**: Managed Redis and Memcached<br>**Amazon MemoryDB for Redis**: Fully managed Redis-compatible in-memory database | - Caching web application data<br>- Session management<br>- Real-time analytics |
| **Identifying database migration tools**      | Understanding AWS tools available for migrating databases                                                      | **AWS Database Migration Service (DMS)**: Migrates databases with minimal downtime<br>**AWS Schema Conversion Tool (SCT)**: Converts database schema to AWS-compatible formats | - Migrating on-premises databases to AWS<br>- Database consolidation<br>- Schema conversion and transformation |

### Summary

- **Deciding between EC2 hosted and AWS managed databases**:
  - **EC2 Hosted Databases**: Use when full control over the database environment is needed or for unsupported engines.
  - **AWS Managed Databases**: Use for reduced operational overhead, automated maintenance, and built-in high availability.

- **Identifying relational databases**:
  - **Amazon RDS**: Managed relational database service supporting multiple engines (MySQL, PostgreSQL, Oracle, SQL Server, MariaDB).
  - **Amazon Aurora**: MySQL and PostgreSQL compatible, designed for high performance and availability.

- **Identifying NoSQL databases**:
  - **Amazon DynamoDB**: Key-value and document database with low latency.
  - **Amazon DocumentDB**: Managed document database service, compatible with MongoDB.

- **Identifying memory-based databases**:
  - **Amazon ElastiCache**: In-memory caching service supporting Redis and Memcached.
  - **Amazon MemoryDB for Redis**: Fully managed, Redis-compatible in-memory database service.

- **Identifying database migration tools**:
  - **AWS Database Migration Service (DMS)**: Facilitates database migration with minimal downtime and supports continuous data replication.
  - **AWS Schema Conversion Tool (SCT)**: Converts database schemas to AWS-compatible formats, facilitating migrations.
