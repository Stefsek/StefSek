<div align="center">
  
  # Hi, I'm Stefanos Sekis 👋
  
  ### Data Engineering | AWS Cloud Architecture | Real-Time Data Pipelines | LLM Integration
  
  🎓 MSc Big Data Analytics (University of Derby)
  
  <a href="https://www.linkedin.com/in/stefanos-sekis/"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
  
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

### [Weather App - Real-Time City Weather with Interactive Map](https://github.com/yourusername/weather-app)
A dark-themed weather dashboard built with Streamlit and powered by the free Open-Meteo API
- **Tech Stack:** Python 3.13, Streamlit, Open-Meteo API, Folium, UV
- **Description:** A single-page weather dashboard that delivers real-time conditions for any searched city, including temperature with °C/°F toggle, humidity, wind speed, and cardinal wind direction. Uses Open-Meteo's geocoding and forecast APIs (no API key required) with response caching to reduce redundant calls. Features an interactive Folium map and a modular src/ architecture separating services, models, and utilities.

### [ReflectionAgent - Iterative Prompt Engineering with Self-Critique](https://github.com/Stefsek/reflection-agent)
LangGraph-based AI agent that generates high-quality prompts through automated self-critique 
and refinement cycles.
- **Tech Stack:** Python 3.13.5+, LangGraph, LangChain, Google Gemini API, Pydantic, LangSmith
- **Description:** Description: An agentic prompt engineering system implementing the reflection pattern where AI models examine and improve their own outputs iteratively. Uses a two-node LangGraph workflow (Generation + Reflection) with structured Pydantic outputs, comprehensive token tracking, and LangSmith observability. Each iteration incorporates feedback to progressively refine prompts, addressing edge cases, safety, and user experience. Demonstrated with a Wi-Fi troubleshooting chatbot that evolved from basic framework to production-ready prompt across 4 iterations. Ideal for technical documentation, customer support automation,requirements analysis, and complex content generation where quality matters more than speed.

---

## Currently Implementing

- **RAG pipeline**