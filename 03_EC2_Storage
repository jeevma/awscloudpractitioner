### EC2 Instance Storage Cheat Sheet

**Elastic Block Store (EBS)**
- **Definition**: A network drive you can attach to your instances while they run, allowing data to persist after instance termination.
- **Key Features**:
  - Can only be mounted to one instance at a time.
  - Bound to a specific availability zone.
  - Considered a "network USB stick".
  - Free tier includes 30 GB of General Purpose (SSD) or Magnetic storage per month.

- **EBS Volume Characteristics**:
  - Uses the network to communicate with the instance, potentially introducing latency.
  - Can be detached from one instance and attached to another.
  - Locked to an Availability Zone (e.g., a volume in us-east-1a cannot be attached to us-east-1b).
  - To move a volume across AZs, you must create a snapshot and restore it in the desired AZ.

**Local EC2 Instance Store**
- **Definition**: High-performance hardware disk attached to an EC2 instance.
- **Key Features**:
  - Provides very high IOPS (Input/Output Operations Per Second).
  - Data is lost if the instance is stopped, making it suitable for temporary data like buffers, caches, or scratch data.
  - Risk of data loss if hardware fails, so backups and replication are the user's responsibility.

**Elastic File System (EFS)**
- **Definition**: Managed Network File System (NFS) that can be mounted on hundreds of EC2 instances.
- **Key Features**:
  - Works with Linux EC2 instances in multi-AZ.
  - Highly available, scalable, and pay-per-use.
  - Expensive (approximately 3 times the cost of EBS gp2).
  - No capacity planning required.

**Comparison: EBS vs EFS**
- **EBS**:
  - Attached to one instance at a time.
  - Bound to a specific AZ.
  - Suitable for persistent block storage.
- **EFS**:
  - Can be mounted on multiple instances.
  - Works across multiple AZs.
  - Suitable for shared file storage.

**EBS Snapshot Features**
- **Snapshot Archive**:
  - Move snapshots to an archive tier, reducing costs by 75%.
  - Restoration from archive can take 24 to 72 hours.
- **Recycle Bin**:
  - Retain deleted snapshots for recovery.
  - Retention period ranges from 1 day to 1 year.

**Instance Store vs. EBS**
- **Instance Store**:
  - High I/O performance.
  - Data is ephemeral and lost when the instance stops.
  - Best for temporary storage needs.
- **EBS**:
  - Network-attached storage.
  - Persistent storage that survives instance termination.
  - Suitable for data that needs to be retained.

**Shared Responsibility Model for EC2 Storage**
- **AWS Responsibilities**:
  - Infrastructure management.
  - Data replication for EBS volumes and EFS drives.
  - Replacing faulty hardware.
  - Ensuring employee data access is restricted.
- **User Responsibilities**:
  - Setting up backup and snapshot procedures.
  - Data encryption.
  - Managing any data on the drives.
  - Understanding the risks of using EC2 Instance Store.

This cheat sheet provides a concise overview of the EC2 Instance Storage options, their features, and the shared responsibility model. For a more detailed explanation, please refer to the relevant sections in the provided AWS Certified Cloud Practitioner materials【6:0†source】【6:2†source】【6:3†source】【6:4†source】.