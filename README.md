# John B. Roberts | Cloud Solutions Architect · AI Automation

<div align="center">
  <img src="./images/Gemini_Generated_Image_ewxrfeewxrfeewxr.png" alt="John B. Roberts at work in a server room" width="100%" />

  [![Blog](https://img.shields.io/badge/Blog-roberjo.github.io-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://roberjo.github.io)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/roberjo)
  [![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:johnbroberts@gmail.com)
</div>

---

## 🚀 About Me

I design and build **high-leverage software systems**: cloud architectures on AWS, automation that removes toil, and AI workflows that put LLMs to work inside real engineering processes. My background is enterprise cloud architecture, so the things I build are **secure, cost-aware, observable, and tested**, whether that's a serverless platform, a vulnerability-remediation pipeline, or tooling around a COBOL batch shop.

### 🎯 What I Work On
- 🤖 **AI-powered automation** - LLM agents that turn tickets into pull requests, and tooling that makes AI coding agents (Claude Code, Copilot, Gemini CLI, Codex) better at using real tools
- 🏗️ **Cloud architecture** - Multi-region, highly available, fault-tolerant, event-driven designs on AWS
- ⚡ **Infrastructure as Code** - Terraform, CloudFormation, AWS CDK
- 🔄 **Serverless & edge** - Lambda, API Gateway, DynamoDB, EventBridge, Step Functions, Cloudflare Workers
- 🧱 **Legacy modernization** - Modern tooling, observability, and dev workflows around mainframe COBOL
- 🛠️ **DevOps & CI/CD** - GitHub Actions, Terraform Cloud, Harness, Jenkins
- 🔒 **Security & compliance** - Zero Trust, automated security controls, SOC2/ISO27001
- 💰 **Cost optimization** - FinOps practices, resource optimization, cost governance
- 📊 **Observability** - CloudWatch, X-Ray, Prometheus, Grafana, ELK

---

## 💼 Featured Projects

### 🧱 [mainframe-frontier](https://github.com/roberjo/mainframe-frontier)
**Modern engineering around mainframe COBOL**
> A realistic COBOL batch shop (JCL job streams, copybooks, EBCDIC packed-decimal files) that runs in a container without a mainframe, surrounded by the tooling production shops rarely have: job visibility, data interfacing, monitoring, and a modern development loop.

**Tech:** Rust · GnuCOBOL · JCL · Docker · GitHub Actions

---

### 🎫 [ticket-remediation](https://github.com/roberjo/ticket-remediation)
**From vulnerability finding to pull request, automatically**
> Two pipelines: one turns ServiceNow application-vulnerability findings into Jira issues; the other has an LLM read the target repo, write the fix, and open a GitHub PR, then notifies the team over Teams, Slack, and email. Pluggable LLM providers (Claude, Gemini).

**Tech:** Python · Anthropic Claude API · Google Gemini · Jira · ServiceNow · GitHub API

---

### 🧰 [tool-enabler](https://github.com/roberjo/tool-enabler)
**Teach AI coding agents to use your tools**
> One catalog of "how to use this tool" knowledge for CLIs (`gh`, `kubectl`, `aws`, ...) and HTTP-only systems (Jira, Confluence, Slack, Splunk, Jenkins, Harness), compiled into the context format each agent reads: Claude Code Skills, `AGENTS.md`, `GEMINI.md`, and `copilot-instructions.md`.

**Tech:** Python · Claude Code · GitHub Copilot · Gemini CLI · Codex CLI

---

### ☁️ [aws-testing](https://github.com/roberjo/aws-testing)
**A full event-driven AWS app, deployed and tested on a laptop**
> Proof of concept evaluating fakecloud as a local AWS stand-in: ~70 Terraform resources (Lambda, API Gateway, SNS/SQS with DLQs, DynamoDB Streams, S3, Kafka, CloudFront, Route 53) plus a Next.js front end, verified by 22 end-to-end tests, with 15 documented emulator findings.

**Tech:** Terraform · AWS Lambda (Node.js) · SNS/SQS · DynamoDB · Kafka · Next.js

---

### 🚗 [VINScout](https://github.com/roberjo/VINScout)
**Used-vehicle opportunity screening**
> Pulls real listings every 6 hours, normalizes them by VIN, and gates every vehicle on its history (accident, salvage, flood) before ranking it on price, mileage, and NHTSA recall data. Runs entirely on free tiers.

**Tech:** TypeScript · React · Cloudflare Workers · Hono · D1 · GitHub Actions

---

### 📻 [world-radio](https://github.com/roberjo/world-radio) · [Live demo](https://roberjo.github.io/world-radio/)
**Listen to the world's radio on a live map**
> 5,000+ geo-located stations on an interactive clustered map, with HLS playback, a regional "radio scanner" mode, and shareable station lists.

**Tech:** TypeScript · Vite · Leaflet · HLS.js

---

### More projects

| Project | What it is | Tech |
|---|---|---|
| [AuraStream](https://github.com/roberjo/AuraStream) | Serverless sentiment analysis API (real-time and batch) with PII protection and caching | Python · AWS Lambda · Comprehend · DynamoDB · Terraform |
| [AdPilot](https://github.com/roberjo/AdPilot) | Conversational AdTech agent system | Next.js · Vercel AI SDK · Claude / OpenAI / Gemini · Supabase |
| [intellidoc-rag-system](https://github.com/roberjo/intellidoc-rag-system) | RAG document intelligence: query and summarize large document sets | FastAPI · ChromaDB · PostgreSQL · OpenAI / Anthropic · Docker |
| [role-fusion](https://github.com/roberjo/role-fusion) · [demo](https://role-fusion.lovable.app/) | Role-based access control UI with granular permissions and dynamic roles | React · TypeScript · Tailwind · Radix UI |
| [guardrail-radar](https://github.com/roberjo/guardrail-radar) | Zero-budget content-discovery pipeline for an AI-assisted-development newsletter | Python · GitHub Actions · GitHub Pages |
| [roomba-telemetry](https://github.com/roberjo/roomba-telemetry) | Local-network telemetry and control dashboard for WiFi Roombas | Python |

---

## 🛠️ Technology Stack

### ☁️ Cloud
![AWS Lambda](https://img.shields.io/badge/AWS-Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![Amazon API Gateway](https://img.shields.io/badge/AWS-API%20Gateway-FF9900?style=for-the-badge&logo=amazon-api-gateway&logoColor=white)
![Amazon DynamoDB](https://img.shields.io/badge/AWS-DynamoDB-FF9900?style=for-the-badge&logo=amazon-dynamodb&logoColor=white)
![Amazon S3](https://img.shields.io/badge/AWS-S3-FF9900?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/AWS-ECS-FF9900?style=for-the-badge&logo=amazon-ecs&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/AWS-EKS-FF9900?style=for-the-badge&logo=amazon-eks&logoColor=white)
![Amazon CloudWatch](https://img.shields.io/badge/AWS-CloudWatch-FF9900?style=for-the-badge&logo=amazon-cloudwatch&logoColor=white)
![AWS Organizations](https://img.shields.io/badge/AWS-Organizations-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

### 🤖 AI & Agents
![Claude](https://img.shields.io/badge/Anthropic-Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude-Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=for-the-badge&logo=openai&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub-Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)

### 🔧 DevOps & Infrastructure
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS-CDK-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![COBOL](https://img.shields.io/badge/COBOL-005CA5?style=for-the-badge)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

---

## 📈 Architecture Expertise

<div align="center">

![Architecture Expertise](images/ArchitectureExpertise_Mermaid%20Chart-2025-08-11-015334.png)

</div>

**Specializing in designing and implementing:**
- **🏗️ Multi-Region Architectures** - High availability and disaster recovery
- **⚡ Serverless Solutions** - Event-driven, auto-scaling applications
- **🔒 Security-First Design** - Zero Trust, defense in depth
- **💰 Cost-Optimized Solutions** - FinOps and resource optimization
- **📊 Observability** - Comprehensive monitoring and alerting

---

## 📚 Writing

More on the blog at **[roberjo.github.io](https://roberjo.github.io)**.

- **[Serverless Architecture Patterns for Enterprise Applications](serverless-patterns.md)** - Scalable patterns for modern applications
- **[Cost Optimization Strategies for AWS Infrastructure](aws-cost-optimization.md)** - Practical FinOps implementation
- **[Implementing Zero Trust Security in AWS](aws-zero-trust.md)** - Security-first architecture design
- **[Production Ready Microfrontend Build with Codex](Microfrontends-Build.md)** - Building a React portal on microfrontends with OpenAI Codex

---

## 📫 Let's Connect

I'm passionate about helping organizations get real leverage from cloud and AI. Whether you're looking to:
- **🤖 Put LLMs and coding agents to work inside your engineering workflow**
- **🏗️ Design scalable cloud architectures**
- **🔄 Implement DevOps practices**
- **🔒 Enhance security posture**
- **💰 Optimize cloud costs**

Let's talk.

<div align="center">
  <a href="mailto:johnbroberts@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/roberjo">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://roberjo.github.io">
    <img src="https://img.shields.io/badge/Blog-roberjo.github.io-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="Blog" />
  </a>
</div>

---

<div align="center">
  <p><strong>"Building reliable, secure, and scalable systems that give the people using them an unfair advantage."</strong></p>
  <p><em>Available for consulting, full-time opportunities, and speaking engagements</em></p>
</div>
