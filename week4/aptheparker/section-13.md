# Section 13. Cloud Integrations

## 1. SQS (Simple Queue Service)
- Distributed message queueing system
- Decouple applications
- FIFO Queue: First In First Out (Message Order)

## 2. Kinesis 
- Real-time big data streaming.
- Kinesis Streams: Low latency streaming ingest at scale.
- Kinesis Firehose: Load streams into S3, Redshift, ElasticSearch.
- Kinesis Analytics: Real-time analytics on streams using SQL.
- Kinesis Video Streams: Capture, process, and store video streams.

## 3. SNS (Simple Notification Service)
- Pub/Sub messaging and mobile notifications for microservices, distributed systems, and serverless applications.
- Each topic can have multiple subscribers.
- Each subscriber to a topic will get all the messages (no filtering).

## 4. MQ (Message Queue)
- Managed message broker service for Apache ActiveMQ and RabbitMQ.
- MQ does not scale as much as SQS/SNS.
- MQ runs on servers, can run in Multi-AZ with failover.