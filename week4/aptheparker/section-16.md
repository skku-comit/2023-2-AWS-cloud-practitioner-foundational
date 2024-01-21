# Section 16. Security & Compliance

## 1. AWS Shared Responsibility Model

- AWS is responsible for the security of the cloud.
  - Physical security of data centers.
  - Security of hardware & software infrastructure.
- Customer is responsible for the security in the cloud.
  - Security of data.
  - Security of operating systems, platforms, & data.
- Shared Controls: Patch management, configuration management, awareness & training.

## 2. AWS Shield

- Protect against DDoS attacks.
  - AWS Shield Standard: Free, always on.
  - AWS Shield Advanced: Paid, extra protection, 24/7 access to DDoS response team.

## 3. AWS WAF (Web Application Firewall)

- Protect against web attacks.
  - Layer 7 firewall (HTTP/HTTPS).
  - Protect against SQL injection, cross-site scripting, etc.
  - Works with CloudFront, Application Load Balancer, API Gateway.
  - Define Web ACL (Access Control List) to allow or deny requests based on rules.

## 4. AWS Network Firewall

- Protect against network attacks.
  - Layer 4 firewall (TCP/UDP).
  - Protect against IP spoofing, port scanning, etc.

## 5. Penetration Testing

- Carry out security assessments or penetration tests against AWS infrastructure without prior approval.

## 6. AWS KMS (Key Management Service)

- Create & manage encryption keys.
- Integrated with other AWS services.
- CloudHSM: AWS provisions encryption hardware.

## 7. AWS Certificate Manager (ACM)

- Provision, manage, & deploy SSL/TLS certificates.
- Provide in-flight encryption for CloudFront, ALB, API Gateway, etc.

## 8. AWS Secrets Manager

- Store & manage secrets (passwords, API keys, etc.)
- Rotate secrets automatically.

## 9. AWS Artifact

- On-demand access to AWS compliance reports.
- Download AWS security & compliance documents.

## 10. Amazon GuardDuty

- Intelligent threat detection service.
- Monitor for malicious activity & unauthorized behavior.

## 11. AWS Inspector

- Automated security assessment service.
- Analyze EC2 instances for vulnerabilities & deviations from best practices.

## 12. AWS Config

- Track changes to AWS resources over time.
- Evaluate resources against compliance rules.

## 13. AWS Macie

- Use machine learning to detect sensitive data, such as PII (Personally Identifiable Information).

## 14. AWS Security Hub

- Centrally view & manage security alerts & compliance status across AWS accounts.

## 15. Amazon Detective

- Analyze, investigate, & quickly identify the root cause of potential security issues or suspicious activities.

## 16. Root user privileges

- Root user: Has access to everything in the AWS account.
- Best practice: Don't use root user.

