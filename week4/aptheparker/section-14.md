# Section 14. Cloud Monitoring

## 1. CloudWatch
- Metrics: collect and track key metrics
- Logs: collect, monitor, analyze, and store log files
- Events: send notifications when certain events happen in your AWS
- Alarms: react in real-time to metrics/events
- Dashboards: create dashboards to monitor your resources

## 2. CloudWatch Alarms
- Alarms are used to trigger notifications for any metric
- Alarms can go to Auto Scaling, EC2 Actions, SNS notifications

## 3. CloudWatch Logs
- Real-time monitoring of logs
- Can send logs from anywhere using SDK

## 4. EventBridge
- Schedule: run tasks based on a cron job
- Event Pattern: react to a service doing something
- Schema Registry: structure of events sent through EventBridge

## 5. CloudTrail
- Governance, compliance, operational auditing for AWS Account
- Can put logs from CloudTrail into CloudWatch Logs or S3
- Track changes to AWS Resources and API calls made to AWS

## 6. X-Ray
- Debugging in production: troubleshoot performance
- Understand dependencies in a microservice architecture
- Pinpoint service issues
- Review request behavior
- Find errors and exceptions

## 7. CodeGuru
- Automated code reviews and application performance recommendations
- Two offerings:
  - CodeGuru Reviewer: analyzes code and provides recommendations
  - CodeGuru Profiler: collects runtime performance data from live applications, identifies most expensive lines of code, and provides recommendations

## 8. Health Dashboard (Service Health Dashboard)
- Service History
  - Shows all regions and all services.
  - Shows historical information about service issues.
- Account
  - Provides alerts about service issues that affect just your account.
  - Displays relevant information to plan for scheduled activities.
  