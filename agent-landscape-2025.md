# Agent Landscape 2025 — Functional Role Architecture

This document provides an updated classification of intelligent agents in 2025, reflecting the growing ecosystem across major AI companies and emerging startups.  
We organize agents by their **dominant operational function**—how they reason, act, communicate, and self-improve.

---

## Functional Role Framework

A developer-friendly breakdown of how agents operate:

| Role Type | What It Does | Developer Analogy | Keywords |
|-----------|---------------|-------------------|----------|
| **Reasoning** | Thinks for you | Code logic engine / problem solver | planning, coding, analysis |
| **Narrative** | Talks to you | Chatbot / assistant / presenter | summarizing, storytelling |
| **Execution** | Acts for you | Macro / shell / API client | clicking, calling APIs, automating |
| **Reflection** | Improves itself | CI/CD + learning loop | self-update, recursive planner |

---

## Big Tech Agents

| Company        | Agent / Product        | Description | Functional Flow | Notes |
|----------------|------------------------|-------------|------------------|-------|
| **OpenAI**     | **Operator (CUA)**     | Desktop agent for file/app/command control | **Execution → Reasoning → Narrative** | MCP adopted |
|                | GPTs + Custom Tools    | User-defined AI agents | **Reasoning / Narrative** | Interface-limited |
| **Anthropic**  | Claude Computer Use    | Local file and system command access | **Execution** | Integrated in Claude 3.5 |
|                | MCP Protocol           | Agent interop protocol | **Reasoning → Execution** | Openly adopted |
| **Google**     | Gemini + Robotics      | Fusion of vision, robotics, and planning | **Reasoning → Execution → Reflection** | Gr00T N1 project |
| **Apple**      | Apple Intelligence     | GPT-4o + Siri integration | **Execution → Narrative** | iOS ecosystem |
| **Microsoft**  | Magentic-One           | Backend Copilot+PC orchestrator | **Execution** | Windows-native |
| **Meta**       | Meta AI                | Social-native agent for dialog & content | **Narrative** | Instagram, WhatsApp, etc. |

---

## Notable Startups & Research Projects

| Project         | Agent Name        | Description | Functional Flow | Notes |
|-----------------|------------------|-------------|------------------|-------|
| **Cognition**   | **Devin**        | Full-stack AI software engineer | **Reasoning → Execution → Reflection** | Self-looping planner |
| **Cursor**      | Agent Mode       | In-editor autonomous coder | **Execution** | VSCode-based, MCP |
| **Manus AI**    | Manus            | Research + API execution agent | **Execution → Reasoning** | Scientific toolchain |
| **MainFunc**    | MainFunc Agent   | Terminal command assistant | **Execution** | CLI-focused |
| **Genspark**    | Spark Agents     | Dialog-first action agent | **Narrative → Execution** | LLM-native UX |
| **AI Co-Scientist** | -           | Academic collaboration agent | **Reasoning → Reflection** | Scientific design partner |

---

## Open Source Ecosystem

| Project         | Agent Type              | Functional Flow | Notes |
|-----------------|-------------------------|------------------|-------|
| AutoGPT         | Task-chain executor     | **Execution** | Early experimental |
| AgentGPT        | Web UI over AutoGPT     | **Execution** | User interface layer |
| CrewAI          | Role-based multi-agent  | **Narrative / Execution** | Task delegation system |
| LangGraph       | DAG-based agent graph   | **Reasoning → Execution → Reflection** | Memory + stateful logic |
| LangChain Agents| Function-calling agent chains | **Reasoning / Execution** | Widely adopted |

---

## MCP Timeline

- **Nov 2024**: MCP proposed by Anthropic
- **Mar 2025**: Operator (OpenAI) adopts MCP
- **Apr 2025**: Google joins MCP stack
- **Cursor / Manus / MainFunc** align with MCP-compatible runtime

---

## Reflective Agent Highlights

- **Devin**, **Gemini+Robotics**, and **LangGraph** are early examples of **adaptive recursive agents**
- **MCP** helps unify agent ecosystems across companies through a shared protocol

---

## Summary by Functional Role

### Reasoning Agents
- Devin
- Claude
- LangGraph
- LangChain Agents

### Narrative Agents
- Meta AI
- ChatGPT
- Genspark
- CrewAI

### Execution Agents
- Operator
- Apple Intelligence
- Cursor
- MainFunc
- Manus

### Reflective Agents
- Devin
- Gemini + Robotics
- LangGraph

---

> This classification supports both theoretical clarity and developer intuition. It frames agents by their **dominant operational behavior**, not their branding.
