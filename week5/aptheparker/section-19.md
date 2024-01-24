# Section 19. Advanced Identity

## 1. AWS STS (Security Token Service)

- Generate temporary, limited-privilege credentials for IAM users or for users that you authenticate (federated users)
- Use cases:
  - Federation
  - Cross-Account Access
  - Roles for EC2 Instances
  - Web Identity Federation (Google, Facebook, Amazon, etc.)

## 2. Amazon Cognito

- Web identity federation service
- Sign in users and give them access to AWS resources

## 3. AWS Directory Service

- Managed Microsoft Active Directory (AD)in the AWS Cloud.
- AD Connector: Directory Gateway (proxy) to redirect to on-premise AD.
- Simple AD: AD-compatible managed directory on AWS.

## 4. AWS IAM Identity Center

- Centralized view to manage all identities in AWS
- One login for all AWS accounts
- Identity Providers: AD, OneLogin, Okta...