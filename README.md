# BankIntegrationC4ArchitectureModel

This repository contains a proposal for a bank integration architecture applying the C4 model, focused on enabling the coexistence of a legacy core with a new digital core.

---

## 📊 Diagrams C4

1. **Context Diagram** – Contains a general overview of the banking ecosystem, including users (web/mobile), API Gateway, core systems (legacy and digital), and interaction with external systems such as Open Banking, fraud and risk platforms.

2. **Containers Diagram** – Describes the architecture of applications and services, including microservices, API Gateway, event bus, identity provider, and integration with external systems and core banking.

3. **Components Diagram** – Explains the internal structure of a microservice (based on .NET + Clean Architecture), including the use of CQRS, domain events, repositories and handlers.

4. **Deployment Diagram** – Shows the cloud infrastructure in Azure, including containerized services, databases, monitoring, and multi-region strategy for high availability and disaster recovery.


## 🔄 Integration & Architecture Patterns

- API Gateway  
- Event-Driven Architecture  
- Saga Pattern  
- CQRS  
- Anti-Corruption Layer  


## 🧠 Domain Model

The architecture is aligned with BIAN domains:

- Customer Management  
- Account Management  
- Payments  
- Fraud Detection  
- Risk Management  

## 🔐 Security

- OAuth2 + OpenID Connect  
- Identity Provider (Azure AD B2C)  
- TLS encryption (in transit)  
- Data encryption (at rest)  
- Zero Trust Architecture  
- API Security (rate limiting, throttling)  

## ☁️ Technologies

- Microservices  
- Azure Container Apps  
- Azure PostgreSQL  
- Azure Cosmos DB  
- Azure API Management  
- API Gateway  
- .NET  
- Angular  
- Flutter  
- Docker  
- Event Bus (Service Bus / Kafka)  
- REST API  
- HTTPS  
- GitHub Actions (CI/CD)  
- Azure Monitor & Application Insights  

## 🚀 Migration Strategy

The migration approach is based on the **Strangler Fig Pattern**, allowing gradual decoupling and replacement of the legacy core.


## 📄 Documentation

Full document available in:

👉 `Documentation/Integration_Architecture_Bank_Core_C4.pdf`

---

## 👤 Author

👤 *Wilian Orlando Nieves Rumipulla*  
📅 *08/04/2026 *
