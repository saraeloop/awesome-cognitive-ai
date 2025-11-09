[English](../README.md) | [Español](README.es.md)

# 🌟 Awesome Cognitive-AI (ES)

> Construye agentes que **piensan en voz alta**: **planificar → actuar → observar → reflexionar → aprender**.  
> Un listado curado y verificado de marcos, herramientas, papers y datasets para **cognición inspeccionable**.

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</p>

**¿Te sirve?** Deja un 👍 · ⭐ · 👏 en los repos que uses — le da vida a los mantenedores (y a tus futuros tú).

---

## ✨ ¿Por qué esta lista?

- **Cognición primero** — prioriza estado, memoria, telemetría y guardrails sobre demos opacas de “agentes”.
- **Rica en metadatos** — cada entrada indica **licencia, mantenimiento y señales de evaluación**.
- **Trazable por diseño** — preferimos proyectos que emiten **eventos/trazas/artefactos de evaluación**.
- **Transparencia** — las entradas de mantenedores se marcan como _Maintainer-Contributed_.

---

## 🕹️ Cómo usarla

1. **Elige tu carril** en la taxonomía (frameworks, memoria, evaluación, observabilidad…).
2. **Lee los metadatos** de cada entrada (licencia ✔, mantenimiento 🔧, artefactos 📄).
3. **Construye “trace-first”** — usa herramientas que expongan estado/eventos y cablea observabilidad.
4. **Devuélvele amor al ecosistema** — mira [CONTRIBUTING.md](../CONTRIBUTING.md) para el esquema JSON + checklist.

> Pro tip: Trata a tu agente como a un servicio. Logs, métricas y una carpeta de postmortems salvan horas 🧯.

---

## 🧭 Taxonomía resumida

| Categoría | Enfoque |
| --- | --- |
| **Cognición y bucles** | Fases explícitas: plan/act/observe/reflect/learn. |
| **Marcos** | Frameworks de agentes y workflows (LangGraph, CrewAI, OpenAI Agents SDK). |
| **Memoria** | Capas de memoria, entidades, vectores/índices. |
| **Evaluación** | RAG, seguridad, razonamiento, regresión, HIL. |
| **Observabilidad** | Telemetría, trazas, diff de prompts, replay/debug. |
| **Guardrails y seguridad** | Políticas, constrained decoding, clasificadores, red-teaming. |
| **MCP** | Servidores, registros y tooling del Model Context Protocol. |
| **RAG** | Recuperación, búsqueda híbrida, enrutamiento, distillation, monitoreo. |
| **Datasets** | Razonamiento, tool-use, seguridad, multi-hop QA. |
| **Papers** | Cognición, bucles, reflexión, RAG, evaluación de agentes. |
| **Sistemas productivos** | Blueprints, ref-arch y estudios de caso.

---

## 🧺 Catálogo curado

> ✅ Esta sección se **auto-genera** desde `/catalog/items/**`. No la edites aquí — usa [CONTRIBUTING](../CONTRIBUTING.md).

<!-- BEGIN:CATALOG -->
### Frameworks
- **LangGraph** — Grafo tipado para flujos de agentes; persistencia y HIL.

### Memoria
- **Mem0** — Capa de memoria personalizable con conectores.

### Evaluación
- **Ragas** — Métricas y reportes centrados en RAG.

### Observabilidad
- **Langfuse** — Trazas, spans, prompts, eval y dashboards.

### Guardrails y seguridad
- **Guardrails AI** — Esquemas validados, políticas y controles.

### MCP
- **MCP Spec** — Protocolo para herramientas/servers sobre stdio/HTTP.

### Datasets
- **HotpotQA** — Multi-hop QA para razonamiento.

### Papers
- **Tree of Thought (ToT)** — Búsqueda estructurada de “pensamientos”.

### Sistemas productivos
- [**AutoEval Pipeline**](autoeval-pipeline.md) — Plantilla de CI para evaluación.

### Marcos cognitivos
- **Noesis** — Bucles cognitivos con artefactos de estado/eventos.
<!-- END:CATALOG -->

---

## 🗺️ Guía rápida (selecciones)

### Marcos de bucle cognitivo
| Proyecto | Destacados |
| --- | --- |
| [**LangGraph**](https://github.com/langchain-ai/langgraph) | Orquestación tipada, checkpoints, aprobaciones humanas. |
| [**CrewAI**](https://github.com/joaomdmoura/crewai) | Agentes por rol, memoria compartida y tools. |
| [**MetaGPT**](https://github.com/geekan/MetaGPT) | “Empresa virtual” multi-agente con planning/review. |
| [**OpenDevin**](https://github.com/OpenDevin/OpenDevin) | Agente de ingeniería de software con trazas claras. |
| [**Noēsis**](https://github.com/saraeloop/noesis) | Emite artefactos de estado/eventos/insight para replay y evaluación.

### Observabilidad y QA
- [**Langfuse**](https://github.com/langfuse/langfuse) · [**LangSmith**](https://smith.langchain.com/) · [**Helicone**](https://github.com/Helicone/helicone) · [**Braintrust**](https://github.com/braintrustdata/braintrust) · [**HoneyHive**](https://www.honeyhive.ai/)

### 🧠 Memoria y sustratos de conocimiento
- [**Mem0**](https://github.com/mem0ai/mem0) · [**LlamaIndex**](https://github.com/run-llama/llama_index) · [**Pinecone**](https://www.pinecone.io/) · [**Weaviate**](https://weaviate.io/) · [**Chroma**](https://github.com/chroma-core/chroma) · [**Qdrant**](https://github.com/qdrant/qdrant)

### Evaluación y métricas
- [**Ragas**](https://github.com/explodinggradients/ragas) · [**TruLens**](https://github.com/truera/trulens) · [**OpenAI Evals**](https://github.com/openai/evals) · [**Giskard**](https://github.com/Giskard-AI/giskard) · [**DeepEval**](https://github.com/confident-ai/deepeval)

### Coordinación multi-agente
- [**Swarm**](https://github.com/openai/swarm) · [**CAMEL**](https://github.com/camel-ai/camel) · [**SuperAGI**](https://github.com/TransformerOptimus/SuperAGI) · [**ChatDev**](https://github.com/OpenBMB/ChatDev) · [**AutoGen**](https://github.com/microsoft/autogen)

### Kits de inicio & tutoriales
- [**OpenAI Agents SDK Quickstart**](https://github.com/openai/openai-agents-quickstart) · [**Google ADK**](https://github.com/google-deepmind/agent-framework) · [**Voyager**](https://github.com/MineDojo/Voyager) · [**Reflexion**](https://github.com/noahshinn/reflexion) · [**Ejemplos LangGraph**](https://github.com/langchain-ai/langgraph/tree/main/examples)

---

## 📚 Libros y obras fundamentales (edición divertida)

- **Miller, Galanter, Pribram — _Plans and the Structure of Behavior_ (1960)** — el OG del ciclo **TOTE**.  
- **Newell & Simon — _Human Problem Solving_ (1972)** — por qué planificar importa.  
- **Minsky — _The Society of Mind_ (1986)** — micro-agentes, macro-mente.  
- **Anderson — _Cognitive Psychology… (ACT-R)_** — memoria que realmente recuerda.  
- **Hawkins — _On Intelligence_** — predicción jerárquica antes de que fuera mainstream.  
- **Russell — _Human Compatible_** — alineación como control cognitivo.

---

## 🛠️ Manos a la obra
1. Haz fork/clone y apunta el CI a `/catalog/items`.  
2. Usa las entradas como **fuente** para tus evaluaciones y due diligence.  
3. Lanza con trazas y evaluaciones **antes** del video demo.  
4. Comparte repros y postmortems vía PR 📨.

---

## 🤝 Contribuir
- Abre un issue para proponer ideas.  
- Agrega `catalog/items/<categoria>/<proyecto>.json` según el esquema.  
- Ejecuta los scripts de formateo/regeneración (ver **CONTRIBUTING.md**).  
- Declara afiliaciones; marca lo tuyo como _Maintainer-Contributed_.  
- Mantén descripciones ≤ 140 caracteres con links oficiales.

---

## 📜 Licencia
- Contenido de la lista: **CC BY 4.0**  
- Scripts/tooling: **MIT**  
Por favor atribuye cuando reutilices o mezcles secciones. Ver [LICENSE](../LICENSE).
