# Awesome Free Models [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of free AI models, APIs, and tools you can use without paying a cent.

Running AI shouldn't require a credit card. This list curates genuinely free models — open-weight models you can self-host, free API tiers from major providers, and tools to run everything locally.

## Contents

- [Recent Releases (Apr–Jun 2026)](#recent-releases-aprjun-2026)
- [Open-Weight Models](#open-weight-models)
  - [Llama Family (Meta)](#llama-family-meta)
  - [Qwen Family (Alibaba)](#qwen-family-alibaba)
  - [Mistral Family](#mistral-family)
  - [DeepSeek Family](#deepseek-family)
  - [Gemma Family (Google)](#gemma-family-google)
  - [Phi Family (Microsoft)](#phi-family-microsoft)
  - [Other Notable Models](#other-notable-models)
- [Free API Providers](#free-api-providers)
- [Local Inference Tools](#local-inference-tools)
- [AI Chatbot UIs](#ai-chatbot-uis)
- [AI Coding Assistants](#ai-coding-assistants)
- [Multimodal & Vision Models](#multimodal--vision-models)
- [Code Models](#code-models)
- [Image Generation Models](#image-generation-models)
- [Video Generation Models](#video-generation-models)
- [Audio & Speech Models](#audio--speech-models)
- [Embedding Models](#embedding-models)
- [RAG & Vector Databases](#rag--vector-databases)
- [Agentic Frameworks](#agentic-frameworks)
- [Fine-tuning Tools](#fine-tuning-tools)
- [Prompt Engineering Tools](#prompt-engineering-tools)
- [Datasets](#datasets)
- [Model Hosting Platforms](#model-hosting-platforms)
- [Learning Resources](#learning-resources)
- [Resources & Leaderboards](#resources--leaderboards)
- [Communities](#communities)

## Recent Releases (Apr–Jun 2026)

> 🔥 The newest additions to this list — models and tools released or with major updates in the last 2 months.

- [Gemma 4 (Google)](https://huggingface.co/google) - **April 2026.** Google's latest open-weight family with fully permissive Apache 2.0 license. Includes 31B dense, 26B MoE variants, and E4B/E2B edge models. 256K context, native multimodal.
- [DeepSeek V4](https://huggingface.co/deepseek-ai) - **April 2026.** Latest generation with extreme cost-efficiency. MIT license.
- [Qwen 3.6-Plus (Alibaba)](https://huggingface.co/Qwen) - **April 2026.** Agentic coding variant with 1M token context window. Apache 2.0.
- [Llama 4 Scout / Maverick (Meta)](https://huggingface.co/meta-llama) - **April 2026.** Scout: 109B MoE with 10M context. Maverick: 402B MoE with 1M context. Native multimodal.
- [GLM-5.1 (Zhipu AI)](https://huggingface.co/THUDM) - **May 2026.** 744B MoE model, competitive with top proprietary models. MIT license.
- [MiniMax M3](https://huggingface.co/Minimax) - **June 2026.** Frontier-tier open-weight model. 1M context, native multimodal + computer use. MiniMax Sparse Attention architecture.
- [Trinity (Arcee AI)](https://huggingface.co/arcee-ai) - **May 2026.** 400B parameter open-weight model for enterprises. Apache 2.0.
- [MAI-Code-1-Flash (Microsoft)](https://huggingface.co/microsoft) - **June 2026.** Microsoft's inaugural open-weight coding model for lowering infrastructure costs.
- [Fazm](https://github.com/fazm-ai/fazm) - **April 2026.** Open-source local computer-use agent for macOS. Drives apps via accessibility APIs, model-agnostic.
- [Cursor 3](https://www.cursor.com/) - **Apr 2026.** Major update to AI-native code editor with deeper model integration and agentic features.
- [Windsurf (Codeium)](https://codeium.com/windsurf) - **New (2026).** AI-native IDE with deep contextual understanding, free tier for individuals.

## Open-Weight Models

Models you can download and run on your own hardware. Most use permissive licenses (Apache 2.0, MIT, or custom open-weight licenses).

### Llama Family (Meta)

The industry standard for open-weight models. Optimized for local hardware with extensive quantization support.

- [Llama 4](https://huggingface.co/meta-llama) - Latest generation with Mixture-of-Experts architecture. Multiple sizes: Scout (109B, 1 active), Maverick (402B, 17 active). [[License]](https://github.com/facebookresearch/llama/blob/main/LICENSE)
- [Llama 3.3 70B](https://huggingface.co/meta-llama/Llama-3.3-70B-Instruct) - Top-tier instruct model, rivals GPT-4 on many benchmarks.
- [Llama 3.1 8B / 70B / 405B](https://huggingface.co/meta-llama) - Widely adopted, massive ecosystem of fine-tunes and tools.
- [Llama 3.2 1B / 3B / 11B / 90B](https://huggingface.co/meta-llama) - Includes small edge-friendly models (1B, 3B) and multimodal vision models (11B, 90B).

**License:** Custom open-weight license — permissive for most use cases, restrictions on large-scale commercial services (>700M MAU).

### Qwen Family (Alibaba)

Top-tier performers across language, code, and vision tasks. Released under Apache 2.0.

- [Qwen 3.6-Plus](https://huggingface.co/Qwen) - **NEW (Apr 2026).** Agentic coding model with 1M token context window. Apache 2.0.
- [Qwen3 0.6B / 1.7B / 7B / 14B / 32B / 110B / 235B](https://huggingface.co/Qwen) - Excellent reasoning, multilingual support. Apache 2.0.
- [Qwen3-Coder](https://huggingface.co/Qwen/Qwen3-Coder-14B) - Code-specialized variant, state-of-the-art for open-weight coding.
- [Qwen3-VL](https://huggingface.co/Qwen/Qwen3-VL-7B) - Vision-language model, strong on document and image understanding.
- [Qwen2.5 7B / 32B / 72B](https://huggingface.co/Qwen) - Mature ecosystem, tons of community fine-tunes and tools.
- [Qwen2.5-Coder 1.5B / 7B / 32B](https://huggingface.co/Qwen) - Code-specialized, rivals GPT-4 on coding benchmarks.
- [Qwen2.5-VL 3B / 7B / 72B](https://huggingface.co/Qwen) - Vision-language model.

**License:** Apache 2.0 — fully permissive for commercial use.

### Mistral Family

Known for high-quality, efficient models that run well on consumer hardware.

- [Mistral Large](https://huggingface.co/mistralai) - Mistral's most capable open-weight model.
- [Mistral Small 3.1 24B](https://huggingface.co/mistralai) - High performance in a compact 24B package. Apache 2.0.
- [Mistral Small 3 24B](https://huggingface.co/mistralai) - Outperforms Llama 3.3 70B on several benchmarks at 1/3 the size.
- [Mistral 7B](https://huggingface.co/mistralai) - Classic 7B model, huge community ecosystem.
- [Mixtral 8x7B / 8x22B](https://huggingface.co/mistralai) - Mixture-of-Experts models offering high capability per compute.
- [Codestral](https://huggingface.co/mistralai) - Code-specialized models with permissive license.

**License:** Apache 2.0 (Small 3, Codestral), Mistral Research License, or Mistral Commercial License. Check each model's page.

### DeepSeek Family

Exceptional reasoning and coding performance. Known for efficiency innovations.

- [DeepSeek V4](https://huggingface.co/deepseek-ai) - **NEW (Apr 2026).** Latest generation with extreme cost-efficiency. MIT license.
- [DeepSeek V3](https://huggingface.co/deepseek-ai/DeepSeek-V3) - Large MoE model rivaling top closed-source models.
- [DeepSeek R1](https://huggingface.co/deepseek-ai/DeepSeek-R1) - Reasoning-focused model with chain-of-thought capabilities.
- [DeepSeek Coder V2 / V3](https://huggingface.co/deepseek-ai) - State-of-the-art code generation and completion.

**License:** MIT (most models) — fully permissive for commercial use.

### Gemma Family (Google)

Google's open-weight line. Excellent efficiency and quality.

- [Gemma 4 31B / 26B MoE / E4B / E2B](https://huggingface.co/google) - **NEW (Apr 2026).** Fully permissive Apache 2.0 license. 256K context, native multimodal. New standard for open-weight.
- [Gemma 3 1B / 4B / 12B / 27B](https://huggingface.co/google) - Strong multilingual and reasoning performance.
- [Gemma 2 2B / 9B / 27B](https://huggingface.co/google) - Widely adopted, punch above their weight class.
- [CodeGemma 2B / 7B](https://huggingface.co/google) - Code-specialized variants.
- [RecurrentGemma 2B / 9B](https://huggingface.co/google) - Recurrent architecture variant, efficient for long sequences.
- [EmbeddingGemma 300M](https://huggingface.co/google) - Lightweight embedding model for RAG.

**License:** Apache 2.0 (Gemma 4), custom open-weight (Gemma 2/3).

### Phi Family (Microsoft)

Small models that punch far above their weight. Perfect for edge deployment and fast local inference.

- [Phi-4 14B](https://huggingface.co/microsoft/phi-4) - Microsoft's latest, rivals models 2-3x its size.
- [Phi-3 Mini (3.8B) / Small (7B) / Medium (14B)](https://huggingface.co/microsoft) - Run on phones and laptops.
- [Phi-3 Vision (4.2B)](https://huggingface.co/microsoft) - Small multimodal model.
- [Phi-3.5 MoE (4x3.8B)](https://huggingface.co/microsoft) - Mixture-of-Experts variant.

**License:** MIT (Phi-3 family), custom (Phi-4) — check each model.

### Other Notable Models

- [GLM-5.1 (Zhipu AI)](https://huggingface.co/THUDM) - **NEW (May 2026).** 744B MoE model, competitive with top proprietary models. MIT license.
- [MiniMax M3](https://huggingface.co/Minimax) - **NEW (Jun 2026).** Frontier-tier 1M context, native multimodal + computer use. MSA architecture.
- [Trinity (Arcee AI)](https://huggingface.co/arcee-ai) - **NEW (May 2026).** 400B parameter enterprise model. Apache 2.0.
- [GLM-4 / GLM-4V (Zhipu AI)](https://huggingface.co/THUDM) - Strong multilingual model, MIT license.
- [Falcon 2 / 3 (TII)](https://huggingface.co/tiiuae) - Apache 2.0, available in multiple sizes.
- [Yi 1.5 / Yi 1.5-Chat (01.AI)](https://huggingface.co/01-ai) - Strong bilingual (Chinese/English) models.
- [Dbrx (Databricks)](https://huggingface.co/databricks) - MoE model, permissive license.
- [Kimi K2 (Moonshot AI)](https://huggingface.co/moonshotai) - Recent strong performer in reasoning tasks.
- [Solar Pro / Mini (Upstage)](https://huggingface.co/upstage) - Strong LLM with permissive license.
- [Command R / R+ (Cohere)](https://huggingface.co/CohereForAI) - Optimized for RAG, CC-BY-NC (free for non-commercial).
- [Hermes 3 (Nous Research)](https://huggingface.co/NousResearch) - Top-performing fine-tunes with strong instruction following. Apache 2.0.
- [OLMo 2 (AI2)](https://huggingface.co/allenai) - Fully open model — weights, training data, and code all released. Apache 2.0.
- [Nemotron / Nemo (NVIDIA)](https://huggingface.co/nvidia) - NVIDIA's open models, competitive with leading alternatives.
- [Aya 23 / Aya Expanse (Cohere)](https://huggingface.co/CohereForAI) - Multilingual models covering 23+ languages. Apache 2.0.
- [InternLM / InternLM2 (Shanghai AI Lab)](https://huggingface.co/internlm) - Strong general-purpose models with long context. Apache 2.0.
- [MiniCPM / MiniCPM-MoE (OpenBMB)](https://huggingface.co/openbmb) - Compact models with strong performance for their size. Apache 2.0.
- [BLOOM / BLOOMZ (BigScience)](https://huggingface.co/bigscience) - 176B multilingual model. Open RAIL-M license.
- [T5 / Flan-T5 (Google)](https://huggingface.co/google) - Text-to-text transformer, excellent for fine-tuning. Apache 2.0.
- [Mamba / Mamba-2 (State Space Models)](https://huggingface.co/state-spaces) - Alternative to Transformer architecture, linear-time inference. Apache 2.0.
- [RWKV (Eagle)](https://huggingface.co/RWKV) - RNN-Transformer hybrid, efficient for long sequences. Apache 2.0.
- [SmolLM (Hugging Face)](https://huggingface.co/HuggingFaceTB) - Tiny models (135M / 360M / 1.7B) for edge and mobile. Apache 2.0.
- [Zephyr (Hugging Face)](https://huggingface.co/HuggingFaceH4) - Fine-tuned Mistral/Starling variants with strong instruction following. MIT.
- [OpenChat (Community)](https://huggingface.co/openchat) - Open-source chat models using C-RLFT. Apache 2.0.
- [Starling (UC Berkeley)](https://huggingface.co/berkeley-nest) - RLHF-tuned models trained with preference data. CC-BY-NC.

## Free API Providers

Providers offering free tiers to access models via API — no local hardware required.

- [Google AI Studio](https://aistudio.google.com/) - **Most generous free tier.** Access Gemini 2.5 Flash, Gemini 2.0 Flash, and other models. Generous rate limits for prototyping.
- [OpenRouter](https://openrouter.ai/) - Aggregates 500+ models. Filter by "Free" to see models available at no cost. Includes experimental and subsidized open-weight models.
- [Groq](https://console.groq.com/) - Ultra-fast inference. Free tier includes Llama, Gemma, Mixtral, Whisper models with generous daily rate limits.
- [Hugging Face Inference API](https://huggingface.co/inference-api) - Free tier for thousands of community models. Rate-limited but excellent for testing.
- [NVIDIA NIM](https://build.nvidia.com/) - Free API access to accelerated versions of Llama, Mistral, Gemma, and more on NVIDIA infrastructure.
- [DeepInfra](https://deepinfra.com/) - Serverless inference. Free tier with daily rate limits for popular open-source models.
- [Together AI](https://www.together.ai/) - Free trial credits for new users. Fast inference on open-source models.
- [Fireworks AI](https://fireworks.ai/) - Free tier for community models. Optimized for low latency.
- [Perplexity Labs](https://labs.perplexity.ai/) - Free access to Sonar models and open-source models for testing.
- [SiliconFlow](https://siliconflow.cn/) - Rising platform with free access to many open-source models.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) - Free tier for running select open-source models at the edge.
- [Replicate](https://replicate.com/) - Free tier with limited credits for running open-source models.
- [Poe (Quora)](https://poe.com/) - Free tier with daily credits for GPT-4 mini, Claude instant, and community bots.
- [CatGPT](https://www.catgpt.cc/) - Completely free chat with multiple models, no login required.

## Local Inference Tools

Run models on your own machine — no API keys needed, full privacy.

- [Ollama](https://ollama.com/) - The easiest way to run local LLMs. One command to download and run any model. macOS, Linux, Windows. [GitHub](https://github.com/ollama/ollama)
- [LM Studio](https://lmstudio.ai/) - Polished desktop GUI. Browse, download, and chat with models. Built-in model browser and local API server.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - High-performance C++ inference engine. Runs on CPU and GPU. Supports GGUF quantization. Powers most other local tools.
- [Jan](https://jan.ai/) - Open-source ChatGPT alternative for desktop. Built-in model downloader, local API server. [GitHub](https://github.com/janhq/jan)
- [GPT4All](https://gpt4all.io/) - Privacy-focused local chatbot. Runs on consumer hardware. Built-in model browser. [GitHub](https://github.com/nomic-ai/gpt4all)
- [text-generation-webui (Oobabooga)](https://github.com/oobabooga/text-generation-webui) - Feature-rich web UI. Supports multiple backends (Transformers, llama.cpp, ExLlama, AutoGPTQ).
- [LocalAI](https://localai.io/) - Drop-in OpenAI API replacement. Run models locally with an OpenAI-compatible API. [GitHub](https://github.com/mudler/LocalAI)
- [KoboldCPP](https://github.com/LostRuins/koboldcpp) - Single-file executable for running GGUF models. Focused on story generation but general-purpose.
- [llamafile (Mozilla)](https://github.com/Mozilla-Ocho/llamafile) - Distributable single-file executables that run LLMs. No installation needed.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput production inference engine. Uses PagedAttention for efficient serving.
- [SGLang](https://github.com/sgl-project/sglang) - Fast inference framework with structured generation and RadixAttention.
- [TensorRT-LLM (NVIDIA)](https://github.com/NVIDIA/TensorRT-LLM) - NVIDIA's optimized inference engine. Best performance on NVIDIA GPUs.
- [ExLlamaV2](https://github.com/turboderp/exllamav2) - Optimized inference for Llama-family models. Fastest option for single-GPU inference.
- [Aphrodite Engine](https://github.com/PygmalionAI/aphrodite-engine) - High-performance LLM serving engine with advanced quantization support.
- [TabbyAPI](https://github.com/theroyallab/tabbyAPI) - Lightweight, fast OpenAI-compatible API server for ExLlamaV2.

## AI Chatbot UIs

Free, open-source web interfaces for chatting with AI models — self-host or use hosted versions.

- [Open WebUI](https://openwebui.com/) - Feature-rich ChatGPT-like interface for Ollama and OpenAI-compatible backends. RAG, image generation, multi-user. [GitHub](https://github.com/open-webui/open-webui)
- [LibreChat](https://librechat.ai/) - Open-source ChatGPT clone supporting 40+ providers, multi-user, plugins, and RAG. [GitHub](https://github.com/danny-avila/LibreChat)
- [AnythingLLM](https://anythingllm.com/) - All-in-one desktop app for chatting with documents and models. Built-in RAG pipeline. [GitHub](https://github.com/Mintplex-Labs/anything-llm)
- [Big-AGI](https://big-agi.com/) - Feature-rich AI chat with personas, multi-model support, voice, and code execution. [GitHub](https://github.com/enricoros/big-agi)
- [Lobe Chat](https://lobehub.com/) - Modern, extensible chat framework with plugin system and multi-provider support. [GitHub](https://github.com/lobehub/lobe-chat)
- [Chatbot UI](https://www.chatbotui.com/) - Simple, clean ChatGPT interface. Easy to self-host with any OpenAI-compatible API. [GitHub](https://github.com/mckaywrigley/chatbot-ui)
- [NextChat (ChatGPT-Next-Web)](https://nextchat.dev/) - Lightweight cross-platform chat app. One-click deploy to Vercel. [GitHub](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)

## AI Coding Assistants

Free tools that integrate AI into your development workflow.

- [Continue.dev](https://continue.dev/) - Open-source AI code assistant for VS Code and JetBrains. Chat, autocomplete, and edit with any model. [GitHub](https://github.com/continuedev/continue)
- [Aider](https://aider.chat/) - AI pair programming in the terminal. Edits code in your local git repo. Supports GPT, Claude, and local models. [GitHub](https://github.com/paul-gauthier/aider)
- [Codeium (Windsurf)](https://codeium.com/) - Free AI code assistant with autocomplete, chat, and search. Individual plan is free forever.
- [Tabby](https://tabby.tabbyml.com/) - Self-hosted AI coding assistant with no dependency on external services. [GitHub](https://github.com/TabbyML/tabby)
- [Cody (Sourcegraph)](https://sourcegraph.com/cody) - Free tier for individuals. Chat, autocomplete, and commands with codebase context.
- [Llama Coder (Nutlope)](https://llamacoder.together.ai/) - Free AI code generation tool. Generate entire apps from prompts.
- [Bolt.new (StackBlitz)](https://bolt.new/) - Free tier for AI-powered full-stack web app development in browser.
- [Claude Code (Anthropic)](https://docs.anthropic.com/en/docs/claude-code/overview) - Free tier with limited usage for terminal-based AI coding assistant.

## Multimodal & Vision Models

Free models that understand images, video, and documents.

- [Qwen3-VL 7B / 72B](https://huggingface.co/Qwen) - State-of-the-art open vision-language model. Document understanding, image captioning, visual Q&A.
- [Qwen2.5-VL 3B / 7B / 72B](https://huggingface.co/Qwen) - Mature vision-language model with strong multilingual OCR.
- [InternVL2 1B / 4B / 8B / 26B / 76B](https://huggingface.co/OpenGVLab) - Top-tier open-source VLM, competitive with GPT-4V on many benchmarks.
- [MiniCPM-V-2.6 (OpenBMB)](https://huggingface.co/openbmb) - Strong small VLM running on mobile devices. Apache 2.0.
- [Llama 3.2 Vision 11B / 90B](https://huggingface.co/meta-llama) - Meta's vision-language models integrated with Llama ecosystem.
- [Pixtral 12B (Mistral)](https://huggingface.co/mistralai) - Mistral's multimodal model with strong document understanding.
- [LLaVA-NeXT (Microsoft)](https://huggingface.co/llava-hf) - Popular vision-language assistant with strong image reasoning. Apache 2.0.
- [CogVLM2 (Zhipu AI)](https://huggingface.co/THUDM) - Vision-language model with high-resolution image understanding.
- [GLM-4V-9B (Zhipu AI)](https://huggingface.co/THUDM/glm-4v-9b) - Vision-language model, MIT license.
- [Florence-2 (Microsoft)](https://huggingface.co/microsoft/Florence-2-large) - Lightweight vision model for captioning, detection, segmentation.
- [PaliGemma (Google)](https://huggingface.co/google/paligemma) - Vision-language model built on Gemma.
- [SigLIP (Google)](https://huggingface.co/google/siglip-so-vit-patch16-256) - Vision encoder for multimodal applications.
- [ImageBind (Meta)](https://github.com/facebookresearch/ImageBind) - Embeds images, text, audio, depth, temperature, IMU data jointly.
- [Video-LLaMA (DAMO Academy)](https://github.com/DAMO-NLP-SG/Video-LLaMA) - Video-language understanding model.

## Code Models

Specialized for code generation, completion, and analysis.

- [Qwen3-Coder 14B](https://huggingface.co/Qwen/Qwen3-Coder-14B) - State-of-the-art open-weight code model. Apache 2.0.
- [Qwen2.5-Coder 1.5B / 7B / 32B](https://huggingface.co/Qwen) - Excellent multi-language code generation.
- [DeepSeek-Coder V2 / V3](https://huggingface.co/deepseek-ai) - Rivals GPT-4 on coding benchmarks. MIT license.
- [Codestral (Mistral)](https://huggingface.co/mistralai) - Mistral's code model with permissive license.
- [CodeGemma 2B / 7B (Google)](https://huggingface.co/google) - Lightweight code models for completion and generation.
- [MAI-Code-1-Flash (Microsoft)](https://huggingface.co/microsoft) - **NEW (Jun 2026).** Microsoft's open-weight coding model for lowering infrastructure costs.
- [Code Llama 7B / 13B / 34B / 70B (Meta)](https://huggingface.co/meta-llama) - Meta's code-specialized Llama variants.
- [StarCoder2 3B / 7B / 15B](https://huggingface.co/bigcode) - Trained on The Stack v2 (619 programming languages). Apache 2.0.
- [Stable Code 3B](https://huggingface.co/stabilityai) - Compact code model for fill-in-the-middle tasks.
- [CodeGeeX4 (Zhipu AI)](https://huggingface.co/THUDM) - Multilingual code generation model. Apache 2.0.

## Image Generation Models

Free, open models for generating images.

- [Stable Diffusion 3.5 / 3 (Stability AI)](https://huggingface.co/stabilityai) - Latest SD generation, improved prompt adherence and typography.
- [Stable Diffusion XL (SDXL)](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) - Mature, widely adopted with thousands of fine-tunes and LoRAs.
- [FLUX.1 (Black Forest Labs)](https://huggingface.co/black-forest-labs) - State-of-the-art open image generation. Variants: dev (non-commercial), schnell (Apache 2.0).
- [Playground v3 (Playground AI)](https://huggingface.co/playgroundai) - High-quality image generation with strong prompt understanding.
- [PixArt-Σ / PixArt-α (Huawei)](https://huggingface.co/PixArt-alpha) - Efficient text-to-image transformer. Competitive with SDXL quality.
- [Wuerstchen (Stability AI)](https://huggingface.co/warp-ai) - Efficient text-to-image model with 42x compression.
- [Kandinsky 3 (Sber AI)](https://huggingface.co/ai-forever) - Multilingual text-to-image model with good quality.
- [DeepFloyd IF (Stability AI)](https://huggingface.co/DeepFloyd) - Text-to-image model with exceptional text rendering.
- [LCM-LoRA (Latent Consistency Models)](https://huggingface.co/latent-consistency) - Real-time image generation in 1-4 steps.

**Where to run:** Locally via [ComfyUI](https://github.com/comfyanonymous/ComfyUI), [Automatic1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui), [InvokeAI](https://github.com/invoke-ai/InvokeAI), or for free on [Hugging Face Spaces](https://huggingface.co/spaces).

## Video Generation Models

Free, open models for generating video from text or images.

- [Wan 2.1 (Alibaba)](https://huggingface.co/Wan-AI) - State-of-the-art open video generation. High-quality text-to-video and image-to-video. Apache 2.0.
- [Mochi 1 (Genmo)](https://huggingface.co/genmo) - Open-source video generation with high motion and long duration clips.
- [LTX-Video (Lightricks)](https://huggingface.co/Lightricks) - Fast video generation model, runs in real-time on consumer GPUs. Apache 2.0.
- [CogVideo / CogVideoX (Zhipu AI)](https://huggingface.co/THUDM) - Large-scale video generation with text and image conditioning. Apache 2.0.
- [AnimateDiff (Stability AI)](https://github.com/guoyww/AnimateDiff) - Animate existing image generation models (SDXL, SD1.5) to create videos.
- [Stable Video Diffusion (Stability AI)](https://huggingface.co/stabilityai) - Image-to-video generation with state-of-the-art quality.

**Where to run:** Locally via [ComfyUI](https://github.com/comfyanonymous/ComfyUI) or for free on [Hugging Face Spaces](https://huggingface.co/spaces).

## Audio & Speech Models

Free models for speech-to-text, text-to-speech, music generation, and more.

- [Whisper (OpenAI)](https://github.com/openai/whisper) - State-of-the-art speech-to-text. Multiple sizes (tiny to large). MIT.
- [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) - High-performance port of Whisper. Runs on CPU.
- [Bark (Suno)](https://github.com/suno-ai/bark) - Text-to-audio generation (speech, music, sound effects). MIT.
- [Kokoro](https://huggingface.co/hexgrad/Kokoro-82M) - Fast, lightweight TTS model. 82MB, runs on CPU.
- [F5-TTS (Shanghai AI Lab)](https://github.com/SWivid/F5-TTS) - Flow-matching TTS with zero-shot voice cloning. Apache 2.0.
- [Fish Speech](https://github.com/fishaudio/fish-speech) - Multilingual TTS with voice cloning. Apache 2.0.
- [XTTS-v2 (Coqui)](https://github.com/coqui-ai/TTS) - Cross-lingual TTS with voice cloning. CPML.
- [ChatTTS](https://github.com/2noise/ChatTTS) - Conversational TTS optimized for dialogue. CC-BY-NC.
- [StyleTTS 2](https://github.com/yl4579/StyleTTS2) - High-quality TTS with style control. MIT.
- [Coqui TTS](https://github.com/coqui-ai/TTS) - Deep learning TTS. 1100+ languages.
- [SeamlessM4T (Meta)](https://github.com/facebookresearch/seamless_communication) - Multimodal translation: speech-to-speech, speech-to-text, text-to-speech. CC-BY-NC 4.0.
- [MMS (Meta)](https://github.com/facebookresearch/mms) - Massively Multilingual Speech. 1100+ languages. CC-BY-NC 4.0.
- [MusicGen (Meta)](https://github.com/facebookresearch/audiocraft) - Music generation from text descriptions. CC-BY-NC 4.0.
- [Stable Audio Open (Stability AI)](https://huggingface.co/stabilityai/stable-audio-open-1.0) - Generate audio from text prompts. Apache 2.0.

## Embedding Models

Free models for semantic search, RAG, and text similarity.

- [BGE-M3 (BAAI)](https://huggingface.co/BAAI/bge-m3) - Top-tier multilingual embedding. Supports dense and sparse retrieval. Apache 2.0.
- [BGE-Large / Small / Base (BAAI)](https://huggingface.co/BAAI) - Family of embedding models for different performance/speed tradeoffs. Apache 2.0.
- [E5-Mistral 7B (intfloat)](https://huggingface.co/intfloat/e5-mistral-7b-instruct) - LLM-based embedding with state-of-the-art performance. MIT.
- [E5-Small / Base / Large (intfloat)](https://huggingface.co/intfloat) - Efficient embedding models. MIT.
- [gte-large / gte-small (Alibaba)](https://huggingface.co/Alibaba-NLP) - Strong general-purpose embeddings. Apache 2.0.
- [EmbeddingGemma 300M (Google)](https://huggingface.co/google/embedding-gemma-300M) - Lightweight, fast embedding for Edge devices.
- [Qwen-Embedding 8B](https://huggingface.co/Qwen) - High-performance embedding for RAG pipelines.
- [jina-embeddings-v3 (Jina AI)](https://huggingface.co/jinaai/jina-embeddings-v3) - Multi-task embedding model. Apache 2.0.
- [Nomic Embed Text V1 (Nomic AI)](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) - Long-context embedding (8192 tokens). Apache 2.0.
- [instructor-xl (HKUNLP)](https://huggingface.co/hkunlp/instructor-xl) - Task-adaptable embeddings for retrieval and classification. Apache 2.0.
- [Sentence Transformers (SBERT)](https://www.sbert.net/) - Library and model hub for computing sentence embeddings. Pre-trained models for 100+ languages.

## RAG & Vector Databases

Free tools for building retrieval-augmented generation pipelines — vector storage, embedding search, and document retrieval.

- [Chroma](https://www.trychroma.com/) - AI-native open-source embedding database. Runs in-process, no GPU needed. [GitHub](https://github.com/chroma-core/chroma)
- [Qdrant](https://qdrant.tech/) - High-performance vector search engine. Free tier on Qdrant Cloud or self-host via Docker. [GitHub](https://github.com/qdrant/qdrant)
- [pgvector](https://github.com/pgvector/pgvector) - Vector similarity search inside PostgreSQL. Free if you already run Postgres.
- [LanceDB](https://lancedb.com/) - Developer-friendly vector database built on Lance columnar format. Runs locally, no server needed. [GitHub](https://github.com/lancedb/lancedb)
- [Weaviate](https://weaviate.io/) - Open-source vector database. Free sandbox tier on Weaviate Cloud. [GitHub](https://github.com/weaviate/weaviate)
- [Milvus (Zilliz)](https://milvus.io/) - Cloud-native vector database. Free tier on Zilliz Cloud or self-host. [GitHub](https://github.com/milvus-io/milvus)
- [txtai](https://neuml.github.io/txtai/) - AI-powered semantic search and RAG in a single Python package. [GitHub](https://github.com/neuml/txtai)
- [R2R (SciPhi)](https://r2r-docs.sciphi.ai/) - Production-ready RAG engine with API, user management, and observability. [GitHub](https://github.com/SciPhi-AI/R2R)
- [Docling (IBM)](https://docling.ibm.com/) - Document understanding and conversion for RAG pipelines. Extracts PDFs, images, and more. [GitHub](https://github.com/DS4SD/docling)
- [Unstructured.io](https://unstructured.io/) - Preprocessing toolkit for documents (PDF, HTML, Word) for RAG pipelines. Free tier available.

## Agentic Frameworks

Free, open-source frameworks for building AI agents and multi-agent systems.

- [LangGraph (LangChain)](https://langchain-ai.github.io/langgraph/) - Low-level framework for building stateful, multi-agent applications. [GitHub](https://github.com/langchain-ai/langgraph)
- [CrewAI](https://www.crewai.com/) - Multi-agent framework for orchestrating specialized AI agents to work together. [GitHub](https://github.com/crewAIInc/crewAI)
- [AutoGen (Microsoft)](https://microsoft.github.io/autogen/) - Extensible framework for building multi-agent conversations. [GitHub](https://github.com/microsoft/autogen)
- [Agno (formerly Phidata)](https://www.agno.com/) - Full-stack AI framework for building multimodal agents with memory, knowledge, and tools. [GitHub](https://github.com/agno-org/agno)
- [PydanticAI](https://ai.pydantic.dev/) - Agent framework by Pydantic with type-safe outputs and dependency injection. [GitHub](https://github.com/pydantic/pydantic-ai)
- [Mastra](https://mastra.ai/) - TypeScript framework for building AI applications and agent workflows. [GitHub](https://github.com/mastra-ai/mastra)
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) - Lightweight SDK for building single and multi-agent systems. [GitHub](https://github.com/openai/openai-agents-python)
- [Semantic Kernel (Microsoft)](https://learn.microsoft.com/en-us/semantic-kernel/) - SDK for orchestrating AI agents with planners, memory, and connectors. [GitHub](https://github.com/microsoft/semantic-kernel)
- [Dify](https://dify.ai/) - LLM app development platform with visual workflow builder and agent capabilities. [GitHub](https://github.com/langgenius/dify)
- [Flowise](https://flowiseai.com/) - Low-code visual LLM flow builder with drag-and-drop interface. [GitHub](https://github.com/FlowiseAI/Flowise)
- [TaskWeaver (Microsoft)](https://microsoft.github.io/TaskWeaver/) - Code-first agent framework for planning and executing complex tasks. [GitHub](https://github.com/microsoft/TaskWeaver)
- [Fazm](https://github.com/fazm-ai/fazm) - **NEW (Apr 2026).** Open-source local computer-use agent for macOS. Drives apps via accessibility APIs, model-agnostic, faster than screenshot-based agents.

## Fine-tuning Tools

Tools to fine-tune free models on your own data — all free and open-source.

- [Unsloth](https://github.com/unslothai/unsloth) - Fast memory-efficient fine-tuning. 2x faster, 50% less memory. Supports QLoRA, LoRA, full fine-tune.
- [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) - Streamlined fine-tuning framework supporting multiple model architectures and quantization methods.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - Easy-to-use fine-tuning with web UI. Supports 100+ models, multiple training methods.
- [Hugging Face TRL](https://github.com/huggingface/trl) - Transformer Reinforcement Learning library. SFT, PPO, DPOTrainer, GRPOTrainer for aligning models.
- [TorchTune (Meta)](https://github.com/pytorch/torchtune) - Native PyTorch library for fine-tuning LLMs. Simple, extensible, efficient.
- [AutoTrain (Hugging Face)](https://github.com/huggingface/autotrain-advanced) - No-code fine-tuning platform. Train models with a web UI or API.
- [XTuner (InternLM)](https://github.com/InternLM/xtuner) - Efficient fine-tuning toolkit supporting QLoRA, LoRA, and full fine-tune with multiple model architectures.
- [Ludwig (Predibase)](https://ludwig.ai/) - Declarative ML framework. Fine-tune models with a simple config file. [GitHub](https://github.com/ludwig-ai/ludwig)

## Prompt Engineering Tools

Free tools for testing, managing, and optimizing prompts.

- [Promptfoo](https://www.promptfoo.dev/) - Open-source tool for prompt testing and evaluation. Systematic A/B testing of prompts. [GitHub](https://github.com/promptfoo/promptfoo)
- [Fabric (Daniel Miessler)](https://github.com/danielmiessler/fabric) - Open-source framework for augmenting humans with AI. Library of curated prompts (patterns) for common tasks.
- [LangFuse](https://langfuse.com/) - Open-source LLM engineering platform with prompt management, versioning, and evaluation. [GitHub](https://github.com/langfuse/langfuse)
- [OpenPrompt](https://thunlp.github.io/OpenPrompt/README.html) - Framework for prompt-learning research. Supports template and verbalizer design.
- [DSPy (Stanford)](https://dspy.ai/) - Framework for algorithmically optimizing LM prompts and weights. [GitHub](https://github.com/stanfordnlp/dspy)
- [Agenta](https://agenta.ai/) - Open-source LLM platform for prompt management, evaluation, and deployment. [GitHub](https://github.com/Agenta-AI/agenta)

## Datasets

Free, open datasets for training, fine-tuning, and evaluating models.

- [Hugging Face Datasets](https://huggingface.co/datasets) - The standard hub for open datasets. 150,000+ datasets across all tasks.
- [Common Corpus](https://huggingface.co/datasets/common-catalog) - Massive open-source dataset for training large language models.
- [The Stack v2 (BigCode)](https://huggingface.co/datasets/bigcode/the-stack-v2) - Large-scale code dataset covering 619 programming languages. Permissive license.
- [FineWeb (Hugging Face)](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - High-quality web dataset for LLM pre-training. 15T tokens.
- [Dolly (Databricks)](https://huggingface.co/datasets/databricks/databricks-dolly-15k) - 15k instruction-response pairs for fine-tuning. CC-BY-SA.
- [OpenAssistant Conversations](https://huggingface.co/datasets/OpenAssistant/oasst1) - 160k human-generated assistant conversations. Apache 2.0.
- [ShareGPT (RyokoAI)](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) - Real user-ChatGPT conversations for fine-tuning.
- [UltraChat (Sean C.)](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k) - 200k multi-turn conversations synthesized by ChatGPT.
- [No Robots (Hugging Face)](https://huggingface.co/datasets/HuggingFaceH4/no_robots) - 10k high-quality human-written instructions. Apache 2.0.
- [RLAIF-V (OpenBMB)](https://huggingface.co/datasets/openbmb/RLAIF-V) - AI-generated preference data for RLHF. Apache 2.0.
- [MMLU / GSM8K](https://huggingface.co/datasets) - Standard benchmarks for evaluation. Available on Hugging Face Datasets.

## Model Hosting Platforms

Free platforms that host models — run inference without downloading anything.

- [Hugging Face Spaces](https://huggingface.co/spaces) - Free hosting for ML apps (Gradio, Streamlit). Thousands of community demos.
- [Hugging Face Inference Endpoints (Free Tier)](https://huggingface.co/inference-endpoints) - Deploy models with free trial credits.
- [Google Colab (Free Tier)](https://colab.research.google.com/) - Free GPU (T4, sometimes A100). Perfect for running models and fine-tuning.
- [Kaggle Notebooks](https://www.kaggle.com/code) - Free GPU (T4 x2). 30 hours/week. Good for heavier workloads.
- [Lightning AI Studio](https://lightning.ai/) - Free tier with GPU access for development and prototyping.
- [Modal](https://modal.com/) - Free monthly credits for serverless GPU compute.
- [Replicate (Free Tier)](https://replicate.com/) - Free credits for running community models.
- [Deepnote](https://deepnote.com/) - Free tier with GPU for data science and ML notebooks.

## Learning Resources

Free courses, books, and tutorials for learning AI and LLMs.

- [Fast.ai](https://www.fast.ai/) - Code-first deep learning education. Practical, free courses from fundamentals to advanced.
- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) - Comprehensive free course on transformers, tokenizers, datasets, and deployment.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - Free short courses on LLMs, RAG, LangChain, and AI agents.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) - Free course on ML engineering: training, deploying, and maintaining models.
- [Andrej Karpathy's Course](https://karpathy.ai/zero-to-hero.html) - From-scratch neural network implementation videos.
- [Neural Networks: Zero to Hero](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) - YouTube series building neural networks from scratch.
- [LLM University (Cohere)](https://docs.cohere.com/docs/llmu) - Free course on LLMs, embeddings, and RAG.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) - Comprehensive free guide on prompt engineering techniques.
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) - Free recipes and patterns for working with Claude.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Free examples and guides for the OpenAI API.

## Resources & Leaderboards

- [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) - The primary benchmark for open-weight models. Updated regularly.
- [LMSYS Chatbot Arena](https://lmarena.ai/) - Human preference rankings of models. Best source for real-world quality comparisons.
- [Artificial Analysis](https://artificialanalysis.ai/) - Independent benchmarks for speed, pricing, and quality across providers.
- [Hugging Face Models](https://huggingface.co/models) - Search 1M+ models. Filter by license, task, framework.
- [OpenRouter Models](https://openrouter.ai/models) - Browse models available via API with pricing and free tiers.
- [Ollama Library](https://ollama.com/library) - Browse models available for one-command local setup.
- [cheahjs/free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources) - Community-maintained list of free LLM API resources.
- [SweetTea](https://www.sweettea.ai/) - Community voting on model quality and preference.
- [Natural Language Processing (NLP) Progress](https://nlpprogress.com/) - Tracking progress in NLP across tasks and benchmarks.
- [EvalPlus (Code)](https://evalplus.github.io/) - Rigorous evaluation framework for code generation models.
- [Hugging Face Open ASR Leaderboard](https://huggingface.co/spaces/open-asr-leaderboard/leaderboard) - Benchmarks for speech recognition models.
- [Hugging Face Text-to-Image Leaderboard](https://huggingface.co/spaces/text-to-image-leaderboard/leaderboard) - Rankings for image generation models.

## Communities

- [Hugging Face Discord](https://discord.gg/huggingface) - Model releases, discussions, and community support.
- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) - The largest Reddit community for running local LLMs.
- [Ollama Discord](https://discord.gg/ollama) - Ollama community for local model enthusiasts.
- [LM Studio Discord](https://discord.gg/lmstudio) - LM Studio community.
- [Hugging Face Forums](https://discuss.huggingface.co/) - Discussions on models, datasets, and Spaces.
- [r/MachineLearning](https://reddit.com/r/MachineLearning) - General ML/AI research and news.
- [LinkedIn AI Community](https://www.linkedin.com/groups/14249523/) - Professional AI discussions and networking.
- [Discord: AI Agents](https://discord.gg/ai-agents) - Community for AI agent development and agentic frameworks.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
