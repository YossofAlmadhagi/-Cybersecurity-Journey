# 🗺️ Detailed Roadmap

### Month-by-month plan, technologies, projects, checklists and transition criteria

> This document expands on [`README.md`](./README.md). Check off each task as it is completed — this file is the single source of truth for progress in this journey.

---

## 📑 Table of Contents

- [🧱 Phase 01 — Foundations](#-phase-01--foundations)
- [🛡️ Phase 02 — Application Security](#️-phase-02--application-security)
- [🏗️ Phase 03 — Product Security Engineering](#️-phase-03--product-security-engineering)
- [☁️ Phase 04 — Cloud Security Engineering](#️-phase-04--cloud-security-engineering)
- [🌟 Phase 05 — Professional Presence](#-phase-05--professional-presence)
- [🏆 Top 1% Practices](#-top-1-practices)
- [✅ Five-Year Success Indicators](#-five-year-success-indicators)

---

## 🧱 Phase 01 — Foundations

**Duration:** Months 1–3+

### Month 1

**Linux**
- [ ] Install Linux
- [ ] Navigate the filesystem
- [ ] Manage files
- [ ] Manage users
- [ ] Permissions
- [ ] Processes
- [ ] Services
- [ ] SSH
- [ ] Cron jobs
- [ ] Bash basics

**Project — Linux Automation**
- [ ] Bash script: create a user
- [ ] Bash script: create a directory structure
- [ ] Bash script: copy files
- [ ] Bash script: create a backup
- [ ] Bash script: compress the backup

**Python**
- [ ] Variables
- [ ] Conditionals
- [ ] Loops
- [ ] Functions
- [ ] File handling
- [ ] Exceptions
- [ ] Object-Oriented Programming (OOP)
- [ ] Working with JSON
- [ ] Using third-party libraries

**Project — Password Manager**
- [ ] Build a command-line password manager in Python

**Web**
- [ ] How the internet works
- [ ] HTTP
- [ ] Request / Response cycle
- [ ] Cookies
- [ ] Sessions
- [ ] JWT
- [ ] REST APIs

**Project — REST API**
- [ ] Build a REST API using FastAPI

**Git**
- [ ] Create a repository
- [ ] Commit
- [ ] Branch
- [ ] Merge
- [ ] Pull Request

**End of Month 1**
- [ ] Complete every project above without copying full solutions

**Flagship Repository (start on day one)**
- [ ] Create `Cybersecurity-Journey` repository on GitHub
- [ ] One folder per month
- [ ] One folder per project
- [ ] `README.md` explaining what was learned
- [ ] Screenshots or short recordings for projects when relevant

---

### Month 2 — Networking

**Fundamentals**
- [ ] OSI Model
- [ ] TCP/IP
- [ ] TCP vs UDP
- [ ] IPv4 & IPv6
- [ ] Subnetting
- [ ] MAC Address
- [ ] ARP
- [ ] NAT
- [ ] DNS
- [ ] DHCP
- [ ] Routing
- [ ] Switching
- [ ] VPN
- [ ] Proxy

**Protocols to master**
- [ ] HTTP
- [ ] HTTPS
- [ ] TLS/SSL
- [ ] FTP
- [ ] SSH
- [ ] SMTP
- [ ] POP3
- [ ] IMAP
- [ ] DNS
- [ ] WebSocket

**Tools**
- [ ] Wireshark
- [ ] tcpdump
- [ ] curl
- [ ] Postman
- [ ] netcat
- [ ] nmap (only on environments you're authorized to test)

**Project**
- [ ] Build a simple chat server in Python using sockets (TCP, connection handling, data transfer, error handling)

---

### Month 3 — Professional Python

**Python Advanced**
- [ ] Decorators
- [ ] Generators
- [ ] Context managers
- [ ] Async programming
- [ ] Threading
- [ ] Multiprocessing
- [ ] Logging
- [ ] Virtual environments
- [ ] Packaging
- [ ] Testing
- [ ] Type hints
- [ ] Dataclasses

**Libraries**
- [ ] `requests`
- [ ] `httpx`
- [ ] `BeautifulSoup`
- [ ] `asyncio`
- [ ] `pathlib`
- [ ] `subprocess`
- [ ] `re`
- [ ] `json`
- [ ] `sqlite3`
- [ ] `pytest`

**Small Projects**
- [ ] Web crawler
- [ ] Directory scanner
- [ ] Port scanner (authorized environment only)
- [ ] HTTP header analyzer
- [ ] SSL certificate checker

**Git — Advanced**
- [ ] Rebase
- [ ] Cherry-pick
- [ ] Tags
- [ ] GitHub Actions
- [ ] Releases

**Clean Code**
- [ ] Clean Code principles
- [ ] SOLID
- [ ] Design patterns
- [ ] Refactoring

---

### Phase Project — 🛠️ Security Toolkit

- [ ] DNS Lookup
- [ ] WHOIS
- [ ] Ping
- [ ] Authorized port scan
- [ ] SSL check
- [ ] HTTP headers analysis
- [ ] `robots.txt` reader
- [ ] Sitemap reader
- [ ] Screenshot tool
- [ ] JSON export

### Transition Criteria → Phase 02

- [ ] Can write a Python program from scratch
- [ ] Can read any API documentation
- [ ] Can use Git without following a tutorial
- [ ] Understands any HTTP request/response
- [ ] Can analyze a basic network capture in Wireshark

### Recommended Reading

- [ ] *Python Crash Course*
- [ ] *Fluent Python* (advanced reference)
- [ ] *TCP/IP Illustrated* (progressively)

### Building Reputation — Weekly / Monthly

- [ ] Weekly: push a project to GitHub
- [ ] Weekly: write a clear README
- [ ] Weekly: document what was learned
- [ ] Monthly: ship a new project
- [ ] Monthly: improve an older project
- [ ] Monthly: review and clean up code

---

## 🛡️ Phase 02 — Application Security

**Duration:** Months 4–8

### Month 4 — How the Web Really Works

**Architecture**
- [ ] Client
- [ ] Server
- [ ] Browser
- [ ] Frontend
- [ ] Backend
- [ ] API
- [ ] Reverse proxy
- [ ] CDN
- [ ] Database
- [ ] Cache
- [ ] Queue

**HTTP Methods**
- [ ] GET, POST, PUT, PATCH, DELETE, OPTIONS, HEAD

**Status Codes**
- [ ] 2xx (200 / 201 / 204)
- [ ] 3xx (301 / 302)
- [ ] 4xx (400 / 401 / 403 / 404 / 429)
- [ ] 5xx (500 / 502 / 503)

**Headers**
- [ ] Host, Cookie, Authorization, Origin, Referer
- [ ] CSP, CORS, HSTS
- [ ] X-Frame-Options, X-Content-Type-Options

**Authentication**
- [ ] Sessions
- [ ] JWT
- [ ] OAuth2
- [ ] API Keys
- [ ] MFA

**Project — Build Your Own Authentication System (FastAPI + PostgreSQL)**
- [ ] Register
- [ ] Login
- [ ] Logout
- [ ] Password hashing
- [ ] JWT issuance
- [ ] Refresh tokens
- [ ] Rate limiting
- [ ] Email verification
- [ ] Password reset

---

### Month 5 — OWASP Top 10

> For each vulnerability: **understand → build a vulnerable app → exploit it in a controlled environment → fix it → write it up.**

- [ ] Broken Access Control
- [ ] Cryptographic Failures
- [ ] Injection
- [ ] Insecure Design
- [ ] Security Misconfiguration
- [ ] Vulnerable and Outdated Components
- [ ] Identification and Authentication Failures
- [ ] Software and Data Integrity Failures
- [ ] Security Logging and Monitoring Failures
- [ ] Server-Side Request Forgery (SSRF)

**Vulnerability Project Loop** *(repeat for each item above, e.g. SQL Injection)*
- [ ] Build a deliberately vulnerable app
- [ ] Exploit it in a training environment
- [ ] Fix it (e.g. with prepared statements)
- [ ] Write a report explaining what happened and how it was fixed

---

### Month 6 — Secure Coding

- [ ] Input validation
- [ ] Output encoding
- [ ] Password hashing
- [ ] Secrets management
- [ ] File upload security
- [ ] Logging
- [ ] Error handling
- [ ] Secure cookies
- [ ] CSP
- [ ] CSRF protection
- [ ] Rate limiting
- [ ] Security headers

**Project**
- [ ] Update the Month 4 authentication system to apply every Secure Coding practice above

---

### Month 7 — Code Review

- [ ] Learn to spot vulnerabilities directly in code
- [ ] Write clear, actionable review notes for developers
- [ ] Explain the root cause and the fix

**Project**
- [ ] Pick a small open-source project on GitHub
- [ ] Create a `SECURITY_REVIEW.md` covering:
  - [ ] Potential vulnerabilities
  - [ ] Severity level
  - [ ] Impact
  - [ ] Suggested fix

---

### Month 8 — AppSec Tools

- [ ] Burp Suite
- [ ] OWASP ZAP
- [ ] Nuclei
- [ ] Semgrep
- [ ] Trivy
- [ ] Gitleaks
- [ ] Dependency-Check

### Major Project — 🔎 Mini AppSec Platform

- [ ] HTTP security header scanning
- [ ] Basic misconfiguration detection
- [ ] `robots.txt` / `sitemap.xml` analysis
- [ ] SSL certificate verification
- [ ] PDF report generation
- [ ] Simple web dashboard

### Success Criteria → Phase 03

- [ ] Understands how an application works before hunting for vulnerabilities
- [ ] Can read and understand Python and JavaScript code
- [ ] Can explain the root cause of a vulnerability and how to fix it
- [ ] Builds small tools that support security analysis
- [ ] Can write a professional security report

---

## 🏗️ Phase 03 — Product Security Engineering

**Duration:** Months 9–18

### Month 9 — Secure SDLC (SSDLC)

- [ ] SDLC & SSDLC
- [ ] Agile & Scrum
- [ ] DevOps & DevSecOps
- [ ] Git Flow & CI/CD
- [ ] Security gates

**Project**
- [ ] Reorganize a previous project around a professional development lifecycle: GitHub Issues, GitHub Projects, Pull Requests, Code Review, Security Review, Release Notes

### Month 10 — Threat Modeling

- [ ] STRIDE
- [ ] DREAD (for historical context)
- [ ] Attack trees
- [ ] Data Flow Diagrams (DFD)
- [ ] Risk assessment

**Project**
- [ ] Pick an application (e.g. e-commerce or e-learning platform) and produce: a DFD, trust boundaries, likely threats, and mitigations

### Month 11 — Secure Architecture

- [ ] Monolith vs Microservices
- [ ] API Gateway
- [ ] Reverse proxy & load balancer
- [ ] Message queues & caching
- [ ] Service Mesh (conceptually)

**Project**
- [ ] Design the architecture of a SaaS platform (frontend, backend, PostgreSQL, Redis, queue, object storage, auth service, logging, monitoring) with a security layer defined for every component

### Month 12 — Secrets Management

- [ ] Environment variables
- [ ] Secret rotation
- [ ] API key & token management
- [ ] Key Management Systems (KMS)
- [ ] Least privilege

**Project**
- [ ] Refactor a previous project so that: it contains no hardcoded credentials, relies fully on environment variables, and documents setup correctly

### Month 13 — CI/CD Security

- [ ] GitHub Actions
- [ ] Security checks in pipelines
- [ ] Dependency scanning
- [ ] Secret scanning
- [ ] SAST & DAST
- [ ] SBOM

**Project**
- [ ] Build a pipeline that: runs tests, analyzes code, scans dependencies/secrets, and produces an automated scan report

### Month 14 — Container Security

- [ ] Docker basics
- [ ] Dockerfile best practices
- [ ] Image scanning
- [ ] Root vs non-root containers
- [ ] Multi-stage builds
- [ ] Container isolation

**Project**
- [ ] Containerize a FastAPI application: harden the Dockerfile, scan the image for vulnerabilities, document the results

---

### Months 15–18 — Major Project: Product Security Platform

**Phase 1**
- [ ] User registration & authentication
- [ ] Project management
- [ ] Dashboard

**Phase 2**
- [ ] Vulnerability management
- [ ] Risk assessment
- [ ] Assignment to owners

**Phase 3**
- [ ] Integrate scanning tools
- [ ] Display results
- [ ] Reporting

**Phase 4**
- [ ] Notifications
- [ ] Audit log
- [ ] Role-based access control

**Engineering Requirements**
- [ ] Automated tests
- [ ] API documentation
- [ ] Professional README
- [ ] Docker
- [ ] CI/CD
- [ ] Logging & error handling
- [ ] Security policy for the project

---

## ☁️ Phase 04 — Cloud Security Engineering

**Duration:** Months 19–30 · **Provider:** AWS

### Month 19 — Cloud Fundamentals

- [ ] Cloud computing concepts
- [ ] IaaS / PaaS / SaaS
- [ ] Public / Private / Hybrid cloud
- [ ] High availability & scalability
- [ ] Fault tolerance
- [ ] Choose AWS as the primary provider

### Months 20–21 — AWS Core

- [ ] IAM
- [ ] EC2
- [ ] S3
- [ ] VPC
- [ ] Security Groups & NACLs
- [ ] Route tables
- [ ] CloudWatch & CloudTrail
- [ ] KMS & Secrets Manager
- [ ] RDS
- [ ] Lambda & API Gateway

**Project**
- [ ] Deploy a cloud environment: app server, database, file storage, logging, monitoring, backups

### Month 22 — AWS IAM

- [ ] Users, Groups, Roles, Policies
- [ ] Least privilege
- [ ] Temporary credentials & MFA

**Project**
- [ ] Model a fictional company with fine-grained roles: Developer, Security Engineer, Admin, Auditor

### Month 23 — Docker Sizing

- [ ] Images & containers
- [ ] Volumes & networks
- [ ] Docker Compose
- [ ] Multi-stage builds
- [ ] Docker security

**Project**
- [ ] Fully containerize your SaaS platform with Docker Compose and isolated containers

### Months 24–25 — Kubernetes

- [ ] Pods & Deployments
- [ ] Services & Ingress
- [ ] ConfigMaps & Secrets
- [ ] RBAC & Network Policies
- [ ] Helm

**Project**
- [ ] Run and manage the full application inside a Kubernetes cluster

### Month 26 — Infrastructure as Code (Terraform)

- [ ] Terraform basics
- [ ] Modules & variables
- [ ] State & workspaces

**Project**
- [ ] Provision the entire AWS infrastructure using Terraform

### Month 27 — Cloud Security

- [ ] Cloud misconfiguration
- [ ] IAM auditing
- [ ] Logging & incident response
- [ ] Backup & disaster recovery
- [ ] Encryption & network segmentation
- [ ] WAF & DDoS protection

**Project**
- [ ] Conduct a full security review of the cloud environment: risks, priorities, remediation plan

### Month 28 — Monitoring

- [ ] Metrics
- [ ] Logs
- [ ] Traces
- [ ] Alerts
- [ ] Dashboards

### Month 29 — Security Automation

Write Python tools to:
- [ ] Review IAM configurations
- [ ] Check storage buckets
- [ ] Verify encryption settings
- [ ] Detect common misconfigurations

### Month 30 — Final Project: Secure SaaS Platform

- [ ] Frontend & backend
- [ ] PostgreSQL & Redis
- [ ] Docker & Kubernetes
- [ ] CI/CD pipeline
- [ ] Monitoring, logging, alerting
- [ ] Secrets management & IAM
- [ ] Backup & disaster recovery
- [ ] HTTPS, WAF, load balancer, auto scaling

---

## 🌟 Phase 05 — Professional Presence

**Weekly**
- [ ] New project or improvement to an existing one
- [ ] Technical article
- [ ] New documentation on GitHub

**Monthly**
- [ ] Contribute to an Open Source project
- [ ] Solve practical challenges or labs

**Quarterly**
- [ ] Update the personal website
- [ ] Review and update the CV

**Yearly**
- [ ] Ship one major achievement or project

**Flagship Project**
- [ ] AI Security SaaS — an AI-assisted Product Security platform, built up gradually as skills mature

---

## 🏆 Top 1% Practices

**Learning Ratio**
- [ ] Maintain roughly 30% theory — 70% hands-on practice

**Core Repositories on GitHub**
- [ ] `Cybersecurity-Labs`
- [ ] `Python-Security-Tools`
- [ ] `Application-Security`
- [ ] `Cloud-Security`
- [ ] `Product-Security`
- [ ] `Security-Research`
- [ ] `Secure-SaaS`
- [ ] `Writeups`
- [ ] `Notes`

**Yearly Flagship Projects**
- [ ] Year 1 — Security Toolkit
- [ ] Year 2 — Vulnerable Web Lab
- [ ] Year 3 — Mini AppSec Platform
- [ ] Year 4 — Product Security Platform
- [ ] Year 5 — AI Security SaaS

**10 Habits of Highly Visible Engineers**
- [ ] Read code — study one open-source project weekly and understand its structure
- [ ] Write — publish a technical article or project write-up monthly
- [ ] Present professionally — polished README, screenshots, setup steps, features, limitations, future work
- [ ] Prioritize — Skill → Projects → Reputation → Certifications
- [ ] Network — talk to one security engineer monthly, join technical discussions and talks
- [ ] Technical English — read official documentation 15–30 minutes daily
- [ ] Stay focused — avoid chasing side technologies that don't serve the current goal

---

## ✅ Five-Year Success Indicators

**Technical Skills**
- [ ] Advanced Python
- [ ] Linux & Bash
- [ ] Git
- [ ] Networking
- [ ] Web Security
- [ ] Application Security
- [ ] Product Security
- [ ] Cloud Security
- [ ] Docker
- [ ] Kubernetes
- [ ] CI/CD
- [ ] Threat Modeling

**Projects & Work**
- [ ] 30+ small projects
- [ ] 5 medium projects
- [ ] 3 large projects
- [ ] 1 flagship project

**Professional Reputation**
- [ ] Active GitHub
- [ ] Professional LinkedIn
- [ ] Personal website
- [ ] Open Source contributions
- [ ] Published technical articles

**Practical Experience**
- [ ] Internship or team collaboration
- [ ] Real code reviews performed
- [ ] Professional security reports written
- [ ] Worked alongside software development teams

---

⬅️ **[Back to README.md](./README.md)**
