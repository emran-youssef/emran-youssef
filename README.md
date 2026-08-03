<h1 align="center">Hi, I'm Emran 👋</h1>
<h3 align="center">
Backend Developer • Java • Spring Boot 
</h3>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&center=true&vCenter=true&width=650&lines=Building+Scalable+Backend+Applications;Java+%7C+Spring+Boot+%7C+Kafka+%7C+Docker;REST+APIs+%7C+Microservices+%7C+Secure+Applications" />
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/emran-al-khaleel-1b86b0343">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me
Backend developer passionate about building scalable, secure, and maintainable applications using the Java ecosystem, with a focus on Spring Boot and FinTech solutions.

---

## 🛠️ Tech Stack

**Backend Development**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

**Architecture & Messaging**

![Microservices](https://img.shields.io/badge/Microservices-4285F4?style=for-the-badge)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Databases & Data Management**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JPA](https://img.shields.io/badge/JPA/Hibernate-59666C?style=for-the-badge)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

**Development & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🚀 Featured Projects

---

# 🛡️ Transactions Monitoring Platform

<p align="center">
  <a href="https://github.com/emran-youssef/transactions_monitoring">
    <img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

<p align="center">
A Spring Boot microservices project for detecting suspicious transactions, built around Kafka for service-to-service communication and a configurable rule engine.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Status-In_Progress-yellow?style=flat-square"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white"/>
</p>

### Architecture Flow

Transaction Service → Kafka → Rule Engine → Case Management → Audit Service


### Engineering Highlights

- 🧠 Rule engine implemented with the Strategy pattern, so new detection rules can be added without changing existing ones
- 🔁 Kafka consumers designed to be idempotent, to avoid double-processing on message redelivery
- 📤 Outbox pattern used for publishing events, to reduce the risk of lost or duplicate messages between services
- 🔐 JWT-based authentication with role-based access control
- 🗄️ Schema changes tracked with Flyway across services
- 🐳 Local development environment set up with Docker Compose

**Technical Focus**

`Microservices` `Event-Driven Architecture` `Rule-Based Detection`

<br>

---

# ⚙️ Backend Engineering Projects

## 💳 Digital Wallet

<p align="center">
  <a href="https://github.com/emran-youssef/digital_wallet_spring">
    <img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

<p align="center">
A backend service that simulates basic digital wallet operations — accounts, balances, and transfers — with JWT-based auth.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

### Engineering Highlights

- 🔐 JWT-based authentication and authorization
- 💰 Transfer logic that accounts for concurrent balance updates
- 🏗️ Layered architecture (Controller → Service → Repository)
- ✅ Centralized exception handling and input validation
- 📜 Transaction history stored per account

**Technical Focus**

`Secure APIs` `Backend Architecture`

<br>

---

## 📊 Log Monitoring & Alert System

<p align="center">
  <a href="https://github.com/emran-youssef/log_monitoring_alert_system">
    <img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

<p align="center">
An event-driven system that processes application logs and generates alerts based on configurable rules. Built during my Eastnets internship, and later extended into the Transactions Monitoring Platform above.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

### Engineering Highlights

- 📨 Kafka-based asynchronous log processing
- 🚨 Alert generation based on configurable rules
- 🔄 Event-driven design separating ingestion from alerting

**Technical Focus**

`Event Streaming` `Monitoring Systems`

<br>

---

# 🏠 UniShare

<p align="center">
<a href="https://github.com/emran-youssef/unishare_backend">
<img src="https://img.shields.io/badge/Backend-181717?style=for-the-badge&logo=github"/>
</a>
<a href="https://github.com/emran-youssef/UniShare_Frontend">
<img src="https://img.shields.io/badge/Frontend-181717?style=for-the-badge&logo=github"/>
</a>
</p>

<p align="center">
A full-stack rental platform where university students can list and rent everyday items from each other.
</p>

<p align="center">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

### Features

- 🔐 Authentication and user management
- 🏠 Listing creation and discovery, including meetup-location selection
- 📅 Booking workflow with a simulated payment method
- ⭐ Review system and messaging between users
- 🧬 Zod schemas on the frontend and MapStruct mapping on the backend for consistent request/response shapes

**Technical Focus**

`Full-Stack Development` `REST APIs`

<br>

---

## 🏗️ Architecture & Engineering Practices

- Microservices architecture with service isolation and independent responsibilities
- Layered backend architecture (Controller → Service → Repository)
- REST API design with request validation and clean API contracts
- Database modeling with JPA/Hibernate
- Event-driven communication using Apache Kafka
- Database versioning and migration management with Flyway
- Containerized development environments using Docker Compose
- Secure API development with Spring Security and JWT


