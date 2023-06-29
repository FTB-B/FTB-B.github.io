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

For building application with LLM (Large Language Models) we need to have an API-Key for the LLM provider. If you want to use Hugging Face LLM models the API is free, but you might sacrifice accuracy with it. To get more accurate results you can use OpenAPI Key  which cost a little bit of money in your pocket! 
