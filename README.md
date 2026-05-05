# AgenticStudio

**Full-stack workspace for building, testing, and deploying agentic AI features.**

AgenticStudio is an open platform for developers building production-grade autonomous AI agents — supporting Claude, GPT-4, Gemini, Mistral, Llama, and more through a unified development workspace.

**Live:** [ambientprototype.vercel.app/agenticstudio](https://ambientprototype.vercel.app/agenticstudio)

---

## Features

| Module | Description |
|--------|-------------|
| **Agent Builder** | Visual node editor for multi-step agentic workflows — wire tools, memory, sub-agents, and decision branches |
| **Tool Use Studio** | Build and validate JSON tool schemas; live sandbox runs real Claude API calls |
| **MCP Server Builder** | Scaffold Model Context Protocol servers from templates; deploy to Vercel or Docker |
| **Multi-Agent Orchestration** | Chain specialized agents with typed state handoffs, retry logic, and parallel fan-out |
| **Prompt Engineering Lab** | A/B test prompts across models with custom rubrics and model-as-judge scoring |
| **Memory & Context Manager** | Connect vector stores (Pinecone, pgvector), manage episodic memory across sessions |
| **Evaluation Framework** | Define evals as code; run in CI/CD to catch regressions before every release |
| **API Gateway & Cost Tracker** | Unified API key management; route by cost/latency; real-time token burn dashboards |

## Supported Models

- **Claude 4** (Opus / Sonnet) — Anthropic · Tool use, MCP, prompt caching, computer use
- **GPT-4o / o3** — OpenAI · Structured outputs, parallel function calling, Assistants API
- **Gemini 2.5 Pro** — Google · 1M context, code execution, Search grounding
- **Mistral / Llama 3** — Open Source · Self-hosted, fine-tuning, vLLM / Ollama support

## Tech Stack

- **Frontend:** Next.js 16 App Router · React 19 · TypeScript
- **Deployed:** Vercel (ambientprototype.vercel.app)
- **AI SDKs:** Anthropic SDK · OpenAI SDK · Google Generative AI · Vercel AI SDK

## Getting Started

```bash
git clone https://github.com/john3913/agenticstudio.git
cd agenticstudio
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Roadmap

- [ ] Visual agent workflow editor (drag-and-drop)
- [ ] Live tool-use sandbox with real API calls
- [ ] MCP server scaffolding CLI
- [ ] Multi-model eval runner with rubric grading
- [ ] Vector memory integration (Pinecone, pgvector)
- [ ] Cost tracking dashboard
- [ ] Export to TypeScript / Python agent templates

## License

MIT — built on [Ambient Intelligence](https://github.com/ambientintel/ambientprototype)
