# 👋 Hi, I'm Víctor Piles

**Director of Engineering** | Former DevOps Lead | AI & Open Source Enthusiast

Building resilient systems and exploring how AI transforms software development. Passionate about infrastructure, data platforms, and empowering engineering teams through automation and intelligent tools.

---

## 🚀 What I Do

- 🏗️ **Lead engineering teams** building scalable, distributed systems
- 🤖 **Explore AI & LLMs** for developer productivity and automation  
- 🔧 **Champion DevOps practices** with focus on reliability and observability
- 🌍 **Contribute to open source** communities and emerging standards

---

## 🛠️ Tech Stack

**Infrastructure & DevOps:**
- Container orchestration: Kubernetes, Docker
- IaC: Terraform, Ansible
- CI/CD: GitHub Actions, GitLab CI, Jenkins
- Monitoring: Prometheus, Grafana, ELK Stack
- Cloud: AWS, Azure, GCP

**Data & IoT:**
- FIWARE (Context Broker, IoT Agents)
- Databases: PostgreSQL, MySQL, TimescaleDB, MongoDB
- Real-time: Apache Kafka, InfluxDB, MQTT
- ETL: Apache Airflow, custom pipelines

**AI & Development:**
- LLMs: Claude, GPT, local models
- AI Tools: Claude Code, Cursor, MCP
- Languages: Python, Bash, Go, TypeScript
- Automation: Python scripting, AI agents

---

## 🌟 Current Focus

- 🗿 **[Runestone](https://github.com/vict00r99/runestone)** - YAML specification format for consistent AI code generation
- 🤖 Building AI-assisted development workflows with agents.md and MCP
- 🔧 Exploring multi-agent systems for code quality and automation
- 📚 Bridging DevOps culture with AI-powered developer tools

---

## 💡 What I Believe In

- **Open Source First** - Best solutions emerge from collaborative development
- **AI Augmentation** - AI should amplify developer capabilities, not replace judgment
- **DevOps Culture** - Breaking silos, building empathy between dev and ops
- **Standards Matter** - FIWARE, OpenAPI, and open specs enable interoperability
- **Continuous Learning** - Engineering leadership requires staying hands-on

---

## 🎯 Featured Project

### 🗿 [Runestone](https://github.com/vict00r99/runestone)

A YAML-based specification format that solves the chaos of AI code generation.

**The Problem:** AI generates different code every time - no tests, no consistency, no contract.

**The Solution:** Write a `.rune` spec once → Generate consistent, tested, documented code forever.

**Integrates with:** Claude Code, agents.md, MCP servers, Claude Projects
```yaml
# Example: validate_email.rune
RUNE: validate_email
SIGNATURE: def validate_email(email: str) -> tuple[bool, str]
BEHAVIOR:
  - WHEN email is empty THEN return (False, "Email cannot be empty")
  - WHEN email matches RFC 5322 THEN return (True, "Valid")
TESTS:
  - validate_email('user@example.com') == (True, "Valid")
  - validate_email('') == (False, "Email cannot be empty")
```

Give this to any AI → Get consistent, reliable implementations.

---

## 💬 Ask Me About

- Engineering leadership and scaling technical teams
- DevOps best practices and infrastructure as code
- FIWARE ecosystem and IoT platforms
- AI coding assistants (Claude, MCP, agents.md)
- Database scaling and performance (SQL, time-series)
- Building reliable distributed systems

---

## 📫 Let's Connect

- 💼 LinkedIn: ([add your LinkedIn](https://www.linkedin.com/in/victorpilestemporal/))

Open to collaboration on DevOps tools, AI development workflows, and open source projects.

---

**"Turning infrastructure complexity into elegant simplicity, one system at a time."**

<!--
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
-->
