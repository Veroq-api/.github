# VEROQ

**The verified intelligence layer for AI agents.**

Every claim fact-checked. Every output verified. Multi-agent pipelines for finance, legal, research, and compliance.

```python
pip install veroq
```

```python
from veroq import VeroqClient
client = VeroqClient()

# Ask anything — 41 intents, trade signals, LLM summaries
answer = client.ask("How is NVDA doing?")

# Verify any claim — evidence chains, confidence breakdown
result = client.verify("NVIDIA beat Q4 earnings")

# Multi-agent verified analysis — 5 agents, one verified answer
swarm = client.create_verified_swarm("Analyze NVDA for a long position")
print(swarm["synthesis"]["summary"])
```

## Platform (v2.0)

| Capability | What you get |
|-----------|-------------|
| **Verified Swarm** | 5-agent pipeline — planner, researcher, verifier, critic, synthesizer |
| **Agent Runtime** | Domain-specific verticals: finance, legal, research, compliance, custom |
| **62 MCP Tools** | Every tool with WHEN TO USE, RETURNS, COST, EXAMPLE |
| **Enterprise Safety** | Permission engine, decision lineage, escalation, audit trails |
| **External MCP** | Securely proxy external APIs with trust levels and rate limits |
| **Self-Improvement** | Feedback loop with web search fallback fills data gaps over time |
| **Cost Control** | 3 modes (cheap/balanced/premium), per-step budgets, credit transparency |

## SDKs

| Package | Install | |
|---------|---------|--|
| [**Python**](https://github.com/Veroq-api/veroq-python) | `pip install veroq` | `.ask()` `.verify()` `.create_verified_swarm()` |
| [**TypeScript**](https://github.com/Veroq-api/veroq-js) | `npm i @veroq/sdk` | `.ask()` `.verify()` `.createVerifiedSwarm()` |
| [**MCP Server**](https://github.com/Veroq-api/veroq-mcp) | `npm i -g veroq-mcp` | 62 tools for Claude / Cursor |
| [**CLI**](https://github.com/Veroq-api/veroq-cli) | `npm i -g @veroq/cli` | `veroq ask` `veroq verify` |
| [**LangChain**](https://github.com/Veroq-api/langchain-veroq) | `pip install langchain-veroq` | 40 tools |
| [**CrewAI**](https://github.com/Veroq-api/crewai-veroq) | `pip install crewai-veroq` | 40 tools |
| [**Vercel AI**](https://github.com/Veroq-api/veroq-vercel-ai) | `npm i @veroq/ai` | 53 tools |
| [**n8n**](https://github.com/Veroq-api/veroq-n8n) | `npm i n8n-nodes-veroq` | 38 operations |

## Demo Apps

| App | What it does |
|-----|-------------|
| [**TradingAgents-Pro**](https://github.com/Veroq-api/TradingAgents-Pro) | 18 AI agents — showcases the verified intelligence layer |
| [**trading-agent**](https://github.com/Veroq-api/trading-agent) | Autonomous trading — scans, analyzes, verifies, signals |
| [**financial-research-agent**](https://github.com/Veroq-api/financial-research-agent) | Multi-step research with evidence chains |
| [**portfolio-tracker**](https://github.com/Veroq-api/portfolio-tracker) | Real-time SSE portfolio monitoring |
| [**crypto-monitor**](https://github.com/Veroq-api/crypto-monitor) | 200 tokens — prices, DeFi, sentiment |
| [**fact-checker**](https://github.com/Veroq-api/fact-checker) | CLI — verify any claim with evidence |
| [**veroq-cookbook**](https://github.com/Veroq-api/veroq-cookbook) | 10 ready-to-run examples (Python + TypeScript) |

## What You Get

- **`/ask`** — 41 intents, LLM summaries, SSE streaming, composite trade signals (0-100)
- **`/verify`** — Evidence chains, confidence breakdown (4 factors), source reliability scores, verification receipts
- **`/swarm/run`** — 5 verified agents coordinate on any query. Every step verified with decision lineage.
- **`/runtime/run`** — Domain-specific pipelines with pre-configured safety rules per vertical
- **1,061+ tickers** — equities, crypto, ETFs, commodities + auto-discovery
- **200+ sources** across 18 categories
- **300+ API endpoints** when you need granular control

## Links

[veroq.ai](https://veroq.ai) · [API Reference](https://veroq.ai/api-reference) · [Docs](https://veroq.ai/docs) · [Pricing](https://veroq.ai/pricing)

Free tier: 1,000 credits/month. No credit card required. [Enterprise plans](https://veroq.ai/pricing) for audit trails, escalation, and external MCP.
