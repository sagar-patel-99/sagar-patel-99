# 👋 Hey there, I'm Sagar Patel

### 🚀 Software Engineer | Backend Specialist | Cloud & AI Enthusiast | M.S. @ San José State University

I specialize in designing scalable backend architectures, integrating intelligent systems with real-world applications, and building distributed microservices that drive performance and reliability. I enjoy taking complex problems and breaking them into elegant, production-ready solutions.

---

## 💼 Professional Experience

### 🔹 **Software Engineer Intern – Flex**
*May 2024 – October 2024 | Austin, TX*

**Project: 5S Automated Inspection System for Manufacturing Plants**

Worked on a real-world robotics and AI use-case that automates factory inspections using **MiR AMRs (Autonomous Mobile Robots)** and **Nvidia Jetson Nano**.

- 🧠 **AI/ML Integration**: Trained a custom **PyTorch-based SSD DetectNet** model with **CUDA** acceleration to detect compliance-related objects (e.g., safety signs, misplaced equipment).
- 🔄 **Asynchronous Data Pipeline**: Designed a multithreaded listener service that watches image directories, categorizes images using AI inference, then archives results into a **Windows-hosted Photo Inspect portal** via **SMB**.
- 🛰️ **GPS + PLC Sync**: Implemented a **GPS-based tracking system** for the AMR to confirm location accuracy before triggering a camera via PLCs (Programmable Logic Controllers).
- 🔐 **Audit & Monitoring**: Used the **ELK Stack (Elasticsearch, Logstash, Kibana)** to aggregate logs, analyze trends, and provide compliance traceability.
- 📄 **DevOps & Docs**: Documented technical flows in **Confluence** and integrated tasks with **JIRA**, improving transparency and collaboration.

> 📊 *Impact*: Reduced manual inspection efforts by 60%, increased defect detection accuracy by 30%, and sped up model updates by 40%.

---

### 🔹 **Software Developer – Shree Hari Info Solution**
*Oct 2021 – June 2023 | Ahmedabad, India*

#### 🛒 **Project 1: Shopping Platform**
A secure eCommerce platform with a powerful real-time backend and intuitive frontend.

- 🔐 **Authentication Overhaul**: Replaced legacy login with **Auth0 JWT-based authentication**, 2FA, and **role-based access control**.
- 🔍 **Search Engine**: Built an **Elasticsearch-powered search** that reduced query latency by 50%.
- 🔄 **Event-Driven Architecture**: Integrated **Google Pub/Sub** + **gRPC** to decouple services, optimize message passing, and reduce request overhead.
- 🛡️ **Encryption**: Strengthened password security using **SHA-256 + salting** and secured all data-in-transit with HTTPS.

> 🚀 *Result*: Increased platform scalability, improved fault tolerance, and reduced server load during peak shopping hours.

---

#### 🚗 **Project 2: Ride-Sharing Platform**
Designed a multi-city ride-matching platform with dynamic pricing and real-time tracking.

- 📍 **Geo-Matching Engine**: Developed a ride allocation engine using **Spring Boot**, **PostGIS**, **Redis Geo**, and **Neo4j**, reducing rider wait times by 80%.
- 💸 **Dynamic Surge Pricing**: Trained a **DeepLearning4J-based ML model** to dynamically adjust fares using **AWS Lambda**, improving pricing accuracy by 40%.
- 📡 **Live Tracking**: Integrated **WebSockets** for millisecond-precision driver location updates.
- 💰 **Stripe Integration**: Added secure, PCI-compliant payment flow with **Stripe API**.
- ⚙️ **CI/CD & Monitoring**: Used **GitHub Actions** for CI/CD and **Splunk** for real-time logs and alerting.

> 🔁 *Result*: Enabled fault-tolerant ride-matching across multiple cities, with 30% improvement in user retention and 25% reduction in ops support tickets.

---

## 🧠 Key Projects

### 🌐 **QuickHire** – Smart Job Platform for Candidates and Employers
*Tech: NextJS, ReactJS, MongoDB, Kafka, Redis, Power BI, AWS, Docker, K8s, Prometheus, Grafana, Spark, Hadoop, NLP, LLM, BERT*

A full-stack job portal that leverages **NLP and machine learning** to streamline job matching.

- 🔍 Built a **BERT-based semantic matcher** to score candidate–job fit with 80% precision.
- 💾 Handled batch processing via **Hadoop** and real-time data via **Kafka**.
- 🧠 Used **Apache Spark** on **AWS EMR** to retrain models using live data streams.
- 📊 Integrated **Power BI dashboards** to visualize job vacancies, applicant conversion rates, and hiring trends.
- 🧪 Developed and documented RESTful APIs using **Swagger**, conforming to OpenAPI specs.
- 🛠️ Deployed scalable infrastructure with **Docker**, **Kubernetes**, and **Terraform**.

> 📈 *Impact*: Significantly improved applicant relevance, boosted hiring efficiency, and reduced manual screening time for recruiters.

---

### 📄 **DocuQuery** – AI Assistant for Document Search
*Tech: Python, Streamlit, FAISS, Langchain, OpenAI*

A document analysis tool that enables natural language queries on PDF and CSV files.

- ⚡ Used **Langchain + OpenAI’s LLMs** for intelligent Q&A over structured/unstructured files.
- 🔍 Integrated **FAISS** for vector similarity search, achieving 90% NLP accuracy.
- 🧵 Created an intuitive **Streamlit UI**, enabling users to upload and interact with files in real time.

> 📊 *Result*: Reduced document review time by 50%, with significant improvements in semantic accuracy.

---

### 💬 **Real-Time Chat App**
*Tech: Node.js, Socket.io, Express*

Built a modern messaging app with blazing-fast response times.

- 🔄 Used **Socket.io** for bidirectional messaging, reducing latency by 25%
- ⚙️ Event-driven backend ensured efficient scaling under multiple concurrent connections

> 📡 *Impact*: Enabled seamless chat functionality suitable for customer support, collaboration, and internal tools.

---

### 🔗 **Socket Interoperability**
*Tech: Java, Python, C++*

Achieved seamless socket communication between three different languages.

- 🧵 Java: Used ThreadPool + enhanced exception handling for concurrency
- 🐍 Python: Managed threads with **ThreadPoolExecutor**, optimized encoding
- 💻 C++: Leveraged **POSIX sockets**, added sanitizers + static analysis for robust I/O

> 🤝 *Impact*: Demonstrated real-world protocol translation and system interoperability across tech stacks.

---

### 🧵 **FabScan** – IoT + Image Processing for Fabric Defect Detection
*Tech: Python, Android, Firebase, Raspberry Pi*

- 📸 Captured high-resolution fabric images using Raspberry Pi camera
- 🧠 Applied image processing to detect bubbles/defects at up to 5 psi
- 📲 Built Android app synced with **Firebase** for real-time updates
- 🕒 Cut manual inspection time by 70%, lowered production cost, and improved quality assurance.

---

## 🧰 Full Skillset

```yaml
Languages:
  - Java, Python, C++, Go, JavaScript, PHP, .NET, C, SQL, HTML, CSS, Android

Frameworks & Libraries:
  - Spring Boot, Node.js, React.js, Next.js, Streamlit, DeepLearning4J, BERT, Langchain, Swagger, Socket.io

Databases:
  - MongoDB, PostgreSQL, MySQL, Redis, DynamoDB, Neo4j, Firebase, ElasticSearch, ArangoDB, MS SQL

Cloud & DevOps:
  - AWS, GCP, Docker, Kubernetes, GitHub Actions, Jenkins, Terraform, CloudWatch

Monitoring & Tools:
  - Prometheus, Grafana, ELK Stack, Datadog, Splunk, Power BI, Tableau, JMeter, Postman, JIRA, Confluence

Messaging & Communication:
  - Apache Kafka, RabbitMQ, Google Pub/Sub, WebSockets, gRPC, SMB

Concepts:
  - Distributed Systems, Microservices, NLP, LLMs, Image Processing, IoT, CI/CD, SDLC, Data Structures & Algorithms
```

## 🔍 I'm currently focused on:
- Scalable backend services & microservices
- Intelligent systems (AI, ML, NLP, LLMs)
- Distributed systems & event-driven architectures
- Cloud DevOps (AWS, GCP, Docker, Kubernetes)

🎯 Always up for a good problem to solve — let’s connect, collaborate, and create something impactful.


## 🤝 Let's Connect

I'm always open to connecting with like-minded professionals, collaborators, and innovators!

If you're working on exciting projects in **AI/ML**, **backend engineering**, **distributed systems**, or **cloud-native architecture** — let's chat! I’m particularly interested in solving real-world problems through intelligent automation, scalable microservices, and efficient system design.

📫 Reach out via:
- 🔗 [LinkedIn](https://www.linkedin.com/in/sagar-patel-03/)
- 💻 [GitHub](https://github.com/sagar-patel-99)
- 📧 Email: patelsagaralpeshkumar@gmail.com

> 💡 Let's connect, explore new ideas, share knowledge, and build impactful solutions together!
