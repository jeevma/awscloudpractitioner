Task Statement 3.5: Identify AWS network services.

Here are the study notes for AWS network services relevant to the AWS Certified Cloud Practitioner certification in tabular format:

| **Service**                  | **Description**                                                                                              | **Key Features**                                                                                     | **Examples/Use Cases**                                      |
|------------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Amazon VPC (Virtual Private Cloud)** | Allows you to provision a logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network you define   | - Customizable IP address ranges<br>- Subnets, route tables, and gateways<br>- Security groups and network ACLs | - Hosting web applications<br>- Running databases<br>- Isolated environments |
| **AWS Direct Connect**       | Provides a dedicated network connection from your premises to AWS                                            | - Private connectivity<br>- High bandwidth<br>- Low latency                                            | - Data-intensive applications<br>- Hybrid environments<br>- Compliance requirements |
| **AWS VPN (Virtual Private Network)** | Enables secure connections from your on-premises network or client device to AWS                       | - IPSec tunnels<br>- Managed VPN service<br>- Easy setup                                              | - Secure remote access<br>- Extending on-premises networks<br>- Disaster recovery |
| **Amazon Route 53**          | Scalable Domain Name System (DNS) web service                                                               | - Domain registration<br>- DNS routing<br>- Health checking and failover                              | - Domain name management<br>- DNS-based routing<br>- Global applications |
| **AWS CloudFront**           | Content Delivery Network (CDN) service                                                                      | - Global edge locations<br>- Caching<br>- DDoS protection                                             | - Serving static and dynamic content<br>- Streaming media<br>- Website acceleration |
| **AWS Global Accelerator**   | Improves the availability and performance of your applications with global users                            | - Global static IP addresses<br>- Intelligent traffic routing<br>- Health checks                      | - Global applications<br>- Multi-region deployments<br>- High-availability applications |
| **AWS Transit Gateway**      | Enables customers to connect their Amazon VPCs and on-premises networks to a single gateway                  | - Centralized connectivity<br>- Simplifies network architecture<br>- Scalable                         | - Large-scale network architectures<br>- Multi-VPC environments<br>- Hybrid cloud architectures |
| **AWS PrivateLink**          | Provides private connectivity between VPCs, AWS services, and on-premises applications, without exposing data to the internet | - Private connectivity<br>- Simplifies network security<br>- Supports cross-account access           | - Accessing AWS services securely<br>- SaaS applications<br>- Cross-account access |
| **Elastic Load Balancing (ELB)** | Automatically distributes incoming application traffic across multiple targets, such as EC2 instances      | - Application Load Balancer (ALB): For HTTP/HTTPS traffic<br>- Network Load Balancer (NLB): For TCP/UDP traffic<br>- Classic Load Balancer (CLB): Basic load balancing for EC2 instances | - High-traffic web applications<br>- Ensuring high availability<br>- Distributing traffic efficiently |
| **AWS App Mesh**             | Service mesh that makes it easy to monitor and control microservices                                         | - Service-to-service communications<br>- Traffic shifting<br>- Observability                          | - Microservices architectures<br>- Enhanced monitoring<br>- Traffic management |

### Summary

- **Amazon VPC**:
  - Allows for the creation of a virtual network with customizable IP address ranges, subnets, route tables, and security groups.

- **AWS Direct Connect**:
  - Provides a dedicated, private connection from on-premises to AWS, suitable for data-intensive applications and hybrid environments.

- **AWS VPN**:
  - Enables secure connections from on-premises networks or client devices to AWS using IPSec tunnels.

- **Amazon Route 53**:
  - Scalable DNS service offering domain registration, DNS routing, and health checks.

- **AWS CloudFront**:
  - Content Delivery Network (CDN) service with global edge locations, caching, and DDoS protection for fast and secure content delivery.

- **AWS Global Accelerator**:
  - Improves availability and performance for global applications using static IP addresses and intelligent traffic routing.

- **AWS Transit Gateway**:
  - Centralizes connectivity between VPCs and on-premises networks, simplifying large-scale network architectures.

- **AWS PrivateLink**:
  - Provides private connectivity between VPCs and AWS services without exposing data to the internet.

- **Elastic Load Balancing (ELB)**:
  - Distributes incoming traffic across multiple targets, ensuring high availability and efficient traffic management with ALB, NLB, and CLB.

- **AWS App Mesh**:
  - A service mesh that facilitates monitoring and controlling microservices communication, traffic shifting, and observability.
 
Here are the study notes for the specified skills for the AWS Certified Cloud Practitioner certification in tabular format:

| **Skill**                                       | **Description**                                                                                                                                         | **Key Points**                                                                                     | **Examples/Use Cases**                                      |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Identifying the components of a VPC**         | Understanding the various components that make up a Virtual Private Cloud (VPC)                                                                          | **Subnets**: Public & private<br>**Route Tables**: Direct traffic within the VPC<br>**Gateways**: Internet, NAT, Transit<br>**VPC Peering**: Connects VPCs<br>**VPC Endpoints**: Private connectivity to AWS services | **Public Subnets**: Host web servers<br>**Private Subnets**: Host databases<br>**Route Tables**: Manage traffic flow<br>**Gateways**: Provide connectivity |
| **Understanding security in a VPC**             | Recognizing the security measures used within a VPC                                                                                                      | **Network ACLs**: Stateless, controls inbound and outbound traffic at the subnet level<br>**Security Groups**: Stateful, controls inbound and outbound traffic at the instance level | - Securing web applications<br>- Controlling traffic to instances<br>- Segmenting networks |
| **Understanding the purpose of Amazon Route 53**| Knowing the role of Amazon Route 53 in DNS management and routing                                                                                        | - Domain registration<br>- DNS routing<br>- Health checking and failover<br>- Latency-based routing | - Managing domain names<br>- Routing user requests based on geography<br>- Ensuring high availability and low latency |
| **Identifying edge services**                   | Recognizing AWS services that provide edge capabilities to improve performance and availability                                                          | **Amazon CloudFront**: Content Delivery Network (CDN) for fast content delivery<br>**AWS Global Accelerator**: Improves application availability and performance using global static IP addresses | - Serving static and dynamic content<br>- Reducing latency for global users<br>- Enhancing availability |
| **Identifying network connectivity options to AWS**| Understanding the different ways to connect on-premises networks to AWS                                                                                   | **AWS VPN**: Secure connection from on-premises to AWS<br>**AWS Direct Connect**: Dedicated network connection<br>**AWS PrivateLink**: Private connectivity to AWS services<br>**Site-to-Site VPN**: Extends on-premises network to AWS | - Hybrid cloud environments<br>- Secure data transfer<br>- Connecting VPCs to on-premises networks |

### Summary

- **Components of a VPC**:
  - **Subnets**: Public subnets for resources that need internet access; private subnets for resources that do not.
  - **Route Tables**: Control the routing of traffic within the VPC.
  - **Gateways**: 
    - **Internet Gateway**: Provides internet access to VPC.
    - **NAT Gateway**: Allows instances in a private subnet to connect to the internet without being exposed.
    - **Transit Gateway**: Connects VPCs and on-premises networks.
  - **VPC Peering**: Enables communication between VPCs.
  - **VPC Endpoints**: Enables private connections to AWS services without using the internet.

- **Security in a VPC**:
  - **Network ACLs**: Stateless traffic filters applied at the subnet level.
  - **Security Groups**: Stateful traffic filters applied at the instance level.

- **Amazon Route 53**:
  - Provides DNS services, including domain registration, DNS routing, and health checking.
  - Supports latency-based routing for directing user traffic to the lowest-latency endpoint.

- **Edge Services**:
  - **Amazon CloudFront**: Distributes content with low latency via a global network of edge locations.
  - **AWS Global Accelerator**: Uses global static IP addresses to improve application availability and performance.

- **Network Connectivity Options to AWS**:
  - **AWS VPN**: Securely connects on-premises networks to AWS using IPSec tunnels.
  - **AWS Direct Connect**: Provides a dedicated, high-bandwidth, low-latency connection from on-premises to AWS.
  - **AWS PrivateLink**: Allows private access to AWS services within the AWS network.
  - **Site-to-Site VPN**: Extends on-premises networks to AWS VPCs securely.
