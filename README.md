# ⚖️ DIALM - Dynamic Infrastructure Availability with Load Management

> A cloud-based **dynamic load balancing system** built on AWS that intelligently distributes workloads across infrastructure, tracks availability at every organizational level, and delivers automated alerts to stakeholders.

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com)
[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io)
[![Cloud Computing](https://img.shields.io/badge/Topic-Cloud_%26_Load_Balancing-blue?style=for-the-badge)]()

---

## 🎯 Overview

DIALM (Dynamic Infrastructure Availability with Load Management) addresses a core challenge in cloud computing — **intelligent, real-time load distribution** across distributed infrastructure — while maintaining full visibility into server health from top to bottom of an organization's infrastructure hierarchy.

---

## ✨ Features

- ⚡ **Dynamic Load Balancing** - Automatically redistributes traffic based on real-time server availability and load metrics
- 🏗️ **Multi-level Infrastructure Tracking** - Monitors availability from top-level organization units down to individual server instances
- 📧 **Automated Notifications** - Generates and sends email alerts, OTP notifications, and system warnings to relevant stakeholders when thresholds are breached
- ☁️ **AWS Integration** - Built on AWS EC2 for scalable compute management
- 📊 **Load Analytics** - Tracks distribution patterns and historical load data
- 🔔 **Event-Driven Alerts** - Proactive notification system for availability changes

---

## 🏗️ Architecture

```
         ┌─────────────────────────────────┐
         │        DIALM Core Engine        │
         │  (Load Monitoring & Balancing)  │
         └──────────┬──────────────────────┘
                    │
         ┌──────────▼──────────┐
         │   AWS EC2 Fleet     │
         │  (Server Pool)      │
         └──────────┬──────────┘
                    │
     ┌──────────────▼─────────────────┐
     │      Availability Tracker      │
     │  (Org → Division → Server)     │
     └──────────────┬─────────────────┘
                    │
     ┌──────────────▼─────────────────┐
     │    Notification Engine          │
     │  (Email / OTP / Alerts)        │
     └────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Java, Spring Boot |
| Cloud | AWS (EC2, S3) |
| Notifications | JavaMail / SMTP, OTP generation |
| Build | Maven |

---

## 🚀 Getting Started

### Prerequisites
- Java 11+
- Maven 3.6+
- AWS account (EC2 access)
- SMTP credentials for email notifications

### Build & Run

```bash
# Clone the repository
git clone https://github.com/dhruvalvaishnav/DIALM.git
cd DIALM

# Configure AWS and SMTP settings
cp src/main/resources/application.properties.example src/main/resources/application.properties
# Edit application.properties with your credentials

# Build
mvn clean install

# Run
mvn spring-boot:run
```

---

## 🎓 Academic Background

This project was developed as part of a **B.E. Information Technology** final year project at L J Institute of Engineering & Technology (GTU), focusing on cloud resource optimization and AWS infrastructure management.

**Research focus:** Efficient load distribution strategies for public cloud environments, with dynamic reallocation based on real-time availability metrics.

---

## 👨‍💻 Author

**Dhruval Vaishnav** - Senior Backend Engineer | Java · AWS · Distributed Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/dhruvalvaishnav)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=for-the-badge&logo=google-chrome)](https://dhruvalvaishnav.github.io/dhruvalvaishnav/)

---

⭐ Star this repo if you're interested in cloud infrastructure and load balancing!
