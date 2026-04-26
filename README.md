<div align="center">

  <a href="https://github.com/Stefsek">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=900&lines=Mr.+Anderson...;Never+send+a+human+to+do+a+machine%27s+job;You+hear+that%3F;That+is+the+sound+of+inevitability;You%27re+empty;So+are+you;If+you+can%27t+beat+us;Then+join+us;The+best+thing+about+being+me;There%27s+so+many+me%27s" />
  </a>

</div>

---

## `> cat ~/whoami.yaml`

```yaml
role:    Data Engineering // AWS Cloud Architecture
focus:   Real-Time Data Pipelines // LLM Integration
edu:     MSc Big Data Analytics — University of Derby
status:  ONLINE ▮▮▮▮▮▮▮▮▮▮ 100%
```

---

## `> cat ~/about_me.md`

```markdown
I'm a Data Engineer with hands-on experience building scalable
data pipelines and cloud-native solutions. I have architected
comprehensive ETL workflows, real-time data ingestion systems,
and LLM-powered solutions using AWS services.
```

---

## `> cat ~/stack.yaml`

```yaml
aws_services:
  - Lambda          - Step Functions   - Glue
  - Kinesis         - EventBridge      - S3
  - RDS             - ECS              - DMS
  - DynamoDB        - Secrets Manager  - CloudWatch
  - Bedrock

infrastructure_as_code:
  - CloudFormation  - AWS CDK

languages:
  - Python          - SQL

databases:
  - Amazon Redshift - PostgreSQL       - MongoDB      - DynamoDB

frameworks_and_tools:
  - FastAPI         - LangChain        - LangGraph
  - Streamlit       - Git
```

---

## `> tail -n +1 ~/projects/*.md`

```
==> aws-ticket-management.md <==
status:  [ HIGHLIGHTED ]
about:   MSc Thesis · serverless event-driven ticketing on AWS
stack:   AWS Lambda · Kinesis · DynamoDB · Step Functions · S3 · AWS CDK · SNS · LangChain

An event-driven serverless ticketing system that processes support requests in real-time.
Incoming tickets are ingested through Kinesis Data Streams and orchestrated by Step Functions.
Each ticket undergoes sentiment analysis with Amazon Comprehend, followed by AI-generated
responses using Bedrock LLMs via Lambda. Ticket metadata is stored in DynamoDB for fast
retrieval, while complete records are archived in S3. SNS handles real-time notifications,
and AWS Glue performs ETL operations to load data into Redshift for analytics. CloudWatch
Alarms monitor the entire pipeline for failures, ensuring reliable ticket processing.
```

`▸ repo` → [github.com/Stefsek/AWS-TicketManagementSystem](https://github.com/Stefsek/AWS-TicketManagementSystem)

```
==> weather-app.md <==
status:  [ SHIPPED ]
about:   Real-time city weather dashboard with interactive map
stack:   Python 3.13 · Streamlit · Open-Meteo API · Folium · UV

A single-page weather dashboard that delivers real-time conditions for any searched city,
including temperature with °C/°F toggle, humidity, wind speed, and wind direction. Uses
Open-Meteo's geocoding and forecast APIs with response caching to reduce redundant calls.
Features an interactive Folium map and a modular architecture separating services, models,
and utilities.
```

`▸ repo` → [github.com/Stefsek/weatherWebApp-gsd](https://github.com/Stefsek/weatherWebApp-gsd)

```
==> reflection-agent.md <==
status:  [ SHIPPED ]
about:   Iterative prompt engineering with LangGraph self-critique
stack:   Python 3.13.5+ · LangGraph · LangChain · Google Gemini API · Pydantic · LangSmith

An agentic prompt engineering system implementing the reflection pattern where AI models
examine and improve their own outputs iteratively. Uses a two-node LangGraph workflow
(Generation + Reflection) with structured Pydantic outputs, comprehensive token tracking,
and LangSmith observability. Each iteration incorporates feedback to progressively refine
prompts, addressing edge cases, safety, and user experience. Demonstrated with a Wi-Fi
troubleshooting chatbot that evolved from basic framework to production-ready prompt across
4 iterations.
```

`▸ repo` → [github.com/Stefsek/reflection-agent](https://github.com/Stefsek/reflection-agent)

---

## `> cat ~/connect.txt`

```
linkedin → linkedin.com/in/stefanos-sekis
email    → schekies@outlook.com.gr
```

---

## `> exit`

```bash
logout
Connection to github.com closed.

  "Goodbye, Mr. Anderson."
```
