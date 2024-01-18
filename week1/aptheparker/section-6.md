# Section 6. EC2 Instance Storage

## 1. EBS (Elastic Block Store)

- Network attached storage volumes that can be attached to EC2 instances
- Persist data even after instance is terminated
- can only be mounted to one instance at a time
- bound to a specific availability zone

## 2. EBS Snapshots

- Point in time copy of an EBS volume
- Not necessary to detach volume to take snapshot
- Can copy snapshots across AZs
  <details>
  <summary>EBS Snapshots Features</summary>
  
    ```
    # EBS Snapshots Archive
    - 75% cheaper
    - 24 to 72 hours to restore

    # Recycle Bin for EBS Snapshots
    - Rules to retain snapshots
    -specify retention
    ``````

</details>

## 3. AMI (Amazon Machine Image)
- Customization of an EC2 instance
- built for a specific region (can be copied across regions)

## 4. EC2 Image Builder
- automate the creation of VM images.
- EC2 Image Builder -> Builder EC2 Instance -> AMI -> Test EC2 Instance -> AMI

## 5. EC2 Instance Store
- network drives with good but limited performance.
- lose data if the instance is stopped or terminated.
- good for buffer, cache, scratch data, temporary content.

## 6. EFS (Elastic File System)
- Managed NFS (Network File System) that can be mounted on many EC2.
- Highly available, scalable, expensive (3x gp2), pay per use, no capacity planning.
- Works with Linux EC2 instances in multi-AZ.
- EFS-IA: Infrequently Accessed Storage class (cost to retrieve files, lower price to store files).

## 7. FSx (File System)
- 3rd party high-performance file system
  - Windows File Server
  - Lustre (high performance computing, machine learning, financial modeling, etc.)
- Can be accessed from on-premise infrastructure (hybrid cloud)
