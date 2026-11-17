# Ziting Niu

**AI Agent Engineering · Agent Harness & Context Engineering · LLM Systems**

Hello! I'm Ziting Niu. I build AI agents and the engineering systems that make them reliable, and efficient. My work spans agent runtimes, context management, tool orchestration, failure recovery, and evaluation-driven iteration.

I'm particularly interested in making non-deterministic models reliable within deterministic engineering systems, from the first working prototype to a robust application.


[Selected projects](#selected-projects) · [Engineering notes](#engineering-notes) · [Open-source work](#open-source-work) · [Technical focus](#technical-focus)

---

## Selected projects

### Next Task · AI Task Manager

**An AI-native task management platform built from the ground up.**

A full-stack application combining natural-language task management, authenticated tool execution, an MCP server, document RAG, and a fine-tuned Qwen3 model. The project brings together agent runtime design, application engineering, and evaluation-driven development.

`Python` `FastAPI` `MCP` `PostgreSQL` `pgvector` `Redis` `React` `TypeScript`

[Live demo](https://eighthhdayy.github.io/ai-task-manager/) · [Source code](https://github.com/EighthhDayy/ai-task-manager) · [Architecture](https://github.com/EighthhDayy/ai-task-manager#system-architecture)

### Transformer-Based Question Answering

**Model adaptation, evaluation, and inference.**

An extractive and generative QA system using DistilBERT and Qwen3-0.6B, with supervised fine-tuning via 4-bit QLoRA. On an 80-example pilot evaluation, token F1 improved from **29.20% to 60.44%**, with a trade-off in false abstentions on answerable questions.

`PyTorch` `Transformers` `TRL` `PEFT` `QLoRA` `SQuAD 2.0`

[Source code](https://github.com/EighthhDayy/Transformer-Based-Question-Answering-System) · [Evaluation results](https://github.com/EighthhDayy/Transformer-Based-Question-Answering-System#qwen3-qlora--observed-results)

### Automotive Sales Decision Support

An applied machine learning system combining budget prediction, customer segmentation, vehicle recommendations, and pricing simulation.

`XGBoost` `K-means` `KNN` `Scikit-learn`

[Source code](https://github.com/EighthhDayy/Automotive-Budget-Prediction-and-Pricing-Model)

---

## Engineering notes

### Agent Notes

A collection of my technical reflections, architectural insights, and practical lessons from building AI agents. I write about agent engineering, system reliability, design decisions, and what I learn along the way.

[Read my engineering notes](https://github.com/EighthhDayy/agent-notes)

## Open-source work

### OpenAI Codex · Rust

Investigated an error-propagation defect in remote context compaction, implemented a patch to surface the actual fallback-model error, and added regression coverage.

[View the patch in my fork](https://github.com/EighthhDayy/codex/pull/1)

## Technical focus

| Area | Focus |
| :--- | :--- |
| Agent Engineering | Agent runtimes, tool calling, MCP, state management, human-in-the-loop |
| Harness & Context Engineering | Checkpoint recovery, idempotency, circuit breakers, context compression, memory management |
| Agent Evaluation | Custom benchmarks, deterministic evaluation, end-to-end LLM evaluation |
| LLM Engineering | SFT, QLoRA, model quantization, inference services, RAG |
| Software Engineering | Python, Rust, FastAPI, PostgreSQL, Redis, React, TypeScript, Docker, pytest |
