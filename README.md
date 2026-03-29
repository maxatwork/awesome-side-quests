# Awesome Side Quests [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A loosely organized list of GitHub repos I starred because they looked useful, clever, weird, or likely to become relevant in some unexpected future.
>
> Broad interests, light curation, and just enough order to keep the interesting bits from escaping.

This is not a strict canon or a carefully pruned "best of" list. It is a map of side quests across AI, frontend, mobile, backend, game development, devtools, and whatever else wandered into view and seemed worth keeping.

## Contents

- [AI & LLM](#ai-llm) (136)
  - [LLM Apps & Interfaces](#llm-apps-interfaces) (43)
  - [Agents & Orchestration](#agents-orchestration) (44)
  - [RAG & Vector Search](#rag-vector-search) (24)
  - [MCP & Tool Use](#mcp-tool-use) (7)
  - [ML & Training](#ml-training) (15)
  - [Image Generation](#image-generation) (3)
- [Web Frontend](#web-frontend) (202)
  - [React & UI Libraries](#react-ui-libraries) (47)
  - [Next.js](#nextjs) (9)
  - [Svelte](#svelte) (16)
  - [Vue](#vue) (1)
  - [JS Libraries & Utilities](#js-libraries-utilities) (89)
  - [Animation & Canvas](#animation-canvas) (13)
  - [UI Components & Styling](#ui-components-styling) (7)
  - [Maps & Geo](#maps-geo) (4)
  - [Data Visualization & Charts](#data-visualization-charts) (2)
  - [Real-Time & Collaboration](#real-time-collaboration) (4)
  - [DOM & Browser APIs](#dom-browser-apis) (3)
  - [General Frontend](#general-frontend) (7)
- [Mobile](#mobile) (81)
  - [React Native & Expo](#react-native-expo) (74)
  - [iOS](#ios) (5)
  - [Android](#android) (1)
  - [Cross-Platform](#cross-platform) (1)
- [Backend & Infrastructure](#backend-infrastructure) (48)
  - [Databases & ORM](#databases-orm) (17)
  - [General Backend](#general-backend) (11)
  - [APIs & Protocols](#apis-protocols) (4)
  - [Auth & Security](#auth-security) (4)
  - [DevOps & Deployment](#devops-deployment) (5)
  - [Self-Hosted & Homelab](#self-hosted-homelab) (3)
  - [Bots & Messaging](#bots-messaging) (3)
  - [Email & Messaging](#email-messaging) (1)
- [Game Development](#game-development) (92)
  - [Godot](#godot) (57)
  - [General Game Dev](#general-game-dev) (22)
  - [Procedural Generation](#procedural-generation) (8)
  - [Graphics & Shaders](#graphics-shaders) (4)
  - [Cloud & Streaming Gaming](#cloud-streaming-gaming) (1)
- [Developer Tools](#developer-tools) (72)
  - [Editors & Plugins](#editors-plugins) (11)
  - [Python Tools](#python-tools) (29)
  - [CLI & Terminal](#cli-terminal) (4)
  - [Linting & Formatting](#linting-formatting) (5)
  - [Build Tools & Bundlers](#build-tools-bundlers) (4)
  - [Testing & Debugging](#testing-debugging) (8)
  - [Desktop App Frameworks](#desktop-app-frameworks) (3)
  - [Document Processing](#document-processing) (2)
  - [General Dev Tools](#general-dev-tools) (6)
- [Systems & Low-Level](#systems-low-level) (35)
  - [Rust](#rust) (5)
  - [C / C++ & Systems](#c-c-systems) (29)
  - [Zig](#zig) (1)
- [Data & Analytics](#data-analytics) (11)
  - [Analytics & Feature Flags](#analytics-feature-flags) (5)
  - [Data Science & Visualization](#data-science-visualization) (6)
- [Knowledge Management](#knowledge-management) (3)
  - [Notes & Diagrams](#notes-diagrams) (3)
- [Productivity & Apps](#productivity-apps) (3)
  - [Personal & Business Apps](#personal-business-apps) (3)
- [Miscellaneous](#miscellaneous) (9)
  - [Curated Lists & Resources](#curated-lists-resources) (2)
  - [Audio & Music](#audio-music) (3)
  - [Media & Streaming](#media-streaming) (2)
  - [Other](#other) (2)

---

## AI & LLM

### LLM Apps & Interfaces

- [openclaw](https://github.com/openclaw/openclaw) — A self-hostable AI assistant with a surprisingly memorable crustacean branding — run it anywhere
- [ollama](https://github.com/ollama/ollama) — The easiest way to run LLMs locally — one command, dozens of models, no cloud required
- [markitdown](https://github.com/microsoft/markitdown) — Converts almost any document format — PDFs, Office files, images — into clean Markdown for LLM ingestion
- [Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam) — Real-time face swap from a single photo — works live on your webcam feed
- [spec-kit](https://github.com/github/spec-kit) — Toolkit for Spec-Driven Development, helping you write specs that AI agents can actually execute
- [vllm](https://github.com/vllm-project/vllm) — The go-to high-throughput LLM serving engine — PagedAttention, continuous batching, serious production scale
- [open-interpreter](https://github.com/openinterpreter/open-interpreter) — Gives an LLM a shell — it can write code, run it, see results, and iterate on your machine
- [Fabric](https://github.com/danielmiessler/Fabric) — A framework of reusable AI prompts ("patterns") for augmenting everyday human workflows
- [chatbox](https://github.com/chatboxai/chatbox) — Desktop AI client that works with any LLM API — clean UI, local history, no subscriptions
- [system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) — Extracted system prompts from ChatGPT, Claude, Gemini and others — a window into how big AI products actually behave
- [langextract](https://github.com/google/langextract) — LLM-powered structured extraction from unstructured text that keeps precise source grounding
- [prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) — Anthropic's official hands-on prompt engineering tutorial — the canonical place to learn how to talk to Claude
- [gpt-pilot](https://github.com/Pythagora-io/gpt-pilot) — ⚠️ STALE — AI developer that writes full apps iteratively — one of the earlier serious attempts at autonomous coding
- [tabby](https://github.com/TabbyML/tabby) — Self-hosted AI coding assistant you can run on your own GPU — GitHub Copilot but yours
- [storm](https://github.com/stanford-oval/storm) — ⚠️ STALE — Researches any topic from scratch and writes a full Wikipedia-style report with citations — remarkably good
- [onlook](https://github.com/onlook-dev/onlook) — Visual design tool that directly edits your React codebase — like Figma but your components stay real
- [langfuse](https://github.com/langfuse/langfuse) — Open-source LLM observability platform — tracing, evals, prompt management, and a playground in one place
- [chatbot](https://github.com/vercel/chatbot) — Vercel's reference AI chatbot — a fully-featured Next.js + AI SDK starter worth forking
- [dia](https://github.com/nari-labs/dia) — ⚠️ STALE — TTS model that generates ultra-realistic multi-speaker dialogue in a single pass — demos are uncanny
- [heretic](https://github.com/p-e-w/heretic) — Strips safety filters from local LLMs — fully automatic, no manual prompt hacking needed
- [gitdiagram](https://github.com/ahmedkhaleel2004/gitdiagram) — Paste a GitHub URL, get an interactive architecture diagram in seconds — free and sharp
- [deepeval](https://github.com/confident-ai/deepeval) — The pytest for LLM apps — unit-test your prompts and RAG pipelines with real evaluation metrics
- [puck](https://github.com/puckeditor/puck) — Self-hostable visual page builder built on React — bring your own components, own your data
- [meetily](https://github.com/Zackriya-Solutions/meetily) — Privacy-first meeting assistant with fast local Whisper transcription, diarization, and Ollama summaries
- [inbox-zero](https://github.com/elie222/inbox-zero) — AI email assistant that actually reaches inbox zero — open-source, self-hostable, integrates with Gmail
- [open-infra-index](https://github.com/deepseek-ai/open-infra-index) — ⚠️ STALE — DeepSeek's production AI infrastructure stack released open-source — the real backbone behind their models
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) — Natural language interface for Kubernetes — describe what you want, get kubectl commands back
- [vibe](https://github.com/thewh1teagle/vibe) — Local Whisper-based transcription desktop app — drag in audio, get clean text, no cloud needed
- [poml](https://github.com/microsoft/poml) — Prompt Orchestration Markup Language — Microsoft's structured format for complex multi-step LLM workflows
- [ARC-AGI](https://github.com/fchollet/ARC-AGI) — ⚠️ STALE — The benchmark that humbles AI — visual pattern puzzles humans solve instantly that still trip up frontier models
- [mlx-lm](https://github.com/ml-explore/mlx-lm) — Run LLMs on Apple Silicon with MLX — the native Apple way to do local inference, fast
- [flyde](https://github.com/flydelabs/flyde) — ⚠️ STALE — Visual node-based programming that actually integrates with existing TypeScript codebases — not a toy
- [mini-omni2](https://github.com/gpt-omni/mini-omni2) — ⚠️ STALE — Open-source GPT-4o-style model with vision, speech, and duplex capabilities — ambitious multimodal experiment
- [contextgem](https://github.com/shcherbak-ai/contextgem) — Effortless structured LLM extraction from documents — schema-driven, with minimal boilerplate
- [ChatGPT-System-Prompts](https://github.com/mustvlad/ChatGPT-System-Prompts) — ⚠️ STALE — Curated collection of effective system prompts for ChatGPT — useful starting points for role/persona design
- [nobodywho](https://github.com/nobodywho-ooo/nobodywho) — Inference engine designed to run LLMs locally on any device, including within game engines
- [simplexity-ai-app](https://github.com/inulute/simplexity-ai-app) — Community-built Electron desktop app for Perplexity-style AI search — open-source AI browsing
- [nano-aha-moment](https://github.com/McGill-NLP/nano-aha-moment) — ⚠️ STALE — Minimal single-file RL fine-tuning for LLMs — reproduces the "aha moment" effect from DeepSeek-R1
- [openllmetry-js](https://github.com/traceloop/openllmetry-js) — OpenTelemetry-based LLM observability for TypeScript — trace your AI calls just like regular infra
- [langfuse-python](https://github.com/langfuse/langfuse-python) — Langfuse Python SDK — decorator-based or low-level tracing for any LLM app
- [gpt4-spanish](https://github.com/jbrukh/gpt4-spanish) — ⚠️ STALE — A GPT-4 prompt system for Spanish language learning — simple, effective language practice via AI
- [langfuse-js](https://github.com/langfuse/langfuse-js) — Langfuse JS/TS SDK — instrument your LLM app and get detailed tracing in any JavaScript framework
- [qa-kgraph](https://github.com/drskennedy/qa-kgraph) — ⚠️ STALE — Queries private documents using LlamaIndex knowledge graphs and a local LLM — local RAG with graph structure

### Agents & Orchestration

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — The original autonomous AI agent — sparked the whole agentic AI movement, still actively developed
- [langflow](https://github.com/langflow-ai/langflow) — Low-code visual builder for LLM workflows and agents — drag, connect, deploy
- [superpowers](https://github.com/obra/superpowers) — Agentic skills framework for Claude Code — the methodology this very system is built on
- [firecrawl](https://github.com/firecrawl/firecrawl) — Turns any website into clean LLM-ready data — scraping, crawling, and structured extraction as a service
- [browser-use](https://github.com/browser-use/browser-use) — Lets AI agents control a real browser — the cleanest abstraction for web automation with LLMs
- [claude-code](https://github.com/anthropics/claude-code) — Anthropic's official agentic coding tool — understands your codebase and works from the terminal
- [lobehub](https://github.com/lobehub/lobehub) — All-in-one AI workspace with agent marketplace, plugin system, and multi-model chat
- [OpenBB](https://github.com/OpenBB-finance/OpenBB) — Open-source financial data platform built for analysts, quants, and AI agents — Bloomberg alternative
- [crewAI](https://github.com/crewAIInc/crewAI) — Role-playing multi-agent framework — assign tasks to AI "crew members" who collaborate autonomously
- [TradingAgents](https://github.com/TauricResearch/TradingAgents) — Multi-agent LLM system for financial trading — multiple specialized agents debate and decide together
- [cherry-studio](https://github.com/CherryHQ/cherry-studio) — AI productivity studio with 300+ assistants and unified access to frontier LLMs — polished all-in-one
- [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — Curated list of skills, hooks, commands, and agents for Claude Code — the community resource for this ecosystem
- [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Chrome DevTools as an MCP server — lets coding agents inspect, debug, and automate in the browser
- [CopilotKit](https://github.com/CopilotKit/CopilotKit) — Frontend SDK for building in-app AI copilots — adds AI-native UI patterns to any React app
- [awesome-copilot](https://github.com/github/awesome-copilot) — Community-contributed instructions, agents, and configurations for GitHub Copilot — the unofficial cookbook
- [ai](https://github.com/vercel/ai) — Vercel's AI SDK for TypeScript — abstracts over all major LLM providers with streaming, tools, and RSC support
- [mastra](https://github.com/mastra-ai/mastra) — TypeScript agent framework from the Gatsby team — well-structured, production-minded, modern DX
- [AionUi](https://github.com/iOfficeAI/AionUi) — Local 24/7 AI cowork app with support for Claude Code, Codex, Gemini CLI, and more in one place
- [deep-research](https://github.com/dzhng/deep-research) — ⚠️ STALE — AI research assistant that iterates through search and synthesis to produce deep, sourced reports
- [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) — Alibaba's open-source deep research agent — iterative web research with planning and synthesis
- [deepagents](https://github.com/langchain-ai/deepagents) — LangGraph-based agent harness with planning tools, filesystem access, and web browsing
- [agent-lightning](https://github.com/microsoft/agent-lightning) — Microsoft's training framework for AI agents — optimizing agent behavior at scale
- [hermes-agent](https://github.com/NousResearch/hermes-agent) — Agent framework from the Hermes model team — grows and adapts with your use cases
- [maxun](https://github.com/getmaxun/maxun) — No-code web scraping platform — turn any website into structured data with visual point-and-click automation
- [iii](https://github.com/iii-hq/iii) — Backend unification engine with three primitives: Function, Stream, and State — opinionated but powerful
- [DeepCode](https://github.com/HKUDS/DeepCode) — Agentic coding system for paper-to-code, text-to-web, and text-to-backend generation
- [page-agent](https://github.com/alibaba/page-agent) — In-page JavaScript GUI agent — control web interfaces with natural language from within the page itself
- [pentagi](https://github.com/vxcontrol/pentagi) — Fully autonomous AI penetration testing agent — hands-off security research at agent scale
- [cmux](https://github.com/manaflow-ai/cmux) — Ghostty-based macOS terminal with vertical tabs and agent-specific notification management
- [tambo](https://github.com/tambo-ai/tambo) — Generative UI SDK for React — LLMs render actual React components, not just text
- [Personal_AI_Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure) — Daniel Miessler's personal agentic AI stack — a blueprint for AI-augmented personal productivity
- [PocketFlow](https://github.com/The-Pocket/PocketFlow) — 100-line LLM framework — so minimal it fits in a README, yet capable enough to build real agents
- [rowboat](https://github.com/rowboatlabs/rowboat) — Open-source AI coworker with persistent memory — multi-agent collaboration with context retention
- [open-swe](https://github.com/langchain-ai/open-swe) — Open-source async coding agent from LangChain — tackles software engineering tasks autonomously
- [openai-realtime-agents](https://github.com/openai/openai-realtime-agents) — Demo of advanced agentic patterns on the OpenAI Realtime API — voice agents with tool calls and handoffs
- [jaaz](https://github.com/11cafe/jaaz) — Open-source multimodal creative assistant — Canva meets Manus for image-first creative workflows
- [browser-agent](https://github.com/magnitudedev/browser-agent) — Vision-first browser agent — uses screenshots to understand and interact with any web UI
- [memgraph](https://github.com/memgraph/memgraph) — Open-source graph database tuned for real-time dynamic analytics — fast, Cypher-compatible, embeddable
- [openai-agents-js](https://github.com/openai/openai-agents-js) — OpenAI's official lightweight multi-agent framework for JS — voice agents, tool use, handoffs built-in
- [RA.Aid](https://github.com/ai-christianson/RA.Aid) — Autonomous software development agent — plans, researches, and implements full features end-to-end
- [gateway](https://github.com/adaline/gateway) — Local production-grade LLM gateway with a unified interface across all major providers — no vendor lock-in
- [awesome-copilot-agents](https://github.com/Code-and-Sorts/awesome-copilot-agents) — Curated Copilot instructions, prompt files, and agent configs — community-maintained best practices
- [PocketFlow-Typescript](https://github.com/The-Pocket/PocketFlow-Typescript) — ⚠️ STALE — TypeScript port of PocketFlow — minimalist LLM framework that lets agents build agents
- [Riona-AI-Agent](https://github.com/David-patrick-chuks/Riona-AI-Agent) — Lightweight TypeScript AI agent for social media automation — built for scheduled job execution

### RAG & Vector Search

- [open-webui](https://github.com/open-webui/open-webui) — The best self-hosted UI for Ollama and OpenAI-compatible APIs — feature-rich, polished, actively developed
- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) — Curated collection of production-ready LLM app examples with RAG, agents, and multiple model providers
- [anything-llm](https://github.com/Mintplex-Labs/anything-llm) — All-in-one local AI workspace — chat with your documents, run agents, no setup friction
- [mem0](https://github.com/mem0ai/mem0) — Universal persistent memory layer for AI agents — remembers users and context across sessions
- [claude-mem](https://github.com/thedotmack/claude-mem) — Claude Code plugin that auto-captures session activity and compresses it into persistent memory
- [khoj](https://github.com/khoj-ai/khoj) — Your self-hostable AI second brain — chat with your notes, schedule automations, build custom agents
- [Vane](https://github.com/ItzCrazyKns/Vane) — AI-powered answering engine — Perplexity-style search but open-source and self-hostable
- [ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub) — In-depth tutorials on LLMs, RAG pipelines, and real-world AI agent deployments — solid learning resource
- [graphiti](https://github.com/getzep/graphiti) — Builds evolving knowledge graphs for AI agents in real time — temporal memory with relationship context
- [PageIndex](https://github.com/VectifyAI/PageIndex) — Reasoning-based RAG without vectors — uses document structure and LLM reasoning instead of embeddings
- [crawlee](https://github.com/apify/crawlee) — Production-grade web scraping and browser automation library for Node.js — the serious crawler framework
- [12-factor-agents](https://github.com/humanlayer/12-factor-agents) — ⚠️ STALE — The Twelve-Factor methodology applied to LLM agents — principles for building reliable production AI software
- [WrenAI](https://github.com/Canner/WrenAI) — GenBI that translates natural language into accurate SQL, then charts — text-to-analytics for any database
- [easy-dataset](https://github.com/ConardLi/easy-dataset) — Tool for creating fine-tuning and RAG datasets from documents — streamlines the data prep pipeline
- [memvid](https://github.com/memvid/memvid) — Encodes agent memory into video files — an unorthodox but creative approach to serverless memory layers
- [note-gen](https://github.com/codexu/note-gen) — Cross-platform AI note-taking app in Markdown — knowledge capture with LLM-powered organization
- [orama](https://github.com/oramasearch/orama) — Full-text + vector + RAG search engine running in browser, server, or edge — zero infrastructure required
- [SQLBot](https://github.com/dataease/SQLBot) — Conversational SQL analytics via LLMs + RAG — ask your database questions in plain Chinese or English
- [UltraRAG](https://github.com/OpenBMB/UltraRAG) — Low-code MCP framework for building complex and innovative RAG pipelines — composable and extensible
- [morphik-core](https://github.com/morphik-org/morphik-core) — Document search and retrieval engine optimized for accuracy in AI apps — beats generic vector stores for docs
- [rag-fusion](https://github.com/Raudaschl/rag-fusion) — Multi-query RAG with Reciprocal Rank Fusion — better retrieval through query expansion and rank merging
- [unfake.js](https://github.com/jenissimo/unfake.js) — ⚠️ STALE — Browser-based tool to fix AI-generated pixel art and vector artifacts — handy post-processing for AI visuals
- [rag-chatbot](https://github.com/datvodinh/rag-chatbot) — ⚠️ STALE — Local RAG chatbot that lets you chat with multiple PDFs — simple, runs entirely offline
- [claude-code-agentic-rag-series](https://github.com/theaiautomators/claude-code-agentic-rag-series) — Planning docs and PRDs for a full-stack Claude Code + RAG masterclass — educational reference material

### MCP & Tool Use

- [n8n](https://github.com/n8n-io/n8n) — Fair-code workflow automation with native AI capabilities — self-hosted Zapier that you actually own
- [repomix](https://github.com/yamadashy/repomix) — Packs an entire repo into a single AI-friendly file — essential for feeding codebases to LLMs
- [servers](https://github.com/modelcontextprotocol/servers) — The official MCP server implementations — reference servers for filesystem, web search, databases, and more
- [typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) — Official TypeScript SDK for building MCP servers and clients — the standard way to implement MCP in TS
- [inspector](https://github.com/modelcontextprotocol/inspector) — Visual testing tool for MCP servers — inspect, test, and debug your MCP implementations interactively
- [ha-mcp](https://github.com/homeassistant-ai/ha-mcp) — Unofficial Home Assistant MCP server — control your smart home through any MCP-compatible AI agent
- [mcp-ui](https://github.com/MCP-UI-Org/mcp-ui) — Brings real UI rendering to MCP — lets AI tools return interactive components, not just text

### ML & Training

- [prompts.chat](https://github.com/f/prompts.chat) — The original ChatGPT prompt collection — community-contributed, open-source, and still growing
- [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) — ⚠️ STALE — DeepSeek's reasoning model that shocked the AI world — open weights, chain-of-thought, competitive with o1
- [LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) — Build a GPT-like LLM from scratch in PyTorch — the best book/repo for understanding transformers deeply
- [netron](https://github.com/lutzroeder/netron) — Visualizer for neural network models — inspect any ONNX, TensorFlow, or PyTorch model's architecture
- [label-studio](https://github.com/HumanSignal/label-studio) — Multi-type data labeling and annotation tool with a standardized output format — the open-source Label Studio
- [DeepSpeech](https://github.com/mozilla/DeepSpeech) — 🪦 ARCHIVED — Mozilla's offline speech-to-text engine — embedded, on-device, real-time capable; now archived but still referenced
- [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) — Generates bitmaps and tilemaps from a single example using quantum-mechanics-inspired constraint propagation
- [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) — Production-grade Rust-native trading engine with deterministic event-driven architecture
- [CosyVoice](https://github.com/FunAudioLLM/CosyVoice) — Multi-lingual voice generation model with full training, inference, and deployment stack
- [HRM](https://github.com/sapientinc/HRM) — ⚠️ STALE — Hierarchical Reasoning Model — research release exploring structured multi-step reasoning architectures
- [transformer-explainer](https://github.com/poloclub/transformer-explainer) — Interactive visual explainer of transformer internals — the best way to understand attention intuitively
- [deep-chat](https://github.com/OvidijusParsiunas/deep-chat) — Fully customizable AI chatbot web component — drop it into any page, connect any LLM
- [ru-gpts](https://github.com/ai-forever/ru-gpts) — ⚠️ STALE — Russian GPT-3-scale models — open-source large language models for the Russian language
- [vocal-remover](https://github.com/tsurumeso/vocal-remover) — ⚠️ STALE — Removes vocals from music using deep neural networks — solid results, runs locally
- [todo-task](https://github.com/plandes/todo-task) — ⚠️ STALE — Research into supervised interpretation of imperative to-do list items — niche but fascinating NLP work

### Image Generation

- [stable-diffusion-webui-docker](https://github.com/AbdBarho/stable-diffusion-webui-docker) — ⚠️ STALE — Docker setup for Stable Diffusion with a user-friendly UI — the easiest way to get AUTOMATIC1111 running
- [Kandinsky-2](https://github.com/ai-forever/Kandinsky-2) — ⚠️ STALE — Multilingual text-to-image latent diffusion model from Sber — Russia's answer to Stable Diffusion
- [UE5-Dream](https://github.com/albertotrunk/UE5-Dream) — ⚠️ STALE — Local Stable Diffusion integration for Unreal Engine 5 — AI image generation inside UE5

---

## Web Frontend

### React & UI Libraries

- [react](https://github.com/facebook/react) — The library that changed web UI forever — declarative, component-based, and still the dominant choice
- [zustand](https://github.com/pmndrs/zustand) — Tiny, bear-themed React state management — no boilerplate, no context hell, just works
- [query](https://github.com/TanStack/query) — Server-state management that makes data fetching feel trivial — caching, syncing, background updates handled
- [tldraw](https://github.com/tldraw/tldraw) — Best-in-class infinite canvas SDK — the whiteboard under the hood of many modern collaboration tools
- [twenty](https://github.com/twentyhq/twenty) — Open-source CRM built as a modern Salesforce alternative — community-powered, clean, extensible
- [remotion](https://github.com/remotion-dev/remotion) — Make videos programmatically with React — render motion graphics and video using the tools you already know
- [novu](https://github.com/novuhq/novu) — Open-source notification infrastructure — in-app, email, SMS, push, and Slack from one unified API
- [outline](https://github.com/outline/outline) — Fast, beautiful team knowledge base — real-time collaborative, Markdown-compatible, great for growing teams
- [ToolJet](https://github.com/ToolJet/ToolJet) — Open-source low-code platform for building internal tools and dashboards — visual but still developer-friendly
- [react-bits](https://github.com/DavidHDev/react-bits) — Animated, interactive, fully customizable React components — the kind that make your app feel premium
- [drawdb](https://github.com/drawdb-io/drawdb) — Free in-browser database diagram editor with SQL generation — fastest way to sketch a schema
- [xyflow](https://github.com/xyflow/xyflow) — React Flow and Svelte Flow — the go-to library for building node-based UIs and flow diagrams
- [solid](https://github.com/solidjs/solid) — Fine-grained reactive UI library that compiles away — faster than React, no virtual DOM, fascinating approach
- [slate](https://github.com/ianstormtaylor/slate) — Fully customizable rich text editor framework — the foundation layer for building Notion-like editors
- [heroui](https://github.com/heroui-inc/heroui) — Beautiful, fast React UI library — previously NextUI, accessible, visually polished, Tailwind-based
- [chartdb](https://github.com/chartdb/chartdb) — Visualize and design your database schema with a single introspection query — instant ER diagrams
- [react-scan](https://github.com/aidenybai/react-scan) — Scans your React app for performance issues and highlights slow renders in real time — zero config
- [dnd-kit](https://github.com/clauderic/dnd-kit) — Modern, accessible drag-and-drop toolkit for React — handles the edge cases other DnD libs ignore
- [inferno](https://github.com/infernojs/inferno) — Extremely fast React-like library — worth knowing when raw rendering performance is the constraint
- [auto-animate](https://github.com/formkit/auto-animate) — Zero-config animation utility — add smooth transitions to any React, Vue, or vanilla JS list with one line
- [pragmatic-drag-and-drop](https://github.com/atlassian/pragmatic-drag-and-drop) — Atlassian's production DnD library — fast, accessible, tech-stack agnostic, and battle-tested at Jira scale
- [cmdk](https://github.com/dip/cmdk) — ⚠️ STALE — Fast, unstyled command menu for React — the headless core behind most ⌘K palettes you've used
- [usehooks](https://github.com/uidotdev/usehooks) — ⚠️ STALE — Curated collection of modern, server-safe React hooks — from the team behind ui.dev
- [BlockNote](https://github.com/TypeCellOS/BlockNote) — Block-based rich text editor like Notion — extensible, built on Prosemirror and Tiptap
- [omni-tools](https://github.com/iib0011/omni-tools) — Self-hosted collection of 100+ browser-based utility tools — no ads, no tracking, just tools
- [virtual](https://github.com/TanStack/virtual) — Headless virtualization for large lists — handles millions of rows in React, Solid, Vue, or Svelte
- [golden-layout](https://github.com/golden-layout/golden-layout) — Multi-window docking layout manager for webapps — the classic choice for IDE-style panel interfaces
- [glide-data-grid](https://github.com/glideapps/glide-data-grid) — Outrageously fast React data grid with rich rendering — handles millions of rows without breaking a sweat
- [signals](https://github.com/preactjs/signals) — Fine-grained reactive state with a tiny footprint — works in React, Preact, and plain JS
- [dockview](https://github.com/mathuo/dockview) — Zero-dependency docking layout with tabs, groups, grids, and split views — the VSCode layout pattern
- [egjs-infinitegrid](https://github.com/naver/egjs-infinitegrid) — Infinite scrolling grid layout for cards and content — smooth, configurable, handles dynamic content
- [intentui](https://github.com/intentui/intentui) — Chill React components built on React Aria and Tailwind — accessible by default, easy to customize
- [twc](https://github.com/gregberge/twc) — ⚠️ STALE — Create reusable React + Tailwind components in a single line — the missing abstraction for Tailwind
- [react-complex-tree](https://github.com/lukasbach/react-complex-tree) — Unopinionated, accessible tree component with multi-select and drag-and-drop — handles the complex cases
- [FlexLayout](https://github.com/caplin/FlexLayout) — Docking layout manager for React — split panels, tabs, and floating windows with minimal setup
- [allotment](https://github.com/johnwalley/allotment) — React component for resizable split views — VSCode-style panel splitting in a few lines
- [form2js](https://github.com/maxatwork/form2js) — Max's own library — parses browser forms into structured JS objects with adapters for React, jQuery, and more
- [normy](https://github.com/klis87/normy) — Automatic normalization and cache updates for react-query, SWR, RTK-query and others — keep your data consistent
- [nx-extensions](https://github.com/nxext/nx-extensions) — ⚠️ STALE — Nx extensions for Stencil, Svelte, SolidJS, Preact, Ionic, and Capacitor — expands the monorepo toolkit
- [devtools](https://github.com/crabnebula-dev/devtools) — Inspect and debug Tauri apps in style — like browser DevTools but for your desktop app
- [neos-ui](https://github.com/neos/neos-ui) — Neos CMS UI built in React with Immutable.js — a well-architected headless CMS frontend
- [workflow-kit](https://github.com/inngest/workflow-kit) — Zapier-like workflow UI you can embed in your product — define actions in your backend, users wire them visually
- [react-calendar](https://github.com/zackify/react-calendar) — ⚠️ STALE — Simple, flexible events calendar component for React — clean and straightforward
- [react-resizable-layout](https://github.com/RyoSogawa/react-resizable-layout) — ⚠️ STALE — Headless React component and hook for resizable layouts — minimal, composable, no styling opinions
- [ChatUI](https://github.com/alibaba/ChatUI) — ⚠️ STALE — React component library purpose-built for conversational UI — clean design language from Alibaba
- [react-theme-provider](https://github.com/callstack/react-theme-provider) — ⚠️ STALE — Set of utilities for building React theming systems — create consistent theming in a few steps
- [react-event-calendar](https://github.com/dptoot/react-event-calendar) — ⚠️ STALE — React calendar component for displaying events — simple, clean, focused on event display

### Next.js

- [ui](https://github.com/shadcn-ui/ui) — Beautiful, copy-paste React components built on Radix — the component distribution model that took over the ecosystem
- [jsoncrack.com](https://github.com/AykutSarac/jsoncrack.com) — Turns JSON, YAML, XML, CSV, and TOML into interactive visual graphs — invaluable for understanding complex data
- [dokploy](https://github.com/Dokploy/dokploy) — Open-source Vercel/Netlify/Heroku alternative — self-host your deployments with Docker, real DX
- [nx](https://github.com/nrwl/nx) — Monorepo platform that speeds up builds and CI with smart caching — essential for large TypeScript codebases
- [postiz-app](https://github.com/gitroomhq/postiz-app) — Social media scheduling tool with AI assistance — open-source alternative to Buffer or Hootsuite
- [midday](https://github.com/midday-ai/midday) — Financial OS for freelancers — invoicing, time tracking, file reconciliation, and an AI assistant
- [examples](https://github.com/vercel/examples) — Vercel's official example collection — reference implementations for almost every Next.js pattern
- [arcjet-js](https://github.com/arcjet/arcjet-js) — JavaScript SDK for protecting AI budgets, blocking bots, and preventing data leaks at the edge
- [turborepo-example](https://github.com/owieth/turborepo-example) — Modern monorepo template with Next.js 16, React 19, Tailwind v4, shadcn/ui, and Turborepo — current best practices

### Svelte

- [svelte](https://github.com/sveltejs/svelte) — The compiler-first web framework — no virtual DOM, ships less JS, developer experience that spoils you
- [shadcn-svelte](https://github.com/huntabyte/shadcn-svelte) — shadcn/ui but for Svelte — same copy-paste philosophy, same quality, native Svelte
- [svelte-material-ui](https://github.com/hperrin/svelte-material-ui) — Full Material Design component library for Svelte — comprehensive and production-ready
- [bits-ui](https://github.com/huntabyte/bits-ui) — Headless Svelte components — the unstyled primitives for building your own design system
- [Svelvet](https://github.com/open-source-labs/Svelvet) — ⚠️ STALE — Svelte library for node-based UIs and flowcharts — the React Flow equivalent for the Svelte world
- [sveltekit-superforms](https://github.com/ciscoheat/sveltekit-superforms) — Makes SvelteKit form handling actually pleasant — validation, errors, progressive enhancement, all of it
- [svelte-headlessui](https://github.com/rgossiaux/svelte-headlessui) — ⚠️ STALE — Unofficial Svelte port of Headless UI — accessible component primitives for Svelte without the React baggage
- [runed](https://github.com/svecosystem/runed) — Magical utility runes for Svelte 5 — reactive helpers that feel like they should be built-in
- [layercake](https://github.com/mhkeller/layercake) — Graphics framework for Svelte — composable, reusable chart components at a lower abstraction level
- [haptic](https://github.com/chroxify/haptic) — ⚠️ STALE — Local-first, privacy-focused Markdown notes app — clean, self-contained, no sync to the cloud
- [svelte-devtools](https://github.com/sveltejs/svelte-devtools) — ⚠️ STALE — Browser devtools extension for inspecting Svelte component trees — essential when debugging Svelte apps
- [svelteui](https://github.com/svelteuidev/svelteui) — ⚠️ STALE — Svelte port of Mantine UI — comprehensive component library with good TypeScript support
- [layerchart](https://github.com/techniq/layerchart) — Composable Svelte chart components built on LayerCake — wide chart variety, beautiful output
- [svelte-ux](https://github.com/techniq/svelte-ux) — Collection of Svelte components and utilities for highly interactive applications — solid companion to layerchart
- [awesome-svelte-resources](https://github.com/ryanatkn/awesome-svelte-resources) — 🪦 ARCHIVED — Curated Svelte resources list — deprecated but historically useful, now points to sveltesociety.dev
- [tela](https://github.com/deta/tela) — ⚠️ STALE — Declarative infinite canvas library for Svelte using native DOM elements — interesting approach, no canvas API

### Vue

- [marktext](https://github.com/marktext/marktext) — Simple, elegant cross-platform Markdown editor — clean UI, distraction-free writing, built with Vue

### JS Libraries & Utilities

- [opencode](https://github.com/anomalyco/opencode) — Open-source AI coding agent for the terminal — the community alternative to Claude Code
- [node](https://github.com/nodejs/node) — Node.js itself — the V8-based JavaScript runtime that made server-side JS real
- [axios](https://github.com/axios/axios) — The HTTP client every JavaScript developer reaches for first — promise-based, works in browser and Node
- [reveal.js](https://github.com/hakimel/reveal.js) — The HTML presentation framework — build slides with web tech, embed code, animate anything
- [cline](https://github.com/cline/cline) — Autonomous AI coding agent inside VS Code — creates files, runs commands, browses the web
- [pdf.js](https://github.com/mozilla/pdf.js) — Mozilla's JavaScript PDF renderer — the engine behind every browser's built-in PDF viewer
- [moment](https://github.com/moment/moment) — ⚠️ STALE — The original JavaScript date library — enormous ecosystem, now in maintenance mode but still everywhere
- [prisma](https://github.com/prisma/prisma) — Next-generation ORM for Node.js — type-safe database queries with a migrations system that actually works
- [react-use](https://github.com/streamich/react-use) — The massive collection of React hooks — 100+ hooks for sensors, UI, animations, and browser APIs
- [bruno](https://github.com/usebruno/bruno) — Open-source API client — lightweight Postman/Insomnia alternative with Git-friendly local storage
- [zod](https://github.com/colinhacks/zod) — TypeScript-first schema validation — parse and validate anything with full type inference at the other end
- [web-check](https://github.com/Lissy93/web-check) — All-in-one OSINT tool for analyzing any website — DNS, headers, tech stack, security, and more
- [async](https://github.com/caolan/async) — The async control flow library Node.js developers used before promises existed — still solid for callbacks
- [eslint](https://github.com/eslint/eslint) — Find and fix JavaScript problems statically — the pluggable linter that underpins every JS project's code quality
- [Modernizr](https://github.com/Modernizr/Modernizr) — Detects HTML5 and CSS3 feature support in browsers — the compatibility shim era in a library
- [simple-icons](https://github.com/simple-icons/simple-icons) — SVG icons for 3000+ popular brands — the definitive source for brand logos in web projects
- [open-lovable](https://github.com/firecrawl/open-lovable) — ⚠️ STALE — Clones and recreates any website as a modern React app — AI-powered reverse engineering of UIs
- [node-red](https://github.com/node-red/node-red) — Low-code event-driven programming for Node.js — visual wiring for hardware, APIs, and services
- [sails](https://github.com/balderdashy/sails) — Realtime MVC framework for Node.js — the Express-based framework with Rails-like conventions
- [agents.md](https://github.com/agentsmd/agents.md) — Simple open format for guiding coding agents via AGENTS.md files — the CLAUDE.md alternative
- [rrweb](https://github.com/rrweb-io/rrweb) — Record and replay any web session — captures DOM mutations for debugging, analytics, or testing
- [pouchdb](https://github.com/apache/pouchdb) — Browser-embedded database that syncs with CouchDB — offline-first data with built-in replication
- [NemoClaw](https://github.com/NVIDIA/NemoClaw) — Run OpenClaw more securely inside NVIDIA OpenShell with managed inference — NVIDIA's hardened agent runtime
- [hydra](https://github.com/hydralauncher/hydra) — Open-source gaming platform and launcher — one tool for your entire game library
- [NodeBB](https://github.com/NodeBB/NodeBB) — Modern Node.js forum software — real-time, plugin-rich, a solid self-hosted community platform
- [youmightnotneedjquery](https://github.com/HubSpot/youmightnotneedjquery) — ⚠️ STALE — Classic reference showing vanilla JS equivalents for jQuery patterns — changed how many people thought about dependencies
- [clients](https://github.com/bitwarden/clients) — Bitwarden client apps — web, browser extension, desktop, and CLI for the open-source password manager
- [gutenberg](https://github.com/WordPress/gutenberg) — The block editor at the heart of WordPress — a full-featured React content editing system
- [es-toolkit](https://github.com/toss/es-toolkit) — Modern utility library replacing lodash — 2-3x faster, 97% smaller, tree-shakable, fully typed
- [knip](https://github.com/webpro-nl/knip) — Finds unused files, exports, and dependencies in JS/TS projects — like a dead code linter for your whole codebase
- [vanilla-extract](https://github.com/vanilla-extract-css/vanilla-extract) — Zero-runtime CSS-in-TypeScript — write styles in TS, get type-safe class names, no runtime cost
- [webtorrent-desktop](https://github.com/webtorrent/webtorrent-desktop) — Streaming torrent client for Mac, Windows, and Linux — play media before it finishes downloading
- [opentui](https://github.com/anomalyco/opentui) — Library for building terminal UIs in JavaScript — TUIs without leaving the JS ecosystem
- [tracking.js](https://github.com/eduardolundgren/tracking.js) — ⚠️ STALE — Computer vision in the browser — color tracking, face detection, and more via JavaScript
- [jsdiff](https://github.com/kpdecker/jsdiff) — JavaScript text diff implementation — computes textual differences between strings, the building block for diff viewers
- [react-big-calendar](https://github.com/jquense/react-big-calendar) — ⚠️ STALE — Google Calendar-style event calendar for React — flexible, well-maintained, handles complex scheduling UIs
- [seajs](https://github.com/seajs/seajs) — ⚠️ STALE — Module loader for the web from the CommonJS era — precursor to the modern module system, historically interesting
- [modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) — The official MCP specification and docs — the open standard connecting AI models to tools and data sources
- [umd](https://github.com/umdjs/umd) — ⚠️ STALE — Universal Module Definition patterns — the compatibility wrapper that made JS modules work everywhere before ES modules
- [metrics-graphics](https://github.com/metricsgraphics/metrics-graphics) — ⚠️ STALE — D3-based library for clean, principled data graphics — opinionated simplicity for time-series and scatter plots
- [sjcl](https://github.com/bitwiseshiftleft/sjcl) — Stanford JavaScript Crypto Library — serious cryptographic primitives for the browser, now deprecated
- [log.js](https://github.com/tj/log.js) — ⚠️ STALE — Super light-weight Node.js logging with streaming log reader — TJ minimalism applied to logging
- [jquery-aim](https://github.com/cihadturhan/jquery-aim) — ⚠️ STALE — jQuery plugin that predicts which element the user's cursor is heading toward — smart hover optimization
- [typograf](https://github.com/typograf/typograf) — JavaScript typography tool for Russian text — correct punctuation, quotes, and whitespace automatically
- [trycatch](https://github.com/CrabDude/trycatch) — ⚠️ STALE — Async domain-based exception handler with long stack traces for Node.js — caught errors with useful context
- [jog](https://github.com/tj/jog) — ⚠️ STALE — JSON document logging and filtering for Node.js — structured logging with querying capabilities
- [Pilot](https://github.com/RubaXa/Pilot) — ⚠️ STALE — Multifunction JavaScript router — a pre-React Router era routing library with interesting design
- [linq-in-javascript](https://github.com/aaronpowell/linq-in-javascript) — ⚠️ STALE — LINQ implementation in JavaScript with ES6 iterators — proper lazy evaluation for query-style operations
- [bem-mvc](https://github.com/bem/bem-mvc) — ⚠️ STALE — Yet another MVC for i-bem — an experiment in applying MVC patterns to BEM methodology
- [jquery.deserialize](https://github.com/maxatwork/jquery.deserialize) — ⚠️ STALE — Max's jQuery plugin for populating form fields from a URL-encoded string — the inverse of serialize()
- [superoverload](https://github.com/verkholantsev/superoverload) — ⚠️ STALE — Function overloading for JavaScript — dispatch to different implementations based on argument types
- [jsLibs](https://github.com/maxatwork/jsLibs) — Max's personal JavaScript libraries collection — an early personal open-source archive
- [nanostores](https://github.com/nanostores/nanostores) — 286-byte state manager for React, Vue, Svelte — atomic stores that're actually tiny
- [casperjs](https://github.com/casperjs/casperjs) — 🪦 ARCHIVED — PhantomJS-based browser automation and testing — fully archived, the predecessor to headless Chrome automation
- [mapcn](https://github.com/AnmolSaini16/mapcn) — Beautiful, zero-config React map components — one command to get interactive maps on your page
- [fuck-u-code](https://github.com/Done-0/fuck-u-code) — Detects and scores the "legacy-mess level" of your codebase — outputs a delightfully harsh report
- [openauth](https://github.com/anomalyco/openauth) — ⚠️ STALE — Universal, standards-based auth provider — self-hostable OAuth/OIDC server for any stack
- [automerge](https://github.com/automerge/automerge) — CRDT-based JSON-like data structure for concurrent editing — the data layer for offline-first collaborative apps
- [lazy.js](https://github.com/dtao/lazy.js) — ⚠️ STALE — Lazy evaluation for JavaScript sequences — like Underscore but deferred, avoids creating intermediate arrays
- [gantt](https://github.com/frappe/gantt) — Open-source JavaScript Gantt chart library — interactive, draggable, straightforward to use
- [cli](https://github.com/snyk/cli) — Snyk CLI for scanning projects for security vulnerabilities — find and fix dependency issues in CI
- [chrono](https://github.com/wanasit/chrono) — Natural language date parser in JavaScript — understands "next Tuesday", "yesterday", "in 3 hours"
- [derby](https://github.com/derbyjs/derby) — ⚠️ STALE — Realtime MVC framework that runs in both Node.js and browsers — prescient approach, ahead of its time
- [move.js](https://github.com/visionmedia/move.js) — ⚠️ STALE — CSS3-backed JavaScript animation framework — clean API for physics-free declarative animations
- [cherry-markdown](https://github.com/Tencent/cherry-markdown) — Tencent's Markdown editor with a dual-pane view, flow charts, and formulas — feature-rich and i18n-ready
- [drawio](https://github.com/jgraph/drawio) — Client-side JavaScript diagramming editor — the open-source engine behind diagrams.net
- [mirotalk](https://github.com/miroslavpejic85/mirotalk) — P2P WebRTC video conferencing up to 8K 60fps — self-hosted, browser-compatible, no infra required
- [codebuff](https://github.com/CodebuffAI/codebuff) — Terminal-based AI code generation — generate from the command line, stay in your workflow
- [fuckitjs](https://github.com/mattdiamond/fuckitjs) — ⚠️ STALE — The JavaScript error steamroller — swallows all errors and moves on, a joke that's also occasionally useful
- [trendFinder](https://github.com/ericciarla/trendFinder) — ⚠️ STALE — Monitors social media and the web for trending topics with AI-powered synthesis — automated trend radar
- [Unreal.js](https://github.com/ncsoft/Unreal.js) — ⚠️ STALE — Full JavaScript runtime embedded in Unreal Engine — script your game logic in JS
- [echo](https://github.com/toddmotto/echo) — Lazy image loading using data-* attributes — the simple pre-Intersection Observer approach
- [rrule](https://github.com/jkbrzt/rrule) — ⚠️ STALE — JavaScript iCalendar recurrence rule parser — handles all the hairy edge cases of recurring calendar events
- [pretext](https://github.com/chenglou/pretext) — Experimental TypeScript-first text processing framework from the React core team — watch this space
- [rainbow](https://github.com/ccampbell/rainbow) — ⚠️ STALE — Lightweight syntax highlighting library in JavaScript — small, language-plugin-based, no dependencies
- [rivets](https://github.com/mikeric/rivets) — Lightweight data-binding library — declarative two-way binding for vanilla JS before the frameworks took over
- [i18n-node](https://github.com/mashpie/i18n-node) — Lightweight i18n module for Node.js and Express — JSON-backed translations with simple __ syntax
- [connect-redis](https://github.com/tj/connect-redis) — ⚠️ STALE — Redis session store for Connect/Express — the standard way to persist sessions in Node.js apps
- [batarang](https://github.com/angular/batarang) — 🪦 ARCHIVED — AngularJS Chrome DevTools extension — the original AngularJS debugger, now archived and historical
- [redux-router](https://github.com/acdlite/redux-router) — ⚠️ STALE — Redux bindings for React Router — an early attempt at keeping router state in Redux, now archived
- [svelte-dnd-action](https://github.com/isaacHagoel/svelte-dnd-action) — Action-based drag-and-drop container for Svelte — clean Svelte-native approach to DnD
- [letta-code](https://github.com/letta-ai/letta-code) — Memory-first coding agent from the MemGPT team — persistent context that survives across sessions
- [routify](https://github.com/roxiness/routify) — Filesystem-based routing for Svelte — automatic routes from your file structure
- [Sirius](https://github.com/SiriusScan/Sirius) — Vulnerability scanning platform — an open-source security scanner for modern environments
- [hero](https://github.com/ulixee/hero) — Web browser built specifically for scraping — evades bot detection while keeping a clean API
- [cradle](https://github.com/flatiron/cradle) — ⚠️ STALE — High-level CouchDB client for Node.js — the old-school way to talk to CouchDB from the server
- [steal](https://github.com/stealjs/steal) — ⚠️ STALE — JavaScript module loader and builder — pre-webpack bundling for the browser
- [sherif](https://github.com/QuiiBz/sherif) — Opinionated zero-config linter for TypeScript monorepos — catches common monorepo package inconsistencies
- [nano](https://github.com/apache/nano) — 🪦 ARCHIVED — Minimal CouchDB client for Node.js — the official thin wrapper, now living inside the CouchDB repo

### Animation & Canvas

- [excalidraw](https://github.com/excalidraw/excalidraw) — Virtual whiteboard with a hand-drawn aesthetic — the best diagramming tool for thinking out loud
- [three.js](https://github.com/mrdoob/three.js) — The JavaScript 3D library — the foundation layer for almost all 3D on the web
- [anime](https://github.com/juliangarnier/anime) — JavaScript animation engine with a beautiful API — handles CSS, SVG, DOM, and JS values
- [algorithm-visualizer](https://github.com/algorithm-visualizer/algorithm-visualizer) — ⚠️ STALE — Interactive platform that visualizes algorithms running in real time — great for learning and teaching
- [html2canvas](https://github.com/niklasvh/html2canvas) — ⚠️ STALE — Takes screenshots of web pages with JavaScript — imperfect but impressively capable without a headless browser
- [rough](https://github.com/rough-stuff/rough) — ⚠️ STALE — Draws graphics with a hand-sketched appearance — great for diagrams that look human instead of computer-perfect
- [noVNC](https://github.com/novnc/noVNC) — VNC client that runs entirely in the browser — remote desktop access with zero client installation
- [drawnix](https://github.com/plait-board/drawnix) — Open-source all-in-one whiteboard — mind maps, flowcharts, and freehand drawing in one tool
- [wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) — Waveform audio player and visualizer — beautiful, interactive, and customizable
- [two.js](https://github.com/jonobr1/two.js) — Renderer-agnostic 2D drawing API — write once, output to SVG, Canvas, or WebGL
- [magic](https://github.com/miniMAC/magic) — ⚠️ STALE — CSS3 animations with special effects — pure CSS magic tricks for attention-grabbing UI moments
- [jquery.scrollTo](https://github.com/flesler/jquery.scrollTo) — ⚠️ STALE — Lightweight cross-browser animated scrolling with jQuery — the classic pre-scroll-behavior solution
- [atrament](https://github.com/jakubfiala/atrament) — Small JS library for beautiful drawing and handwriting on HTML Canvas — smooth pressure-sensitive feel

### UI Components & Styling

- [tailwindcss](https://github.com/tailwindlabs/tailwindcss) — Utility-first CSS framework that replaced most custom CSS for a generation of developers — the dominant approach
- [tweakcn](https://github.com/jnsahaj/tweakcn) — Visual no-code theme editor for shadcn/ui — tweak colors, radius, and spacing without touching code
- [kartograph.js](https://github.com/kartograph/kartograph.js) — ⚠️ STALE — JavaScript renderer for SVG maps — unmaintained but produced beautiful cartographic outputs
- [css3-buttons](https://github.com/ubuwaits/css3-buttons) — 🪦 ARCHIVED — Collection of CSS3 button styles in Sass — an early Sass showcase, archived but charming
- [Rpg-Awesome](https://github.com/nagoshiashumari/Rpg-Awesome) — ⚠️ STALE — Fantasy-themed icon font and CSS toolkit — RPG iconography for game UIs and thematic web projects
- [bem-method](https://github.com/bem-site/bem-method) — The BEM methodology documentation — Block, Element, Modifier naming that tamed CSS at scale
- [MaskJS](https://github.com/atmajs/MaskJS) — ⚠️ STALE — Markup template and HMVC micro-framework — an interesting pre-component-model take on UI architecture

### Maps & Geo

- [Leaflet](https://github.com/Leaflet/Leaflet) — The lightweight, mobile-friendly interactive map library — simple, elegant, and works everywhere
- [maplibre-gl-js](https://github.com/maplibre/maplibre-gl-js) — Open-source fork of Mapbox GL JS — WebGL-powered vector tile maps without the license restrictions
- [BlenderGIS](https://github.com/domlysz/BlenderGIS) — ⚠️ STALE — Blender addon for importing geographic data — turns real-world GIS data into 3D scenes
- [delaunator-cpp](https://github.com/delfrrr/delaunator-cpp) — ⚠️ STALE — Very fast C++ Delaunay triangulation of 2D points — used in terrain generation and computational geometry

### Data Visualization & Charts

- [mermaid](https://github.com/mermaid-js/mermaid) — Diagrams from text in Markdown — flowcharts, sequence diagrams, and more from simple syntax
- [yagr](https://github.com/gravity-ui/yagr) — Time-series chart renderer from Yandex — fast, production-grade, handles dense metric data well

### Real-Time & Collaboration

- [yjs](https://github.com/yjs/yjs) — The CRDT library for real-time collaborative apps — peer-to-peer shared data types that merge without conflicts
- [teable](https://github.com/teableio/teable) — No-code Airtable alternative backed by Postgres — spreadsheet UI, relational power, no vendor lock-in
- [RealtimeSTT](https://github.com/KoljaB/RealtimeSTT) — Low-latency speech-to-text with voice activity detection and wake word support — the best local real-time STT
- [pushpin](https://github.com/automerge/pushpin) — ⚠️ STALE — Collaborative corkboard app — a real-world demo of Automerge CRDTs in a visual collaboration tool

### DOM & Browser APIs

- [history.js](https://github.com/browserstate/history.js) — ⚠️ STALE — Graceful HTML5 History/State API support for all browsers — the polyfill that made pushState viable
- [snapdom](https://github.com/zumerlab/snapdom) — Next-generation DOM capture engine — fast, modular DOM-to-image conversion
- [Xccessors](https://github.com/eligrey/Xccessors) — ⚠️ STALE — Cross-browser accessor shim implementing standard and legacy property definition methods — browser compatibility JS

### General Frontend

- [this-is-responsive](https://github.com/bradfrost/this-is-responsive) — ⚠️ STALE — Brad Frost's classic responsive web design pattern library — a historical landmark for mobile-first thinking
- [Bebas-Neue](https://github.com/dharmatype/Bebas-Neue) — ⚠️ STALE — Bebas Neue font — the bold, condensed typeface behind countless impactful web headlines
- [the-modal](https://github.com/samdark/the-modal) — ⚠️ STALE — Proper modal boxes — a focused, correct implementation of accessibility-conscious modal dialogs
- [cascadeframework](https://github.com/jslegers/cascadeframework) — ⚠️ STALE — CSS framework experiment from the early responsive era — historically interesting design choices
- [jsdicom](https://github.com/Infogosoft/jsdicom) — ⚠️ STALE — DICOM medical image library and viewer in JavaScript — view medical imaging data in the browser
- [reader](https://github.com/chitalka/reader) — ⚠️ STALE — Reader UI component — minimal, focused reading interface
- [fixer](https://github.com/maxatwork/fixer) — ⚠️ STALE — Max's sticky headers library — makes table headers and other elements stick while scrolling

---

## Mobile

### React Native & Expo

- [appwrite](https://github.com/appwrite/appwrite) — Complete self-hosted cloud infrastructure — auth, databases, storage, and functions for web, mobile, and AI
- [joplin](https://github.com/laurent22/joplin) — Privacy-focused note-taking app with sync — the open-source Evernote replacement that actually works
- [react-hook-form](https://github.com/react-hook-form/react-hook-form) — Performant, flexible React form library — minimal re-renders, native React Native support, great DX
- [karakeep](https://github.com/karakeep-app/karakeep) — Self-hostable bookmark everything app — AI-powered tagging, full-text search, works for links, notes, and images
- [rxdb](https://github.com/pubkey/rxdb) — Reactive offline-first database for JavaScript — real-time queries that work in browser, Node, and React Native
- [openreplay](https://github.com/openreplay/openreplay) — Self-hosted session replay and product analytics — watch exactly what users did, no third-party required
- [svgr](https://github.com/gregberge/svgr) — Transforms SVGs into React components — the tool behind every icon library's React package
- [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) — The definitive high-performance camera library for React Native — Frame Processors make it truly powerful
- [react-native-reanimated](https://github.com/software-mansion/react-native-reanimated) — Software Mansion's Reanimated — the 60fps animation library that makes React Native feel native
- [react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker) — Native media picker for React Native — camera, gallery, video with native UI on both platforms
- [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler) — Declarative gesture system for React Native — the right way to handle swipes, pinches, and complex touches
- [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker) — Image picker with cropping, compression, and multi-select — the Swiss Army knife for image handling in React Native
- [js-lingui](https://github.com/lingui/js-lingui) — Readable, automated, optimized i18n for JavaScript — 2kb runtime, works across React, React Native, and more
- [react-native-styling-cheat-sheet](https://github.com/vhpoet/react-native-styling-cheat-sheet) — ⚠️ STALE — All React Native styling properties on one page — the reference card you keep in a tab
- [iconoir](https://github.com/iconoir-icons/iconoir) — Open-source icon library with 1600+ icons — consistent style, React, React Native, Flutter, and Figma support
- [examples](https://github.com/expo/examples) — Official Expo example projects — reference implementations for every major Expo API and integration
- [react-native-app-intro](https://github.com/FuYaoDe/react-native-app-intro) — ⚠️ STALE — Parallax-effect welcome/onboarding screens for React Native — smooth first-run experience component
- [legend-list](https://github.com/LegendApp/legend-list) — High-performance list component for React Native — the FlatList replacement that doesn't stutter
- [react-native-animated-tabbar](https://github.com/gorhom/react-native-animated-tabbar) — ⚠️ STALE — 60fps animated tab bar for React Native with multiple animation presets — eye-catching navigation
- [react-native-hold-menu](https://github.com/enesozturk/react-native-hold-menu) — ⚠️ STALE — Hold-to-open context menu for React Native powered by Reanimated — the iOS long-press menu pattern
- [react-native-masonry](https://github.com/brh55/react-native-masonry) — ⚠️ STALE — Masonry layout for images in React Native — Pinterest-style grid with dynamic content support
- [react-native-executorch](https://github.com/software-mansion/react-native-executorch) — Run AI models on-device in React Native via ExecuTorch — declarative API for local ML inference
- [ai](https://github.com/callstackincubator/ai) — On-device LLM execution for React Native with Vercel AI SDK compatibility — LLMs in your pocket literally
- [react-native-animated-nav-tab-bar](https://github.com/torgeadelin/react-native-animated-nav-tab-bar) — ⚠️ STALE — Animated bottom tab bar with custom animation support — smooth, customizable navigation component
- [expo-monorepo-example](https://github.com/byCedric/expo-monorepo-example) — ⚠️ STALE — Fast pnpm monorepo template for cross-platform Expo and React Native apps — the reference monorepo setup
- [react-native-sticky-item](https://github.com/gorhom/react-native-sticky-item) — ⚠️ STALE — Interactive sticky item inspired by Facebook Stories — a complex, beautiful scroll interaction
- [react-native-context-menu-view](https://github.com/mpiannucci/react-native-context-menu-view) — Native context menus in React Native — uses the OS-level long-press menu, not a custom implementation
- [react-native-ui-datepicker](https://github.com/farhoudshapouran/react-native-ui-datepicker) — Customizable date picker for React Native — single, range, and multiple date selection with a clean UI
- [react-native-avoid-softinput](https://github.com/mateusz1913/react-native-avoid-softinput) — Native solution for keyboard-covering-input — handles the soft keyboard layout shift at the native level
- [react-native-material-dropdown](https://github.com/n4kz/react-native-material-dropdown) — ⚠️ STALE — Material Design dropdown for React Native — consistent behavior across iOS and Android
- [react-native-swipeable-list](https://github.com/esthor/react-native-swipeable-list) — Zero-dependency swipeable FlatList with quick actions and animations — Inbox-style list interactions
- [orbit](https://github.com/expo/orbit) — Menu bar app for one-click build launches and simulator management — essential Expo DX tool
- [react-native-image-modal](https://github.com/dev-yakuza/react-native-image-modal) — Simple image modal for React Native — tap to expand, pinch to zoom, dismiss by swiping
- [ui](https://github.com/ahmedbna/ui) — ⚠️ STALE — BNA UI component library for Expo and React Native — Expo-native components with good defaults
- [react-native-error-boundary](https://github.com/carloscuesta/react-native-error-boundary) — Simple React Native error boundary component — catch and display errors gracefully instead of crashing
- [react-native-magic-modal](https://github.com/GSTJ/react-native-magic-modal) — Imperative modal library for React Native — call a modal from anywhere without prop drilling
- [expo-local-first-template](https://github.com/expo-starter/expo-local-first-template) — ⚠️ STALE — Opinionated Expo starter with Bun, Tailwind, Drizzle, SQLite, and local-first architecture
- [react-native-confetti-cannon](https://github.com/VincentCATILLON/react-native-confetti-cannon) — ⚠️ STALE — Confetti explosion animation for React Native — because sometimes you need to celebrate
- [react-native-header](https://github.com/codeherence/react-native-header) — High-performance animated header for React Native — iOS large title collapse pattern done right
- [reanimated-color-picker](https://github.com/alabsi91/reanimated-color-picker) — Pure JavaScript color picker for React Native built on Reanimated — smooth, touch-friendly, no native code
- [react-native-chat-ui](https://github.com/flyerhq/react-native-chat-ui) — ⚠️ STALE — Community-driven chat UI for React Native — actively maintained, customizable, optional Firebase backend
- [react-native-portalize](https://github.com/jeremybarbet/react-native-portalize) — ⚠️ STALE — Renders anything on top of the rest of your React Native app — portals for modals, toasts, and overlays
- [react-native-screenshot-aware](https://github.com/huextrat/react-native-screenshot-aware) — Real-time screenshot detection for React Native — respond when the user screenshots your app
- [react-native-reorderable-list](https://github.com/omahili/react-native-reorderable-list) — Drag-to-reorder list for React Native powered by Reanimated — smooth, production-ready sortable lists
- [showtime-tab-view](https://github.com/showtime-xyz/showtime-tab-view) — ⚠️ STALE — TabView with collapsible header and custom refresh for React Native — Reanimated-powered smooth tabs
- [react-native-bidirectional-infinite-scroll](https://github.com/GetStream/react-native-bidirectional-infinite-scroll) — ⚠️ STALE — Bidirectional infinite scroll for React Native — scroll up and down into history from any position
- [react-native-paper-tabs](https://github.com/web-ridge/react-native-paper-tabs) — ⚠️ STALE — Smooth, cross-platform Material Design tabs for React Native Paper — consistent tab navigation
- [react-native-rate-app](https://github.com/huextrat/react-native-rate-app) — In-app review prompts for Android and iOS in React Native — native rating dialogs with one call
- [expo-video-player](https://github.com/ihmpavel/expo-video-player) — ⚠️ STALE — Customizable video player controls for Expo — configurable UI on top of Expo AV
- [atlas](https://github.com/expo/atlas) — ⚠️ STALE — Visualizes React Native bundles to understand and optimize app size — see exactly what's in your JS bundle
- [expo-dynamic-app-icon](https://github.com/outsung/expo-dynamic-app-icon) — ⚠️ STALE — Programmatically change the app icon in Expo — dynamic alternate icons with a simple API
- [expo-alternate-app-icons](https://github.com/pchalupa/expo-alternate-app-icons) — Functions for changing the app icon in Expo — simple alternate icon switching
- [stagger](https://github.com/animate-react-native/stagger) — ⚠️ STALE — Cross-platform stagger animation component for React Native — staggered entry animations made trivial
- [react-native-dynamically-selected-picker](https://github.com/sosog/react-native-dynamically-selected-picker) — React Native picker that updates selected items dynamically as you scroll — smooth selection UX
- [react-native-just-timeline](https://github.com/Syntax00/react-native-just-timeline) — ⚠️ STALE — Customizable RTL-supported timeline component for React Native — events, milestones, vertical history
- [react-native-btr](https://github.com/ThakurBallary/react-native-btr) — ⚠️ STALE — Collection of React Native UI components — assorted widgets and layouts for mobile apps
- [react-native-reanimated-image-viewer](https://github.com/andresribeiro/react-native-reanimated-image-viewer) — ⚠️ STALE — Image viewer for React Native with Reanimated gestures — pinch-to-zoom photo gallery viewer
- [react-native-chatty](https://github.com/MuhammedKpln/react-native-chatty) — 🪦 ARCHIVED — Full-featured high-performance chat UI for React Native — comprehensive messaging interface, now archived
- [progress-bar-android](https://github.com/react-native-progress-view/progress-bar-android) — ⚠️ STALE — ProgressBar component for React Native Android — the native Android progress indicator
- [react-native-gallery-preview](https://github.com/chrizuuu/react-native-gallery-preview) — ⚠️ STALE — Performant gallery preview with smooth gesture interactions and animations — photo gallery with flair
- [expo-ui-kit](https://github.com/react-ui-kit/expo-ui-kit) — ⚠️ STALE — Component-based React Native UI kit for Expo — a starter kit of themed UI components
- [create-turbo-with-expo](https://github.com/Marknjo/create-turbo-with-expo) — ⚠️ STALE — Turborepo monorepo starter with Expo, Next.js, Solito, and NestJS — ambitious full-stack mobile template
- [react-native-cards-swipe](https://github.com/tarasvakulka/react-native-cards-swipe) — ⚠️ STALE — Card stack swiper with Reanimated 2 — Tinder-style card swipe interactions for React Native
- [react-native-liquid-gauge](https://github.com/dimaportenko/react-native-liquid-gauge) — ⚠️ STALE — Liquid gauge UI component for React Native — animated fluid fill for showing progress in style
- [react-native-draw-overlay](https://github.com/vokhuyetOz/react-native-draw-overlay) — ⚠️ STALE — Draw over other apps on Android from React Native — a rare capability for specialized use cases
- [frames-react-native](https://github.com/checkout/frames-react-native) — Checkout.com payment frames for React Native — secure card input components for Checkout integration
- [react-native-stt](https://github.com/kihyunwon/react-native-stt) — ⚠️ STALE — Speech-to-text module for React Native — native STT on both iOS and Android
- [react-native-image-header-scroll-view](https://github.com/bamlab/react-native-image-header-scroll-view) — ⚠️ STALE — ScrollView where the image header shrinks into a navigation bar on scroll — the hero-image scroll pattern
- [react-native-menu](https://github.com/jaysoo/react-native-menu) — ⚠️ STALE — Flexible dropdown menu component for React Native — Android Spinner-like menus on both platforms
- [expo-widgets](https://github.com/mike-stewart-dev/expo-widgets) — ⚠️ STALE — Widget functionality for Expo apps — brings home screen widgets to React Native via Expo
- [expo-mdx](https://github.com/EvanBacon/expo-mdx) — Render MDX universally across Expo platforms — write once in MDX, render on web, iOS, and Android
- [react-native-ui](https://github.com/vishalpwr/react-native-ui) — ⚠️ STALE — Basic React Native UI components collection — a simple component starter
- [UpdatesAPIDemo](https://github.com/expo/UpdatesAPIDemo) — Demo app for the Expo useUpdates() API — reference for OTA update management in Expo apps
- [react-native-context-menu](https://github.com/brnho/react-native-context-menu) — ⚠️ STALE — Context menu component for React Native — long-press activated menu with action items

### iOS

- [material-design-icons](https://github.com/google/material-design-icons) — Material Design icons from Google — the definitive icon set, 2500+ symbols in multiple styles
- [readest](https://github.com/readest/readest) — Modern, feature-rich ebook reader with cross-platform support — polished reading experience, open-source
- [mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples) — MLX Swift examples for running ML models on Apple Silicon — the native iOS/macOS ML path
- [pngpaste](https://github.com/jcsalterego/pngpaste) — ⚠️ STALE — Paste clipboard images into files from the terminal — fills the gap pbpaste leaves with images
- [RNBoilerplate](https://github.com/rnystrom/RNBoilerplate) — ⚠️ STALE — iOS Xcode project boilerplate with curated frameworks and settings — an old but historically useful starting point

### Android

- [Mobile-Security-Framework-MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) — All-in-one automated mobile security testing for Android, iOS, and Windows apps — pen testing in a box

### Cross-Platform

- [tauri](https://github.com/tauri-apps/tauri) — Build smaller, faster, more secure desktop and mobile apps with a web frontend — the Electron killer

---

## Backend & Infrastructure

### Databases & ORM

- [searxng](https://github.com/searxng/searxng) — Free, self-hosted metasearch engine — aggregate results from 70+ search services without being tracked
- [platform](https://github.com/hcengineering/platform) — Huly — all-in-one project management platform covering Linear, Jira, Slack, and Notion in one open-source tool
- [nocobase](https://github.com/nocobase/nocobase) — Most extensible AI-powered no-code platform — build business applications with a plugin-based architecture
- [pglite](https://github.com/electric-sql/pglite) — Embeddable Postgres in your browser or app — real Postgres, in-process, with reactive bindings
- [chat](https://github.com/tinode/chat) — Full-stack instant messaging platform — Swift iOS, Java Android, and JS clients backed by Go
- [univer](https://github.com/dream-num/univer) — Full-stack framework for AI-native spreadsheets — build and edit spreadsheets on web and server
- [grist-core](https://github.com/gristlabs/grist-core) — Spreadsheet that thinks like a database — Python formulas, relational structure, self-hostable
- [postgres](https://github.com/porsager/postgres) — The fastest full-featured PostgreSQL client for Node.js, Deno, and Bun — tagged template literals, zero dependencies
- [better-sqlite3](https://github.com/WiseLibs/better-sqlite3) — The fastest, simplest SQLite3 library for Node.js — synchronous API that actually makes sense for SQLite
- [unqlite](https://github.com/symisc/unqlite) — ⚠️ STALE — Embedded NoSQL transactional database engine — key-value and document store in a single C library
- [usertour](https://github.com/usertour/usertour) — Open-source user onboarding platform — in-app product tours, checklists, and surveys
- [ladybug](https://github.com/LadybugDB/ladybug) — Graph database — LadybugDB brings graph data modeling with a lightweight embedded approach
- [bighorn](https://github.com/Kineviz/bighorn) — ⚠️ STALE — Embedded property graph database with vector search and Cypher — a graph DB that handles similarity search too
- [ydb-js-sdk](https://github.com/ydb-platform/ydb-js-sdk) — YDB JavaScript/TypeScript SDK — access Yandex's distributed NewSQL database from Node.js
- [kuzo_ios](https://github.com/johnbenac/kuzo_ios) — ⚠️ STALE — Kuzu graph database integration for iOS — run an embedded graph database natively on iPhone
- [cypher-query-builder](https://github.com/jamesfer/cypher-query-builder) — ⚠️ STALE — Flexible, intuitive Cypher query builder for Neo4j — write graph queries in JS instead of raw strings
- [nodejs-redis](https://github.com/simplegeo/nodejs-redis) — ⚠️ STALE — Early Redis client for Node.js — precursor to the modern ioredis/node-redis era

### General Backend

- [rclone](https://github.com/rclone/rclone) — rsync for cloud storage — sync files to and from 70+ storage providers from the command line
- [serverless](https://github.com/serverless/serverless) — Serverless Framework — build and deploy functions to AWS Lambda, Azure, GCP, and more with one CLI
- [copyparty](https://github.com/9001/copyparty) — Portable file server with resumable uploads, WebDAV, SFTP, media indexing — one file, everything
- [git-bug](https://github.com/git-bug/git-bug) — Distributed, offline-first bug tracker embedded in git — issues that live in your repository
- [tinypool](https://github.com/tinylibs/tinypool) — Minimal Node.js Worker Thread Pool — lightweight task parallelism without the overhead
- [OWS](https://github.com/Dartanlla/OWS) — Open World Server — networking infrastructure for building large-scale multiplayer game backends
- [grpc-ui](https://github.com/lazada/grpc-ui) — ⚠️ STALE — gRPC web interface — a Postman-style UI for testing gRPC endpoints
- [json-server](https://github.com/typicode/json-server) — Full fake REST API in under 30 seconds from a JSON file — the instant mock backend for prototyping
- [express-expose](https://github.com/expressjs/express-expose) — 🪦 ARCHIVED — Expose raw JS objects and functions from Express to the client side — now archived
- [express-configuration](https://github.com/tj/express-configuration) — ⚠️ STALE — Adds async configuration support to Express — configure your app asynchronously before routes run
- [jog-middleware](https://github.com/tj/jog-middleware) — ⚠️ STALE — JSON logger middleware for Connect/Express — structured request logging built on jog

### APIs & Protocols

- [waha](https://github.com/devlikeapro/waha) — WhatsApp HTTP API — REST API for WhatsApp with multiple engine options, configurable in one click
- [whatsapp-api](https://github.com/chrishubert/whatsapp-api) — 🪦 ARCHIVED — REST API wrapper for whatsapp-web.js — turn the unofficial WhatsApp client into a proper REST API
- [node-modbus-stack](https://github.com/TooTallNate/node-modbus-stack) — ⚠️ STALE — Modbus protocol StreamStack implementation for Node.js — industrial equipment communication in JS
- [upnpjs](https://github.com/swimauger/upnpjs) — ⚠️ STALE — Node.js package for using UPnP — discover and communicate with UPnP devices on the local network

### Auth & Security

- [better-auth](https://github.com/better-auth/better-auth) — The most comprehensive authentication framework for TypeScript — everything from OAuth to 2FA in one library
- [trufflehog](https://github.com/trufflesecurity/trufflehog) — Find, verify, and analyze leaked credentials in code and git history — catches what regular secrets scanners miss
- [passport](https://github.com/jaredhanson/passport) — ⚠️ STALE — Simple, unobtrusive authentication middleware for Node.js — 500+ strategies, the authentication standard
- [connect-bruteforce](https://github.com/revington/connect-bruteforce) — ⚠️ STALE — Connect middleware to prevent brute force attacks — rate limiting for login endpoints

### DevOps & Deployment

- [FossFLOW](https://github.com/stan-smith/FossFLOW) — Create beautiful isometric infrastructure diagrams — architecture visualization with a distinctive visual style
- [Compose-Examples](https://github.com/Haxxnet/Compose-Examples) — Extensive Docker Compose examples for self-hosted FOSS and proprietary projects — the reference collection
- [headlamp](https://github.com/kubernetes-sigs/headlamp) — Fully-featured, user-friendly, extensible Kubernetes web UI — the dashboard that Kubernetes itself should have shipped
- [airo](https://github.com/albersola/airo) — Deploy projects from local to production VPS — simplified deployment pipeline for small-scale hosting
- [express-cdn](https://github.com/ladjs/express-cdn) — 🪦 ARCHIVED — Express module for delivering optimized, gzipped assets via Amazon S3/CloudFront CDN

### Self-Hosted & Homelab

- [automatisch](https://github.com/automatisch/automatisch) — Open-source Zapier alternative — build workflow automations without the cost or vendor lock-in
- [BillionMail](https://github.com/Billionmail/BillionMail) — Self-hosted open-source mail server and newsletter platform — own your email marketing infrastructure
- [frigate](https://github.com/blakeblackshear/frigate) — Local NVR with real-time object detection for IP cameras — no cloud, no subscription, just your hardware

### Bots & Messaging

- [Baileys](https://github.com/WhiskeySockets/Baileys) — TypeScript/JavaScript socket-based API for WhatsApp Web — the most capable unofficial WhatsApp client library
- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) — The classic Node.js Telegram Bot API wrapper — simple, battle-tested, still widely used
- [whatsapp-web.js](https://github.com/wwebjs/whatsapp-web.js) — WhatsApp client library for Node.js via the web interface — the unofficial WhatsApp API

### Email & Messaging

- [useSend](https://github.com/usesend/useSend) — Open-source Resend/SendGrid/Postmark alternative — own your transactional email sending infrastructure

---

## Game Development

### Godot

- [godot](https://github.com/godotengine/godot) — The open-source game engine that's genuinely good — MIT licensed, batteries included, rapidly improving
- [dialogic](https://github.com/dialogic-godot/dialogic) — Dialogue system, visual novel tools, and character management for Godot — the go-to narrative plugin
- [material-maker](https://github.com/RodZill4/material-maker) — Procedural texture authoring and 3D model painting tool built on Godot — a Substance Designer alternative
- [Terrain3D](https://github.com/TokisanGames/Terrain3D) — High-performance editable terrain system for Godot 4 — the serious terrain solution for open-world games
- [godot_voxel](https://github.com/Zylann/godot_voxel) — Voxel terrain module for Godot — infinite blocky or smooth worlds à la Minecraft or No Man's Sky
- [phantom-camera](https://github.com/ramokz/phantom-camera) — Cinemachine-inspired camera addon for Godot 4 — cinematic camera control without the Unity dependency
- [scatter](https://github.com/HungryProton/scatter) — Godot addon for randomly filling areas with props and scenes — foliage, rocks, clutter placement
- [GodotOceanWaves](https://github.com/2Retr0/GodotOceanWaves) — ⚠️ STALE — FFT-based ocean wave rendering in Godot — stunning real-time water simulation with GPU compute
- [godot-jolt](https://github.com/godot-jolt/godot-jolt) — Jolt physics engine extension for Godot — the deterministic, high-performance physics alternative
- [protongraph](https://github.com/protongraph/protongraph) — ⚠️ STALE — Experimental node-based procedural content generation software — visual graph-driven world building
- [gaea](https://github.com/gaea-godot/gaea) — Procedural generation add-on for Godot 4 — wave function collapse, noise-based worlds, and more
- [cyclopsLevelBuilder](https://github.com/blackears/cyclopsLevelBuilder) — Block-out level design inside the Godot editor — CSG-style rapid level prototyping with Godot
- [godot-statecharts](https://github.com/derkork/godot-statecharts) — Hierarchical state charts extension for Godot 4 — clean game state management with visual inspection
- [godot_spatial_gardener](https://github.com/dreadpon/godot_spatial_gardener) — ⚠️ STALE — Plugin for painting plants and props on 3D surfaces in Godot — foliage painting with density control
- [godot-open-rts](https://github.com/lampe-games/godot-open-rts) — ⚠️ STALE — Open-source RTS game in Godot 4 — a playable reference implementation of RTS mechanics
- [godot_experiments](https://github.com/MrEliptik/godot_experiments) — ⚠️ STALE — 2D, 3D, and VR experiments and tutorials in Godot 3 & 4 — a goldmine of mini-demos and techniques
- [godot_debug_draw_3d](https://github.com/DmitriySalnikov/godot_debug_draw_3d) — Draw 3D debug graphics and 2D overlays in Godot — visualize physics, paths, and logic at runtime
- [godot-road-generator](https://github.com/TheDuckCow/godot-road-generator) — Plugin for creating 3D roads and lane-following traffic in Godot — drive simulation basics
- [Virtual-Joystick-Godot](https://github.com/MarcoFazioRandom/Virtual-Joystick-Godot) — ⚠️ STALE — Simple virtual joystick for touchscreens in Godot — 2D and 3D games, configurable, mobile-ready
- [Godot-MTerrain-plugin](https://github.com/mohsenph69/Godot-MTerrain-plugin) — ⚠️ STALE — GDExtension terrain plugin for Godot with highly optimized open-world rendering — massive terrain scales
- [Reia](https://github.com/Quaint-Studios/Reia) — Action-adventure RPG MMO being built with Godot and Rust — an ambitious open-source game project
- [anima](https://github.com/ceceppa/anima) — ⚠️ STALE — Sequential and parallel animations with less code in Godot — declarative animation chaining
- [godot-debug-menu](https://github.com/godot-extended-libraries/godot-debug-menu) — ⚠️ STALE — In-game FPS, performance, and hardware metrics display for Godot 4 — production-grade debug overlay
- [GodotGrass](https://github.com/2Retr0/GodotGrass) — ⚠️ STALE — Per-blade grass rendering in Godot inspired by Ghost of Tsushima — beautiful GPU-driven grass
- [godot4-oceanfft](https://github.com/tessarakkt/godot4-oceanfft) — ⚠️ STALE — Tessendorf FFT ocean waves with buoyancy in Godot 4 — compute shaders for realistic water physics
- [godot-game-settings](https://github.com/zijcht/godot-game-settings) — ⚠️ STALE — Plugin for creating and managing game settings in Godot — proper settings system with persistence
- [VPainter](https://github.com/tomankirilov/VPainter) — ⚠️ STALE — Vertex painting addon for Godot — paint colors and data directly onto 3D mesh vertices
- [SunshineClouds2](https://github.com/Bonkahe/SunshineClouds2) — Procedural volumetric cloud system for Godot 4.4+ — dynamic clouds with lighting and atmosphere
- [godot-deformablemesh](https://github.com/cloudofoz/godot-deformablemesh) — ⚠️ STALE — Deform 3D meshes with customizable deformers at runtime in Godot — procedural mesh animation
- [controller_icons](https://github.com/rsubtil/controller_icons) — Automatic keyboard, mouse, and controller icon remapper for Godot — multi-input UI icons that just work
- [godot-cpp-template](https://github.com/godotengine/godot-cpp-template) — Quickstart template for GDExtension development — the official starting point for Godot C++ plugins
- [Godot-Water-Shader-Prototype](https://github.com/Platinguin/Godot-Water-Shader-Prototype) — ⚠️ STALE — Water shader prototype for Godot — a starting point for stylized water with refraction and waves
- [godot-simplified-flightsim](https://github.com/fbcosentino/godot-simplified-flightsim) — ⚠️ STALE — Simplified flight simulation library for Godot — aerodynamics and control surfaces without the complexity
- [godot-dockable-container](https://github.com/gilzoide/godot-dockable-container) — Dockable and tiling UI panel container addon for Godot — IDE-style panel layout in your game
- [Godot-4-Concave-Mesh-Slicer](https://github.com/PiCode9560/Godot-4-Concave-Mesh-Slicer) — Mesh slicing addon for Godot 4 — cut meshes at runtime for destruction effects
- [quality-godot-first-person-2](https://github.com/ColormaticStudios/quality-godot-first-person-2) — A genuinely good first-person controller for Godot — more realistic than the default templates
- [Keychain](https://github.com/Orama-Interactive/Keychain) — Input action remapping plugin for Godot — give players full control over key bindings
- [Godot-Cloud-Worlds](https://github.com/Platinguin/Godot-Cloud-Worlds) — ⚠️ STALE — Cloudy sky and atmospheric world shaders for Godot — procedural clouds and sky rendering
- [godot-third-person-camera](https://github.com/JeanKouss/godot-third-person-camera) — ⚠️ STALE — Third-person camera for Godot — orbit and follow camera with collision avoidance
- [godot_aerodynamic_physics](https://github.com/addmix/godot_aerodynamic_physics) — Aerodynamic physics simulation for Godot — lift, drag, and thrust for flight simulation
- [GoldGdt](https://github.com/ratmarrow/GoldGdt) — 🪦 ARCHIVED — GoldSrc-style character controller for Godot — Half-Life movement physics recreated in Godot, archived
- [QuestManager](https://github.com/Chevifier/QuestManager) — ⚠️ STALE — Quest manager plugin for Godot 4 — create, track, and manage quests with a clean system
- [godot-animation-player-refactor](https://github.com/poohcom1/godot-animation-player-refactor) — AnimationPlayer refactoring addon for Godot — safely rename and reorganize animation tracks
- [godot-yat](https://github.com/MASSHUU12/godot-yat) — ⚠️ STALE — Customizable in-game terminal/console for Godot (C#) — debug commands and runtime scripting
- [SunshineClouds](https://github.com/Bonkahe/SunshineClouds) — ⚠️ STALE — Earlier procedural cloud system for Godot 4.1 — volumetric clouds with daylight cycling
- [godot-input-buffer](https://github.com/drkitt/godot-input-buffer) — ⚠️ STALE — Input buffering for Godot — makes character controls feel more responsive with input queueing
- [GodotOceanWaves](https://github.com/krautdev/GodotOceanWaves) — ⚠️ STALE — Alternative FFT ocean wave implementation for Godot — different take on the same beautiful water effect
- [godot_flight_navigation_3d](https://github.com/RevolNoom/godot_flight_navigation_3d) — Flight navigation in free 3D space for Godot 4 — pathfinding for flying enemies and aircraft
- [ballistic-solutions](https://github.com/neclor/ballistic-solutions) — Library for calculating interception times, impact positions, and firing vectors — ballistics for projectile prediction
- [godot-input-buffer](https://github.com/johnnyneverwalked/godot-input-buffer) — ⚠️ STALE — Input buffer plugin for Godot — another take on buffered input for snappier game feel
- [godot-volumetric-clouds](https://github.com/kb173/godot-volumetric-clouds) — ⚠️ STALE — Volumetric clouds shader for older Godot versions — a classic volumetric cloud implementation
- [godot-flex-container](https://github.com/Nif-ty/godot-flex-container) — ⚠️ STALE — CSS-flexbox-style adjustable container for Godot — layout flexibility closer to web standards
- [shinobu](https://github.com/EIRTeam/shinobu) — EIRTeam's Godot fork powering their games — extended Godot with proprietary performance enhancements
- [godot-aircraft-plugin](https://github.com/wmigor/godot-aircraft-plugin) — Godot plugin for aerodynamic simulation — fixed-wing aircraft physics with configurable surfaces
- [Godot3DFlightControls](https://github.com/UtMan88/Godot3DFlightControls) — ⚠️ STALE — Template for creating 3D flight controls in Godot — a starting point for arcade flight games
- [Godot-4x.NET-Color-Palettes](https://github.com/hamsterbyte/Godot-4x.NET-Color-Palettes) — ⚠️ STALE — Color palette support added to Godot's built-in color picker — palette management for art-heavy projects
- [godot-SimpleNet](https://github.com/kvbc/godot-SimpleNet) — ⚠️ STALE — Godot 4 addon making multiplayer networking easier — simplified API over Godot's built-in ENet

### General Game Dev

- [Playnite](https://github.com/JosefNemec/Playnite) — Open-source video game library manager — unifies Steam, GOG, Epic, and emulators in one launcher
- [entt](https://github.com/skypjack/entt) — Fast, reliable entity component system for C++ — the ECS used in many serious game projects
- [flecs](https://github.com/SanderMertens/flecs) — High-performance ECS for C and C++ — the most feature-complete open-source ECS with a query language
- [stride](https://github.com/stride3d/stride) — Stride (formerly Xenko) — free cross-platform C# game engine with a full editor and rendering pipeline
- [blockbench](https://github.com/JannisX11/blockbench) — Low-poly 3D model editor perfect for voxel-style games — the definitive Minecraft model creator
- [kaiju](https://github.com/KaijuEngine/kaiju) — General-purpose 3D/2D game engine in Go with Vulkan and a built-in editor — an interesting tech choice
- [Geographical-Adventures](https://github.com/SebLague/Geographical-Adventures) — ⚠️ STALE — Sebastian Lague's geography game — beautifully made, open-source, globe-spanning educational experience
- [SpartanEngine](https://github.com/PanosK92/SpartanEngine) — Fully bindless, GPU-driven game engine with real-time path-traced GI and hardware ray tracing
- [bepuphysics2](https://github.com/bepu/bepuphysics2) — Pure C# 3D real-time physics simulation — high performance, no unsafe code, used in .NET game projects
- [NodeGraphProcessor](https://github.com/alelievr/NodeGraphProcessor) — ⚠️ STALE — Node graph editor framework for Unity UIElements — data-processing visual scripting foundation
- [ecs-faq](https://github.com/SanderMertens/ecs-faq) — ⚠️ STALE — The authoritative ECS FAQ — everything you wanted to know about Entity Component Systems
- [ALS-Community](https://github.com/ShadowfallStudios/ALS-Community) — ⚠️ STALE — Community version of Advanced Locomotion System V4 for Unreal Engine 5 — replicated, optimized, extended
- [FlowGraph](https://github.com/MothCocoon/FlowGraph) — Design-agnostic node system for scripting game flow in Unreal — visual narrative and logic scripting
- [MouseFlight](https://github.com/brihernandez/MouseFlight) — ⚠️ STALE — War Thunder-style mouse flight controls for Unity — aircraft that follow the cursor naturally
- [Aircraft-Physics](https://github.com/gasgiant/Aircraft-Physics) — ⚠️ STALE — Fixed-wing aircraft physics for Unity — lift, drag, and engine simulation for flight games
- [ImpostorBaker](https://github.com/ictusbrucks/ImpostorBaker) — ⚠️ STALE — UE4 plugin for generating impostors of static meshes — fake LODs that look real at a distance
- [Unreal-Polygonal-Map-Gen](https://github.com/Jay2645/Unreal-Polygonal-Map-Gen) — ⚠️ STALE — Polygonal map generation for Unreal Engine 4 — islands and continents from Voronoi diagrams
- [Greebler](https://github.com/alexismorin/Greebler) — ⚠️ STALE — UE4 and Unity plugin for auto-filling nooks with rubble and detail props — greebling made easy
- [Advanced-Camera-Manager](https://github.com/oivio/Advanced-Camera-Manager) — 🪦 ARCHIVED — Advanced player camera component for Unreal Engine — cinematic control with spring arm intelligence
- [Voxel](https://github.com/Phyronnaz/Voxel) — ⚠️ STALE — Voxel world plugin for UE4 — terrain and world generation in the pre-VoxelPlugin era
- [space-ship-panel-set](https://github.com/adamskee/space-ship-panel-set) — ⚠️ STALE — Low-poly spaceship panel meshes for UE4 in FBX format — ready-to-use sci-fi greeble assets
- [HeartGraph](https://github.com/Drakynfly/HeartGraph) — ⚠️ STALE — Generic runtime node graph editor and viewer for Unreal Engine — visual scripting infrastructure

### Procedural Generation

- [Graphite](https://github.com/GraphiteEditor/Graphite) — Open-source 2D content creation suite with procedural design and interactive real-time motion — ambitious and unique
- [PixiEditor](https://github.com/PixiEditor/PixiEditor) — Universal 2D pixel art and image editor — fast, free, with animation and layer support
- [Fantasy-Map-Generator](https://github.com/Azgaar/Fantasy-Map-Generator) — Web app generating interactive, highly customizable fantasy maps — the definitive browser-based worldbuilding tool
- [TownGeneratorOS](https://github.com/watabou/TownGeneratorOS) — ⚠️ STALE — Source code for the Medieval Fantasy City Generator — the web app that created countless game towns
- [FantasyMapGenerator](https://github.com/rlguy/FantasyMapGenerator) — ⚠️ STALE — Fantasy map generator based on Martin O'Leary's river and coast algorithm — realistic-looking fictional worlds
- [PCGExtendedToolkit](https://github.com/PCGEx/PCGExtendedToolkit) — The missing pieces for Unreal's PCG system — graph theory, pathfinding, spatial ops, and asset management
- [worldgen](https://github.com/baturinsky/worldgen) — ⚠️ STALE — Fast, fairly realistic terrain generator in JavaScript — useful for procedural world building in the browser
- [fractal_cell_noise](https://github.com/lorenSchmidt/fractal_cell_noise) — ⚠️ STALE — Fractal noise algorithm related to Worley/cellular noise — useful for procedural textures and terrain

### Graphics & Shaders

- [webgl-noise](https://github.com/ashima/webgl-noise) — ⚠️ STALE — Procedural noise shader routines for WebGL — Simplex, Perlin, and cellular noise in GLSL
- [ShaderTutorials](https://github.com/Xibanya/ShaderTutorials) — ⚠️ STALE — Shader tutorials for people who don't know how to shader — accessible HLSL teaching material for Unity
- [Water](https://github.com/GarrettGunnell/Water) — ⚠️ STALE — Sum-of-sines and FFT fluid simulation with a physically-based water shader for Unity — stunning results
- [DFoundryFX](https://github.com/DarknessFX/DFoundryFX) — ⚠️ STALE — Unreal Engine plugin with Dear ImGUI, performance charts, and shader analytics — including Shipping builds

### Cloud & Streaming Gaming

- [nestri](https://github.com/nestrilabs/nestri) — Experimental cloud game streaming — deploy and stream games and apps with your own or rented GPUs

---

## Developer Tools

### Editors & Plugins

- [AFFiNE](https://github.com/toeverything/AFFiNE) — Next-gen knowledge base merging Notion and Miro — planning, writing, and diagramming in one tool
- [monaco-editor](https://github.com/microsoft/monaco-editor) — The browser-based code editor powering VS Code — bring VS Code quality editing to any web app
- [LazyVim](https://github.com/LazyVim/LazyVim) — Neovim config for the lazy — opinionated, fast, batteries-included Neovim setup with sensible defaults
- [avante.nvim](https://github.com/yetone/avante.nvim) — Use Neovim like Cursor AI IDE — AI-assisted code changes with a sidebar diff workflow
- [snacks.nvim](https://github.com/folke/snacks.nvim) — QoL plugin collection for Neovim by the author of LazyVim — small improvements that add up fast
- [render-markdown.nvim](https://github.com/MeanderingProgrammer/render-markdown.nvim) — Renders Markdown in Neovim with real styling — headers, bold, code blocks, tables all look right
- [auto-session](https://github.com/rmagatti/auto-session) — Small automated session manager for Neovim — restores your workspace exactly as you left it
- [semver](https://github.com/jscutlery/semver) — Nx plugin for semantic versioning and CHANGELOG generation — automated releases in a monorepo
- [dotfiles](https://github.com/mokevnin/dotfiles) — A developer's public dotfiles with Vim focus — good reference for a Vim-centric terminal setup
- [DockToRight](https://github.com/mauricelam/DockToRight) — 🪦 ARCHIVED — Chrome DevTools theme for dock-to-right usage — optimized layout for the panel on the side
- [codex.nvim](https://github.com/johnseth97/codex.nvim) — ⚠️ STALE — OpenAI Codex integration for Neovim — AI completion right in your editor without leaving the terminal

### Python Tools

- [youtube-dl](https://github.com/ytdl-org/youtube-dl) — The original command-line video downloader for YouTube and hundreds of other sites
- [core](https://github.com/home-assistant/core) — Open-source home automation that keeps local control — the hub for smart home tinkerers who care about privacy
- [openpilot](https://github.com/commaai/openpilot) — Operating system for robotics — adds advanced driver assistance to 300+ supported car models
- [exo](https://github.com/exo-explore/exo) — Run frontier AI models across your own cluster of consumer devices — distributed inference on everyday hardware
- [tinygrad](https://github.com/tinygrad/tinygrad) — Tiny deep learning framework in Python — educational, fast, and used in real production systems
- [VibeVoice](https://github.com/microsoft/VibeVoice) — Microsoft's open-source frontier voice AI system — speech understanding and generation
- [flux](https://github.com/black-forest-labs/flux) — ⚠️ STALE — Official inference repo for FLUX.1 image generation models — the current state-of-the-art in open image gen
- [chatterbox](https://github.com/resemble-ai/chatterbox) — State-of-the-art open-source TTS from Resemble AI — ultra-realistic voice synthesis, free to run
- [Second-Me](https://github.com/mindverse/Second-Me) — ⚠️ STALE — Train an AI version of yourself — captures your writing and thinking style to act as a personal AI proxy
- [git-filter-repo](https://github.com/newren/git-filter-repo) — Fast git history rewriting — the modern replacement for filter-branch that doesn't make you wait forever
- [timesfm](https://github.com/google-research/timesfm) — Google's pre-trained time series foundation model — zero-shot forecasting on any temporal data
- [moshi](https://github.com/kyutai-labs/moshi) — Full-duplex spoken dialogue model — speech-to-speech conversation with no text intermediate step
- [samurai](https://github.com/yangchris11/samurai) — ⚠️ STALE — Zero-shot visual object tracking from the SAM2 lineage — tracks anything across video frames
- [VoxCPM](https://github.com/OpenBMB/VoxCPM) — Tokenizer-free TTS for context-aware speech with voice cloning — no tokenizer bottleneck, natural prosody
- [AI-Researcher](https://github.com/HKUDS/AI-Researcher) — ⚠️ STALE — Production-ready autonomous scientific research agent — generates and validates research hypotheses
- [Step-Audio](https://github.com/stepfun-ai/Step-Audio) — Step-Audio: multimodal audio understanding and generation from Stepfun AI
- [vidgear](https://github.com/abhiTronix/vidgear) — ⚠️ STALE — High-performance cross-platform video processing Python framework — wraps FFmpeg with a clean API
- [DeepResearchAgent](https://github.com/SkyworkAI/DeepResearchAgent) — Hierarchical multi-agent system for deep research and general task solving — multi-step planning and execution
- [CodeBERT](https://github.com/microsoft/CodeBERT) — ⚠️ STALE — Pre-trained bimodal model for code and natural language — the foundational code-understanding transformer
- [dia2](https://github.com/nari-labs/dia2) — ⚠️ STALE — Streaming TTS model for real-time conversational audio — lower latency successor to Dia
- [patma](https://github.com/gvanrossum/patma) — 🪦 ARCHIVED — Guido van Rossum's pattern matching prototype for Python — the research that became Python 3.10 match/case
- [always-on-ai-assistant](https://github.com/disler/always-on-ai-assistant) — ⚠️ STALE — Always-on AI assistant pattern with DeepSeek-V3 and RealtimeSTT — voice-first engineering companion
- [QRemeshify](https://github.com/ksami/QRemeshify) — ⚠️ STALE — Blender extension for easy quad-topology remeshing — good-quality quad output without manual retopology
- [terrain-erosion-3-ways](https://github.com/dandrino/terrain-erosion-3-ways) — ⚠️ STALE — Three implementations of terrain generation with erosion — hydraulic, thermal, and tectonic approaches
- [TheWhisper](https://github.com/TheStageAI/TheWhisper) — Optimized Whisper models for streaming and on-device use — faster, smaller, still accurate
- [bigcouch](https://github.com/cloudant/bigcouch) — 🪦 ARCHIVED — Cloudant's distributed CouchDB fork that powered IBM Cloudant — archived but historically significant
- [hachi](https://github.com/eagledot/hachi) — ⚠️ STALE — End-to-end semantic and metadata search for personal data — local AI-powered personal search engine
- [glados-tts](https://github.com/R2D2FISH/glados-tts) — ⚠️ STALE — GLaDOS text-to-speech using Forward Tacotron and HiFiGAN — runs stably on CPU, sounds like Portal
- [minigram-py](https://github.com/bobuk/minigram-py) — ⚠️ STALE — Ultraminimalistic Python library for building Telegram bots — gets out of your way immediately

### CLI & Terminal

- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — The feature-rich yt-dlp fork — faster, more formats, more sites, actively maintained successor to youtube-dl
- [zellij](https://github.com/zellij-org/zellij) — Terminal workspace with tabs, panes, and plugins — more approachable than tmux, equally powerful
- [prezto](https://github.com/sorin-ionescu/prezto) — The configuration framework for Zsh — fast, modular, the alternative to oh-my-zsh
- [mad](https://github.com/tj/mad) — ⚠️ STALE — Markdown manual page viewer — read man pages written in Markdown right in your terminal

### Linting & Formatting

- [spectral](https://github.com/stoplightio/spectral) — Flexible JSON/YAML linter with built-in OpenAPI support — enforce API design standards automatically
- [PoorMansTSqlFormatter](https://github.com/TaoK/PoorMansTSqlFormatter) — ⚠️ STALE — Free .Net and JS library for formatting T-SQL — works as a CLI, SSMS plugin, or Notepad++ plugin
- [eslint-plugin](https://github.com/lingui/eslint-plugin) — ESLint rules for LinguiJS projects — catch i18n mistakes and missing translations at lint time
- [prettier](https://github.com/prettier/prettier) — The opinionated code formatter — stops all arguments about style by making the decision for you
- [globals](https://github.com/mightyaleksey/globals) — ⚠️ STALE — Global identifier definitions from different JavaScript environments — for linting and static analysis

### Build Tools & Bundlers

- [microbundle](https://github.com/developit/microbundle) — Zero-config bundler for tiny npm modules — the simplest way to publish a library with CJS and ESM outputs
- [enb](https://github.com/enb/enb) — ⚠️ STALE — Build tool and BEM bundler for web projects — the build system that powered large-scale BEM applications
- [lmd](https://github.com/azproduction/lmd) — ⚠️ STALE — JavaScript module assembler for better web apps — a pre-webpack module bundler, now deprecated
- [grunt-criticalcss](https://github.com/filamentgroup/grunt-criticalcss) — 🪦 ARCHIVED — Grunt wrapper for extracting critical CSS — automated above-the-fold CSS extraction, now archived

### Testing & Debugging

- [browser](https://github.com/lightpanda-io/browser) — Lightpanda — headless browser designed for AI agents and automation, with minimal resource usage
- [node-inspector](https://github.com/node-inspector/node-inspector) — ⚠️ STALE — Node.js debugger using Blink DevTools — the precursor to modern node --inspect, now archived
- [lost-pixel](https://github.com/lost-pixel/lost-pixel) — Open-source visual regression testing — catch UI regressions without a Percy or Chromatic subscription
- [webspecter](https://github.com/jgonera/webspecter) — 🪦 ARCHIVED — BDD-style acceptance test framework for PhantomJS — precursor to modern headless browser testing
- [patchright](https://github.com/Kaliiiiiiiiii-Vinyzu/patchright) — Undetected Playwright fork — automation that passes bot detection for research and testing purposes
- [js-must](https://github.com/moll/js-must) — ⚠️ STALE — Assertion library for JavaScript with a fluent BDD syntax — expressive, comprehensive, and ships many matchers
- [mocha-cloud](https://github.com/tj/mocha-cloud) — ⚠️ STALE — Mocha test runner in the cloud via SauceLabs — cross-browser testing from the command line
- [mocha-cloud-grid-view](https://github.com/tj/mocha-cloud-grid-view) — ⚠️ STALE — Terminal browser grid view for mocha cloud cross-browser testing results

### Desktop App Frameworks

- [awesome-tauri](https://github.com/tauri-apps/awesome-tauri) — Curated list of Tauri apps, plugins, and resources — the community guide to the Tauri ecosystem
- [TauRPC](https://github.com/MatsDK/TauRPC) — Typesafe IPC layer for Tauri applications — end-to-end type safety between your Rust backend and TS frontend
- [next-electron-rsc](https://github.com/kirill-konshin/next-electron-rsc) — ⚠️ STALE — Next.js running inside Electron with React Server Components — desktop apps with the full Next.js stack

### Document Processing

- [liteparse](https://github.com/run-llama/liteparse) — Fast, open-source document parser from LlamaIndex — clean text extraction for LLM pipelines
- [node-html-markdown](https://github.com/crosstype/node-html-markdown) — ⚠️ STALE — Fast HTML-to-Markdown converter for Node.js — works in the browser too, handles edge cases well

### General Dev Tools

- [lerna](https://github.com/lerna/lerna) — Fast, modern build system for managing multi-package JavaScript/TypeScript repositories — the monorepo pioneer
- [docco-husky](https://github.com/mbrevoort/docco-husky) — ⚠️ STALE — Fork of docco for generating documentation for whole projects — whole-project literate programming docs
- [nxtensions](https://github.com/nxtensions/nxtensions) — ⚠️ STALE — Nx plugins and extensions expanding the monorepo toolkit beyond the official offerings
- [docco-husky](https://github.com/maxatwork/docco-husky) — ⚠️ STALE — Max's fork of docco-husky — for generating whole-project documentation in the literate programming style
- [bem-tools](https://github.com/bem-archive/bem-tools) — 🪦 ARCHIVED — BEM methodology toolkit for working with files and structure — archived, but foundational to BEM tooling
- [bem-gen-doc](https://github.com/bem-archive/bem-gen-doc) — ⚠️ STALE — Block library documentation generator prototype — early BEM tooling experiment, archived

---

## Systems & Low-Level

### Rust

- [codex](https://github.com/openai/codex) — OpenAI's lightweight terminal coding agent — the Rust-built CLI counterpart to Claude Code
- [Handy](https://github.com/cjpais/Handy) — Free, open-source offline speech-to-text app — completely local Whisper-based transcription
- [tantivy](https://github.com/quickwit-oss/tantivy) — Full-text search engine library in Rust inspired by Lucene — fast, embeddable, no JVM required
- [fresh](https://github.com/sinelaw/fresh) — Terminal-based IDE and text editor — Rust-native, easy to use, surprisingly capable
- [diffsitter](https://github.com/afnanenayet/diffsitter) — Tree-sitter-based AST diff tool — semantic diffs that understand code structure instead of just text

### C / C++ & Systems

- [ladybird](https://github.com/LadybirdBrowser/ladybird) — Truly independent web browser — built from scratch, no Chromium or WebKit, a major engineering achievement
- [UnrealEngine](https://github.com/EpicGames/UnrealEngine) — Unreal Engine source code — the most powerful game engine available with public source access
- [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) — Deep Packet Inspection circumvention utility for Windows — bypass ISP censorship at the network driver level
- [simdjson](https://github.com/simdjson/simdjson) — Parses gigabytes of JSON per second using SIMD instructions — the fastest JSON parser in existence
- [v86](https://github.com/copy/v86) — x86 PC emulator and x86-to-wasm JIT running entirely in the browser — run old operating systems in a tab
- [engine-sim](https://github.com/ange-yaghi/engine-sim) — ⚠️ STALE — Combustion engine simulator that generates realistic audio — actually sounds like the engine you built
- [GASDocumentation](https://github.com/tranek/GASDocumentation) — ⚠️ STALE — The authoritative community documentation for Unreal Engine's Gameplay Ability System
- [pingfs](https://github.com/yarrick/pingfs) — ⚠️ STALE — Stores your data in ICMP ping packets — ping packets as a filesystem, brilliantly absurd
- [dynet](https://github.com/clab/dynet) — ⚠️ STALE — Dynamic neural network toolkit for C++ and Python — builds computation graphs at runtime, not ahead of time
- [DagorEngine](https://github.com/GaijinEntertainment/DagorEngine) — ⚠️ STALE — Dagor Engine source from War Thunder's creators — a real production game engine made open-source
- [poedit](https://github.com/vslavik/poedit) — Translations editor for Mac, Windows, and Linux — the standard GUI tool for working with gettext .po files
- [jsbsim](https://github.com/JSBSim-Team/jsbsim) — Open-source flight dynamics and control software — the simulation engine behind many flight simulators
- [VoxelPluginFreeLegacy](https://github.com/VoxelPlugin/VoxelPluginFreeLegacy) — Legacy free version of Voxel Plugin for Unreal Engine — voxel world generation before the Pro era
- [schismtracker](https://github.com/schismtracker/schismtracker) — Old-school sample-based music composition tool — a Scream Tracker / IT-compatible tracker for modern systems
- [tiny-tpu](https://github.com/tiny-tpu-v2/tiny-tpu) — Minimal tensor processing unit inspired by Google's TPU V1 and V2 — learn how TPUs work by building one
- [MassSample](https://github.com/Megafunk/MassSample) — ⚠️ STALE — Community documentation for Unreal Engine 5's experimental Mass ECS plugin with a sample project
- [Fire](https://github.com/jerryuhoo/Fire) — Multiband distortion audio plugin — JUCE-based distortion with band splitting for character and color
- [pytorch-cpp-rl](https://github.com/Omegastick/pytorch-cpp-rl) — 🪦 ARCHIVED — PyTorch C++ reinforcement learning library — RL algorithms implemented in C++ with PyTorch backend
- [third-person-camera](https://github.com/DaedalicEntertainment/third-person-camera) — ⚠️ STALE — Sample code from the "Six Ingredients for a Dynamic Third-Person Camera" Unreal Fest talk
- [smarties](https://github.com/cselab/smarties) — ⚠️ STALE — Lightweight, scalable reinforcement learning framework — multi-environment, multi-agent, HPC-ready
- [node-discount](https://github.com/tj/node-discount) — ⚠️ STALE — Node.js bindings for the C markdown "discount" library — compile Markdown to HTML using a C library
- [Myra](https://github.com/archangel4031/Myra) — GAS Associate plugin source — makes Unreal's Gameplay Ability System less painful to set up
- [VoxelPluginLegacy](https://github.com/VoxelPlugin/VoxelPluginLegacy) — Dev repo for Voxel Plugin Legacy — use VoxelPluginProLegacy for production projects
- [haste-plugin-ue4](https://github.com/coderespawn/haste-plugin-ue4) — ⚠️ STALE — Haste plugin for Unreal Engine 4 — a utility plugin from the UE4 era
- [Navigation3D](https://github.com/reidtreharne/Navigation3D) — ⚠️ STALE — 3D navigation system component — pathfinding in three-dimensional space
- [TwitchPlay](https://github.com/TheDiG3/TwitchPlay) — ⚠️ STALE — Unreal Engine 4 plugin for Twitch Chat integration — let your viewers control your game
- [MotionSymphony-Plugin-Unreal-Engine](https://github.com/Animation-Uprising/MotionSymphony-Plugin-Unreal-Engine) — ⚠️ STALE — MotionSymphony plugin for motion matching in UE4 — source access for verified users
- [cpp-dqn](https://github.com/takuseno/cpp-dqn) — ⚠️ STALE — Deep Q-Network implementation in C++ with NNabla — blazingly fast DQN for reinforcement learning
- [OTX-Widget-480x272-Widget-Layouts](https://github.com/PD5DJ/OTX-Widget-480x272-Widget-Layouts) — ⚠️ STALE — OpenTX widget layouts for 480x272 displays — custom telemetry widgets for RC transmitters

### Zig

- [ghostty](https://github.com/ghostty-org/ghostty) — Fast, feature-rich, cross-platform terminal emulator with platform-native UI — the terminal worth switching to

---

## Data & Analytics

### Analytics & Feature Flags

- [superset](https://github.com/apache/superset) — Apache Superset — data visualization and exploration platform that rivals Tableau for BI needs
- [duckdb](https://github.com/duckdb/duckdb) — In-process analytical SQL database — run complex queries on large datasets without a server
- [rybbit](https://github.com/rybbit-io/rybbit) — Open-source, privacy-friendly Google Analytics alternative — 10x more intuitive, no cookies, self-hostable
- [growthbook](https://github.com/growthbook/growthbook) — Open-source feature flags, A/B testing, and product analytics — the self-hosted LaunchDarkly and Amplitude
- [duckdb-wasm](https://github.com/duckdb/duckdb-wasm) — DuckDB compiled to WebAssembly — run full analytical SQL in the browser with no server

### Data Science & Visualization

- [OmniParser](https://github.com/microsoft/OmniParser) — ⚠️ STALE — Screen parsing tool for vision-based GUI agents — identifies UI elements from screenshots for AI agents
- [nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero) — ⚠️ STALE — Andrej Karpathy's neural networks course — build everything from scratch, one of the best ML learning resources
- [dinov2](https://github.com/facebookresearch/dinov2) — Meta's DINOv2 — self-supervised vision transformer that produces exceptional general-purpose image features
- [embedding-atlas](https://github.com/apple/embedding-atlas) — Interactive visualization tool for large embedding spaces — explore and label your vector data visually
- [applehealth](https://github.com/krumjahn/applehealth) — Export and analyze Apple Health data with AI — turn your health metrics into insights and visualizations
- [MS-LaTTE](https://github.com/microsoft/MS-LaTTE) — 🪦 ARCHIVED — Dataset of locations and times for to-do task completion — research on contextual task scheduling

---

## Knowledge Management

### Notes & Diagrams

- [marked](https://github.com/markedjs/marked) — Fast Markdown parser and compiler — the standard library for rendering Markdown in JavaScript
- [claude-cookbooks](https://github.com/anthropics/claude-cookbooks) — Anthropic's official collection of Claude usage examples — practical recipes for getting the most out of the API
- [markdown-oxide](https://github.com/Feel-ix-343/markdown-oxide) — PKM Markdown Language Server — LSP server that brings Obsidian-style linking to any editor

---

## Productivity & Apps

### Personal & Business Apps

- [actual](https://github.com/actualbudget/actual) — Local-first personal finance app — your money data stays on your machine, powerful budgeting without subscriptions
- [monica](https://github.com/monicahq/monica) — ⚠️ STALE — Personal CRM — remember important details about the people in your life, relationships as data
- [koodo-reader](https://github.com/koodo-reader/koodo-reader) — Modern ebook manager and reader with cross-platform sync — the best open-source reading app

---

## Miscellaneous

### Curated Lists & Resources

- [awesome-svelte](https://github.com/CalvinWalzel/awesome-svelte) — ⚠️ STALE — Curated list of awesome Svelte things — now deprecated in favor of sveltesociety.dev
- [Clone-Wars](https://github.com/GorvGoyl/Clone-Wars) — ⚠️ STALE — 100+ open-source clones of Airbnb, Netflix, Spotify, WhatsApp, and others — learn by reading real implementations

### Audio & Music

- [VSCO-2-CE](https://github.com/sgossner/VSCO-2-CE) — ⚠️ STALE — Open-source orchestral sample library — free, real recordings of real instruments for music production
- [ggwave](https://github.com/ggerganov/ggwave) — Tiny data-over-sound library — transmit data through audio waves, works between any devices with mic and speaker
- [chiptune2.js](https://github.com/deskjet/chiptune2.js) — ⚠️ STALE — JavaScript chiptune player using Web Audio API — play MOD, XM, S3M files in the browser

### Media & Streaming

- [IPTV](https://github.com/Free-TV/IPTV) — M3U playlist of free, legal TV channels — stream television worldwide without a subscription
- [mediabunny](https://github.com/Vanilagy/mediabunny) — Pure TypeScript media toolkit — read, write, and convert video and audio files directly in the browser

### Other

- [reasonable-default-rules](https://github.com/bobuk/reasonable-default-rules) — ⚠️ STALE — Rules for commenting and communication in chats — a Russian-language community conduct guide
- [maxatwork.github.com](https://github.com/maxatwork/maxatwork.github.com) — ⚠️ STALE — Max's personal GitHub Pages site — the original web presence
