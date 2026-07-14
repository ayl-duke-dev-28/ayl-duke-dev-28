 # 👋 Hey, I'm **Alex Liu**

  I build production AI agents, ML pipelines, and full-stack systems. Rising
  junior at Duke University studying Computer Science and Mathematics, with
  research across three Duke labs and real deployed projects with real users.

  ### 🔗 [linkedin.com/in/alexliu22](https://www.linkedin.com/in/alexliu22/) · [ayliu.636@gmail.com](mailto:ayliu.636@gmail.com)

  ---

  ## 👀 Interests

  - Agentic AI systems · LLMs · RAG · prompt engineering
  - ML pipelines at scale · multi-agent orchestration
  - Full-stack engineering (React, FastAPI, Python)
  - Math · probability · competitive problem solving

  ---

  ## 🌱 Currently Building & Learning

  - AI/ML infrastructure for oncology clinical trial matching (Triomics)
  - Multi-agent LLM pipeline for autonomous biological experiment design (Hickey
  Lab)
  - LLM-powered knowledge assistants and security-hardened data infrastructure
  (Krenzer Lab)
  - Improving DocRAG retrieval accuracy and adding multi-document reasoning
  - Algorithmic trading platform with live paper execution and walk-forward
  backtesting

  ---

  ## 🤝 Open to Collaborating On

  - AI agent systems, LLM tooling, and evaluation frameworks
  - ML applications in healthcare, genomics, or research infrastructure
  - Full-stack AI-powered products with real-world users

  ---

  ## 📫 Connect

  - **Email:** ayliu.636@gmail.com
  - **LinkedIn:**
  [linkedin.com/in/alexliu22](https://www.linkedin.com/in/alexliu22/)

  ---

  ## ⚡ Fun Fact

  Outside of coding, I love playing chess and sports. I've been a lifelong tennis
  player and recently have been getting into golf and basketball.

  ---

  # 📝 Highlights

  ## 🎓 Education

  **Duke University** — Durham, NC
  *B.S. Computer Science and Mathematics · Minor in Finance · GPA: 3.83 ·
  Graduating May 2028*

  - National Merit Scholar 2025
  - AIME Qualifier 2023, 2024, 2025
  - 2nd Place Nationally, Math Madness 2025
  - Bloomberg Market Concepts Certified

  ---

  ## 💼 Experience

  ### **Triomics – ML Engineer Intern** *(Jun 2026 – Present)*

  - Redesigned the core cancer-patient-to-clinical-trial matching pipeline in
  Python and FastAPI, replacing a brute-force inclusion/exclusion criteria
  evaluation with a decision-tree routing structure that reduces per-patient
  compute from O(patients × trials) to a single tree traversal
  - Built an LLM-based extraction pipeline to parse unstructured clinical notes,
  pathology reports, and lab results into structured, schema-validated patient
  profiles using Pydantic; enabling downstream matching logic to operate on clean,
  typed data rather than raw clinical text

  ### **Hickey Lab @ Duke School of Medicine – Research Assistant** *(May 2026 – Present)*

  - Built a multi-agent LLM pipeline from scratch that autonomously designs and
  executes biological experiments by pulling from existing experimental data and
  scientific literature -- reducing experiment cycle time from weeks to minutes
  - Designed agent coordination layer, tool-use interfaces, and evaluation
  frameworks to benchmark output quality across pipeline stages; stack: Python,
  LangChain, Anthropic API, multi-agent orchestration

  ### **Krenzer Lab @ Duke Sanford School of Public Policy – Research Assistant** *(Apr 2026 – Present)*

  - Built a deployable RAG chatbot platform for Duke research labs that ingests
  papers, protocols, and internal documents into secure, lab-specific AI
  assistants with configurable access controls and multi-environment deployment
  - Identified 15+ security vulnerabilities and implemented AES-256 encryption,
  TLS, and RBAC across PostgreSQL/AWS infrastructure; configured MCP servers and
  agentic LLM toolchains using Claude Code daily
  - Deployed production systems on AWS via Docker with GitHub Actions CI/CD in
  Python, TypeScript, FastAPI, and React

  ### **Duke University Baseball – Data Analyst** *(Aug 2025 – Present)*

  - Built Python and SQL analytics pipelines (NumPy, pandas, SciPy, statsmodels)
  modeling 30+ variables across 3+ seasons of historical performance data
  - Developed predictive models and dashboards that directly influenced lineup
  decisions and defensive alignments for coaching staff

  ### **Cohen Lab @ Duke School of Medicine – Research Assistant** *(Apr 2025 – Jun 2026)*

  - Built ML pipelines in Python and Java processing 10M+ NIH records across 500K+
  patients and 3+ disease cohorts; reduced per-cohort runtime from ~8 hours to
  under 90 minutes
  - Designed classification models for patient cohort analysis flagging high-
  confidence at-risk individuals for clinical follow-up

  ### **Hyperspace Ventures – Software Engineer Intern** *(Jun 2024 – Aug 2024)*

  - Shipped full-stack features for a SaaS platform serving 2,000+ users in
  TypeScript, React, and Node.js
  - Reduced average task completion time by ~35% and drop-off rate by ~30% through
  A/B-tested navigation redesigns

  ### **Wasatch Photonics – Software Engineer Intern** *(May 2023 – Jun 2023)*

  - Implemented SPI communication protocol in C and C++ for Airbus optical systems
  achieving sub-millisecond latency between spectrometer components and external
  control modules
  - Built real-time Python monitoring and data pipelines for spectrometer output
  processing

  ---

  ## 🛠️ Projects

  ### **LabGraph – Multi-Source Knowledge-Graph RAG for Research Labs** *(Jan 2026 – Present)*

  - Rebuilding DocRAG from a single-source RAG assistant into LabGraph, a multi-
  source knowledge-graph RAG system that answers multi-hop research questions
  across papers, meeting notes, and lab documents with visible graph-traversal
  traces
  - Shipped a deterministic eval harness and typed knowledge-graph core with 5
  entity types, 6 relation types, alias resolution, NetworkX traversal, SQLite
  persistence, and CI coverage across the full extract → build → traverse loop
  - Building OpenAI structured extraction, Google Drive ingestion, graph-aware
  retrieval, and a trace-first UI that shows the answer, supporting sources, and
  entity path behind each response
  - **Stack:** Python · FastAPI · OpenAI API · NetworkX · SQLite · Pydantic ·
  pytest · Docker · GitHub Actions

  ### **Trader Bot – Algorithmic Trading Platform** *(Mar 2026 – Present)*

  - Built an end-to-end systematic trading system with XGBoost ML models for
  signal generation, live order execution via Alpaca REST API, and a walk-forward
  backtesting framework for strategy validation
  - Implemented risk controls (position limits, stop-losses, kill switch) and
  tracks CAGR, Sharpe ratio, and drawdown metrics; paper trading only -- no live
  capital deployed
  - **Stack:** Python · XGBoost · Alpaca API · pandas · NumPy · Docker · AWS

  ### **Incident Response Bot – AI-Driven Production Triage** *(Jun 2026 – Present)*

  - Built an AI-driven incident response system that triages production alerts via
  three parallel agents -- commit-blame ranking (matches recent commits against
  alert signals), runbook matching (maps alerts to markdown playbooks), and user-
  impact estimation
  - Designed a provider-agnostic integration layer with mock and real
  implementations behind shared interfaces for GitHub, Slack, and Datadog,
  enabling fully offline testing; orchestrated with asyncio, webhook-triggered on
  incoming alerts from monitoring tools
  - Auto-generates blameless post-mortems posted back to originating Slack
  threads; FastAPI backend with SQLite persistence and Pydantic domain models
  - **Stack:** Python · FastAPI · Anthropic API · SQLite · Pydantic · asyncio ·
  pytest

  ### **Tutoring Assistant – AI-Powered SAT Prep** *(Jun 2025 – Sep 2025)*

  - Built a full-stack AI-powered tutoring application with a React.js frontend,
  Python (FastAPI) backend, and Java-based business logic layer, integrating
  OpenAI's API to generate unique question variants with adaptive difficulty
  calibration
  - Deployed to 8 SAT tutoring students over 3 months, achieving average score
  improvements of 80+ points through personalized question targeting and feedback
  loops

  ---

  ## 🧰 Technical Stack

  **Languages:** Python · Java · TypeScript · JavaScript · C · C++ · R · SQL ·
  HTML/CSS

  **Frameworks:** React.js · FastAPI · LangChain · Node.js

  **AI/ML:** Anthropic API · OpenAI API · RAG · LLMs · Prompt Engineering · Multi-
  Agent Orchestration · ChromaDB · XGBoost · scikit-learn

  **Tools:** Git · Docker · AWS · GitHub Actions · PostgreSQL · Linux · Claude
  Code · MCP Servers
