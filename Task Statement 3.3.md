Task Statement 3.3: Identify AWS compute services.

Here are the study notes for AWS compute services relevant to the AWS Certified Cloud Practitioner certification, focusing on the specified skills, in tabular format:

| **Skill**                                       | **Description**                                                                                                                      | **Key Points**                                                                                     | **Examples/Use Cases**                                      |
|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Recognizing the appropriate use of different EC2 instance types** | Understanding the use cases for various EC2 instance types based on their optimization                                                | **Compute Optimized**: High-performance processors for compute-intensive tasks (e.g., C5, C6g)<br>**Memory Optimized**: Large memory sizes for memory-intensive tasks (e.g., R5, X1e)<br>**Storage Optimized**: High disk throughput for storage-intensive tasks (e.g., I3, D2)<br>**General Purpose**: Balanced compute, memory, and storage (e.g., T3, M5) | **Compute Optimized**: High-performance computing, gaming servers<br>**Memory Optimized**: In-memory databases, big data analytics<br>**Storage Optimized**: Data warehousing, log processing<br>**General Purpose**: Web servers, app servers |
| **Recognizing the appropriate use of different container options**  | Identifying suitable container services for different scenarios                                                                       | **Amazon ECS (Elastic Container Service)**: Orchestration service for Docker containers<br>**Amazon EKS (Elastic Kubernetes Service)**: Managed Kubernetes service<br>**AWS Fargate**: Serverless compute engine for containers | **Amazon ECS**: Simple containerized applications<br>**Amazon EKS**: Complex microservices, Kubernetes workloads<br>**AWS Fargate**: Serverless containers, cost optimization |
| **Recognizing the appropriate use of different serverless compute options** | Understanding when to use serverless computing solutions                                                                              | **AWS Lambda**: Run code in response to events without provisioning servers<br>**AWS Fargate**: Run containers without managing servers | **AWS Lambda**: Event-driven applications, back-end services<br>**AWS Fargate**: Containerized applications without server management |
| **Recognizing that auto scaling provides elasticity**                | Understanding that auto scaling helps applications automatically adjust capacity based on demand                                      | - Automatically adjusts the number of EC2 instances<br>- Ensures availability<br>- Optimizes costs by scaling down during low demand | - Websites with variable traffic<br>- Applications with unpredictable load<br>- Cost management |
| **Identifying the purposes of load balancers**                       | Understanding the role of load balancers in distributing traffic and ensuring high availability                                       | **Application Load Balancer (ALB)**: For HTTP/HTTPS traffic, advanced routing<br>**Network Load Balancer (NLB)**: For TCP/UDP traffic, high performance<br>**Classic Load Balancer (CLB)**: Basic load balancing for EC2 instances | **ALB**: Web applications, microservices<br>**NLB**: Real-time gaming, IoT, high-throughput applications<br>**CLB**: Simple EC2 load balancing |

### Summary

- **EC2 Instance Types**:
  - **Compute Optimized**: High-performance compute tasks (e.g., C5, C6g).
  - **Memory Optimized**: Memory-intensive applications (e.g., R5, X1e).
  - **Storage Optimized**: High disk throughput tasks (e.g., I3, D2).
  - **General Purpose**: Balanced use cases (e.g., T3, M5).

- **Container Options**:
  - **Amazon ECS**: For simpler containerized applications.
  - **Amazon EKS**: For Kubernetes workloads and complex microservices.
  - **AWS Fargate**: Serverless containers, no server management required.

- **Serverless Compute Options**:
  - **AWS Lambda**: For event-driven applications and backend services.
  - **AWS Fargate**: For containerized applications without server management.

- **Auto Scaling**:
  - Provides elasticity by automatically adjusting capacity based on demand.
  - Ensures application availability and cost optimization.

- **Load Balancers**:
  - **Application Load Balancer (ALB)**: For HTTP/HTTPS traffic and advanced routing.
  - **Network Load Balancer (NLB)**: For TCP/UDP traffic and high performance.
  - **Classic Load Balancer (CLB)**: Basic load balancing for EC2 instances.
