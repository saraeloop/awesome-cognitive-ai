# 🌟 Awesome Cognitive-AI

> A curated, **fact-checked** catalog of frameworks, patterns, papers, datasets, tools, and systems for building **inspectable cognitive loops** (plan → act → observe → reflect → learn), agentic workflows, RAG, memory, evaluation, and observability.

[English] · [Español] 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![CI](https://img.shields.io/github/actions/workflow/status/OWNER/REPO/ci.yml?label=CI)
![Last Updated](https://img.shields.io/github/last-commit/OWNER/REPO)

---

## Why this list?

- **Cognition-first**: Goes beyond “agents” to highlight **explicit cognitive structure** (state, loops, memory, reflection, insight, evaluation).
- **Quality gate**: Every entry includes **license, maintenance status, artifact types, and evaluation signals**.
- **Inspectability**: Preference for projects that produce **traceable artifacts** (e.g., events.jsonl, memory facts, eval reports).

> ⚖️ **Disclosure policy**: When a maintainer contributes their own project, we mark it **Maintainer-Contributed** so the list stays trustworthy.

---

## Taxonomy

- **Cognition & Loops** — cognitive frameworks, loop orchestration (plan/act/reflect/learn)
- **Frameworks** — agent & workflow frameworks (LangGraph, CrewAI, OpenAI Agents SDK, etc.)
- **Memory** — short/long-term memory, vector stores, entity memory, episodic memory
- **Evaluation** — LLM eval, RAG eval, safety eval, trace-based eval
- **Observability** — tracing, analytics, debug UIs, telemetry
- **Guardrails & Safety** — policy, red-teaming tools, constrained decoding, classifiers
- **MCP** — Model Context Protocol servers/tools/registries
- **RAG** — pipelines, hybrid search, routing, distillation
- **Datasets** — reasoning, QA, tool-use, safety
- **Papers** — seminal cognition/agent/RAG/loop papers
- **Production Systems** — end-to-end blueprints & case studies

---

## Curated catalog

> ✅ This section is **auto-generated** from `/catalog/items/**` via CI.  
> Do not edit directly — see [CONTRIBUTING](CONTRIBUTING.md).

<!-- BEGIN:CATALOG -->
### Cognition & Loops
- **Noēsis** — Cognitive loop + artifacts (state/events/memory/insight). _Maintainer-Contributed; Disclosure in entry._

### Frameworks
- **LangGraph** — Typed graph for agent flows; supports persistence, human-in-the-loop.

### Memory
- **Mem0** — Simple personalizable memory layer with connectors.

### Evaluation
- **Ragas** — RAG-focused metrics + reports.

### Observability
- **Langfuse** — Traces, spans, prompts, eval, dashboards.

### Guardrails & Safety
- **Guardrails AI** — Validated outputs, schemas, policies.

### MCP
- **MCP Spec** — Protocol for tools/servers over stdio/HTTP.

### Datasets
- **HotpotQA** — Multi-hop QA dataset for reasoning.

### Papers
- **Tree of Thought (ToT)** — Structured problem-solving via search over thoughts.

### Production Systems
- **AutoEval Pipeline** — Example CI evaluation harness template.
<!-- END:CATALOG -->

---

# 🧠 Awesome Cognitive AI

A curated collection of **frameworks, tools, and research** building the next generation of cognitive architectures, agent reasoning loops, and observable AI systems.  
This repository highlights projects exploring **planning, reflection, learning, and memory** — the building blocks of machine cognition.

---

## 🤔 Why Awesome Cognitive AI?

💡 **Understand** how modern AI systems reason, plan, and learn — from open-ended agents to reflective LLM loops.  
🧩 **Explore** cognitive frameworks that make reasoning observable and measurable instead of black-box prompting.  
🔥 **Discover** production-grade open-source tools for **agentic reasoning, meta-learning, and cognitive observability.**  
🎓 **Learn** from frameworks inspired by ReAct, Reflexion, Tree-of-Thoughts, Voyager, Meta-CoT, and Claude Code.  

---

## 📂 Featured Cognitive Frameworks

### 🧠 Core Cognitive Loops
| Project | Description |
|----------|--------------|
| [**Noēsis**](https://github.com/saraeloop/noesis) | Cognitive loop framework that turns reasoning into observable artifacts (state, events, insight, learn). |
| [**LangGraph**](https://github.com/langchain-ai/langgraph) | Graph-based agent orchestration and memory for reasoning workflows. |
| [**CrewAI**](https://github.com/joaomdmoura/crewai) | Multi-agent orchestration system for collaborative cognitive processes. |
| [**MetaGPT**](https://github.com/geekan/MetaGPT) | Multi-agent “software company” simulation with shared planning and reasoning memory. |
| [**OpenDevin**](https://github.com/OpenDevin/OpenDevin) | Open-source autonomous software engineering agent with task reasoning. |

---

### 🧭 Reasoning, Planning & Reflection
- 🧩 [**ReAct**](https://github.com/ysymyth/ReAct) — *Reason + Act* prompting framework for interpretable thinking loops.  
- 🪞 [**Reflexion**](https://github.com/noahshinn/reflexion) — Agents that self-evaluate and improve through reflection.  
- 🌲 [**Tree-of-Thoughts**](https://github.com/kyegomez/tree-of-thoughts) — Structured reasoning via multi-path search.  
- 🚀 [**Voyager**](https://github.com/MineDojo/Voyager) — Continual-learning embodied agent using self-improving cognition.  
- 🧬 [**Meta-CoT**](https://github.com/zjunlp/Meta-CoT) — Meta-learning framework for adaptive reasoning strategies.  

---

### 🤝 Multi-Agent Cognition
- ♾️ [**Swarm**](https://github.com/openai/swarm) — Composable multi-agent collaboration framework by OpenAI.  
- 🧑‍💼 [**CAMEL**](https://github.com/camel-ai/camel) — Role-based collaborative AI agents for goal-driven tasks.  
- 🏗️ [**SuperAGI**](https://github.com/TransformerOptimus/SuperAGI) — Autonomous agent platform for production environments.  
- 📰 [**ChatDev**](https://github.com/OpenBMB/ChatDev) — Multi-agent simulation of a software company.  

---

### 🧩 Observability & Cognitive Metrics
- 🧠 [**Noēsis Viewer CLI**](https://github.com/saraeloop/noesis) — Inspect reasoning traces, plan adherence, veto counts, and insight metrics.  
- 📊 [**LangSmith**](https://smith.langchain.com/) — Trace visualization and evaluation for LangChain agents.  
- 🔎 [**Helicone**](https://github.com/Helicone/helicone) — Telemetry and logging for LLM reasoning calls.  
- 🧪 [**Braintrust**](https://github.com/braintrustdata/braintrust) — Evaluation and version control for agent reasoning.  

---

### 📚 Key Research Papers
- **ReAct (Yao et al., 2022)** – *Synergizing Reasoning and Acting in Language Models*  
- **Reflexion (Shinn et al., 2023)** – *Language Agents that Learn to Self-Improve via Reflections*  
- **Tree-of-Thoughts (Yao et al., 2023)** – *Deliberate Problem Solving with LLMs*  
- **Voyager (Wang et al., 2023)** – *An Open-Ended Embodied Agent with LLMs*  
- **Meta-CoT (Zhang et al., 2024)** – *Learning to Learn Reasoning Strategies*  
- **Claude Code / Deep Research (Anthropic, 2024)** – *Structured multi-phase cognitive workflows.*

---

## 🧬 Cognitive Architectures (Classics)
| Name | Description |
|------|--------------|
| 🧱 **Soar** | Symbolic cognitive architecture for goal-directed reasoning. |
| 🧩 **ACT-R** | Psychology-inspired model for memory and decision-making. |
| 🧠 **CLARION** | Hybrid connectionist/symbolic architecture unifying implicit and explicit cognition. |

---

## ⚙️ Related Topics
- Cognitive Loops & Agentic Reasoning  
- Reflective Learning Systems  
- Governance & Veto Metrics  
- Multi-Agent Collaboration  
- Memory Architectures (FAISS, SQLite, HNSW)  
- Meta-Learning & Self-Improvement  
- Cognitive Trace Visualization  

---

## 🌟 How to Contribute
Pull requests welcome!  
Add new frameworks, papers, or demos following the format below:

```markdown
- **[ProjectName](link)** — One-line description of what it contributes to cognitive AI.

## License

- List content: **CC BY 4.0**
- Repo code (scripts/): **MIT**

> Please attribute the list in derivatives. See [LICENSE](LICENSE).