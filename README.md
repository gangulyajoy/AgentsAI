# The Future of Gen AI: Tools and media 

* ( Agents )
* AGS

# AI Agents Masterclass — CrewAI & SmolAgents

Welcome to the **AI Agents Masterclass**, where we explore how to build and orchestrate intelligent agents using **CrewAI** and **SmolAgents**.

---

## 📘 Table of Contents

1. [What Are AI Agents?](#what-are-ai-agents)
2. [Key Concepts](#key-concepts)
3. [Agent Frameworks Overview](#agent-frameworks-overview)
4. [CrewAI Basics](#crewai-basics)
5. [SmolAgents Basics](#smolagents-basics)
6. [Real-World Use Cases](#real-world-use-cases)
7. [Design Patterns for Agents](#design-patterns-for-agents)
8. [Advanced Topics](#advanced-topics)
9. [Resources](#resources)

---

## 🧬 What Are AI Agents?

**AI Agents** are autonomous programs that perceive their environment, reason about it, and take actions to achieve specific goals.

In our context, they:

* Use **LLMs (like GPT-4)** for reasoning.
* Interact via **tools, APIs, or prompts**.
* Operate **individually** or in **multi-agent systems (MAS)**.

---

## 🔑 Key Concepts

| Concept          | Definition                                                         |
| ---------------- | ------------------------------------------------------------------ |
| **Agent**        | A program that can observe, decide, and act to fulfill a goal.     |
| **Tool**         | An external API, function, or service the agent can call.          |
| **LLM**          | The language model (e.g. GPT-4) that powers the agent's reasoning. |
| **Memory**       | Stores past interactions or decisions for context-aware reasoning. |
| **Environment**  | The space in which agents act (can be abstract or interactive).    |
| **Autonomy**     | Degree to which agents act without human intervention.             |
| **Coordination** | How multiple agents collaborate or negotiate tasks.                |

---

## 🛠 Agent Frameworks Overview

### ✅ CrewAI

* Designed for **multi-agent collaboration**.
* Inspired by a "movie crew" metaphor: Director, Researcher, Writer, etc.
* Focus on **structured agent roles** and **delegation**.

### ✅ SmolAgents

* Lightweight, **minimalist agent systems**.
* Emphasizes simplicity and chain-of-thought interactions.
* Good for **local-first**, single-agent logic.

---

## 👥 CrewAI Basics

```python
from crewai import Agent, Crew
```

* **Agents** are defined by roles, goals, and tools.
* **Crew** handles orchestration and task management.

**Example Roles:**

* `ResearchAgent`: Fetches data via search APIs.
* `WriterAgent`: Generates structured summaries.

**Key Concepts:**

* Task delegation
* Parallelism
* Agent communication

---

## 🧱 SmolAgents Basics

```python
from smolagents import SmolAgent
```

* Build **single-purpose agents** that use **functions as tools**.
* Focus on **reasoning chains** and **context prompts**.

**Example Workflow:**

* Give agent a goal → Agent reasons through steps → Calls functions.

---

## 🔍 Real-World Use Cases

* Research assistants
* Code generation and refactoring
* Data summarization and extraction
* Automated proposal drafting
* AI-driven agents for customer support or product development

---

## ↺ Design Patterns for Agents

| Pattern              | Description                               |
| -------------------- | ----------------------------------------- |
| **Reflex Agent**     | Reacts to current input (stateless)       |
| **Utility Agent**    | Chooses actions based on expected utility |
| **Planner Agent**    | Plans a sequence of steps to meet a goal  |
| **Team Agents**      | Coordinate tasks among multiple agents    |
| **Chain-of-Thought** | Use intermediate reasoning steps          |

---

## 🚀 Advanced Topics

* Tool execution tracing
* Memory-enabled agents (e.g., via vector DBs)
* Long-term planning
* Autonomy toggling & human-in-the-loop
* Fine-tuning tools and prompts
* Agent evaluation frameworks

---

## 📚 Resources

* [CrewAI GitHub](https://github.com/joaomdmoura/crewAI)
* [SmolAgents GitHub](https://github.com/smol-ai/smol-agents)
* [LangChain Agents](https://docs.langchain.com/docs/components/agents/)
* [AutoGPT / BabyAGI](https://github.com/Torantulino/Auto-GPT) for historical reference
* [ReAct Prompting](https://arxiv.org/abs/2210.03629) — foundation for reasoning+acting


## Agents AI - Definitions

* https://huggingface.co/blog/smolagents
* https://www.anthropic.com/research/building-effective-agents
* https://huggingface.co/docs/smolagents/en/conceptual_guides/intro_agents

## How to Build Effective AI Agents in Pure Python 

* https://www.youtube.com/watch?v=bZzyPscbtI8
* 

## Options

* [crewai.com](https://www.crewai.com)
* not diamond .com

## Repos of AI agent related subjects such as tools, etc

* https://github.com/ALucek?tab=repositories&q=&type=&language=&sort=stargazers

## Gemini AI

* [cook book](https://github.com/google-gemini/cookbook)


## 👋 About

Maintained by [Ricardo Calix](https://www.rcalix.com), author and AI consultant. This repository supports interactive workshops and masterclasses on **AI without code**. Contact: rcalix@rcalix.com

## 📘 Featured Book 

<a href="https://amzn.to/3QmKKwC" target="_blank">
  <img src="https://m.media-amazon.com/images/I/71F2QLFMCFL._SL1233_.jpg" alt="Books" width="300" style="border-radius:10px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);" />
</a>

➡️ **[Grab your copy on Amazon »](https://amzn.to/3QmKKwC)**

---

## ⚠️ Disclaimer

- 🤖 Portions of this content were generated or assisted by AI.
- 🔗 This post includes [Amazon affiliate links](https://amzn.to/3QmKKwC). Purchases made through them may earn a small commission at no extra cost to you.






