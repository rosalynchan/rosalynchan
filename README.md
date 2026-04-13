# 👩‍💻 Rosalyn Chen
## Quant Developer × AI Agent Engineer

> **Building intelligent tools for traders and quant teams. Specializing in data pipelines, real-time analytics, and AI-powered automation.**

---

<div align="center">

📍 **London, UK** | 💼 **Quant Tools & AI Development** | 🚀 **Open to Opportunities**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rosalyn--Chen-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/rocn/)
[![GitHub](https://img.shields.io/badge/GitHub-@rosalynchan-181717?style=flat&logo=github)](https://github.com/rosalynchan)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat)](mailto:xiaoqingwala@gmail.com)

</div>

---

## 🎯 About Me

I'm a **Quant & Data Pipeline Developer** with **3+ years of hands-on experience** building front-office analytics, trading data applications, and quantitative tools directly for traders and quant teams at tier-1 investment banks.

I specialize in **delivering high-impact tools** that trading desks depend on optimizing data workflows, reducing manual work, and enabling faster decision-making in fast-paced trading environments.

**Current Focus at Investment Bank:**
- 🎯 **Quantitative Tool Development**: Built configurable calculation engines and analytical tools supporting trading desk workflows with dynamic formula evaluation and scalable metric generation
- 💰 **Front-Office Platform Architecture**: Architected end-to-end Python web applications with Enaml + Atom frontend, processing output of model data, reducing analysis time from hours to minutes
- 📊 **Data Quality & Explainability**: Developed rule-based explainability systems for metrics, with interactive dashboard interfaces and automated rule creation, **reduced daily manual investigation time by 20-30 minutes per analyst**
- 🔄 **Trading Data Pipelines**: Optimized data pipelines for daily batch processing with focus on reliability, scalability, and trader usability

**My Edge:**
- Deep understanding of **what traders actually need**, not theoretical infrastructure, but practical tools
- Full-stack expertise: **Python backend + Enaml/Atom and  React/Typescript frontend + AG-Grid + Plotly + KDB+/q**
- Experience with optimized the trading workflow
- Now expanding into **AI Agents & LLM-powered automation** to make trading tools even smarter

I believe the future of quantitative trading tools is **intelligent automation powered by AI Agents**. 

In my spare time, I'm building 4 personal AI Agent projects to:
1. Master this emerging technology
2. Show how AI can amplify the practical tools I build for traders
3. Demonstrate end-to-end system design from scratch
4. Prepare for the next chapter of my career at the intersection of AI and trading technology

---

## 🧠 Technical Expertise

| Domain | Skills | 
|--------|---------|
| **Frontend** | Enaml (declarative Python UI framework) • Atom (reactive data model) • AG-Grid • Plotly (interactive visualization) • React + TypeScript |
| **Backend & Data** | Python (primary) • Pandas • Polars • PySpark • SQL • KDB+/q • C++ (learning)|
| **AI Agent Systems** | Multi-agent orchestration • LangGraph • OpenAI Agents • Tool-calling • LLM integration |
| **Quant Engineering** | Risk formula engines • Data pipelines • Drift detection • Explains engine (predicate rules) • Market data processing |
| **Software Engineering** | Test-Driven Development • OOP • Git • Linux • Jira • Scrum |
| **Databases & Tools** | SQLite • PostgreSQL • Blob storage • Cloud (Azure/S3) • CI/CD concepts |

---

## 🌟 My AI Agent × Quant Portfolio

### Four Personal Projects (Built in Spare Time)
*Leveraging my 3+ years of trading tools experience to build the next generation of AI-powered systems*

**Why I plan to Build These:**
While my day job is focused on immediate trader needs, I believe the future of quant tools is **AI-powered and autonomous**. So I'm building these 4 projects in my spare time to:
- ✅ Master AI Agent systems and LLM integration
- ✅ Demonstrate how AI can amplify the tools I've built at my investment bank
- ✅ Create a portfolio showing my ability to architect intelligent systems from scratch
- ✅ Prepare for the next evolution of my career in AI × Trading Technology

**Important Note:** These are **personal projects** built independently in my spare time, inspired by real trading workflows but not using any company code or proprietary information.

---

### 1️⃣ **Trading Data Multi-Agent Assistant**
**Tick Replay + Cleaning + Microstructure + SQL Generation + Reporting**

*Evolution of the data pipeline work I've done for trading desks but with AI Agents*

A **multi-agent system** for managing trading data quality and microstructure analysis:

✅ **Capabilities:**
- Ingest tick data from multiple sources (CSV, Parquet, S3)
- Detect & repair missing ticks, irregular timestamps, data anomalies
- Perform anomaly detection and market event flagging
- Execute tick replay simulations (time-window based)
- Extract microstructure features (imbalance, depth, intensity, bounce)
- Generate SQL for VWAP, OHLC, aggregated bars
- Produce automated daily summaries & HTML reports

✅ **Why I Built This (Personal Project):**
In my trading desk work, data quality consumed significant manual effort from traders. This sparked an idea: what if an AI Agent could automate this? 

I built this as a **personal side project** to explore how AI Agents can solve real trading workflow problems. It's inspired by the data challenges I see daily at work, but it's my own implementation from scratch — no company code, pure learning and building.

The system automates what previously required hours of trader investigation, directly improving trader efficiency and decision-making speed.

✅ **Tech Stack:**
`OpenAI Agents` | `LangGraph` | `LangChain` | `Pandas` | `FastAPI` | `Jinja2` | `Plotly` *(React + TypeScript upgrade planned)*

✅ **Architecture:**
```
User Query → PlannerAgent
             ↓
    IngestionAgent → CleaningAgent → AnalysisAgent
             ↓
         ReportingAgent → Final Output
```

📂 **Repository:** [trading-data-agent](https://github.com/rosalynchan/quant-dev-portfolio/tree/main/ai-agents-quant-tools/trading-data-agent)

**Status:** In Active Development

---

### 2️⃣ **Quant ETL Multi-Agent Pipeline**
**Drift Detection + Reconciliation + Schema Validation + ETL Orchestration**

*Extension of the data pipeline optimization I've done supporting trading operations*

An **intelligent ETL system** for quantitative workflows and trading data:

✅ **Capabilities:**
- Auto-detect data source schema & metadata
- Schema validation & type correction
- Statistical drift detection (mean/variance/distribution drift)
- Seasonal drift & column-level drift explanation
- Data reconciliation (T-1 vs T, source vs derived)
- Root cause analysis for reconciliation gaps
- Automated SQL generation for EOD queries
- Pipeline health reports & ready-for-analysis status

✅ **Why I Built This (Personal Project):**
Every day at work, I see quant teams spend hours on manual data validation before analysis. I built this **as a personal project** to demonstrate how multi-agent systems can automate the entire ETL workflow.

It's inspired by real challenges I face in my job — drift detection, reconciliation, data quality, but it's my own independent exploration of how AI Agents can solve these problems at scale. The result: traders and analysts get clean, validated data in minutes instead of hours, letting them focus on strategy instead of data hunting.

✅ **Tech Stack:**
`LangGraph` | `Pandas` | `Polars` | `SQLite` | `FastAPI` | `Plotly` | `Jinja2` *(React + TypeScript upgrade planned)*

✅ **Architecture:**
```
Data Sources (S3, DB, API)
         ↓
    PlannerAgent
         ↓
SourceAgent | ValidationAgent | DriftAgent | ReconcileAgent
         ↓
    SQLAgent → ReportingAgent
         ↓
    Dashboard Output
```

📂 **Repository:** [quant-etl-agent](https://github.com/rosalynchan/quant-dev-portfolio/tree/main/ai-agents-quant-tools/quant-etl-agent)

**Status:** TO DO

---

### 3️⃣ **Explainability Agent Engine** ⭐
**Rule Builder + Explain Classifier + Rationale NLG + Dashboard**

*Natural evolution of the explainability work I've built for trading metrics — now with AI agents*

A **next-generation explainability system** powered by AI Agents:

✅ **Capabilities:**
- Natural language → predicate rule builder agent
- Automatic explained/unexplained classification
- Rationale generation (natural language explanations)
- Rule performance & coverage evaluation
- Trader/desk-level summaries
- Heatmap visualization of unexplained metrics
- Dashboard-ready JSON/HTML output

✅ **Why This Matters (Personal Project):**
In my daily work with traders, explaining metric changes quickly is critical. I've built rule-based systems that achieved this, reducing investigation time by **20-30 minutes per trader per day**.

I created this **as a personal side project** to take that concept further with AI Agents. The idea: what if agents could automatically generate and refine rules, learn from trader feedback, and continuously improve explanations?

It's my independent exploration of how LLMs and agents can make explainability systems smarter and more autonomous, letting traders understand *why* metrics changed in seconds instead of hours, with minimal manual rule creation.

This is where I'm most excited about AI's potential in trading technology.

✅ **Tech Stack:**
`OpenAI Agents` | `Pandas` | `Custom Rule Engine` | `Jinja2` | `Plotly` *(React + TypeScript upgrade planned)*

✅ **Perfect for:**
- Trading metric explainability
- Compliance & audit trails
- Dashboard-driven trader workflows

📂 **Repository:** [explainability-agent](https://github.com/rosalynchan/quant-dev-portfolio/tree/main/ai-agents-quant-tools/explainability-agent)

**Status:** TO DO

---

### 4️⃣ **AI Agent QuantOps Engine** ⭐ (Masterpiece)
**The End-to-End Multi-Agent Orchestration System**

*Everything I've built to support traders, now powered by AI Agents*

My **flagship project** — a comprehensive agentic system combining all four domains:

✅ **Integrated Capabilities:**
- **Multi-Agent Orchestration:** Stateful DAG execution, error recovery, observability logging
- **Trading Data Layer:** Ingestion, cleaning, microstructure, replay, anomaly detection
- **Quant Data Pipeline Layer:** Drift detection, reconciliation, analysis-readiness checks
- **Explainability Layer:** Rule building, explain generation, rule coverage, dashboards
- **Utility Layer:** SQL generation, file export, report automation
- **API Layer:** FastAPI service, async task queues, real-time monitoring
- **Dashboard:** Pipeline status, drift heatmaps, unexplained tables, replay graphs, SQL preview

✅ **Why This Project Matters (Personal Capstone):**
Over 3+ years, I've built individual tools to support traders:
- Data pipeline tools
- Calculation platforms
- Explainability systems
- Data ingestion systems

This **personal capstone project** brings all these threads together: what if one unified AI Agent system could orchestrate everything?

It's my independent exploration of **intelligent autonomous systems** , not infrastructure automation, but smart agents that understand trader workflows and make autonomous decisions about data processing, quality checks, and reporting.

This project demonstrates how all my trading tools experience converges into a modern, AI-powered architecture. It's where I'm exploring the future of how trading teams will work with intelligent systems.

**This is my vision for the next evolution of trading tools.**

✅ **Tech Stack:**
`LangGraph` | `OpenAI Agents` | `FastAPI` | `Pandas` | `SQLite` | `React` | `TypeScript` | `Plotly`

✅ **Full Architecture Diagram:**
```
                        API / Web UI
                             ↓
                        PlannerAgent
                             ↓
        ┌────────────────────────────────────────┐
        │      Multi-Agent Orchestration Layer    │
        └────────────────────────────────────────┘
           ↓              ↓                ↓
      IngestionAgent  CleaningAgent  AnalysisAgent   (P1)
           ↓              ↓                ↓
    SourceAgent  ValidationAgent  DriftAgent  ReconcileAgent  SQLAgent  (P2)
           ↓              ↓                ↓
      RuleAgent  ClassifyAgent  ExplainAgent  FeedbackAgent   (P3)
           ↓              ↓                ↓
                  ReportingAgent
                         ↓
        ┌─────────────────────────────────┐
        │    Dashboard + API Output        │
        │  (JSON, HTML, API endpoints)     │
        └─────────────────────────────────┘
```

📂 **Repository:** [quantops-agent-engine](https://github.com/rosalynchan/quant-dev-portfolio/tree/main/ai-agents-quant-tools/quantops-agent-engine) 

**Status:** TO DO
---

## 🎓 Education & Background

**MSc Computing Science** | University of Glasgow, UK (Jan 2021 - Jan 2022)
- Dissertation: *Automation in Quantitative Strategy Systems* , implemented quantitative trading strategies using PyAlgoTrade framework
- Core courses: Data Science & Systems, Machine Learning & AI for Data Science, Information Visualization

**B.Eng Software Engineering** | East China University of Technology, China
- High-distinction grades: Software Engineering (95%), Data Structures & Algorithms (83%), Data Mining & Business Intelligence (89%)
- Strong foundation in OOP, systems design, and data-driven applications

**Financial Background:**
- 3+ years at tier-1 investment bank (risk tools, funding optimization, explains engine)
- Cross-functional experience: financial product management + technical leadership with trading desks

---

## 🔄 From Trading Tools to AI-Powered Tools

My **3+ years building tools directly for traders and quant teams** gave me deep insight into:

| Trader Pain Point | Tool I Built | How AI Agents Improve It |
|-----------|--------------|------------------------|
| **Data quality checks slow down analysis** | Data pipelines + validation | Automated agents detect + fix issues in real-time |
| **Metric calculation takes time** | Calculation tools + workflows | Agent-driven orchestration processes in parallel |
| **"Why did my metric change?" → hours of investigation** | Explainability dashboards | AI agents auto-generate answers + rationales instantly |
| **Manual batch processing every day** | Data pipeline tools | Agents autonomously handle pipeline workflows |

**The Insight:** Most trading tools today are built for *humans to manually operate*. My AI Agent projects are built for *humans to leverage intelligent agents*.

The future of quant tools is **AI-augmented, not human-replaced**. Traders spend time on strategy, agents handle the operational work.

---

## 📚 Architecture & Design Documentation

Every project includes:

| Document | Purpose |
|----------|---------|
| **`/docs/architecture.md`** | Full system design, data flow, agent patterns |
| **`/docs/api-reference.md`** | API endpoints, request/response examples |
| **`/docs/design-decisions.md`** | Why we chose X over Y, trade-offs, learnings |
| **`/docs/agent-patterns.md`** | Planner/Worker/Evaluator breakdown |
| **`README.md`** | Quick start, local setup, example usage |

---

## 💡 Key Technical Decisions

**Why Multi-Agent Architecture?**
- **Separation of concerns:** Each agent specializes in one domain
- **Composability:** Reuse agents across projects
- **Explainability:** Clear reasoning trail for each decision
- **Resilience:** If one agent fails, others continue

**Why LangGraph + OpenAI Agents?**
- Stateful DAG execution for complex workflows
- Built-in tool-calling for SQL, file I/O, API calls
- Human-in-the-loop capabilities
- Production-ready error handling

**Why Polars + SciPy?**
- Fast, memory-efficient data processing
- Statistical analysis for drift detection (KS test, distribution shifts)
- Seamless integration with NumPy for numerical operations
- Superior to pandas for large financial datasets

---

## ✍️ Articles & Thought Leadership

📝 **Coming soon on LinkedIn & Medium:**

- *How Multi-Agent Systems Transform QuantOps Workflows*
- *Trading Data Quality: The Agent-Powered Approach*
- *LangGraph vs Microsoft Agent Framework: A Real-World Comparison*
- *Drift Detection at Scale: Automated Monitoring with Agents*

---

## 🔗 Connect With Me

| Platform | Link | Purpose |
|----------|------|---------|
| **GitHub** | [@rosalynchan](https://github.com/rosalynchan) | Code & projects |
| **LinkedIn** | [Rosalyn Chen](#) | Professional updates |
| **Email** | xiaoqingwala@gmail.com | Direct inquiries |
| **Community** | TechDudes (600+ members) | London tech community founder |

---

## 💼 What I'm Looking For

I'm passionate about **building market data pipline and trading tools that traders and quants actually use every day**, and now adding **AI Agent intelligence** to make those tools even more powerful.

🎯 **Ideal Opportunities:**
- **Quant Developer / Trading Tools Engineer** at hedge funds, asset managers, prop trading firms
- **AI Agent / AI Infrastructure** roles in fintech or trading technology
- **Trading Technology** teams building next-generation quant platforms
- **Quant Platform** teams that value both technical depth and trader feedback
- **AI × Trading** startups building intelligent trading infrastructure

**Why I'm Making This Transition:**
- ✅ 3+ years building practical tools traders depend on daily (not abstract infrastructure)
- ✅ Gained deep understanding of what traders actually need vs. what engineers think they need
- ✅ Now adding **AI Agent + LLM engineering** to amplify the impact of those tools
- ✅ Trading desks are moving toward AI, I want to lead that transformation

**What Makes Me Valuable:**
- **Trader perspective** : I build tools WITH traders
- **Full-stack capability** : backend + frontend + data pipelines + systems design
- **Proven track record** : shipped production tools that traders use daily
- **Quant mindset** : understand data, metrics, strategies, workflows
- **Now adding AI** : can automate what traders spend time on, let them focus on strategy

If you're building **tools that traders love and that intelligence amplifies**, let's talk.

---

## 🚀 What's Next?

### Currently Working On:
- ✅ Expanding Trading Data Agent with real market tick data
- ✅ Building production-ready Quant ETL with drift monitoring
- ✅ Shipping Explainability Agent with rule learning capabilities
- ⚙️ Scaling QuantOps Engine to full enterprise deployment

### Future Roadmap:
- [ ] Real-time trading signal generation with agents
- [ ] Machine learning drift detection (vs statistical)
- [ ] Interactive dashboard for QuantOps (React frontend)
- [ ] Open-source library releases
- [ ] Technical blog launch

---

<div align="center">

## Let's Build the Future of Quant Engineering Together

**Rosalyn Chen** | London, UK  
## Quant Developer × AI Agent Engineer

**Status:** 🟢 Open to new opportunities

[GitHub](https://github.com/rosalynchan) • [LinkedIn](https://www.linkedin.com/in/rocn/) • [Email](mailto:xiaoqingwala@gmail.com)

</div>

---
