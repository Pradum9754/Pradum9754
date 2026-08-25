# 👋 Hi, I'm Pradum

### DevOps / DevSecOps Engineer | Azure | Terraform | Kubernetes | CI/CD | Cloud Infrastructure

> I build, automate, secure, deploy, and monitor cloud infrastructure and applications using modern DevOps practices.

I work across the complete delivery lifecycle — from **Infrastructure as Code and cloud networking** to **CI/CD, containerization, Kubernetes, security, application deployment, and observability**.

My focus is on building **reproducible, secure, automated, and maintainable infrastructure and application delivery platforms.**

---

## ⚡ Core Engineering Skills

### ☁️ Cloud & Infrastructure

* Microsoft Azure
* Resource Groups
* Virtual Networks & Subnets
* NSG & Network Security
* Load Balancers
* Application Gateway
* Virtual Machines
* Storage Accounts
* Azure Container Registry
* Azure Kubernetes Service (AKS)
* Azure Key Vault
* Private Endpoints
* Azure SQL
* Log Analytics
* Azure Monitor
* Managed Identity
* RBAC

### 🏗️ Infrastructure as Code

* Terraform
* Modular Terraform Architecture
* Reusable Terraform Modules
* Environment-based Infrastructure
* Terraform Remote State
* Azure Blob Backend
* Variables & Outputs
* `for_each`
* Dynamic Blocks
* Infrastructure Lifecycle Management

### 🔄 CI/CD & Automation

* Azure DevOps
* Azure DevOps YAML Pipelines
* GitHub Actions
* Jenkins
* Multi-stage Pipelines
* Jobs & Stages
* Build → Test → Deploy
* Terraform Plan / Apply
* PR-based Workflows
* Infrastructure Pipelines
* Application Pipelines

### 🐳 Containers & Kubernetes

* Docker
* Docker Networking
* Docker Multi-stage Builds
* Kubernetes
* Azure Kubernetes Service (AKS)
* Kind
* Deployments
* Services
* ConfigMaps
* Secrets
* Readiness / Liveness Probes
* Scaling
* Kubernetes Troubleshooting
* Helm

### 🔐 DevSecOps

* TFLint
* TFSec
* Checkov
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
* Kubernetes Monitoring

### 🧪 Application & API

* 3-Tier Applications
* Monolithic Applications
* Microservices Architecture
* React
* Flask
* SQL Server
* REST APIs
* Postman
* Dockerized Applications

### 🛠️ Engineering Tools

* Git
* GitHub
* Linux
* Bash
* PowerShell
* Nginx
* Packer
* JMeter
* VS Code

---

# 🏗️ DevOps Delivery Architecture

```text
                         SOURCE CODE
                      Git / GitHub
                           │
                           ▼
                    ┌───────────────┐
                    │    CI / CD    │
                    │               │
                    │ Azure DevOps  │
                    │ GitHub Actions│
                    └───────┬───────┘
                            │
                 ┌──────────┴──────────┐
                 │                     │
                 ▼                     ▼
          APPLICATION              INFRASTRUCTURE
            PIPELINE                  PIPELINE
                 │                     │
                 ▼                     ▼
              Docker               Terraform
                 │                     │
                 ▼                     ▼
                ACR                   Azure
                 │
                 ▼
              AKS / K8s
                 │
                 ▼
        Prometheus + Grafana
```

My approach is to connect **application delivery and infrastructure automation** into a repeatable engineering workflow.

---

# 🚀 Featured Projects

## 🥇 VARISEN Enterprise Azure App Platform

**Azure + Terraform + Kubernetes + DevSecOps + Cloud Infrastructure**

An enterprise-style Azure platform built using **Infrastructure as Code**, modular Terraform architecture, cloud networking, containerization, security practices, CI/CD, and observability.

### Key Areas

* Modular Terraform Architecture
* Azure Networking
* Resource Groups
* VNet / Subnets / NSGs
* Azure Compute
* Azure Container Registry
* Azure Kubernetes Service
* Application Gateway
* Azure Key Vault
* Private Endpoints
* Azure SQL
* Log Analytics
* Azure Monitor
* Prometheus & Grafana
* Terraform Remote State
* DevSecOps Integration
* CI/CD Automation

**Repository:** `VARISEN-ENTERPRISE-AZURE-APP-PLATFORM`

---

## 🥈 Azure Fullstack Terraform

**Terraform + Azure + Full-Stack Application + CI/CD**

Infrastructure and application deployment architecture covering:

```text
Frontend
    │
    ▼
Backend
    │
    ▼
Database
    │
    ▼
Azure Infrastructure
    │
    ▼
Terraform
    │
    ▼
CI/CD
```

Demonstrates how **application architecture, infrastructure automation, and deployment pipelines** work together.

**Repository:** `azure-fullstack-terraform`

---

## 🥉 Azure Terraform DevSecOps Pipeline

**Terraform + Azure DevOps + Security + Cost Awareness**

Infrastructure delivery workflow:

```text
Pull Request
     │
     ▼
Validation
     │
     ├── TFLint
     ├── TFSec
     ├── Checkov
     └── Infracost
            │
            ▼
     Terraform Plan
            │
            ▼
        Approval
            │
            ▼
      Terraform Apply
```

Focus: **secure, reviewable, automated infrastructure delivery.**

---

# ☸️ Kubernetes & Application Deployment

Hands-on deployment experience across:

* Dockerized applications
* Kubernetes workloads
* AKS
* Kind
* Helm
* Container registries
* Application CI/CD
* Frontend / Backend / Database architectures
* Prometheus & Grafana monitoring

Typical application architecture:

```text
                    Users
                      │
                      ▼
                 Frontend
                      │
                      ▼
                  Backend
                      │
                      ▼
                  Database
```

Applications have also been explored through **monolithic, 3-tier, and microservices deployment patterns**.

---

# 🔐 DevSecOps Approach

Security should be integrated into the delivery lifecycle rather than treated as a final deployment step.

```text
Developer
    │
    ▼
Git / GitHub
    │
    ▼
CI/CD Pipeline
    │
    ├── TFLint
    ├── TFSec
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

The goal is to identify infrastructure, configuration, and code issues **before they reach production environments**.

---

# 📊 Observability

> **If you cannot observe it, you cannot operate it confidently.**

Monitoring and observability experience includes:

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

Alongside:

* Azure Monitor
* Log Analytics
* Kubernetes monitoring
* Infrastructure metrics
* Application visibility
* Alerting

---

# 🧰 Troubleshooting Mindset

I approach infrastructure and deployment failures by moving from **symptom → evidence → root cause → corrective action**.

### Terraform

* Backend configuration issues
* State locking
* Provider issues
* Resource dependencies
* Terraform drift
* Module issues
* Invalid resource configuration
* Plan / Apply failures

### Azure

* VNet / Subnet issues
* NSG configuration
* IP allocation problems
* VM connectivity
* Load Balancer issues
* Private Endpoint connectivity
* Resource dependency failures
* Authentication / Authorization issues

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

# 🏛️ Engineering Philosophy

I prefer infrastructure that is:

```text
Reproducible
     │
     ▼
Version Controlled
     │
     ▼
Automated
     │
     ▼
Secure
     │
     ▼
Observable
     │
     ▼
Scalable
     │
     ▼
Maintainable
```

My approach:

> **Build it → Automate it → Secure it → Deploy it → Observe it → Improve it**

---

# 💰 Cloud Cost Awareness

Good cloud engineering is not only about making infrastructure work.

I also consider:

* Resource sizing
* Public IP usage
* Storage costs
* Environment lifecycle
* Unused resources
* Monitoring costs
* Cost estimation
* Infrastructure optimization

> **Reliability, security, performance, and cost should be considered together when designing cloud infrastructure.**

---

# 📚 Currently Improving

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

> **Knowing tools → Understanding systems → Designing platforms**

---

# 🎯 What I Build

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
🧪 REST API Testing
🖥️ Azure VM Infrastructure
📦 Custom VM Images
🗄️ Azure Database Infrastructure
```

---

# 🤝 Open to Opportunities

Interested in opportunities involving:

**DevOps · DevSecOps · Azure · Terraform · Kubernetes · CI/CD · Cloud Infrastructure · Platform Engineering**

I enjoy solving problems where **infrastructure, automation, security, applications, and observability** come together.

---

# ⚡ Final Thought

> ### Building infrastructure is easy.
>
> ### Building infrastructure that is reproducible, secure, observable, scalable, and maintainable is engineering.

### 🚀 Build. Automate. Secure. Deploy. Observe. Improve.

**— Pradum **
