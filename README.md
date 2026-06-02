##  About Me

I have interests spanning multiple domains:

- **Backend Development** - Building server-side applications
- **AI & Machine Learning** - Exploring neural networks and data science
- **Security** - Interested in secure coding practices and infrastructure security
- **Cloud Technologies** - AWS, Azure, and cloud-native solutions
- **DevOps** - Infrastructure as Code, containerization, K8s and CI/CD


## Tech Stack

### **Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

 ### **Backend & Frameworks**
- **Java**: Spring Boot, JUnit5, Hibernate
- **Python**: FastAPI
- **Node.js**: Express.js
- **Databases**: MySQL, PostgreSQL, MongoDb

### **Frontend**
- **Angular** | **React** | **TypeScript**

### **AI & Machine Learning**
- **Python**: TensorFlow, PyTorch, Hugging Face, Scikit-learn

### **Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### **Observability & Monitoring**

- #### **Metrics & Dashboarding**
    - **Prometheus** - Metrics collection and time-series database
    - **Grafana** - Visualization and alerting dashboards

- #### **Logging & Analytics**
    - **Elasticsearch** - Centralized log aggregation and search
    - **Kibana** - Log visualization and analysis

- #### **Distributed Tracing**
    - **OpenTelemetry** - Instrumentation for traces, metrics, and logs
    - **Jaeger** - Trace visualization


 ## Projects

- **[Social network](https://github.com/knetsov91/social-network)** - A social network backend split into seven Spring Boot 3 microservices using Java 21. Services register with Netflix Eureka and all traffic routes through Spring Cloud Gateway with JWT authentication. Users can post, like, follow, and chat in real time — Kafka handles async events between services, while STOMP over WebSocket powers live chat and presence (online/offline). Redis is used for caching and presence tracking, with each service having own database — PostgreSQL for users and posts, MySQL for relationships, and MongoDB for chat messages. Unit tests are covered with JUnit, and CI runs on GitHub Actions. Observability is implemented using Prometheus, Grafana and OpenTelemetry.

- **[E-shop](https://github.com/knetsov91/e-shop)** - Backend e-commerce REST API with three Spring Boot microservices, each with its own database. Order service implements CQRS — PostgreSQL for writes, MongoDB for reads, synced via Kafka. Services self-register with Consul and Traefik acts as the API gateway routing requests to the appropriate service. Unit tests with JUnit 5 and Mockito. Two Docker Compose environments for dev and prod, with observability in prod — Prometheus, Grafana and ELK log aggregation.

- **[Restaurant management](https://github.com/knetsov91/restaurant)** - Restaurant management system built with Java 17 and Spring Boot. Works alongside a separate order-service, communicating synchronously via OpenFeign with scheduled polling. Access control is handled by Spring Security 6 with role-based permissions. Data is persisted in PostgreSQL through Hibernate/Spring Data JPA. Covered by unit, integration, and web layer tests, with a GitHub Actions pipeline running on every push and dockerized for deployment.
