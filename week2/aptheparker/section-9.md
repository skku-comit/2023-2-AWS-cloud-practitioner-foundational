# Section 9. Databases & Analytics

## 1. RDS (Relational Database Service)

- Managed DB service for DBs based on SQL.
- Supports MySQL, PostgreSQL, Oracle, SQL Server, MariaDB, Aurora.

## 2. Aurora

- Aurora is AWS's own DB engine (compatible with MySQL and PostgreSQL).
  - 5x performance of MySQL, 3x performance of PostgreSQL.
- Aurora Serverless: automatically scales up/down based on demand.
  - Good for infrequently accessed DBs.

## 3. ElastiCache

- Managed Redis or Memcached.
- In-memory DBs for caching.
- Helps reduce load off of DBs.

## 4. DynamoDB

- Managed NoSQL DB.
- Supports key-value and document data models.
- Serverless option available.
- DynamoDB Global Tables: multi-region, multi-master replication.
  - Good for low-latency global apps.

## 5. Redshift

- Managed data warehouse.
- Used for analytics.
- Supports SQL.
- Can be connected to BI (Business Intelligence) tools like Tableau.

## 7. EMR (Elastic MapReduce)

- Create Hadoop clusters to process big data.
- Used for big data processing and analysis.

## 8. Athena

- Query data stored in S3 using SQL.
- Serverless.

## 9. Amazon QuickSight

- Business Intelligence tool.
- Create dashboards and visualizations.
- Can connect to many data sources, including AWS ones.

## 10. DocumentDB

- Managed MongoDB.
- Serverless option available.

## 11. Neptune

- Managed graph database.
- Good for relationship data.
- Highly available across multiple AZs.

## 12. Amazon QLDB

- Managed ledger database.
- Maintains a complete and verifiable history of data changes.
- Centralized, immutable, and cryptographically verifiable.

## 13. Amazon Managed Blockchain

- Managed blockchain service.
- Decentralized ledger that keeps a record of transactions.

## 14. Glue (ETL) & DMS (Database Migration Service)

- Glue: ETL (Extract, Transform, Load) service.
  - Used to prepare and transform data for analytics.
- DMS: migrate databases to AWS.
  - Can migrate to RDS, DynamoDB, S3, etc.
  - Support:
    - Homogeneous migrations (e.g. Oracle to Oracle).
    - Heterogeneous migrations (e.g. Oracle to Aurora).

## 15. RDS Multi-AZ vs Multi-Region vs Read Replicas
![RDS Mutli-AZ vs Multi-Region vs Read Replicas](image.png)