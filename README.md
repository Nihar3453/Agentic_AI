# Agents and Tools: Practical LLM Tool-Use with Mistral & LangGraph

This repository demonstrates how to build, integrate, and experiment with tool-using language agents using open and commercial LLMs. It includes both a minimal LLM+tools workflow and an advanced flow-based agent leveraging LangGraph for multi-step tool orchestration.

---

## Notebooks

### **Agents_and_Tools.ipynb**

Shows how to connect a powerful LLM (Mistral model) to a set of Python functions (tools) and use function-calling to answer user queries with factual, real-time data from a pandas DataFrame.

Covers API key setup, Mistral client usage, pandas dataset simulation, tool definition, tool-to-model linkage, and interaction cycles.

Includes end-to-end examples like querying payment status, transaction amount, or date using natural language.

---

### **Agents_and_Tools_LangGraph.ipynb**

Explores the LangGraph library for advanced agent flows, building a modular call chain where LLM-generated tool selections trigger function calls and merge responses.

Illustrates multi-stage prompt-tool-model planning, conditional logic between graph nodes (planning → execution → synthesis), and stateful conversation handling.

Brings more structure to agent orchestration compared to a one-shot tool-using assistant.

---

## Key Features

* Uses Mistral AI LLMs for conversational and tool-assisted reasoning.
* Realistic, extensible DataFrame data demo (transaction/payments).
* Self-contained: All code, data, and logic are in Jupyter notebooks—run in Colab or locally.
* Both minimal and modular approaches shown (basic vs. LangGraph).

--

## Use Cases

* Retrieval-augmented generation (RAG) with live lookups.
* Agent-based workflows (planning, tool use, synthesis).
* Reference for LLM tool-use, function-calling, and chaining agent design.
