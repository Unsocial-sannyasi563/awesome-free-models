# Awesome Free Models [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of free AI models, APIs, and tools you can use without paying a cent.

![Last Updated](https://img.shields.io/badge/Last%20Checked-June%206%2C%202026-brightgreen?style=for-the-badge)
![Models](https://img.shields.io/badge/Models-7-blue?style=flat-square)
![Tools](https://img.shields.io/badge/Tools-50%2B-blue?style=flat-square)
![Sections](https://img.shields.io/badge/Sections-15-blue?style=flat-square)
![License](https://img.shields.io/badge/License-CC0-lightgrey?style=flat-square)

> ✅ All links verified live on June 6, 2026. 5 broken links found and fixed during this check.

Running AI shouldn't require a credit card. This list curates genuinely free models — open-weight models you can self-host, free API tiers from major providers, and tools to run everything locally.

---

## Contents

- [🧠 Open-Weight Models](#-open-weight-models)
- [🔌 Free API Providers](#-free-api-providers)
- [💻 Local Inference Tools](#-local-inference-tools)
- [💬 AI Chatbot UIs](#-ai-chatbot-uis)
- [🤖 AI Coding Assistants](#-ai-coding-assistants)
- [📝 Code Models](#-code-models)
- [🔍 RAG & Vector Databases](#-rag--vector-databases)
- [🧩 Agentic Frameworks](#-agentic-frameworks)
- [🎛 Fine-tuning Tools](#-fine-tuning-tools)
- [✨ Prompt Engineering Tools](#-prompt-engineering-tools)
- [📊 Datasets](#-datasets)
- [☁ Model Hosting Platforms](#-model-hosting-platforms)
- [📚 Learning Resources](#-learning-resources)
- [🏆 Resources & Leaderboards](#-resources--leaderboards)
- [👥 Communities](#-communities)

---

## 🧠 Open-Weight Models

> 📅 Last checked: June 6, 2026

Open-weight models released since March 2026 that you can download and run on your own hardware.

- [Llama 4 Scout / Maverick](https://huggingface.co/meta-llama) — Meta's latest MoE generation. Scout: 109B, 10M context. Maverick: 402B, 1M context. Native multimodal. [[License]](https://github.com/facebookresearch/llama/blob/main/LICENSE)
- [Qwen 3.6-Plus](https://huggingface.co/Qwen) — Agentic coding model with 1M token context. Apache 2.0.
- [DeepSeek V4](https://huggingface.co/deepseek-ai) — Latest generation with extreme cost-efficiency. MIT license.
- [Gemma 4 31B / 26B MoE / E4B / E2B](https://huggingface.co/google) — Fully permissive Apache 2.0. 256K context, native multimodal. New standard for open-weight.
- [GLM-5.1 (Zhipu AI)](https://huggingface.co/THUDM) — 744B MoE model, competitive with top proprietary models. MIT license.
- [MiniMax M3](https://huggingface.co/Minimax) — Frontier-tier 1M context, native multimodal + computer use. MSA architecture.
- [Trinity (Arcee AI)](https://huggingface.co/arcee-ai) — 400B parameter enterprise model. Apache 2.0.

---

## 🔌 Free API Providers

> 📅 Last checked: June 6, 2026

Providers offering free tiers to access models via API — no local hardware required.

- [Google AI Studio](https://aistudio.google.com/) — **Most generous free tier.** Access Gemini 2.5 Flash, Gemini 2.0 Flash, and other models. Generous rate limits for prototyping.
- [OpenRouter](https://openrouter.ai/) — Aggregates 500+ models. Filter by "Free" to see models available at no cost. Includes experimental and subsidized open-weight models.
- [Groq](https://console.groq.com/) — Ultra-fast inference. Free tier includes Llama, Gemma, Mixtral, Whisper models with generous daily rate limits.
- [Hugging Face Inference API](https://huggingface.co/inference-api) — Free tier for thousands of community models. Rate-limited but excellent for testing.
- [NVIDIA NIM](https://build.nvidia.com/) — Free API access to accelerated versions of Llama, Mistral, Gemma, and more on NVIDIA infrastructure.
- [DeepInfra](https://deepinfra.com/) — Serverless inference. Free tier with daily rate limits for popular open-source models.
- [Together AI](https://www.together.ai/) — Free trial credits for new users. Fast inference on open-source models.
- [Fireworks AI](https://fireworks.ai/) — Free tier for community models. Optimized for low latency.
- [SiliconFlow](https://siliconflow.cn/) — Rising platform with free access to many open-source models.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) — Free tier for running select open-source models at the edge.
- [Replicate](https://replicate.com/) — Free tier with limited credits for running open-source models.
- [Poe (Quora)](https://poe.com/) — Free tier with daily credits for GPT-4 mini, Claude instant, and community bots.
- [CatGPT](https://www.catgpt.cc/) — Completely free chat with multiple models, no login required.

---

## 💻 Local Inference Tools

> 📅 Last checked: June 6, 2026

Run models on your own machine — no API keys needed, full privacy.

- [Ollama](https://ollama.com/) — The easiest way to run local LLMs. One command to download and run any model. macOS, Linux, Windows. [GitHub](https://github.com/ollama/ollama)
- [LM Studio](https://lmstudio.ai/) — Polished desktop GUI. Browse, download, and chat with models. Built-in model browser and local API server.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — High-performance C++ inference engine. Runs on CPU and GPU. Supports GGUF quantization. Powers most other local tools.
- [Jan](https://jan.ai/) — Open-source ChatGPT alternative for desktop. Built-in model downloader, local API server. [GitHub](https://github.com/janhq/jan)
- [GPT4All](https://gpt4all.io/) — Privacy-focused local chatbot. Runs on consumer hardware. Built-in model browser. [GitHub](https://github.com/nomic-ai/gpt4all)
- [text-generation-webui (Oobabooga)](https://github.com/oobabooga/text-generation-webui) — Feature-rich web UI. Supports multiple backends (Transformers, llama.cpp, ExLlama, AutoGPTQ).
- [LocalAI](https://localai.io/) — Drop-in OpenAI API replacement. Run models locally with an OpenAI-compatible API. [GitHub](https://github.com/mudler/LocalAI)
- [KoboldCPP](https://github.com/LostRuins/koboldcpp) — Single-file executable for running GGUF models. Focused on story generation but general-purpose.
- [llamafile (Mozilla)](https://github.com/Mozilla-Ocho/llamafile) — Distributable single-file executables that run LLMs. No installation needed.
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput production inference engine. Uses PagedAttention for efficient serving.
- [SGLang](https://github.com/sgl-project/sglang) — Fast inference framework with structured generation and RadixAttention.
- [TensorRT-LLM (NVIDIA)](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA's optimized inference engine. Best performance on NVIDIA GPUs.
- [ExLlamaV2](https://github.com/turboderp/exllamav2) — Optimized inference for Llama-family models. Fastest option for single-GPU inference.
- [Aphrodite Engine](https://github.com/PygmalionAI/aphrodite-engine) — High-performance LLM serving engine with advanced quantization support.
- [TabbyAPI](https://github.com/theroyallab/tabbyAPI) — Lightweight, fast OpenAI-compatible API server for ExLlamaV2.

---

## 💬 AI Chatbot UIs

> 📅 Last checked: June 6, 2026

Free, open-source web interfaces for chatting with AI models — self-host or use hosted versions.

- [Open WebUI](https://openwebui.com/) — Feature-rich ChatGPT-like interface for Ollama and OpenAI-compatible backends. RAG, image generation, multi-user. [GitHub](https://github.com/open-webui/open-webui)
- [LibreChat](https://librechat.ai/) — Open-source ChatGPT clone supporting 40+ providers, multi-user, plugins, and RAG. [GitHub](https://github.com/danny-avila/LibreChat)
- [AnythingLLM](https://anythingllm.com/) — All-in-one desktop app for chatting with documents and models. Built-in RAG pipeline. [GitHub](https://github.com/Mintplex-Labs/anything-llm)
- [Big-AGI](https://big-agi.com/) — Feature-rich AI chat with personas, multi-model support, voice, and code execution. [GitHub](https://github.com/enricoros/big-agi)
- [Lobe Chat](https://lobehub.com/) — Modern, extensible chat framework with plugin system and multi-provider support. [GitHub](https://github.com/lobehub/lobe-chat)
- [Chatbot UI](https://www.chatbotui.com/) — Simple, clean ChatGPT interface. Easy to self-host with any OpenAI-compatible API. [GitHub](https://github.com/mckaywrigley/chatbot-ui)
- [NextChat (ChatGPT-Next-Web)](https://github.com/ChatGPTNextWeb/NextChat) — Lightweight cross-platform chat app. Self-host on Vercel or download official desktop/mobile clients.

---

## 🤖 AI Coding Assistants

> 📅 Last checked: June 6, 2026

Free tools that integrate AI into your development workflow.

- [Continue.dev](https://continue.dev/) — Open-source AI code assistant for VS Code and JetBrains. Chat, autocomplete, and edit with any model. [GitHub](https://github.com/continuedev/continue)
- [Aider](https://aider.chat/) — AI pair programming in the terminal. Edits code in your local git repo. Supports GPT, Claude, and local models. [GitHub](https://github.com/paul-gauthier/aider)
- [Codeium (Windsurf)](https://codeium.com/) — Free AI code assistant with autocomplete, chat, and search. Individual plan is free forever.
- [Tabby](https://tabby.tabbyml.com/) — Self-hosted AI coding assistant with no dependency on external services. [GitHub](https://github.com/TabbyML/tabby)
- [Cody (Sourcegraph)](https://sourcegraph.com/cody) — Free tier for individuals. Chat, autocomplete, and commands with codebase context.
- [Llama Coder (Nutlope)](https://llamacoder.together.ai/) — Free AI code generation tool. Generate entire apps from prompts.
- [Bolt.new (StackBlitz)](https://bolt.new/) — Free tier for AI-powered full-stack web app development in browser.
- [Claude Code (Anthropic)](https://docs.anthropic.com/en/docs/claude-code/overview) — Free tier with limited usage for terminal-based AI coding assistant.
- [Cursor 3](https://www.cursor.com/) — **Apr 2026.** AI-native code editor with deep model integration and agentic features. Free tier available.

---

## 📝 Code Models

> 📅 Last checked: June 6, 2026

Specialized for code generation, completion, and analysis.

- [MAI-Code-1-Flash (Microsoft)](https://huggingface.co/microsoft) — **Jun 2026.** Microsoft's open-weight coding model for lowering infrastructure costs.

---

## 🔍 RAG & Vector Databases

> 📅 Last checked: June 6, 2026

Free tools for building retrieval-augmented generation pipelines — vector storage, embedding search, and document retrieval.

- [Chroma](https://www.trychroma.com/) — AI-native open-source embedding database. Runs in-process, no GPU needed. [GitHub](https://github.com/chroma-core/chroma)
- [Qdrant](https://qdrant.tech/) — High-performance vector search engine. Free tier on Qdrant Cloud or self-host via Docker. [GitHub](https://github.com/qdrant/qdrant)
- [pgvector](https://github.com/pgvector/pgvector) — Vector similarity search inside PostgreSQL. Free if you already run Postgres.
- [LanceDB](https://lancedb.com/) — Developer-friendly vector database built on Lance columnar format. Runs locally, no server needed. [GitHub](https://github.com/lancedb/lancedb)
- [Weaviate](https://weaviate.io/) — Open-source vector database. Free sandbox tier on Weaviate Cloud. [GitHub](https://github.com/weaviate/weaviate)
- [Milvus (Zilliz)](https://milvus.io/) — Cloud-native vector database. Free tier on Zilliz Cloud or self-host. [GitHub](https://github.com/milvus-io/milvus)
- [txtai](https://neuml.github.io/txtai/) — AI-powered semantic search and RAG in a single Python package. [GitHub](https://github.com/neuml/txtai)
- [R2R (SciPhi)](https://github.com/SciPhi-AI/R2R) — Production-ready RAG engine with API, user management, and observability.
- [Docling (IBM)](https://www.docling.ai/) — Document understanding and conversion for RAG pipelines. Extracts PDFs, images, and more. [GitHub](https://github.com/DS4SD/docling)
- [Unstructured.io](https://unstructured.io/) — Preprocessing toolkit for documents (PDF, HTML, Word) for RAG pipelines. Free tier available.

---

## 🧩 Agentic Frameworks

> 📅 Last checked: June 6, 2026

Free, open-source frameworks for building AI agents and multi-agent systems.

- [LangGraph (LangChain)](https://langchain-ai.github.io/langgraph/) — Low-level framework for building stateful, multi-agent applications. [GitHub](https://github.com/langchain-ai/langgraph)
- [CrewAI](https://www.crewai.com/) — Multi-agent framework for orchestrating specialized AI agents to work together. [GitHub](https://github.com/crewAIInc/crewAI)
- [AutoGen (Microsoft)](https://microsoft.github.io/autogen/) — Extensible framework for building multi-agent conversations. [GitHub](https://github.com/microsoft/autogen)
- [Agno (formerly Phidata)](https://www.agno.com/) — Full-stack AI framework for building multimodal agents with memory, knowledge, and tools. [GitHub](https://github.com/agno-org/agno)
- [PydanticAI](https://ai.pydantic.dev/) — Agent framework by Pydantic with type-safe outputs and dependency injection. [GitHub](https://github.com/pydantic/pydantic-ai)
- [Mastra](https://mastra.ai/) — TypeScript framework for building AI applications and agent workflows. [GitHub](https://github.com/mastra-ai/mastra)
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) — Lightweight SDK for building single and multi-agent systems. [GitHub](https://github.com/openai/openai-agents-python)
- [Semantic Kernel (Microsoft)](https://learn.microsoft.com/en-us/semantic-kernel/) — SDK for orchestrating AI agents with planners, memory, and connectors. [GitHub](https://github.com/microsoft/semantic-kernel)
- [Dify](https://dify.ai/) — LLM app development platform with visual workflow builder and agent capabilities. [GitHub](https://github.com/langgenius/dify)
- [Flowise](https://flowiseai.com/) — Low-code visual LLM flow builder with drag-and-drop interface. [GitHub](https://github.com/FlowiseAI/Flowise)
- [TaskWeaver (Microsoft)](https://microsoft.github.io/TaskWeaver/) — Code-first agent framework for planning and executing complex tasks. [GitHub](https://github.com/microsoft/TaskWeaver)
- [Fazm](https://github.com/mediar-ai/fazm) — **Apr 2026.** Open-source local computer-use agent for macOS. Drives apps via accessibility APIs, model-agnostic, faster than screenshot-based agents.

---

## 🎛 Fine-tuning Tools

> 📅 Last checked: June 6, 2026

Tools to fine-tune free models on your own data — all free and open-source.

- [Unsloth](https://github.com/unslothai/unsloth) — Fast memory-efficient fine-tuning. 2x faster, 50% less memory. Supports QLoRA, LoRA, full fine-tune.
- [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) — Streamlined fine-tuning framework supporting multiple model architectures and quantization methods.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) — Easy-to-use fine-tuning with web UI. Supports 100+ models, multiple training methods.
- [Hugging Face TRL](https://github.com/huggingface/trl) — Transformer Reinforcement Learning library. SFT, PPO, DPOTrainer, GRPOTrainer for aligning models.
- [TorchTune (Meta)](https://github.com/pytorch/torchtune) — Native PyTorch library for fine-tuning LLMs. Simple, extensible, efficient.
- [AutoTrain (Hugging Face)](https://github.com/huggingface/autotrain-advanced) — No-code fine-tuning platform. Train models with a web UI or API.
- [XTuner (InternLM)](https://github.com/InternLM/xtuner) — Efficient fine-tuning toolkit supporting QLoRA, LoRA, and full fine-tune with multiple model architectures.
- [Ludwig (Predibase)](https://ludwig.ai/) — Declarative ML framework. Fine-tune models with a simple config file. [GitHub](https://github.com/ludwig-ai/ludwig)

---

## ✨ Prompt Engineering Tools

> 📅 Last checked: June 6, 2026

Free tools for testing, managing, and optimizing prompts.

- [Promptfoo](https://www.promptfoo.dev/) — Open-source tool for prompt testing and evaluation. Systematic A/B testing of prompts. [GitHub](https://github.com/promptfoo/promptfoo)
- [Fabric (Daniel Miessler)](https://github.com/danielmiessler/fabric) — Open-source framework for augmenting humans with AI. Library of curated prompts (patterns) for common tasks.
- [LangFuse](https://langfuse.com/) — Open-source LLM engineering platform with prompt management, versioning, and evaluation. [GitHub](https://github.com/langfuse/langfuse)
- [OpenPrompt (THUNLP)](https://thunlp.github.io/OpenPrompt/) — Framework for prompt-learning research. Supports template and verbalizer design. [GitHub](https://github.com/thunlp/OpenPrompt)
- [DSPy (Stanford)](https://dspy.ai/) — Framework for algorithmically optimizing LM prompts and weights. [GitHub](https://github.com/stanfordnlp/dspy)
- [Agenta](https://agenta.ai/) — Open-source LLM platform for prompt management, evaluation, and deployment. [GitHub](https://github.com/Agenta-AI/agenta)

---

## 📊 Datasets

> 📅 Last checked: June 6, 2026

Free, open datasets for training, fine-tuning, and evaluating models.

- [Hugging Face Datasets](https://huggingface.co/datasets) — The standard hub for open datasets. 150,000+ datasets across all tasks.
- [Common Corpus](https://huggingface.co/datasets/common-catalog) — Massive open-source dataset for training large language models.
- [The Stack v2 (BigCode)](https://huggingface.co/datasets/bigcode/the-stack-v2) — Large-scale code dataset covering 619 programming languages. Permissive license.
- [FineWeb (Hugging Face)](https://huggingface.co/datasets/HuggingFaceFW/fineweb) — High-quality web dataset for LLM pre-training. 15T tokens.
- [Dolly (Databricks)](https://huggingface.co/datasets/databricks/databricks-dolly-15k) — 15k instruction-response pairs for fine-tuning. CC-BY-SA.
- [OpenAssistant Conversations](https://huggingface.co/datasets/OpenAssistant/oasst1) — 160k human-generated assistant conversations. Apache 2.0.
- [ShareGPT (RyokoAI)](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) — Real user-ChatGPT conversations for fine-tuning.
- [UltraChat (Sean C.)](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k) — 200k multi-turn conversations synthesized by ChatGPT.
- [No Robots (Hugging Face)](https://huggingface.co/datasets/HuggingFaceH4/no_robots) — 10k high-quality human-written instructions. Apache 2.0.
- [RLAIF-V (OpenBMB)](https://huggingface.co/datasets/openbmb/RLAIF-V) — AI-generated preference data for RLHF. Apache 2.0.
- [MMLU / GSM8K](https://huggingface.co/datasets) — Standard benchmarks for evaluation.

---

## ☁ Model Hosting Platforms

> 📅 Last checked: June 6, 2026

Free platforms that host models — run inference without downloading anything.

- [Hugging Face Spaces](https://huggingface.co/spaces) — Free hosting for ML apps (Gradio, Streamlit). Thousands of community demos.
- [Hugging Face Inference Endpoints (Free Tier)](https://huggingface.co/inference-endpoints) — Deploy models with free trial credits.
- [Google Colab (Free Tier)](https://colab.research.google.com/) — Free GPU (T4, sometimes A100). Perfect for running models and fine-tuning.
- [Kaggle Notebooks](https://www.kaggle.com/code) — Free GPU (T4 x2). 30 hours/week. Good for heavier workloads.
- [Lightning AI Studio](https://lightning.ai/) — Free tier with GPU access for development and prototyping.
- [Modal](https://modal.com/) — Free monthly credits for serverless GPU compute.
- [Replicate (Free Tier)](https://replicate.com/) — Free credits for running community models.
- [Deepnote](https://deepnote.com/) — Free tier with GPU for data science and ML notebooks.

---

## 📚 Learning Resources

> 📅 Last checked: June 6, 2026

Free courses, books, and tutorials for learning AI and LLMs.

- [Fast.ai](https://www.fast.ai/) — Code-first deep learning education. Practical, free courses from fundamentals to advanced.
- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) — Comprehensive free course on transformers, tokenizers, datasets, and deployment.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) — Free short courses on LLMs, RAG, LangChain, and AI agents.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free course on ML engineering: training, deploying, and maintaining models.
- [Andrej Karpathy's Course](https://karpathy.ai/zero-to-hero.html) — From-scratch neural network implementation videos.
- [Neural Networks: Zero to Hero](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — YouTube series building neural networks from scratch.
- [LLM University (Cohere)](https://docs.cohere.com/docs/llmu) — Free course on LLMs, embeddings, and RAG.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) — Comprehensive free guide on prompt engineering techniques.
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) — Free recipes and patterns for working with Claude.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Free examples and guides for the OpenAI API.

---

## 🏆 Resources & Leaderboards

> 📅 Last checked: June 6, 2026

- [Perplexity](https://www.perplexity.ai/) — Free AI search and research assistant with real-time answers and source citations.
- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) — The primary benchmark for open-weight models. Updated regularly.
- [LMSYS Chatbot Arena](https://lmarena.ai/) — Human preference rankings of models. Best source for real-world quality comparisons.
- [Artificial Analysis](https://artificialanalysis.ai/) — Independent benchmarks for speed, pricing, and quality across providers.
- [Hugging Face Models](https://huggingface.co/models) — Search 1M+ models. Filter by license, task, framework.
- [OpenRouter Models](https://openrouter.ai/models) — Browse models available via API with pricing and free tiers.
- [Ollama Library](https://ollama.com/library) — Browse models available for one-command local setup.
- [cheahjs/free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources) — Community-maintained list of free LLM API resources.
- [SweetTea](https://www.sweettea.ai/) — Community voting on model quality and preference.

---

## 👥 Communities

> 📅 Last checked: June 6, 2026

- [Hugging Face Discord](https://discord.gg/huggingface) — Model releases, discussions, and community support.
- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) — The largest Reddit community for running local LLMs.
- [Ollama Discord](https://discord.gg/ollama) — Ollama community for local model enthusiasts.
- [LM Studio Discord](https://discord.gg/lmstudio) — LM Studio community.
- [Hugging Face Forums](https://discuss.huggingface.co/) — Discussions on models, datasets, and Spaces.
- [r/MachineLearning](https://reddit.com/r/MachineLearning) — General ML/AI research and news.
- [Discord: AI Agents](https://discord.gg/ai-agents) — Community for AI agent development and agentic frameworks.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
