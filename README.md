# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 


<div align="center">
    <a title="Awesome AI Agents" href="https://github.com/Smithech/awesome-ai-agent">
        <img src="assets/banner.png" width="768" alt="Awesome AI Agent Banner"/>
    </a>
    <br>
</div>


 > Build and deploy autonomous and multi-agent systems powered by large language models (LLMs). 

## Contents

- [Cloud Platforms for Agents](#cloud-platforms-for-agents)
- [Context Processing](#context-processing)
    - [Embedding models](#embedding-models)
    - [Transformers](#transformers)
- [Foundation Models Providers](#foundation-models-providers)
- [Inference Providers](#inference-providers)
- [Interoperability Protocols](#interoperability-protocols)
- [Local LLM Tools](#local-llm-tools)
- [Observability](#observability)
- [Orchestration Frameworks](#orchestration-frameworks)
- [Sandboxes](#sandboxes)
- [Learning resources](#learning-resources)
    - [Google](#google) 
    - [Huggin Face](#huggin-face)
    - [LangChain](#langchain)
    - [Microsoft](#microsoft)


## Cloud Platforms for Agents

- [Amazon Bedrock](https://aws.amazon.com/bedrock/) - The AWS platform for building generative AI applications and agents.
- [Vertex AI Agent Builder](https://docs.cloud.google.com/agent-builder) - A suite of Google Cloud products designed to build, scale, and manage AI agents in production environments.


## Context Processing

### Embedding models
- [Harrier OSS](https://huggingface.co/microsoft/harrier-oss-v1-0.6b) - A family of multilingual text embedding models developed by Microsoft.
- [OpenAI Embedding Models](https://developers.openai.com/api/docs/guides/embeddings) - Large and small models developed by OpenAI.

### Transformers
- [Huggin Face Transformers](https://huggingface.co/docs/transformers/index) - HF library for Transformers with hundreds of models.


## Foundation Models Providers

- [Anthropic Claude](https://claude.ai/) - Foundational models such as Haiku, Opus, and Sonnet.
- [Google DeepMind](https://deepmind.google/models/) - The Gemini family and Gemma open models, spanning multimodal and lightweight use cases.
- [Meta LLaMA](https://www.llama.com/) - A family of open-weight language models designed for developers and researchers, supporting fine-tuning, adaptation, and deployment across a broad ecosystem.
- [Open AI](https://developers.openai.com/api/docs/models) - Frontier and specialized models for text, image, speech-to-speech, text-to-speech and transcription tasks. 

## Inference Providers

- [Cerebras](https://www.cerebras.ai/) - High-performance AI inference infrastructure focused on large-scale workloads and low-latency execution.
- [Cohere](https://cohere.com/) - Enterprise-oriented language models and inference APIs for NLP and retrieval-based applications.
- [Fal](https://fal.ai/) - Platform for running and fine-tuning generative media models (image, video, audio) using serverless and on-demand GPU infrastructure.
- [Hyperbolic](https://www.hyperbolic.ai/) - Open-access cloud platform for running and serving AI models.
- [Featherless](https://featherless.ai/) - Infrastructure for deploying and serving open-weight models with minimal setup.
- [Fireworks](https://fireworks.ai/) - Inference platform for open-source models with optimization for performance, scalability, and customization.
- [Groq](https://groq.com/) - Low-latency inference platform powered by custom hardware for deterministic model execution.
- [HF Inference](https://huggingface.co/docs/inference-providers/providers/hf-inference) - Serverless inference APIs provided by Hugging Face for deploying and consuming machine learning models.
- [Novita](https://novita.ai/) - Unified API platform for accessing and deploying multiple models and running agent-based workflows.
- [Nscale](https://www.nscale.com/) - Infrastructure provider covering compute, storage, and deployment for AI systems across environments.
- [ovhOVH AI Endpoints](https://www.ovhcloud.com/en/public-cloud/ai-endpoints/) - Managed APIs for integrating and serving machine learning and generative AI models.
- [Public AI](https://publicai.co/) - Open-source and nonprofit initiative providing shared infrastructure for public AI model access and experimentation.
- [Replicate](https://replicate.com/) - Platform for running, deploying, and fine-tuning models via API-based workflows.
- [SambaNova](https://sambanova.ai/) - AI inference systems built on specialized hardware and software for large-scale model execution.
- [Scaleway](https://www.scaleway.com/en/) - Cloud platform supporting the deployment and scaling of AI models and applications.
- [Together AI](https://www.together.ai/) - Platform for training, fine-tuning, and serving open and research-driven AI models.
- [WaveSpeedAI](https://wavespeed.ai/) - Infrastructure for accelerating generative media workloads, particularly image and video models.
- [Zai](https://chat.z.ai/) - Platform providing access to conversational AI and agent-based systems.


## Interoperability Protocols

- [Agent2Agent (A2A)](https://a2a-protocol.org/latest/) - An open standard designed to enable seamless communication and collaboration between AI agents.
- [Agent Payments Protocol (AP2)](https://agentpaymentsprotocol.info/) - An open protocol for the emerging Agent Economy. It enables secure, reliable, and interoperable agent commerce for developers, merchants, and the payments industry.
- [Model Context Protocol - (MCP)](https://modelcontextprotocol.io/docs/getting-started/intro) - An open-source standard for connecting AI applications to external systems.


## Local LLM Tools
 
- [DiffusionBee](https://diffusionbee.com/) - Desktop application for running generative models locally, with a focus on image generation.
- [Docker Model Runner](https://docs.docker.com/ai/model-runner/) - Tooling for managing, running, and deploying AI models within Docker-based environments.
- [Draw Things](https://drawthings.ai/) - Application for running image generation models locally, with support for offline workflows.
- [Jan](https://www.jan.ai/) - Local-first AI assistant designed to run models privately on user devices.
- [JellyBox](https://jellybox.com/) - Environment for running AI models locally with full offline support.
- [Lemonade](https://lemonade-server.ai/) - Open-source local AI runtime for deploying and interacting with models on personal hardware.
- [Local AI](https://localai.io/) - Self-hosted AI stack for running language models, agents, and related workloads locally.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Lightweight inference engine in C/C++ for running large language models on local hardware.
- [LM Studio](https://lmstudio.ai/) - Desktop interface for discovering, running, and interacting with local language models.
- [MLX LM](https://github.com/ml-explore/mlx-lm) - Python library for inference and fine-tuning of language models on Apple Silicon using MLX.
- [Ollama](https://ollama.com/) - Tool for running and managing language models locally with a simplified CLI and API.
- [SGLang](https://github.com/sgl-project/sglang) - High-performance framework for serving language and multimodal models.
- [Unsloth](https://unsloth.ai/) - Toolkit for running and fine-tuning models locally, with support for offline environments. 
- [vLLM](https://vllm.ai/) - Inference and serving engine optimized for throughput and memory efficiency in LLM workloads.


## Observability

- [LangSmith Platform](https://www.langchain.com/langsmith-platform) - Framework-agnostic platform for monitoring, evaluating, and debugging LLM applications and agents.


## Orchestration Frameworks

- [Deep Agents](https://www.langchain.com/deep-agents) - Open-source agent framework for long-running tasks, with support for planning, context management, and multi-agent coordination.
- [Google Agent Development Kit (ADK)](https://google.github.io/adk-docs/) - Framework for building AI agents with a model-agnostic and deployment-agnostic design.
- [LangChain](https://www.langchain.com/langchain) - Open-source framework providing abstractions, integrations, and tooling for building LLM-powered applications.
- [LangGraph](https://www.langchain.com/langgraph) - Low-level orchestration framework for building and running stateful, long-lived agent workflows.
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) - Framework for developing agent-based systems, supporting both simple interactions and multi-agent workflows with graph-based orchestration in .NET and Python. 


## Sandboxes

- [Amazon Bedrock AgentCore](https://docs.aws.amazon.com/bedrock-agentcore/) - Managed environment for deploying and running AI agents with support for multiple models and frameworks.
- [Daytona](https://www.daytona.io/) - Infrastructure for executing AI-generated code in isolated and reproducible environments.
- [Modal Sandboxes](https://modal.com/products/sandboxes) - Serverless container-based environments for running AI-generated code with support for dynamic configuration and GPU workloads.
- [Runloop](https://runloop.ai/) - Ephemeral development environments for executing code in isolation, with support for agent-based workflows and evaluation pipelines.


## Learning resources

### Google
- [5-Day AI Agents Intensive Course with Google](https://www.kaggle.com/learn-guide/5-day-agents) - Learn guide so anyone can explore the foundations, architecture and practical development of AI agents.
- [5-Day Gen AI Intensive Course with Google](https://www.kaggle.com/learn-guide/5-day-genai) - Learning guide for exploring the fundamental technologies and techniques behind Generative AI.

### Huggin Face 
- [AI Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) - This free course will take you on a journey, from beginner to expert, in understanding, using and building AI agents.
- [MCP Course](https://huggingface.co/learn/mcp-course/unit0/introduction) - This free course, built in partnership with Anthropic, will take you on a journey, from beginner to informed, in understanding, using, and building applications with MCP. 

### LangChain 
- [Ambient Agents with LangGraph](https://academy.langchain.com/courses/ambient-agents) - Build your own ambient agent to manage your email. You’ll learn the fundamentals of LangGraph as you build an email assistant from scratch, and use LangSmith to evaluate its performance.
- [Building Reliable Agents](https://academy.langchain.com/courses/building-reliable-agents) - Take an agent from first run to production-ready system through iterative cycles of improvement with LangSmith, the agent engineering platform for observing and evaluating agents.
- [Deep Agents](https://academy.langchain.com/courses/deep-agents-with-langgraph) - Learn the fundamental characteristics of Deep Agents and how to implement your own Deep Agent for complex, long-running tasks.
- [Deep Research with LangGraph](https://academy.langchain.com/courses/deep-research-with-langgraph) - Build your own deep research agent to handle research tasks. Learn how to use LangGraph to build a multi-agent system, then use LangSmith to evaluate its performance.
- [Introduction to Agent Observability & Evaluations](https://academy.langchain.com/courses/intro-to-langsmith) - Learn the essentials of agent observability & evaluations with LangSmith. Continuously improve your agents with LangSmith's tools for observability, evaluation, and prompt engineering.
- [Introduction to LangChain - Python](https://academy.langchain.com/courses/foundation-introduction-to-langchain-python) - Learn how to build AI agents with LangChain. Get started quickly using pre-built architectures and model integrations, then debug your agents with LangSmith Observability.
- [Introduction to LangGraph - Python](https://academy.langchain.com/courses/intro-to-langgraph) - Learn the basics of LangGraph, the framework helps developers add better precision and control into agentic workflows.
- [Quickstart courses](https://academy.langchain.com/collections/quickstart) - Collection of quickstart courses about LangChain, LangGraph and LangSmith.

### Microsoft
- [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) - A course teaching everything you need to know to start building AI Agents.
- [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners/) - Learn MCP with Hands-on Code Examples in C#, Java, JavaScript, Rust, Python, and TypeScript.
- [Python + Agentes: Creando agentes y flujos de IA](https://developer.microsoft.com/es-es/reactor/series/s-1633/) - \[Spanish version] A series that explores the foundational concepts behind building AI agents in Python using the Microsoft Agent Framework.
- [Python + Agents: Building AI agents and workflows](https://developer.microsoft.com/es-es/reactor/series/s-1631/) - \[English version] A series that explores the foundational concepts behind building AI agents in Python using the Microsoft Agent Framework.


## Contributing

Your contributions and suggestions are heartily welcome. Please check the [Contributing Guidelines](contributing.md) for more details.
