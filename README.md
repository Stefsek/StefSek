<div align="center">
  
  # Hi, I'm Stefanos Sekis 👋
  
  ### Data Engineering | AWS Cloud Architecture | Real-Time Data Pipelines | LLM Integration
  
  🎓 MSc Big Data Analytics (University of Derby)
  
  <a href="https://www.linkedin.com/in/stefanos-sekis/"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
  <a href="https://github.com/Stefsek"><img src="https://skillicons.dev/icons?i=github" /></a>
  
</div>

---

## About Me

I'm a Data Engineer with hands-on experience building scalable data pipelines and cloud-native solutions. I have architected comprehensive ETL workflows, real-time data ingestion systems, and LLM-powered solutions using AWS services.

---

## Technical Stack

### AWS Services

<p>
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" alt="Lambda"/>
  <img src="https://img.shields.io/badge/Step_Functions-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Step Functions"/>
  <img src="https://img.shields.io/badge/Glue-8C4FFF?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Glue"/>
  <img src="https://img.shields.io/badge/Kinesis-8C4FFF?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Kinesis"/>
  <img src="https://img.shields.io/badge/EventBridge-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white" alt="EventBridge"/>
  <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" alt="S3"/>
  <img src="https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white" alt="RDS"/>
  <img src="https://img.shields.io/badge/ECS-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white" alt="ECS"/>
  <img src="https://img.shields.io/badge/DMS-527FFF?style=for-the-badge&logo=amazonaws&logoColor=white" alt="DMS"/>
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white" alt="DynamoDB"/>
  <img src="https://img.shields.io/badge/Secrets_Manager-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Secrets Manager"/>
  <img src="https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white" alt="CloudWatch"/>
  <img src="https://img.shields.io/badge/Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Bedrock"/>
</p>

### Infrastructure as Code
![CloudFormation](https://img.shields.io/badge/CloudFormation-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Databases & Data Warehouses
![Amazon Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

### Frameworks & Tools
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Highlighted Projects

### [AWS Ticket Management System](https://github.com/Stefsek/AWS-TicketManagementSystem)
MSc Thesis project implementing a serverless ticketing system using AWS services
- **Tech Stack:** AWS Lambda, Kinesis, DynamoDB, Step Functions, S3, AWS CDK, SNS, LangChain
- **Description:** An event-driven serverless ticketing system that processes support requests in real-time. Incoming tickets are ingested through Kinesis Data Streams and orchestrated by Step Functions. Each ticket undergoes sentiment analysis with Amazon Comprehend, followed by AI-generated responses using Bedrock LLMs via Lambda. Ticket metadata is stored in DynamoDB for fast retrieval, while complete records are archived in S3. SNS handles real-time notifications, and AWS Glue performs ETL operations to load data into Redshift for analytics. CloudWatch Alarms monitor the entire pipeline for failures, ensuring reliable ticket processing.

---

## Recent Projects

### [FastMCP Servers - Development Workflow Automation](https://github.com/Stefsek/my-fastmcp-servers)
Collection of Model Context Protocol (MCP) servers that enhance AI coding assistants with specialized development tools
- **Tech Stack:** Python 3.13.5+, FastMCP, Git, Commitlint, MCP Protocol, JSON
- **Description:** A suite of MCP servers that extend AI coding assistants (Claude Code, Gemini CLI, GitHub Copulot) with specialized development capabilities. The Conventional Commits Server analyzes staged git changes in real-time, loads conventional commit guidelines from local markdown files, generates commit type recommendations based on code diffs, and validates messages against industry standards using commitlint integration. The Python Code Documentation Server provides comprehensive Google-style docstring guidelines for modules, classes, functions, and inline comments, enabling AI assistants to automatically generate well-documented Python code following industry best practices. Both servers use FastMCP framework for seamless integration, support stdio transport protocol for local deployment, and return structured JSON responses with error handling. The system demonstrates practical implementation of the MCP protocol for developer tool automation, reducing context switching and enforcing code quality standards directly within AI-assisted workflows.

---

## Currently Implementing

- **RAG pipeline**
- **Reflection agent**
