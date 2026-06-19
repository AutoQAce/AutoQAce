<!--
  ╔════════════════════════════════════════════════════════════════╗
  ║   Bhavya Mandaliya — AI Agent Engineer                          ║
  ║   Profile README. Copy to: AutoQAce/AutoQAce/README.md         ║
  ╚════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=240&section=header&text=Bhavya%20Mandaliya&fontSize=52&fontColor=ffffff&fontAlignY=34&desc=I%20build%20agentic%20AI%20that%20survives%20contact%20with%20production&descSize=20&descAlignY=54&animation=fadeIn" width="100%"/>

<a href="https://www.typingsvgalternatives.example">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=4FC3F7&center=true&vCenter=true&width=820&lines=AI+Agent+Engineer+%C2%B7+10+yrs+in+trading+%26+banking+automation;Multi-agent+systems+for+regulated+financial+services;Auditable.+Governed.+Resilient+to+real+failure+modes;Notebook+demos+are+easy.+Production+agents+are+the+job." alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bhavya_Mandaliya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhavya-mandaliya/)
[![GitHub](https://img.shields.io/badge/GitHub-AutoQAce-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AutoQAce)
[![Followers](https://img.shields.io/github/followers/AutoQAce?style=for-the-badge&logo=github&label=Follow&color=1f6feb)](https://github.com/AutoQAce?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=AutoQAce&style=for-the-badge&label=Profile+views&color=4FC3F7)](https://github.com/AutoQAce)

</div>

---

<div align="center">

### `“Most agents work in a demo. Mine have to work at 2 a.m., under audit, when a dependency is down.”`

</div>

---

<table>
<tr>
<td width="50%" valign="top">

```python
class Bhavya:
    role       = "AI Agent Engineer"
    day_job    = "Automation Engineer @ UBS"
    experience = "10 yrs · trading & banking"
    domain     = "regulated financial services"
    builds     = "production agentic systems"
    not_this   = "notebook demos"

    @property
    def edge(self):
        return ("I know exactly where agents "
                "break in production — and I "
                "design around it from line 1.")
```

</td>
<td width="50%" valign="top">

**The 30-second version**

🏦 A decade automating complex **trading & banking** platforms.

🤖 Now building **multi-agent systems** that solve real operational problems at scale.

🧪 I treat **evals and failure-mode design** as the work — not the cleanup.

🎯 Heading toward **agent architect**: reliable, scalable, auditable systems, end-to-end.

📐 I measure my own skill honestly — *can I rebuild it cold, and can I defend the design choice?*

</td>
</tr>
</table>

---

## 🧭 What makes me different

Most agent projects ignore the constraints that define my world — **compliance, change control, access governance, operational risk, and auditability.** Ten years inside regulated trading platforms means I don't bolt those on after the demo; they're my **design inputs**. I build agents that ops teams will actually adopt and regulators can actually sign off on.

> **Anyone can make an LLM call a tool. The hard part is making it safe, observable, reversible, and explainable when it's wrong.** That's the part I'm good at.

---

## 🚀 Flagship Build — Environment Triage Agent  `active POC`

> A multi-agent system automating test-environment management across a **900+ component UAT trading platform.**

```mermaid
flowchart LR
    A[QA report / ticket] --> B[Triage Orchestrator]
    B --> C[Splunk log analysis]
    B --> D[Cross-service correlation]
    C --> E{Root cause?}
    D --> E
    E -->|config drift / outage / dependency| F[Remediation planner]
    F --> G[/Safe? trigger automation/]
    F --> H[/Risky? human-in-the-loop/]
    G --> I[Audit-friendly runbook + justification]
    H --> I
```

| | |
|---|---|
| 🔍 **Diagnoses** | Splunk log analysis + cross-service correlation to find probable root cause |
| 🛠️ **Acts (safely)** | Restart services, re-run provisioning, apply config fixes — with HITL gates on anything risky |
| 📋 **Proves it** | Emits an **audit-ready runbook** justifying every action, for governance |
| 📉 **Delivers** | Less triage time, less human toil, higher test reliability — controls intact |

---

## 🧩 Real Builds, Not Just Reading

I'm working through a **40-article, 11-phase agent-engineering curriculum** with a finance-capstone through-line. Every article becomes a self-contained build — notebooks, **evals**, learning journals, and **architecture decision records.** A sample of what's already shipped:

| 🏗️ Build | What it proves |
|---|---|
| **Multi-Agent Supervisor System** | `create_supervisor` + handoff tools · human-in-the-loop `interrupt()` · two-tier memory · LangSmith + openevals eval harness |
| **14 Pillars of Agentic Parallelism** | fan-out/fan-in at every layer — `Send` map-reduce · speculative execution · hedged/redundant calls · sharded scatter-gather · hybrid-search fusion · multi-hop RAG |
| **Contextual Engineering & Retrieval Eval** | scratchpad / context isolation / sub-agents · tool-retrieval metrics (nDCG · Recall · Precision · **Completeness@k**) · two-stage re-ranking |

<details>
<summary><b>📐 The part I'm proudest of — I measure capability, not activity</b></summary>

<br/>

Reading a notebook into existence proves almost nothing. So every pattern I learn is tracked on two honest axes:

- **Build axis** — *L0 encountered → L1 reproduce-with-reference → L2 rebuild-cold → L3 transfer to a novel problem.* A working notebook only earns L1. L2 means a blank file, from memory.
- **Architecture axis** — *can I defend choosing this pattern over a real alternative, under a real constraint?* Tracked in an ADR log, with **predicted vs. actual failure modes** filled in after the build.

This is exactly the discipline a regulated-finance architect is paid for: not "it ran," but **"I can rebuild it cold and justify why it's the right design."**

</details>

<details>
<summary><b>🧠 Agentic patterns I prototype & stress-test against financial-services failure modes</b></summary>

<br/>

`Reflection / self-eval` · `Secured tool use` · `ReAct` · `Plan → Execute → Verify` · `Blackboard coordination` · `Meta-controller / orchestrator` · `Short- & long-term memory`

Each is tested against what actually goes wrong in production: **noisy logs, partial outages, flaky dependencies, and sensitive-data handling.**

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Agent Engineering & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=for-the-badge&logo=graphql&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

**Quality Engineering & Automation**

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![WebdriverIO](https://img.shields.io/badge/WebdriverIO-EA5906?style=for-the-badge&logo=webdriverio&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Infra & DevOps · Languages**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 📊 By the Numbers

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AutoQAce&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=AutoQAce&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AutoQAce&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img src="https://github-profile-trophy.vercel.app/?username=AutoQAce&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" width="100%"/>

</div>

---

## 🤝 Let's Build the Hard Version

I want to talk if you're working on **AI agents in financial services**, **environment / infrastructure automation for trading & banking platforms**, or **production LLM evaluation & deployment.**

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhavya-mandaliya/)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AutoQAce)

<br/>

***Production constraints from line one — not retrofitted after the demo.***

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" width="100%"/>

</div>
