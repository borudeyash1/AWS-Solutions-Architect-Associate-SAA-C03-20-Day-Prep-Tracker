# 🎯 AWS Solutions Architect Associate (SAA-C03) 20-Day Prep Tracker

> **Source Material**: [AWS Solution Architect Handbook.pdf](file:///d:/Interview/SAA/AWS%20Solution%20Architect%20Handbook.pdf)  
> **Goal**: Master all 16 AWS domains and 100+ core services across 20 structured prep days to clear the **SAA-C03** examination with confidence.

---

## 📊 Preparation Overview

| Phase | Days | Focus Areas | Primary Handbook Categories Covered |
| :--- | :--- | :--- | :--- |
| **Phase 1** | Days 1–5 | Core Infrastructure & Storage | Compute, Serverless, Storage, VPC & Core Networking |
| **Phase 2** | Days 6–10 | Advanced Networking, Databases & App Integration | Edge Networking, Databases, Containers, Developer Tools & Messaging |
| **Phase 3** | Days 11–15 | Security, Governance, Analytics & Cost Management | Security & Identity, Compliance, Management & Governance, Analytics & Cost |
| **Phase 4** | Days 16–20 | Migration, AI/ML, Architecture Patterns & Mock Exams | Migration & Transfer, Front-End/ML, Well-Architected Framework & Practice Exams |

---

## 🤝 Study Commitment & Dedicated Hours Promise

> **The 60-Hour SAA-C03 Mastery Pledge** 📜  
> *"I promise to dedicate **2.5 to 3 hours daily** over the next **20 days** (totaling **50–60 hours** of focused study) to thoroughly read the handbook, solve topic quizzes, analyze architectural trade-offs, and pass the **AWS Certified Solutions Architect Associate (SAA-C03)** exam with confidence."*

### ⏳ Daily Hours Breakdown (2.5 – 3.0 Hours / Day):
- 📖 **Theory & Handbook Deep-Dive (1.0 – 1.5 hrs/day)**: Study service architectures, configuration parameters, limits, and Well-Architected pillars from the handbook.
- 🧪 **Topic Quizzes & Scenario Solving (1.0 hr/day)**: Practice scenario-based questions, multi-select evaluation, and jumbled option drills across interactive quiz modules.
- 📝 **Audit & Retention Review (0.5 hr/day)**: Analyze incorrect options, review explanations, and solidify core architectural concepts.

---

## 🗓️ Phase 1: Core Infrastructure & Storage (Days 1–5)

### 📅 Day 1: Core Compute Services
**Focus**: Primary EC2 instances, auto-scaling, batch workloads, and Elastic Beanstalk.  
**Handbook Category**: `COMPUTE`

- [ ] **Amazon EC2** — Instance types (General, Compute, Memory, Storage), Pricing Models (On-Demand, Reserved, Spot, Dedicated), Placement Groups, AMIs.
- [ ] **Amazon EC2 Auto Scaling** — Auto Scaling Groups (ASG), Scaling Policies (Target Tracking, Step, Simple, Predictive), Health Checks.
- [ ] **AWS Batch** — Batch processing, Job Definitions, Job Queues, Compute Environments (Managed vs Unmanaged).
- [ ] **AWS Elastic Beanstalk** — PaaS deployment model, Deployment Strategies (All-at-once, Rolling, Rolling with batch, Immutable, Blue/Green).
- [ ] 🎯 *Day 1 Review*: Review EC2 pricing models and scaling policy selection scenarios in the Handbook.

---

### 📅 Day 2: Edge/Hybrid Compute & Serverless Foundations
**Focus**: Hybrid compute infrastructure, edge deployment, and core serverless compute.  
**Handbook Categories**: `COMPUTE`, `SERVERLESS`

- [ ] **AWS Outposts** — Extending AWS infrastructure and services on-premises for low-latency workloads.
- [ ] **AWS Wavelength** — Ultra-low latency application deployment for 5G devices at the carrier edge.
- [ ] **AWS Serverless Application Repository** — Managing and sharing serverless applications and components.
- [ ] **AWS Lambda** — Serverless computing, Execution Context, Concurrency (Unreserved, Reserved, Provisioned), Event Sources, Function URLs.
- [ ] **AWS Fargate** — Serverless compute engine for containerized workloads without managing EC2 instances.
- [ ] 🎯 *Day 2 Review*: Contrast Lambda provisioned concurrency vs on-demand execution.

---

### 📅 Day 3: Storage Deep Dive (Part 1 — S3 & EBS)
**Focus**: Object storage partitioning, lifecycle management, and block storage performance.  
**Handbook Category**: `STORAGE`

- [ ] **Amazon S3** — Storage Classes (Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier Instant/Flexible/Deep Archive), Lifecycle Rules, Versioning, Replication (CRR/SRR), Object Lock.
- [ ] **Amazon S3 Security & Performance** — S3 Bucket Policies, KMS Encryption, S3 Select, Byte-Range Fetches, Multipart Upload, Access Points, Multi-Region Access Points.
- [ ] **Amazon Elastic Block Store (Amazon EBS)** — Volume types (gp2/gp3, io1/io2, st1, sc1), EBS Snapshots, Data Lifecycle Manager (DLM), Encryption, Multi-Attach.
- [ ] 🎯 *Day 3 Review*: Solve storage class cost-optimization scenarios.

---

### 📅 Day 4: Storage Deep Dive (Part 2 — File Systems, Backup & Hybrid Storage)
**Focus**: Distributed file systems, central backups, and hybrid storage gateways.  
**Handbook Category**: `STORAGE`

- [ ] **Amazon Elastic File System (Amazon EFS)** — Network file system (NFSv4), Performance Modes (General Purpose, Max I/O), Throughput Modes (Bursting, Provisioned, Elastic), Storage Classes.
- [ ] **Amazon FSx (All Types)** — FSx for Windows File Server, FSx for Lustre (HPC), FSx for NetApp ONTAP, FSx for OpenZFS.
- [ ] **AWS Backup** — Centralized backup management across AWS services (EBS, S3, RDS, DynamoDB, EFS).
- [ ] **AWS Storage Gateway** — File Gateway (S3/FSx), Volume Gateway (Stored vs Cached), Tape Gateway.
- [ ] 🎯 *Day 4 Review*: Compare EFS vs FSx for Windows vs FSx for Lustre use cases.

---

### 📅 Day 5: Core Networking & Load Balancing
**Focus**: Virtual Private Cloud setup, subnet routing, security, and load distribution.  
**Handbook Category**: `NETWORKING & CONTENT DELIVERY`

- [ ] **Amazon VPC (Part 1)** — CIDR blocks, Public & Private Subnets, Route Tables, Internet Gateways (IGW), NAT Gateways vs NAT Instances.
- [ ] **Amazon VPC (Part 2)** — Security Groups (Stateful) vs Network ACLs (Stateless), VPC Flow Logs, VPC Peering.
- [ ] **Elastic Load Balancing (ELB)** — Application Load Balancer (ALB), Network Load Balancer (NLB), Gateway Load Balancer (GWLB), Target Groups, Cross-Zone Load Balancing, SSL Termination.
- [ ] **Amazon Route 53** — Routing Policies (Simple, Weighted, Latency, Failover, Geolocation, Geoproximity, Multi-Value Answer), Health Checks, Private Hosted Zones.
- [ ] 🎯 *Day 5 Review*: Practice drawing a multi-AZ VPC architecture with ALB and Auto Scaling.

---

## 🗓️ Phase 2: Advanced Networking, Databases & App Integration (Days 6–10)

### 📅 Day 6: Advanced Networking & Content Delivery
**Focus**: Global network acceleration, hybrid connectivity, and inter-VPC transit.  
**Handbook Category**: `NETWORKING & CONTENT DELIVERY`

- [ ] **Amazon CloudFront** — CDN origins, Edge Locations, CloudFront Functions vs Lambda@Edge, Signed URLs/Cookies, OAC/OAI, Cache Behaviors.
- [ ] **AWS Direct Connect (DX)** — Dedicated network connections, DX Locations, Private VIF, Public VIF, Transit VIF, Direct Connect Gateway, High Availability design (Active/Active vs Active/Passive).
- [ ] **AWS Global Accelerator** — Anycast IP addresses, Traffic Dial, Endpoint Groups, Static IP routing acceleration.
- [ ] **AWS Transit Gateway (TGW)** — Central hub connecting VPCs, VPNs, and Direct Connect; Route Table domain isolation.
- [ ] 🎯 *Day 6 Review*: Compare CloudFront vs Global Accelerator for dynamic content.

---

### 📅 Day 7: Relational Databases & Caching
**Focus**: SQL database engine patterns, read replicas, multi-AZ high availability, and in-memory caches.  
**Handbook Category**: `DATABASE`

- [ ] **Amazon RDS** — Engines (PostgreSQL, MySQL, MariaDB, Oracle, SQL Server), Multi-AZ Deployments (Synchronous), Read Replicas (Asynchronous), Automated Backups vs Manual Snapshots, Storage Auto-Scaling.
- [ ] **Amazon Aurora** — Aurora Architecture (6 copies across 3 AZs), Aurora Serverless v2, Aurora Global Database, Aurora Read Replicas, Parallel Query, Fault Tolerance.
- [ ] **Amazon ElastiCache** — Redis/Valkey (Clustering, Pub/Sub, Persistence) vs Memcached (Multi-threading, Simple Key-Value), Cache Strategies (Lazy Loading, Write-Through).
- [ ] 🎯 *Day 7 Review*: Master RDS Multi-AZ failover mechanics vs Aurora Shared Storage architecture.

---

### 📅 Day 8: NoSQL, Specialized Databases & Data Stores
**Focus**: Non-relational databases, ledger, graph, and column-store databases.  
**Handbook Category**: `DATABASE`

- [ ] **Amazon DynamoDB** — Partition Keys & Sort Keys, Read/Write Capacity Units (On-Demand vs Provisioned), Global Secondary Indexes (GSI) vs Local Secondary Indexes (LSI), DynamoDB Streams, Global Tables.
- [ ] **Amazon DocumentDB** — MongoDB-compatible managed document database.
- [ ] **Amazon Keyspaces** — Apache Cassandra-compatible managed database service.
- [ ] **Amazon Neptune** — Managed Graph database service (Gremlin, SPARQL).
- [ ] **Amazon Quantum Ledger Database (Amazon QLDB)** — Immutable, cryptographically verifiable ledger database.
- [ ] **Amazon Redshift (Database Focus)** — Columnar storage, Leader Node & Compute Nodes, Redshift Spectrum, Concurrency Scaling.
- [ ] 🎯 *Day 8 Review*: Compare database selection criteria across OLTP, OLAP, NoSQL, and Graph.

---

### 📅 Day 9: Containers & Microservices Infrastructure
**Focus**: Container management, orchestration, and image registries.  
**Handbook Category**: `CONTAINERS`

- [ ] **Amazon Elastic Container Service (Amazon ECS)** — Task Definitions, Services, Clusters, Launch Types (EC2 vs Fargate), Capacity Providers.
- [ ] **Amazon Elastic Container Registry (Amazon ECR)** — Image repositories, vulnerability scanning, lifecycle policies, cross-account/cross-region replication.
- [ ] **Amazon Elastic Kubernetes Service (Amazon EKS)** — Control plane management, Worker nodes (Managed Node Groups, Fargate profiles), kubectl integration.
- [ ] **Amazon ECS Anywhere, EKS Anywhere & EKS Distro** — Hybrid container management on customer infrastructure.
- [ ] 🎯 *Day 9 Review*: Review container deployment options (ECS Fargate vs EKS Fargate).

---

### 📅 Day 10: Application Integration, Messaging & Developer Tools
**Focus**: Event-driven architectures, asynchronous decoupling, and distributed tracing.  
**Handbook Categories**: `APPLICATION INTEGRATION`, `DEVELOPER TOOLS`

- [ ] **Amazon Simple Queue Service (Amazon SQS)** — Standard vs FIFO Queues, Visibility Timeout, Short vs Long Polling, Dead Letter Queues (DLQ), Delay Queues.
- [ ] **Amazon Simple Notification Service (Amazon SNS)** — Topic subscriptions (SQS, Lambda, HTTP, Email), Fan-out pattern, FIFO Topics, Message Filtering.
- [ ] **Amazon EventBridge** — Event Bus, Custom Rules, Schema Registry, EventBridge Pipes, API Destinations.
- [ ] **AWS Step Functions** — State Machines (Standard vs Express), Task States, Choice States, Parallel States, Error Handling and Retries.
- [ ] **Amazon MQ** — Managed message broker for Apache ActiveMQ and RabbitMQ.
- [ ] **Amazon AppFlow & AWS AppSync** — SaaS data ingestion and GraphQL endpoint integration.
- [ ] **AWS X-Ray** — Distributed tracing, Service Maps, Traces, Segments, Annotations.
- [ ] 🎯 *Day 10 Review*: Architectural patterns for SQS + SNS Fan-out and EventBridge routing.

---

## 🗓️ Phase 3: Security, Governance, Analytics & Cost Management (Days 11–15)

### 📅 Day 11: Security, Identity & Key Management
**Focus**: IAM policies, identity federation, cryptographic keys, and secret management.  
**Handbook Category**: `SECURITY, IDENTITY & COMPLIANCE`

- [ ] **AWS Identity and Access Management (IAM)** — Users, Groups, Roles, Policies (Identity-based, Resource-based, SCPs, Permission Boundaries), STS (AssumeRole), Identity Federation (SAML 2.0, Web Identity).
- [ ] **Amazon Cognito** — User Pools (Authentication, User Directories) vs Identity Pools (Authorization, AWS Temporary Credentials).
- [ ] **AWS Key Management Service (AWS KMS)** — Symmetric vs Asymmetric Keys, Customer Managed Keys (CMK) vs AWS Managed Keys, KMS Key Policies, Envelope Encryption, Multi-Region Keys.
- [ ] **AWS CloudHSM** — Dedicated hardware security module for single-tenant compliance requirements.
- [ ] **AWS Secrets Manager vs Parameter Store** — Automatic secret rotation, KMS integration, SSM Parameter Store (Free tier vs Advanced parameters).
- [ ] **AWS Resource Access Manager (AWS RAM)** — Securely sharing AWS resources across accounts and within AWS Organizations.
- [ ] 🎯 *Day 11 Review*: Solve IAM policy evaluation logic scenarios (Explicit Deny > Explicit Allow > Default Deny).

---

### 📅 Day 12: Network Security, Threat Detection & Compliance
**Focus**: WAF protection, threat monitoring, security compliance, and firewall management.  
**Handbook Category**: `SECURITY, IDENTITY & COMPLIANCE`

- [ ] **AWS WAF & AWS Shield** — Web ACLs, Rules, SQL Injection / XSS protection, Rate-based rules, Shield Standard vs Shield Advanced (DDoS protection).
- [ ] **AWS Firewall Manager & AWS Network Firewall** — Central security management across VPCs and Accounts; Layer 7 inspection.
- [ ] **Amazon GuardDuty** — Intelligent threat detection using machine learning on CloudTrail, VPC Flow Logs, and DNS Logs.
- [ ] **Amazon Inspector & Amazon Macie** — Vulnerability scanning for EC2/ECR vs Sensitive data discovery (PII) in S3.
- [ ] **AWS Security Hub & Amazon Detective** — Centralized security posture management and root cause analysis for security findings.
- [ ] **AWS Directory Service** — AWS Managed Microsoft AD, Simple AD, AD Connector.
- [ ] **AWS Artifact & AWS Audit Manager** — Compliance reports, agreements, and automated audit evidence collection.
- [ ] 🎯 *Day 12 Review*: Differentiate GuardDuty vs Inspector vs Macie vs Security Hub.

---

### 📅 Day 13: Management, Governance & Infrastructure as Code (Part 1)
**Focus**: Resource management, audit logging, monitoring, and automated provisioning.  
**Handbook Category**: `MANAGEMENT & GOVERNANCE`

- [ ] **AWS CloudFormation** — Templates, Stacks, StackSets, Change Sets, Custom Resources, Drift Detection, Rollback behavior.
- [ ] **AWS CloudTrail** — Logging management and data events, Trail organization aggregation, Integrity validation, CloudTrail Insights.
- [ ] **Amazon CloudWatch** — Metrics, Alarm Actions, CloudWatch Logs, Log Groups, CloudWatch Insights, Dashboards, Synthetics.
- [ ] **AWS Config** — Resource configuration history, Compliance Rules (Managed vs Custom), Remediation Actions.
- [ ] **AWS Organizations & Control Tower** — Multi-account strategy, Organizational Units (OUs), Service Control Policies (SCPs), Guardrails.
- [ ] **AWS Systems Manager (SSM)** — Parameter Store, Run Command, Patch Manager, Session Manager, Automation, State Manager.
- [ ] 🎯 *Day 13 Review*: Master SCP inheritance rules across multi-account OU hierarchies.

---

### 📅 Day 14: Operations, Governance & Cost Optimization
**Focus**: Observability tools, operational health, service discovery, and cost monitoring.  
**Handbook Categories**: `MANAGEMENT & GOVERNANCE`, `AWS COST MANAGEMENT`

- [ ] **AWS CLI & AWS Management Console** — Command line automation, profiles, and console controls.
- [ ] **AWS Health Dashboard** — Personal Health Dashboard (PHD) vs Service Health Dashboard (SHD).
- [ ] **Amazon License Manager, Managed Grafana & Prometheus** — Open-source observability and software license management.
- [ ] **AWS Proton & AWS Service Catalog** — Standardized application templates and catalog management for end users.
- [ ] **AWS Trusted Advisor & AWS Well-Architected Tool** — Cost, security, fault tolerance recommendations, and Well-Architected reviews.
- [ ] **AWS Cost Management Tools** — AWS Budgets, AWS Cost Explorer, AWS Cost and Usage Report (CUR), Savings Plans (Compute vs EC2 Instance vs SageMaker), Cost Allocation Tags.
- [ ] 🎯 *Day 14 Review*: Solve cost reduction scenario questions (Savings Plans vs Reserved Instances vs Spot).

---

### 📅 Day 15: Analytics & Data Lake Architectures
**Focus**: Big data pipelines, stream processing, data lakes, and querying engines.  
**Handbook Category**: `ANALYTICS`

- [ ] **Amazon Athena** — Serverless SQL queries on S3, Partitioning, Parquet/ORC compression, Glue Data Catalog integration.
- [ ] **AWS Data Pipeline & AWS Data Exchange** — Data workflow orchestration and third-party data subscriptions.
- [ ] **Amazon EMR** — Hadoop and Spark processing clusters, Spot Instance utilization, EMR Serverless.
- [ ] **AWS Glue** — ETL jobs, Data Catalog, Crawlers, Glue Streaming, AWS Lake Formation (Data Lake governance).
- [ ] **Amazon Kinesis** — Kinesis Data Streams (Shard management, retention), Kinesis Data Firehose (Delivery to S3/Redshift/OpenSearch), Kinesis Data Analytics (Flink).
- [ ] **Amazon MSK & Amazon OpenSearch Service** — Managed Kafka streams and log/text analytics indexing.
- [ ] **Amazon QuickSight & Amazon Redshift** — BI dashboards, SPICE engine, Redshift Data Warehouse (Distkeys & Sortkeys).
- [ ] 🎯 *Day 15 Review*: Architectural comparison of Kinesis Data Streams vs Kinesis Data Firehose vs SQS.

---

## 🗓️ Phase 4: Migration, AI/ML, Architecture Patterns & Mock Exams (Days 16–20)

### 📅 Day 16: Migration, Data Transfer & Hybrid Architectures
**Focus**: Migration strategies (6 Rs), database conversion, and large-scale data transfer.  
**Handbook Category**: `MIGRATION AND TRANSFER`

- [ ] **Migration Strategies (6 Rs)** — Rehost (Lift & Shift), Replatform (Lift, Tinker & Shift), Refactor/Re-architect, Repurchase, Retain, Retire.
- [ ] **AWS Application Discovery Service & AWS Application Migration Service (MGN)** — Server assessment and automated block-level replication.
- [ ] **AWS Database Migration Service (AWS DMS)** — Full load vs Change Data Capture (CDC), Schema Conversion Tool (SCT), Source/Target endpoints.
- [ ] **AWS DataSync** — Automated data transfer between on-premises and AWS (S3, EFS, FSx).
- [ ] **AWS Snow Family** — Snowcone, Snowball Edge (Storage/Compute), Snowmobile (PB/EB scale offline migration).
- [ ] **AWS Transfer Family** — Managed SFTP, FTPS, and FTP transfers directly into S3 and EFS.
- [ ] 🎯 *Day 16 Review*: Determine appropriate migration tool based on data volume, bandwidth, and downtime requirements.

---

### 📅 Day 17: Front-End, Mobile, Media & ML Services
**Focus**: Mobile backends, API management, media conversion, and managed ML services.  
**Handbook Categories**: `FRONT-END & MOBILE`, `MEDIA SERVICES`, `MACHINE LEARNING`

- [ ] **AWS Amplify & Amazon API Gateway** — Full-stack web/mobile app build framework and API management (REST, HTTP, WebSocket APIs, Throttling, API Keys, Authorizers).
- [ ] **AWS Device Farm & Amazon Pinpoint** — Mobile app testing and customer engagement messaging.
- [ ] **Amazon Elastic Transcoder** — Media file transcoding for mobile/web playback.
- [ ] **Managed AI/ML Services** — Amazon Comprehend (NLP), Amazon Forecast (TimeSeries), Amazon Fraud Detector, Amazon Kendra (Enterprise Search), Amazon Lex (Chatbots), Amazon Polly (Text-to-Speech), Amazon Rekognition (Computer Vision), Amazon SageMaker (ML models), Amazon Textract (Document OCR), Amazon Transcribe (Speech-to-Text), Amazon Translate.
- [ ] 🎯 *Day 17 Review*: Identify specific AI service for business scenario questions without requiring custom ML model building.

---

### 📅 Day 18: Architectural Patterns & Scenario Deep Dives
**Focus**: Scenario-based decision making aligned with SAA-C03 exam domains.  
**Framework**: AWS Well-Architected Framework

- [ ] **Design for High Availability & Disaster Recovery** — Multi-AZ vs Multi-Region, RTO (Recovery Time Objective) vs RPO (Recovery Point Objective), Backup & Restore, Pilot Light, Warm Standby, Multi-Site Active-Active.
- [ ] **Design Secure Architectures** — Least privilege access, data protection at rest and in transit, defense-in-depth network design.
- [ ] **Design Resilient Architectures** — Decoupled architectures, failover strategies, self-healing systems via ASG and ELB.
- [ ] **Design High-Performing Architectures** — Caching strategies, read replicas, serverless computing, storage performance optimization.
- [ ] **Design Cost-Optimized Architectures** — Right-sizing instances, lifecycle rules, serverless architectures, savings plans.
- [ ] 🎯 *Day 18 Review*: Solve 20 scenario-based questions focusing on RTO/RPO requirements.

---

### 📅 Day 19: Full-Length Practice Exam 1 & Weak Area Drills
**Focus**: Exam simulation and thorough gap analysis.

- [ ] **Practice Exam 1 (65 Questions / 130 Mins)** — Simulating timed environment without reference materials.
- [ ] **Score Analysis & Question Audit** — Categorize incorrect answers by AWS Domain/Category.
- [ ] **Handbook Reference Check** — Re-read handbook sections corresponding to missed questions.
- [ ] **Flashcard & Cheat Sheet Review** — Review service limits, default timeouts, and metric intervals.
- [ ] 🎯 *Day 19 Milestone*: Target Score ≥ 80% on practice exam.

---

### 📅 Day 20: Full-Length Practice Exam 2, Final Checklist & Exam Readiness
**Focus**: Final readiness check, key service comparisons, and exam mindset.

- [ ] **Practice Exam 2 (65 Questions / 130 Mins)** — Final full-length exam simulation.
- [ ] **Review High-Frequency Exam Distinguishers**:
  - SQS Standard vs FIFO vs SNS Topic vs EventBridge
  - Aurora Global Database vs RDS Read Replica vs DynamoDB Global Tables
  - ALB vs NLB vs Global Accelerator vs CloudFront
  - EBS Snapshots vs EFS Backups vs Storage Gateway
  - KMS CMK vs Secrets Manager vs SSM Parameter Store
- [ ] **Exam Day Strategy Review** — Time management (2 mins per question), flagging strategy, process of elimination.
- [ ] 🎯 *Day 20 Milestone*: **Ready to conquer the AWS Certified Solutions Architect Associate (SAA-C03) Exam! 🚀**

---

## 💡 Daily Study Routine & Checklist Tip
1. Read the specific service section in the [AWS Solution Architect Handbook.pdf](file:///d:/Interview/SAA/AWS%20Solution%20Architect%20Handbook.pdf).
2. Note key **Exam Tips**, **Use Cases**, and **Architectural Trade-offs**.
3. Check off each completed service using `[x]`.
