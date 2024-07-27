These tables cover the services you'll need to understand for the AWS Certified Cloud Practitioner exam, providing a brief overview of each and detailing their primary features and benefits.

### Analytics

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon Athena | Interactive query service for analyzing data in S3 using SQL | Serverless, supports various data formats (CSV, JSON, Parquet), integrates with AWS Glue for metadata management |
| AWS Data Exchange | Service to find, subscribe to, and use third-party data in the cloud | Simplifies data sharing, provides secure data access |
| Amazon EMR | Managed Hadoop framework for processing big data | Supports Apache Hadoop, Spark, HBase, Flink, Hudi, and Presto |
| AWS Glue | ETL (Extract, Transform, Load) service | Serverless, integrates with AWS data services, includes a data catalog |
| Amazon Kinesis | Real-time data streaming service | Components: Kinesis Data Streams, Kinesis Data Firehose, Kinesis Data Analytics, Kinesis Video Streams |
| Amazon MSK | Managed service for Apache Kafka | Fully managed, makes it easy to build and run applications that use Apache Kafka |
| Amazon OpenSearch Service | Managed service for Elasticsearch and OpenSearch | Enables log analytics, real-time application monitoring, and search |
| Amazon QuickSight | Business intelligence service | Create and publish interactive dashboards, supports ML insights |
| Amazon Redshift | Data warehousing service | Scalable, fast, and secure, integrates with S3 and other AWS services |

### Application Integration

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon EventBridge | Serverless event bus service | Connects applications using events, supports custom events and third-party SaaS applications |
| Amazon SNS | Pub/Sub messaging service | Sends messages to multiple subscribers, supports SMS, email, and HTTP/HTTPS endpoints |
| Amazon SQS | Fully managed message queuing service | Decouples and scales microservices, distributed systems, and serverless applications |
| AWS Step Functions | Serverless orchestration service | Coordinates multiple AWS services into serverless workflows, visual interface for building workflows |

### Business Applications

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon Connect | Cloud-based contact center service | Provides a contact center solution with automatic call distribution, real-time and historical analytics, and AI-powered services |
| Amazon SES | Email sending service | Sends transactional emails, marketing messages, and notifications, integrates with other AWS services |

### Cloud Financial Management

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Billing Conductor | Customizes billing data | Tailors AWS billing information to meet specific financial reporting needs |
| AWS Budgets | Set custom cost and usage budgets | Provides alerts when usage exceeds thresholds, integrates with AWS Cost Explorer |
| AWS Cost and Usage Report | Comprehensive AWS cost and usage data | Provides detailed cost and usage data, integrates with Amazon S3 |
| AWS Cost Explorer | Visualize, understand, and manage AWS costs and usage | Offers cost and usage reports, helps in cost optimization |
| AWS Marketplace | Online store to find, buy, and deploy software | Offers thousands of software listings from independent software vendors |

### Compute

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Batch | Fully managed batch processing service | Dynamically provisions resources, supports batch computing workloads |
| Amazon EC2 | Scalable virtual servers in the cloud | Offers a variety of instance types, supports auto scaling and load balancing |
| AWS Elastic Beanstalk | Platform as a Service (PaaS) for web applications | Automatically handles deployment, capacity provisioning, load balancing, and scaling |
| Amazon Lightsail | Simple cloud service for small-scale applications | Provides instances, managed databases, and networking resources at a low, predictable price |
| AWS Local Zones | Extends AWS services to more locations | Provides low-latency access to AWS services closer to end-users |
| AWS Outposts | Brings AWS infrastructure to on-premises locations | Fully managed service, provides a consistent hybrid experience |
| AWS Wavelength | Brings AWS services to the edge of the 5G network | Reduces latency to deliver low-latency applications |

### Containers

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon ECR | Container registry for Docker images | Fully managed, secure, integrates with Amazon ECS and EKS |
| Amazon ECS | Container orchestration service | Manages containerized applications, integrates with AWS Fargate for serverless containers |
| Amazon EKS | Managed Kubernetes service | Deploys, manages, and scales Kubernetes applications |

### Customer Engagement

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Activate for Startups | Startup support program | Provides startups with AWS credits, training, and support |
| AWS IQ | Connects customers with AWS Certified experts | Helps customers get professional services and guidance |
| AWS Managed Services (AMS) | Operates AWS infrastructure on behalf of customers | Provides ongoing management, monitoring, and security |
| AWS Support | Technical support service | Offers different support plans (Basic, Developer, Business, Enterprise) with varying levels of support and response times |

### Database

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon Aurora | MySQL and PostgreSQL-compatible relational database | Fully managed, high performance, and availability |
| Amazon DynamoDB | NoSQL database service | Provides single-digit millisecond latency, fully managed |
| Amazon MemoryDB for Redis | Redis-compatible, in-memory database service | Fully managed, suitable for caching and real-time data processing |
| Amazon Neptune | Managed graph database service | Supports highly connected datasets, fast querying of graph data |
| Amazon RDS | Managed relational database service | Supports multiple database engines, automates administrative tasks |

### Developer Tools

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS AppConfig | Application configuration management service | Deploys configuration changes to applications safely and quickly |
| AWS CLI | Command-line interface for AWS services | Provides a unified tool to manage AWS services |
| AWS Cloud9 | Cloud-based integrated development environment (IDE) | Supports collaborative development, direct terminal access to AWS services |
| AWS CloudShell | Browser-based shell for managing AWS resources | Provides a command-line environment with pre-installed tools |
| AWS CodeArtifact | Artifact repository service | Stores and retrieves software packages |
| AWS CodeBuild | Fully managed build service | Compiles source code, runs tests, produces software packages |
| AWS CodeCommit | Managed source control service | Hosts secure Git repositories |
| AWS CodeDeploy | Automates code deployments | Deploys code to Amazon EC2 instances, AWS Lambda, and on-premises servers |
| AWS CodePipeline | Continuous integration and continuous delivery (CI/CD) service | Automates the build, test, and deploy phases of application development |
| AWS CodeStar | Unified user interface for managing software development activities | Provides templates for various development workflows |
| AWS X-Ray | Analyzes and visualizes application performance | Provides end-to-end tracing for applications |

### End User Computing

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon AppStream 2.0 | Application streaming service | Delivers desktop applications to any computer |
| Amazon WorkSpaces | Managed, secure Desktop-as-a-Service (DaaS) solution | Provides virtual desktops to end users |
| Amazon WorkSpaces Web | Fully managed service for web-based workloads | Delivers web applications to end users securely |

### Frontend Web and Mobile

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Amplify | Development platform for building mobile and web applications | Provides tools and services for frontend and backend development |
| AWS AppSync | Serverless GraphQL service | Simplifies data access, manipulation, and synchronization across multiple data sources |
| AWS Device Farm | App testing service | Tests and interacts with applications on real devices in the AWS Cloud |

### Internet of Things (IoT)

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS IoT Core | Managed cloud service for IoT | Securely connects IoT devices to the cloud |
| AWS IoT Greengrass | Extends AWS to edge devices | Runs local compute, messaging, data caching, and sync capabilities for connected devices |

### Machine Learning

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon Comprehend | Natural language processing (NLP) service | Analyzes text for insights and relationships |
| Amazon Kendra | Intelligent search service | Provides accurate and relevant information through machine learning |
| Amazon Lex | Service for building conversational interfaces | Powers chatbots and virtual assistants using voice and text |
| Amazon Polly | Text-to-speech service | Converts text into natural-sounding speech |
| Amazon Rekognition | Image and video analysis service | Detects objects, scenes, and activities; provides facial analysis and recognition |
| Amazon SageMaker | Fully managed service for building, training, and deploying ML models | Supports the entire machine learning workflow |
| Amazon Textract | Extracts text and data from scanned documents | Uses machine learning to read and process documents |
| Amazon Transcribe | Automatic speech recognition (ASR) service | Converts speech to text |
| Amazon Translate | Neural machine translation service | Provides language translation for multiple languages |

### Management and Governance

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Auto Scaling | Automatically adjusts resources to maintain performance and cost | Monitors applications and adjusts capacity to maintain steady, predictable performance |
| AWS Cloud

Formation | Infrastructure as code service | Creates and manages AWS resources using templates |
| AWS CloudTrail | Logs and monitors account activity | Provides governance, compliance, and operational and risk auditing |
| Amazon CloudWatch | Monitoring and management service | Collects and visualizes real-time logs, metrics, and event data |
| AWS Compute Optimizer | Recommends optimal AWS resources | Analyzes resource usage and recommends cost-effective and performant resources |
| AWS Config | Assesses, audits, and evaluates configurations | Monitors and records AWS resource configurations and changes |
| AWS Control Tower | Automates setup of a secure, multi-account AWS environment | Simplifies governance and compliance |
| AWS Health Dashboard | Provides alerts and remediation guidance | Offers personalized view of AWS service health |
| AWS Launch Wizard | Guides deployment of enterprise applications | Simplifies the deployment of applications like SAP HANA |
| AWS License Manager | Manages software licenses | Tracks and manages licenses for compliance |
| AWS Management Console | Web-based interface for accessing and managing AWS resources | Provides a graphical interface for AWS services |
| AWS Organizations | Central management of multiple AWS accounts | Consolidates billing, control policies, and manage access across AWS accounts |
| AWS Resource Groups and Tag Editor | Organizes and manages AWS resources | Groups resources using tags for easier management |
| AWS Service Catalog | Catalog of approved products for use on AWS | Organizes, governs, and provisions AWS resources |
| AWS Systems Manager | Operational management service | Centralizes operational data and automates tasks |
| AWS Trusted Advisor | Provides real-time guidance for AWS resources | Offers best practices recommendations for cost optimization, security, fault tolerance, and performance |
| AWS Well-Architected Tool | Reviews and improves cloud architectures | Provides recommendations based on AWS best practices |

### Migration and Transfer

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Application Discovery Service | Discovers on-premises applications | Collects and presents configuration, usage, and behavior data |
| AWS Application Migration Service | Simplifies migrating applications to AWS | Automates lift-and-shift migrations |
| AWS Database Migration Service (AWS DMS) | Migrates databases to AWS | Supports homogeneous and heterogeneous migrations |
| AWS Migration Hub | Central location to track migration progress | Provides visibility into application migration projects |
| AWS Schema Conversion Tool (AWS SCT) | Converts database schemas for migration | Supports heterogeneous database migrations |
| AWS Snow Family | Data transfer devices for offline data transfer | Includes Snowcone, Snowball, and Snowmobile for varying data sizes |
| AWS Transfer Family | Managed file transfer service | Supports SFTP, FTPS, and FTP for secure file transfers |

### Networking and Content Delivery

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| Amazon API Gateway | Managed API service | Creates, publishes, and secures APIs |
| Amazon CloudFront | Content delivery network (CDN) service | Delivers content with low latency and high transfer speeds |
| AWS Direct Connect | Dedicated network connection to AWS | Provides a dedicated, private connection from a data center to AWS |
| AWS Global Accelerator | Improves global application availability and performance | Routes traffic to optimal endpoints using the AWS global network |
| Amazon Route 53 | Scalable DNS and domain name registration | Provides DNS services and health checking |
| Amazon VPC | Isolated cloud resources | Enables control over virtual networking environment |
| AWS VPN | Securely connects on-premises networks to AWS | Supports site-to-site and client VPN connections |

### Security, Identity, and Compliance

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Artifact | Self-service portal for on-demand access to AWS compliance reports | Provides compliance reports and select online agreements |
| AWS Audit Manager | Simplifies audit preparation | Automates evidence collection and assessment |
| AWS Certificate Manager (ACM) | Manages SSL/TLS certificates | Simplifies certificate provisioning and management |
| AWS CloudHSM | Hardware security module service | Manages cryptographic keys in FIPS 140-2 Level 3 validated hardware |
| Amazon Cognito | User identity and access management | Provides user sign-up, sign-in, and access control |
| Amazon Detective | Analyzes and visualizes security data | Helps to identify and investigate potential security issues |
| AWS Directory Service | Managed Microsoft Active Directory in the AWS Cloud | Provides directory services for AWS resources |
| AWS Firewall Manager | Centralized management of firewall rules | Simplifies management of AWS WAF and AWS Shield |
| Amazon GuardDuty | Threat detection service | Monitors for malicious activity and unauthorized behavior |
| AWS Identity and Access Management (IAM) | Manages access to AWS services and resources | Controls user and service permissions |
| AWS IAM Identity Center (AWS Single Sign-On) | Centralized access management service | Manages SSO access to AWS accounts and applications |
| Amazon Inspector | Automated security assessment service | Analyzes applications for vulnerabilities and deviations from best practices |
| AWS Key Management Service (AWS KMS) | Managed service for encryption keys | Provides key creation, management, and usage tracking |
| Amazon Macie | Data security and privacy service | Uses machine learning to discover and protect sensitive data in AWS |
| AWS Network Firewall | Managed network firewall service | Provides network protections for Amazon VPCs |
| AWS Resource Access Manager (AWS RAM) | Shares AWS resources across AWS accounts | Simplifies resource sharing using AWS Organizations |
| AWS Secrets Manager | Manages and retrieves secrets | Provides secure storage and automatic rotation of secrets |
| AWS Security Hub | Unified security and compliance center | Aggregates and prioritizes security findings from multiple AWS services |
| AWS Shield | Managed DDoS protection service | Provides protection against DDoS attacks |
| AWS WAF | Web application firewall | Protects web applications from common web exploits |

### Serverless

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Fargate | Serverless compute engine for containers | Eliminates the need to manage servers, integrates with Amazon ECS and EKS |
| AWS Lambda | Serverless compute service | Runs code in response to events and automatically manages compute resources |

### Storage

| **Service** | **Description** | **Details** |
|-------------|-----------------|-------------|
| AWS Backup | Centralized backup service | Automates and manages backups across AWS services |
| Amazon EBS | Block storage for use with EC2 | Provides persistent block storage volumes |
| Amazon EFS | Scalable file storage for EC2 instances | Provides simple, scalable file storage with NFS |
| AWS Elastic Disaster Recovery | Service for disaster recovery | Ensures data recovery and business continuity |
| Amazon FSx | Fully managed file storage | Supports Windows File Server and Lustre |
| Amazon S3 | Object storage service | Provides scalable storage for any type of data |
| Amazon S3 Glacier | Low-cost archive storage | Provides secure and durable storage for data archiving and backup |
| AWS Storage Gateway | Hybrid cloud storage service | Connects on-premises software appliances with cloud-based storage for seamless integration |
