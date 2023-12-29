# Section 7. ELB & ASG (Elastic Load Balancer & Auto Scaling Group)

## 1. ELB (Elastic Load Balancer)

- Servers that forward internet traffic to multiple EC2 instances.
- High availability across zones.
- Three types:
  - Application Load Balancer (HTTP/HTTPS only)
  - Network Load Balancer (TCP, TLS, UDP)
  - Gateway Load Balancer (IP address as target)

## 2. ASG (Auto Scaling Group)

- Scale EC2 instances based on demand.
- Scale based on CloudWatch metrics (CPU, Network, etc.)
- Scale based on time schedule.
- Scale based on health checks.

## 3. ASG Scaling Strategies

- Manual Scaling: Update the size manually.
- Dynamic Scaling: Based on load metrics.
  - Simple/Step Scaling: e.g. CPU > 70% -> add 2 instances
  - Target Tracking Scaling: e.g. average CPU to stay at 40%
  - Scheduled Actions: e.g. scale up at 8am, scale down at 6pm
- Predictive Scaling: ML to predict future traffic.