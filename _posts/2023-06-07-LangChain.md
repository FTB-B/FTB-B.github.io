---
title:  "LLM: LangChain"
category: posts
date: 2023-06-07
excerpt: "Large Language Models"
---

## <a id="introduction">1. Introduction</a>
LangChain, fundamentally, is a framework designed around Large Language Models (LLMs). It has extensive applications including, but not limited to, chatbots, Generative Question-Answering (GQA), and summarization.
The central principle of this library is the ability to "chain" diverse components to generate more complex use cases involving LLMs.
Such chains can incorporate multiple elements from a variety of modules:
- Prompt Templates: These serve as models for different kinds of prompts, such as those designed for chatbots or ELI5 (Explain Like I'm Five) question-answering scenarios.

- LLMs: These are substantial language models, such as GPT-3 and BLOOM.

- Agents: These utilize LLMs to determine the appropriate actions to be carried out. They can employ tools like web search or calculators, all of which are integrated into a coherent operation cycle.

- Memory: This includes both short-term and long-term memory.
