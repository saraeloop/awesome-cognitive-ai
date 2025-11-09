[English](README.md) | [Español](docs/README.es.md)

# 🌟 Awesome Cognitive-AI

> Build agents that *think out loud*: **plan → act → observe → reflect → learn**.  
> A curated, fact-checked map of frameworks, patterns, papers, datasets, and tools for **inspectable cognition**.

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</p>

**Like what you find?** Drop a 👍 · ⭐ · 👏 on the repos you use — it helps the maintainers (and future you).

---

## ✨ Why this list?
- **Cognition-first**, not hype-first — explicit loops, memory, telemetry, guardrails.
- **Metadata-rich** — license, maintenance, and eval signals for sane adoption.
- **Traceable by design** — prefer projects that emit **events/traces/eval artifacts**.
- **Clear disclosure** — maintainer entries are marked _Maintainer-Contributed_.

---

## 🕹️ How to use this repo
1. **Pick a lane** in the taxonomy (frameworks, memory, eval, observability, …).
2. **Skim the metadata** for each entry (license ✔, maintenance 🔧, artifacts 📄).
3. **Ship trace-first** — choose tools that expose state/events and wire up observability.
4. **Contribute back** — see [CONTRIBUTING.md](CONTRIBUTING.md) for the JSON schema + checklist.

> Pro tip: Treat your agent like a service. Logs, metrics, and a postmortem folder save lives 🧯.

---

## 🧭 Taxonomy at a glance

| Category | Focus |
| --- | --- |
| **Cognition & Loops** | Make planning, acting, reflection, and learning explicit. |
| **Frameworks** | LangGraph, CrewAI, OpenAI Agents SDK, and friends. |
| **Memory** | Short/long-term memory, entities, vector/index backends. |
| **Evaluation** | RAG, safety, reasoning, regression, HIL review. |
| **Observability** | Telemetry, tracing, prompt diffing, replay/debug tooling. |
| **Guardrails & Safety** | Policies, constrained decoding, classifiers, red teaming. |
| **MCP** | Model Context Protocol servers, registries, tooling. |
| **RAG** | Retrieval, hybrid search, routing, distillation, monitoring. |
| **Datasets** | Reasoning, tool-use, safety, multi-hop QA. |
| **Papers** | Cognition, loops, reflection, RAG, agent eval. |
| **Production Systems** | Blueprints, ref-archs, and case studies. |

---

## 🧺 Curated catalog

> ✅ Auto-generated from `/catalog/items/**` via CI. Don’t edit here — use [CONTRIBUTING](CONTRIBUTING.md).

<!-- BEGIN:CATALOG -->
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

### Cognition & Loops
- **Noēsis** — Cognitive loop + artifacts (state/events/memory/insight). _Maintainer-Contributed; Disclosure in entry._
<!-- END:CATALOG -->

---

## 🗺️ Field guide (quick picks)

### Core cognitive loop frameworks
| Project | Highlights |
| --- | --- |
| [**LangGraph**](https://github.com/langchain-ai/langgraph) | Typed orchestration, checkpoints, human approval hooks. |
| [**CrewAI**](https://github.com/joaomdmoura/crewai) | Role agents, shared memory, tools. |
| [**MetaGPT**](https://github.com/geekan/MetaGPT) | Multi-agent “virtual company” with planning/review. |
| [**OpenDevin**](https://github.com/OpenDevin/OpenDevin) | Autonomous SE agent with inspectable reasoning. |
| [**Noēsis**](https://github.com/saraeloop/noesis) | Emits state/events/insight artifacts for replay & eval. |

### Observability, telemetry & QA
- [**Langfuse**](https://github.com/langfuse/langfuse) · [**LangSmith**](https://smith.langchain.com/) · [**Helicone**](https://github.com/Helicone/helicone) · [**Braintrust**](https://github.com/braintrustdata/braintrust) · [**HoneyHive**](https://www.honeyhive.ai/)

### 🧠 Memory & knowledge substrates
- [**Mem0**](https://github.com/mem0ai/mem0) · [**LlamaIndex**](https://github.com/run-llama/llama_index) · [**Pinecone**](https://www.pinecone.io/) · [**Weaviate**](https://weaviate.io/) · [**Chroma**](https://github.com/chroma-core/chroma) · [**Qdrant**](https://github.com/qdrant/qdrant)

### Evaluation & measurement
- [**Ragas**](https://github.com/explodinggradients/ragas) · [**TruLens**](https://github.com/truera/trulens) · [**OpenAI Evals**](https://github.com/openai/evals) · [**Giskard**](https://github.com/Giskard-AI/giskard) · [**DeepEval**](https://github.com/confident-ai/deepeval)

### Multi-agent coordination
- [**Swarm**](https://github.com/openai/swarm) · [**CAMEL**](https://github.com/camel-ai/camel) · [**SuperAGI**](https://github.com/TransformerOptimus/SuperAGI) · [**ChatDev**](https://github.com/OpenBMB/ChatDev) · [**AutoGen**](https://github.com/microsoft/autogen)

### Starter kits & tutorials
- [**OpenAI Agents SDK Quickstart**](https://github.com/openai/openai-agents-quickstart) · [**Google ADK**](https://github.com/google-deepmind/agent-framework) · [**Voyager**](https://github.com/MineDojo/Voyager) · [**Reflexion**](https://github.com/noahshinn/reflexion) · [**LangGraph examples**](https://github.com/langchain-ai/langgraph/tree/main/examples)

---

## 📚 Books & Foundational Works (fun edition)
- **Miller, Galanter, Pribram — _Plans and the Structure of Behavior_ (1960)** — the OG **TOTE loop**.  
- **Newell & Simon — _Human Problem Solving_ (1972)** — why planning matters.  
- **Minsky — _Society of Mind_ (1986)** — tiny agents, big brain.  
- **Anderson — _Cognitive Psychology…_ (ACT-R)** — memory that actually remembers.  
- **Hawkins — _On Intelligence_** — predictive coding before it was cool.  
- **Russell — _Human Compatible_** — alignment as cognitive control.

(See full list with links in the Books section below.)

---

## 🛠️ Getting hands-on
1. Fork/clone and point CI at your `/catalog/items` JSON.  
2. Use entries as **sourcing** for evals and due diligence.  
3. Ship with tracing & evals **before** the demo video.  
4. Share repro notes and post-incident writeups via PRs 📨.

---

## 🤝 Contributing
- Open an issue to pitch ideas.  
- Add `catalog/items/<category>/<project>.json` per the schema.  
- Run the format/regenerate scripts (see **CONTRIBUTING.md**).  
- Disclose affiliations; tag your stuff as _Maintainer-Contributed_.  
- Keep blurbs ≤ 140 chars with authoritative links.

---

## 📜 License
- List content: **CC BY 4.0**  
- Scripts/tooling: **MIT**  
Please attribute when you remix or embed sections. See [LICENSE](LICENSE).