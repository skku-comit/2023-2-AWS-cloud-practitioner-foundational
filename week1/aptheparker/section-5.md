# Section 5. EC2

## 1. Amazon EC2
- EC2: Renting virtual machines.
- EBS: Storing data on virtual drives.
- ELB: Distributing load across machines.
- ASG: Scaling the services up or down.

## 2. EC2 sizing & configuration options

- Operating System
- CPU
- RAM
- Storage
- Network Performance
- Firewall Rules
- Bootstrap Scripts

## 3. EC2 Instance Types

- General Purpose： Balance of CPU, memory and networking. (t2)
- Compute Optimized： High CPU performance. (c6g)
- Memory Optimized： High memory performance. (r6g)
- Storage Optimized： High storage performance. (i3)

## 4. Security Groups

- Security Groups: firewall on EC2 instances.
- Regulate:
  - Access to ports
  - Authorised IP ranges - IPv4 and IPv6
  - Control of inbound network (from other to the instance)
  - Control of outbound network (from the instance to other)
- Classic Ports:
  - 22: SSH
  - 21: FTP
  - 22: SFTP
  - 80: HTTP
  - 443: HTTPS
  - 3389: RDP

## 5. SSH / EC2 Instance Connect

- SSH: Secure Shell
  - A way to remotely access a terminal.
- EC2 Instance Connect: Connect to EC2 instance in browser.
  - No need to create a key pair.

## 6. EC2 Instance Pricing

- On-Demand Instances: Pay for what you use.
- Reserved Instances: Pay for a reserved instance.
- Savings Plans: Pay for a commitment to use a specific amount of compute power.
- Spot Instances: Bid for unused capacity.
- Dedicated Hosts: Pay for a physical server.
- Dedicated Instances: similar to Dedicated Hosts, but pay for a virtual machine.
- Capacity Reservations: Reserve capacity in advance.

## 7. EC2 Shared Responsibility Model

- AWS is responsible for security of the cloud.
- Customer is responsible for security in the cloud.
