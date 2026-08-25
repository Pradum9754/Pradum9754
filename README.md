# 👋 Hi, I'm Pradum

### DevOps / DevSecOps Engineer | Azure | Terraform | Kubernetes | CI/CD | Cloud Infrastructure

> **I build, automate, secure, deploy, and monitor cloud infrastructure and applications using modern DevOps practices.**

I work across the complete delivery lifecycle — from **Infrastructure as Code and cloud networking** to **CI/CD, containerization, Kubernetes, security, application deployment, and observability**.

My focus is not just learning tools, but understanding **how the tools work together to build reliable and repeatable engineering platforms.**

---

## ⚡ What I Do

```text
                    ┌─────────────────────────┐
                    │       SOURCE CODE       │
                    │      Git / GitHub       │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │        CI / CD           │
                    │ Azure DevOps / GitHub   │
                    │        Actions           │
                    └────────────┬────────────┘
                                 │
                    ┌────────────┴────────────┐
                    │                         │
                    ▼                         ▼
             ┌─────────────┐          ┌─────────────┐
             │ Application │          │Infrastructure│
             │   Pipeline  │          │   Pipeline   │
             └──────┬──────┘          └──────┬──────┘
                    │                         │
                    ▼                         ▼
                Docker                  Terraform
                    │                         │
                    ▼                         ▼
                   ACR                      Azure
                    │
                    ▼
                 AKS / K8s
                    │
                    ▼
           Prometheus + Grafana
```

---

# 🧠 Engineering Focus

### ☁️ Cloud & Infrastructure

* Microsoft Azure
* Resource Groups
* Virtual Networks & Subnets
* NSG & Networking
* Load Balancers
* Virtual Machines
* Storage Accounts
* Azure Container Registry
* Azure Kubernetes Service
* Azure Key Vault
* Application Gateway
* Private Endpoints
* Azure SQL
* Log Analytics
* Azure Monitor
* Managed Identity
* RBAC

### 🏗️ Infrastructure as Code

* Terraform
* Modular Terraform Architecture
* Environment-based Infrastructure
* Terraform Remote State
* Azure Blob Backend
* Variables & Outputs
* `for_each`
* Dynamic Blocks
* Terraform Workspaces / Environment Strategies
* Infrastructure Validation
* Infrastructure Lifecycle Management

### 🔄 CI/CD & Automation

* Azure DevOps
* Azure DevOps YAML Pipelines
* GitHub Actions
* Infrastructure Pipelines
* Application Pipelines
* Multi-stage Pipelines
* Jobs & Stages
* Build → Test → Deploy
* Terraform Plan / Apply
* PR-based workflows
* Deployment automation

### 🐳 Containers & Kubernetes

* Docker
* Docker Networking
* Docker Multi-stage Builds
* Kubernetes
* AKS
* Kind
* Deployments
* Services
* ConfigMaps
* Secrets
* Probes
* Scaling
* Kubernetes Troubleshooting
* Helm

### 🔐 DevSecOps

* TFSEC
* Checkov
* TFLint
* SonarQube
* Infrastructure Security Scanning
* Static Code Analysis
* Security Gates
* Shift-left Security
* Secure CI/CD Practices

### 📊 Observability

* Prometheus
* Grafana
* Azure Monitor
* Log Analytics
* Metrics
* Dashboards
* Alerting
* Infrastructure Monitoring
* Kubernetes Monitoring

### 🧪 Application & API

* 3-Tier Applications
* Frontend / Backend / Database Architecture
* React
* Flask
* SQL Server
* REST APIs
* Postman
* Monolithic Applications
* Microservices Architecture
* Containerized Applications

### 🛠️ Additional Engineering

* Git
* GitHub
* Jenkins
* Linux
* Bash
* PowerShell
* Nginx
* Packer
* Custom Azure VM Images
* Infrastructure Troubleshooting

---

# 🏗️ How I Think About DevOps

I look at DevOps as an **end-to-end engineering lifecycle**, not as a collection of individual tools.

```text
Requirement
     │
     ▼
Architecture
     │
     ▼
Infrastructure as Code
     │
     ▼
Validation
     │
     ▼
Security
     │
     ▼
CI/CD
     │
     ▼
Application Deployment
     │
     ▼
Monitoring
     │
     ▼
Troubleshooting
     │
     ▼
Optimization
```

> **Build it. Automate it. Secure it. Deploy it. Observe it. Improve it.**

---

# 🚀 Featured Projects

## 🥇 VARISEN Enterprise Azure App Platform

**Azure + Terraform + DevSecOps + Cloud Infrastructure**

A modular Azure infrastructure platform built around Infrastructure as Code, cloud networking, reusable Terraform modules, security practices, monitoring, and operational readiness.

**Key areas:**

* Modular Terraform
* Azure Networking
* Resource Groups
* Subnets & NSGs
* Azure Compute
* ACR / AKS
* Application Gateway
* Key Vault
* Private Endpoints
* Azure SQL
* Log Analytics
* Monitoring
* Remote Terraform State
* CI/CD integration
* Security scanning

---

## 🥈 Azure Fullstack Terraform

**Terraform + Azure + Full-Stack Application + CI/CD**

Infrastructure and application deployment architecture covering:

```text
Frontend
   ↓
Backend
   ↓
Database
   ↓
Azure Infrastructure
   ↓
Terraform
   ↓
CI/CD
```

Demonstrates how application delivery and infrastructure automation work together.

---

## 🥉 Azure Terraform Infrastructure Pipeline

**Terraform + Azure DevOps + DevSecOps + Infracost**

Infrastructure pipeline implementing:

```text
Pull Request
     ↓
Validation
     ↓
TFLint
     ↓
TFSEC
     ↓
Checkov
     ↓
Infracost
     ↓
Terraform Plan
     ↓
Approval
     ↓
Terraform Apply
```

Focus: **secure, reviewable, automated infrastructure delivery.**

---

## ☸️ Application & Kubernetes Deployments

Hands-on deployment experience across:

* Dockerized applications
* Kubernetes workloads
* AKS
* Helm
* Application pipelines
* Container registries
* Frontend / Backend / Database architectures
* Monitoring with Prometheus & Grafana

---

# 🔥 Application Architecture Experience

I've worked with applications across multiple architectural patterns.

### Monolithic

```text
┌─────────────────────────────┐
│       Full Application      │
│                             │
│ Frontend + Backend + DB     │
└─────────────────────────────┘
```

### 3-Tier

```text
        Users
          │
          ▼
     ┌──────────┐
     │ Frontend │
     └────┬─────┘
          │
          ▼
     ┌──────────┐
     │ Backend  │
     └────┬─────┘
          │
          ▼
     ┌──────────┐
     │ Database │
     └──────────┘
```

### Microservices

```text
                    API Gateway
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
     Service A      Service B      Service C
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                    Data Layer
```

This gives me practical exposure to the difference between **application architecture, infrastructure architecture, and deployment architecture.**

---

# 🔐 DevSecOps Mindset

Security should be part of the delivery lifecycle — not an activity performed after deployment.

```text
Developer
    │
    ▼
Git
    │
    ▼
CI/CD
    │
    ├── TFLint
    ├── TFSEC
    ├── Checkov
    └── SonarQube
          │
          ▼
      Validation
          │
          ▼
      Terraform Plan
          │
          ▼
       Approval
          │
          ▼
       Deployment
```

---

# 📊 Observability

I believe:

> **If you cannot observe it, you cannot operate it confidently.**

Monitoring experience includes:

```text
Application
     │
     ▼
Infrastructure
     │
     ▼
Kubernetes
     │
     ▼
Prometheus
     │
     ▼
Grafana
     │
     ▼
Metrics / Dashboards / Alerts
```

Alongside Azure Monitor and Log Analytics for Azure resources and platform-level visibility.

---

# 🧰 Production Troubleshooting Mindset

Some of the scenarios I work with include:

### Terraform

* State locking
* Backend configuration
* Provider issues
* Resource dependencies
* Terraform drift
* Module issues
* Invalid resource configuration
* Plan / Apply failures

### Azure

* VNet / subnet issues
* NSG configuration
* IP allocation problems
* VM connectivity
* Load Balancer issues
* Private Endpoint connectivity
* Azure resource dependency failures
* Authentication / authorization issues

### Kubernetes

* `CrashLoopBackOff`
* `ImagePullBackOff`
* Pending Pods
* Service connectivity
* Readiness / Liveness failures
* Resource exhaustion
* Deployment failures
* Configuration issues

### CI/CD

* Pipeline failures
* Agent issues
* Authentication problems
* Terraform Plan failures
* Terraform Apply failures
* Security scan failures
* Deployment failures

---

# 🏛️ Infrastructure Philosophy

```text
Infrastructure
      │
      ├── Reproducible
      ├── Version Controlled
      ├── Automated
      ├── Secure
      ├── Observable
      ├── Scalable
      └── Maintainable
```

I prefer infrastructure that can be:

**created consistently → reviewed through code → deployed automatically → monitored continuously → recovered when things fail.**

---

# 💰 Cloud Cost Awareness

Good cloud engineering is not only about making infrastructure work.

It also means understanding:

* Resource sizing
* Storage costs
* Public IP usage
* Environment lifecycle
* Unused resources
* Monitoring costs
* Infrastructure review
* Cost estimation

> **Reliability, security, performance, and cost should be considered together when designing cloud infrastructure.**

---

# 📚 What I'm Continuously Improving

```text
Azure Architecture
        │
        ▼
Terraform
        │
        ▼
Kubernetes / AKS
        │
        ▼
CI/CD
        │
        ▼
DevSecOps
        │
        ▼
Platform Engineering
        │
        ▼
Cloud Architecture
```

My goal is to continuously move from:

> **Knowing tools → Understanding systems → Designing platforms.**

---

# 🧩 Core Technology Map

```text
                    DEVOPS
                       │
        ┌──────────────┼──────────────┐
        │              │              │
      CLOUD          IaC            CI/CD
        │              │              │
      Azure        Terraform      Azure DevOps
        │              │          GitHub Actions
        │              │              │
        └──────────────┼──────────────┘
                       │
                 CONTAINERS
                       │
                 Docker / ACR
                       │
                 KUBERNETES
                       │
                  AKS / Helm
                       │
                 DEVSECOPS
                       │
          TFSEC / Checkov / TFLint
                       │
                OBSERVABILITY
                       │
          Prometheus / Grafana
```

---

# 🎯 What I Can Build

```text
☁️ Azure Cloud Infrastructure
🏗️ Modular Terraform Platforms
🔄 Infrastructure CI/CD Pipelines
🚀 Application CI/CD Pipelines
🐳 Dockerized Applications
☸️ Kubernetes / AKS Platforms
⛵ Helm Deployments
🔐 DevSecOps Pipelines
📊 Prometheus + Grafana Monitoring
🌐 3-Tier Applications
🧩 Monolithic Applications
🔗 Microservices Deployments
🧪 REST API Testing with Postman
🖥️ Azure VM Infrastructure
📦 Custom VM Images with Packer
🗄️ Azure Database Infrastructure
```

---

# 🌟 Engineering Principles

> **Automate what is repeatable.**

> **Secure what is exposed.**

> **Monitor what is important.**

> **Document what is complex.**

> **Design for failure.**

> **Learn from every deployment.**

---

# 🤝 Open to Opportunities

I'm interested in opportunities involving:

**DevOps · DevSecOps · Azure · Terraform · Kubernetes · CI/CD · Cloud Infrastructure · Platform Engineering**

I enjoy working on problems where **infrastructure, automation, security, and applications come together.**

---

# ⚡ Final Thought

> ### Building infrastructure is easy.
>
> ### Building infrastructure that is reproducible, secure, observable, scalable, and maintainable is engineering.

---

### 🚀 Build. Automate. Secure. Deploy. Observe. Improve.

**— Pradum **
