<div align="center">

  <a href="https://github.com/Stefsek">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=900&lines=Mr.+Anderson...;Never+send+a+human+to+do+a+machine%27s+job;You+hear+that%3F;That+is+the+sound+of+inevitability;You%27re+empty;So+are+you;If+you+can%27t+beat+us;Then+join+us;The+best+thing+about+being+me;There%27s+so+many+me%27s" />
  </a>

</div>

---

```bash
$ ./identify --target stefsek
[+] Establishing secure shell to host: github.com ................. OK
[+] Bypassing firewall ............................................ OK
[+] Decrypting profile ............................................ OK

  ╔════════════════════════════════════════════════════════════════════╗
  ║  NAME     : Stefanos Sekis                                         ║
  ║  ROLE     : Data Engineering  //  AWS Cloud Architecture           ║
  ║  FOCUS    : Real-Time Data Pipelines  //  LLM Integration          ║
  ║  EDU      : MSc Big Data Analytics — University of Derby        ║
  ║  STATUS   : ONLINE  ▮▮▮▮▮▮▮▮▮▮  100%                               ║
  ╚════════════════════════════════════════════════════════════════════╝
```

---

## `> cat /home/stefsek/about_me.md`

```markdown
# Hi, I'm Stefanos Sekis 👋

I'm a Data Engineer with hands-on experience building scalable
data pipelines and cloud-native solutions. I have architected
comprehensive ETL workflows, real-time data ingestion systems,
and LLM-powered solutions using AWS services.
```

---

## `> inspect /opt/stefsek/tech_stack/`

```bash
stefsek@matrix:~$ ls -la /opt/stefsek/tech_stack/
drwxr-xr-x  stefsek  staff   aws_services/
drwxr-xr-x  stefsek  staff   infrastructure_as_code/
drwxr-xr-x  stefsek  staff   languages/
drwxr-xr-x  stefsek  staff   databases/
drwxr-xr-x  stefsek  staff   frameworks_and_tools/

stefsek@matrix:~$ cat aws_services/*
▸ Lambda             ▸ Step Functions     ▸ Glue
▸ Kinesis            ▸ EventBridge        ▸ S3
▸ RDS                ▸ ECS                ▸ DMS
▸ DynamoDB           ▸ Secrets Manager    ▸ CloudWatch
▸ Bedrock

stefsek@matrix:~$ cat infrastructure_as_code/*
▸ CloudFormation     ▸ AWS CDK

stefsek@matrix:~$ cat languages/*
▸ Python             ▸ SQL

stefsek@matrix:~$ cat databases/*
▸ Amazon Redshift    ▸ PostgreSQL         ▸ MongoDB            ▸ DynamoDB

stefsek@matrix:~$ cat frameworks_and_tools/*
▸ FastAPI            ▸ LangChain          ▸ LangGraph
▸ Streamlit          ▸ Git
```

---

## `> cat ~/projects/*.md`

```
╔══════════════════════════════════════════════════════════════════════╗
║  ▶ AWS Ticket Management System                    [ HIGHLIGHTED ]   ║
║    MSc Thesis · serverless event-driven ticketing on AWS             ║
╚══════════════════════════════════════════════════════════════════════╝
```

`▸ repo`        → [github.com/Stefsek/AWS-TicketManagementSystem](https://github.com/Stefsek/AWS-TicketManagementSystem)

`▸ stack`       → AWS Lambda · Kinesis · DynamoDB · Step Functions · S3 · AWS CDK · SNS · LangChain

`▸ description` → An event-driven serverless ticketing system that processes support requests in real-time. Incoming tickets are ingested through Kinesis Data Streams and orchestrated by Step Functions. Each ticket undergoes sentiment analysis with Amazon Comprehend, followed by AI-generated responses using Bedrock LLMs via Lambda. Ticket metadata is stored in DynamoDB for fast retrieval, while complete records are archived in S3. SNS handles real-time notifications, and AWS Glue performs ETL operations to load data into Redshift for analytics. CloudWatch Alarms monitor the entire pipeline for failures, ensuring reliable ticket processing.

```
╔══════════════════════════════════════════════════════════════════════╗
║  ▶ Weather App                                         [ SHIPPED ]   ║
║    Real-time city weather dashboard with interactive map             ║
╚══════════════════════════════════════════════════════════════════════╝
```

`▸ repo`        → [github.com/Stefsek/weatherWebApp-gsd](https://github.com/Stefsek/weatherWebApp-gsd)

`▸ stack`       → Python 3.13 · Streamlit · Open-Meteo API · Folium · UV

`▸ description` → A single-page weather dashboard that delivers real-time conditions for any searched city, including temperature with °C/°F toggle, humidity, wind speed, and wind direction. Uses Open-Meteo's geocoding and forecast APIs with response caching to reduce redundant calls. Features an interactive Folium map and a modular architecture separating services, models, and utilities.

```
╔══════════════════════════════════════════════════════════════════════╗
║  ▶ ReflectionAgent                                     [ SHIPPED ]   ║
║    Iterative prompt engineering with LangGraph self-critique         ║
╚══════════════════════════════════════════════════════════════════════╝
```

`▸ repo`        → [github.com/Stefsek/reflection-agent](https://github.com/Stefsek/reflection-agent)

`▸ stack`       → Python 3.13.5+ · LangGraph · LangChain · Google Gemini API · Pydantic · LangSmith

`▸ description` → An agentic prompt engineering system implementing the reflection pattern where AI models examine and improve their own outputs iteratively. Uses a two-node LangGraph workflow (Generation + Reflection) with structured Pydantic outputs, comprehensive token tracking, and LangSmith observability. Each iteration incorporates feedback to progressively refine prompts, addressing edge cases, safety, and user experience. Demonstrated with a Wi-Fi troubleshooting chatbot that evolved from basic framework to production-ready prompt across 4 iterations. Ideal for technical documentation, customer support automation, requirements analysis, and complex content generation where quality matters more than speed.

---

## `> cat ~/projects/in_progress.md`

```
╔══════════════════════════════════════════════════════════════════════╗
║  ▶ RAG Pipeline                                    [ IN PROGRESS ]   ║
║    Currently implementing                                            ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

## `> connect --user stefsek`

```bash
$ ./connect.sh
[+] Establishing secure handshake .................... OK
[+] Authentication verified .......................... OK
[+] Channel open. Awaiting transmission.
```

`▸ linkedin`    → [linkedin.com/in/stefanos-sekis](https://www.linkedin.com/in/stefanos-sekis/)

---

```bash
[+] Transmission complete.
[+] Closing channel .................................. OK

  "Goodbye, Mr. Anderson."
```
