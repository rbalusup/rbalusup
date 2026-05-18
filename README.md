# Rajasekhar Balusupati — Technology Leader

🚀 Backend • AI/ML Engineer • Data • Distributed Systems • Infra • Real-Time Systems • Cloud-Native

📍 Tracy, CA 
📧 rbalusupati777@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rbalusupati) | [GitHub](https://github.com/rbalusup)

---

## 🧠 About Me

- I am an accomplished technology leader with deep expertise in designing and delivering cutting-edge solutions that transform business operations and drive innovation. 
- I specialize in building distributed software architectures that scale to meet high transaction volumes, integrating technologies such as microservices, event-driven architectures, and Kafka-based streaming platforms. My designs ensure fault tolerance, high availability, and seamless integration, enabling businesses to adapt to evolving demands while safeguarding mission-critical operations.
- I excel in creating robust data pipelines, integrating advanced analytics, and driving intelligent decision-making through actionable insights.
- With extensive experience in enterprise technology modernization, distributed software architectures, and AI-driven systems, I have consistently delivered scalable, secure, and high-impact outcomes across industries.
- Proficient in designing scalable event-driven systems using AWS/GCP services, developing high-performance microservices with technologies like Java, Kotlin, Golang, Python, Spring Boot, Kafka, and integrating advanced AI tools including LLMs for data extraction and analysis.
- Proven expertise building production-grade intelligent document processing platforms and financial research tools for institutional investors. Deep technical proficiency in generative AI (Claude, AWS Bedrock), advanced LLM orchestration, and AWS service integration.
- My work spans the development of intelligent systems powered by AI/ML, leveraging technologies like LLMs to enhance user experiences and optimize operational workflows. I have architected solutions that integrate RAG frameworks to tackle complex challenges and improve efficiency.
- I'm currently energized by the potential of generative AI and agentic workflows. My focus is on building AI-powered products that drive meaningful change, provide business value, and push technological boundaries.

---

## 🛠️ Skills

- **Programming Languages:** Java, Kotlin, Python3, Golang, JavaScript, TypeScript, SQL
- **Microservices Frameworks(Backend):** OpenAPI, SpringBoot, Micronaut, FastAPI, Gin, Express.js (SOAP, RESTful, GraphQL, gRPC)
- **Data Serialization/Interchange Formats:** XML, JSON, Avro, Protobuf, FlatBuffers, Parquet, ORC
- **Frontend:** React.js, TypeScript, Redux, TailwindCSS, Next.js
- **Databases:** Oracle, PostgreSQL, MySQL, DB2, MongoDB, Cassandra, Redis, DynamoDB, AWS RDS, Neo4J
- **Infra & DevOps:** Docker, Kubernetes, Terraform (IaC), Jenkins, GitHub Actions, GitLab, Drone, Spinnaker, Vault, Consul, Vagrant
- **AI/ML & Agentic:** Model Context Protocol (MCP), Agentic AI (Crew AI, Langgraph, Langchain), AWS Bedrock, Claude APIs, RAG Pipelines, PyTorch, TensorFlow, Vertex AI, Sagemaker AI, HuggingFace
- **AWS Services:** Lambda, EC2, API Gateway, S3, OpenSearch, Glue, Athena, Step Functions, DynamoDB, Bedrock, CloudWatch, KMS
- **Cloud & Big Data:** AWS, GCP, Azure, IBM, Snowflake, Databricks, Kafka, Spark, Hadoop, BigQuery
- **Middleware:** Apache/Confluent Kafka, Apache Spark, Apache Camel
- **Testing:** JUnit, Spock Framework, Kotest, K6, JMeter, Gatling
- **Observability:** Grafana, ELK, Prometheus, Splunk, Datadog
- **AI Tools:** Claude, Gemini, Cursor, CoPilot, Antigravity
- **Exploring:** Rust, Go, Web3, LLMs, Account Abstraction

---

## 💼 Professional Experience

### Centene Corporation @ APEX Systems LLC (Remote - Contract) Mar2025 – Feb2026
#### 🔹 Lead Application Engineer / Cloud Architect
##### 🚀 Intelligent Document Processing Platform
- Architected end-to-end serverless OCR document processing platform on AWS leveraging Lambda, Step Functions, EventBridge, and Textract to automate enrollment data extraction from healthcare PDFs
- Designed asynchronous multi-document processing, PDF boundary detection, and parallel execution; validated extracted data against ground truth datasets achieving 96% accuracy.
- Implemented multi-stage document transformation: PDF ingestion via email (AWS SES) → Textract OCR processing → image conversion → Claude Sonnet 3.7 entity extraction → Pydantic schema-based structuring → CSV template output with validation; integrated IaC (Terraform, CloudFormation) for reproducible drift-free environments across all deployment stages.
- Automated deployment via GitLab CI/CD pipelines with Docker Containerization and AWS ECR registry integration.
- Designed event-driven data persistence architecture using S3 for document storage, DynamoDB for metadata and audit logging, and VPC security endpoints for network isolation.
- Built real-time event streaming pipeline publishing granular events at each transformation stage to Confluent Cloud Kafka topics, synced to Snowflake for analytics visibility and compliance reporting; managed 1000+ daily document operations with production-grade reliability and observability.
- Implemented RAG framework using hierarchical document chunking strategies, AWS Titan embedding model to generate vector embeddings from chunked segments, and AWS OpenSearch vector database for persistent semantic storage and similarity-based retrieval; enabled intelligent contextual understanding for multi-agent workflows.
- Evolved platform from single-purpose enrollment processing to multi-agent (document classification, entity extraction & validation), object orchestration system using AWS Bedrock Knowledge Base with RAG semantic search capabilities; extended capabilities to hospital bills, claims processing, and general document workflows with vector-based retrieval.

### Franklin Templeton @ Blend360 LLC (Remote - Contract) Oct2024 – Feb2025
#### 🔹 Full Stack AI Engineer
##### 🚀 Financial Intelligence Platform (Investments)
- Built full-stack RAG summarization platform combining FastAPI backend (Python 3.12, CrewAI) with 5 specialized pipelines (ODD, Board, Research, PMSR, Putnam Trading) for MosaiQ compute and data platform;
- Engineered audio-enhanced RAG with AWS Transcribe speaker diarization and Claude 3.5 Sonnet via AWS Bedrock; developed evasion detection classifier using few-shot prompting with 9-category Q&A classification and risk scoring (1-10); persisted outputs in DynamoDB with style personalization and automated citations.
- Built full-stack Next.js 14/15, Typescript, GraphQL application with Redux Toolkit state management, RTK Query API layer, react-hook-form validation, and Tailwind CSS styling; worked on real-time WebSocket notifications, PDF/DOCX multi-format generation, and DynamoDB-backed ACL authorization with SAML SSO authentication for institutional-grade security.
- Deployed using AWS provided CI/CD (CodePipeline, CodeBuild, CodeDeploy) orchestrating FastAPI backend, Next.js frontend.

### Target Corporation (Sunnyvale, CA - Fulltime) Jun2015 – Aug2024
#### 🔹 Lead Software Engineer - Digital 🔹 Lead Software Engineer - Stores & Supply Chain
##### 🚀 Available to Promise (ATP) 🚀 Ship Methods (Guest Fulfillment) 🚀 Serialized Item Availability (Stores Mobile Inventory) 🚀 3rd Party Mobile Activations (Point of Sale) 
- Led the strategic transformation of Inventory & Allocation modules on Target.com from legacy IBM Sterling to a distributed, cloud-native architecture, enabling 5x throughput increase and reducing operational complexity.
- Engineered high-performance backend microservices using Java/Kotlin (SpringBoot/Micronaut), Go, and Python on GCP, containerized with Docker and orchestrated via Kubernetes to ensure auto scaling and high availability.
- Led the strategic re-architecture of the Connected Commerce Platform from AWS monoliths to hybrid GCP and event-driven architectures, generating $1B in revenue growth.
- Built 3+ production microservices in Go using Gin framework with concurrent goroutine-based request handlers, gRPC/Protocol Buffers for inter-service communication; Also engineered integration test data setup pipelines using Golang.
- Engineered CI/CD automation and infrastructure orchestration: certificate rotation, secret management, and infrastructure provisioning; and managed Jenkins→Drone→Spinnaker→Vela pipeline evolution.
- Designed distributed systems resilience patterns (circuit breakers, bulkheads, exponential backoff); architected multi-layer caching (Fastly CDN, Redis, Hazelcast) delivering sub-millisecond response times for P1 inventory and guest fulfillment APIs handling 1M+ concurrent member requests.
- Led Kafka transformation from Zookeeper+brokers to managed Confluent Cloud; designed Avro/Protobuf schema evolution; architected Kafka Streams-based real-time monitoring/alerting pipeline integration with Slack.
- Implemented reactive programming frameworks (RxJava, Spring WebFlux) and non-blocking I/O patterns across Java/Kotlin microservices; paired with comprehensive observability (Prometheus, Grafana, distributed tracing, logging) and synthetic monitoring (Runscope) for proactive incident detection. Built performance testing framework using JMeter & Gatling.
- Established enterprise-scale DevSecOps practices: automated vulnerability scanning (OWASP), static/dynamic code analysis (SAST/DAST), certificate management (PEM→JKS rotation), and Vault integration; led security vulnerability management and compliance across open-source dependencies.
- Led technology integration of acquired companies in stores & supply chain portfolio: established unified coding standards, integrated third-party mobile activations (AT&T, Consumer Cellular, Cricket), and trained engineers on cloud-native patterns.
- Built reusable libraries for rate limiting, distributed request tracing, and Prometheus/Grafana observability; adopted by 15+ teams with measurable impact (60% reduction in MTTR, 40% reduction in code duplication) enabling self-service deployment patterns across the organization.

### CipherCloud Inc (acquired by Lookout Inc)
#### 🔹 Software Development Manager / Technical Manager (Hyderabad, India - Fulltime) Jun2012 – May2015
##### 🚀 Management Console
- Directed the end-to-end development and delivery of a Management Console across Salesforce, ServiceNow, Box, and SuccessFactors, increasing customer engagement and reducing project delivery timelines through unified cloud management capabilities.
- Designed and deployed a responsive SPA using Twitter Bootstrap, BackboneJS, ReactJS, and Java.
- Led and developed a high-performing engineering team through strategic hiring, mentoring, performance evaluations, and career development programs, achieving increase in team productivity by and aligning ambitious growth objectives.

### Prokarma Inc (acquired by Concentrix Corporation)
#### 🔹 Technical Lead (Denver, CO | Omaha, NE | Hyderabad, India - Fulltime) Mar2006 – Jun2012
- **Clients:** Union Pacific Rail Roads (UPRR), DEX Media, Hughes Telematics Inc (Verizon Telematics)
- **Technical Stack:** Java, Spring, Hibernate, JavaScript, SOAP-based Webservices, JMS, CMS, IBM Mainframe

### Optimos Inc
#### 🔹 Sr. Java Consultant (Peewaukee, WI | Herndon, VA - Fulltime) Aug2004 – Feb2006
- **Clients:** GE Healthcare, Lafarge North America
- **Technical Stack:** Java, Struts, JSP, Oracle, Jasper Reports, JavaScript

---

## 🏆 Achievements/Certifications
- **Claude with Amazon Bedrock:** Anthropic
- **Building AI Agents and Agent Workflows (Langgraph, CrewAI, AutoGen & BeeAI):** IBM
- **Generative AI with Large Language Models:** Amazon Web Services, DeepLearning.AI
- **Machine Learning Specialization:** Stanford University, DeepLearning.AI
- **Certified Kubernetes Administrator (CKA):** CNCF/Linux Foundation.
- **Cloudera Certified Developer for Apache Hadoop (CCDH)**
- **Google Cloud Certified Professional Cloud Architect**
- **Certified Scrum Master (CSM):** Scrum Alliance.

---

## 📬 Let’s Connect!

Always open to exciting remote roles and collaborations.  
Feel free to reach out via [email](mailto:rbalusupati777@gmail.com).
