<div align="center">

![banner](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=200&section=header&text=Bhavya%20Mandaliya&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=AI%20Agent%20Engineer&descAlignY=52)

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/bhavya-mandaliya/)
[![GitHub followers](https://img.shields.io/github/followers/AutoQAce?style=for-the-badge&logo=github&color=181717)](https://github.com/AutoQAce)

</div>

---

## About Me

I am Bhavya Mandaliya — a Software Automation Engineer at UBS with 10 years of experience designing and building automation frameworks across complex trading and banking platforms. I specialize in reliable, production-grade automation for regulated financial services environments.

I'm currently focused on AI Agent Engineering: building agentic systems that solve operational problems at scale (not just research demos). My domain experience gives me a practical advantage: I know where agent systems tend to fail in production, how to design around platform operational constraints, and how to deliver solutions that comply with regulatory and risk requirements.

---

## What I'm Building

### Environment Triage Agent (Active POC)
A multi-agent system that automates test environment management across a 900+ component UAT trading platform. Key capabilities:

- Ingest QA-reported environment behavior (tickets, structured reports).
- Run automated Splunk log analysis and correlate across services.
- Identify probable root causes (configuration drift, service failures, dependency issues).
- Propose remediation steps and, where safe, trigger automation to repair or rebuild environments (e.g., restart services, re-run infra provisioning, apply configuration fixes).
- Produce audit-friendly runbooks and justification for each action to satisfy governance.

Goal: reduce environment triage time, lower human toil, and increase test reliability while preserving auditability and operational controls.

### Agentic Architecture Patterns
Exploring and implementing production-relevant agent patterns with hands-on prototypes and tests:

- Reflection and self-evaluation
- Tool use & secured tool access
- ReAct (Reason + Act)
- PEV (Plan → Execute → Verify)
- Blackboard & shared-memory coordination
- Meta-controller / orchestrator patterns
- Memory systems (short- and long-term)

Each pattern is tested against failure modes we see in financial services (noisy logs, partial outages, flaky dependencies, sensitive data handling).

---

## Technical Skills

### Agent Engineering & LLM Tooling
[LangChain](https://langchain.com) • [LangGraph](https://langgraph-ai.github.io/langgraph/) • OpenAI API • Python

### Test Automation & Quality Engineering
Selenium • Pytest • RestAssured • WebdriverIO • JUnit • TestNG • JMeter • Postman

### Infrastructure & DevOps
Azure DevOps • Docker • Jenkins • Azure

### Languages
Python • Java • JavaScript

---

## Why Financial Services + Agent Engineering
Financial services engineering comes with constraints that many ML/agent projects ignore: strong compliance requirements, strict change and access controls, complex environment topologies, and high operational risk if automation behaves unexpectedly.

My background of 10 years inside trading and banking platforms means I can design agent systems that are robust to real failure modes, auditable for regulators, and practical for operations teams to adopt. I build with production constraints in mind — not just to get a notebook demo working.

---

## Work & Demos
I maintain a collection of small demos and reference implementations that exercise the architecture patterns above, focused on reproducibility and safety in realistic environments. If you'd like access to specific examples (PEV pipelines, Splunk-driven diagnosers, meta-controller prototypes), open an issue or contact me and I’ll share the relevant repo paths or example runs.

---

## Let's Connect
If you're working on AI agents in financial services, environment automation for trading/banking platforms, or production LLM evaluation and deployment, I'd like to connect.

**LinkedIn:** [Bhavya Mandaliya](https://www.linkedin.com/in/bhavya-mandaliya/)
**GitHub:** [@AutoQAce](https://github.com/AutoQAce)

---

<footer align="center">Built with practical agent engineering and a focus on reliability and governance.</footer>
