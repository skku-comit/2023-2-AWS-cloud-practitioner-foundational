# Section 12. Leveraging the AWS Global Infrastructure

## 1. Global DNS: Route 53
- Great for:
  - Registering domain names.
  - Route users to the closest AWS region.
  - Load balancing across regions.

## 2. Global Content Delivery Network (CDN): CloudFront
- To improve user experience and decrease latency.
- Great for:
  - Replicate part of application to all edge locations.
  - Cache common requests at the edge.

## 3. S3 Transfer Acceleration
- Uses the CloudFront Edge Network to accelerate uploads to S3.

## 4. AWS Global Accelerator
- Improve global application availability and performance using the AWS global network.
- CDN vs Global Accelerator
  - CDN: Improves performance for **random users**.
  - Global Accelerator: Improves performance for **a specific group of users**.

## 5. AWS Outposts
- Run AWS infrastructure on-premise.
- Fully managed and configurable compute and storage racks.
- Uses the same AWS APIs, tools, and hardware.
- Great for:
  - Low latency applications.
  - Local data processing.
  - Migration to AWS.

## 6. AWS Wavelength
- Bring AWS services to the edge of the 5G network.
- Ultra-low latency for mobile devices.
- Great for:
  - Use cases that require ultra-low latency.
  - Use cases that require compute and storage on the edge.

## 7. AWS Local Zones
- Bring AWS services to large cities and closer to end-users.
- Great for:
  - Use cases that require low latency.
  - Use cases that require compute and storage on the edge.
