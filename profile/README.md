# VEROQ

**The trust protocol for agentic AI.**

Two endpoints. Every answer verified. `/ask` anything. `/verify` everything.

## Quick Start

```python
pip install veroq
```

```python
from veroq import VeroqClient
client = VeroqClient()

# Ask anything — routes to 40+ endpoints automatically
answer = client.ask("How is NVDA doing?")

# Verify anything — evidence chain + confidence breakdown
result = client.verify("NVIDIA beat Q4 earnings")
```

## What VEROQ Does

| Capability | Details |
|-----------|---------|
| `/ask` | 41 intents — price, technicals, earnings, sentiment, screener, backtest, competitors, and more. LLM summaries, trade signals, SSE streaming. |
| `/verify` | Fact-check any claim. Evidence chain with source names, quotes, URLs. Confidence breakdown by factor. Live web fallback. |
| **Coverage** | 1,061+ tickers (auto-discovery for any valid ticker), 200+ sources, 18 categories |
| **Streaming** | `GET /ask/stream` — real-time SSE, data arrives as each source responds |
| **Trade Signals** | Composite 0-100 score: RSI, sentiment, VIX, technicals, earnings proximity |

## SDKs

| Package | Install |
|---------|---------|
| [Python](https://github.com/Veroq-api/veroq-python) | `pip install veroq` |
| [TypeScript](https://github.com/Veroq-api/veroq-js) | `npm i @veroq/sdk` |
| [MCP Server](https://github.com/Veroq-api/veroq-mcp) | `npm i -g veroq-mcp` |
| [LangChain](https://pypi.org/project/langchain-veroq/) | `pip install langchain-veroq` |
| [CrewAI](https://pypi.org/project/crewai-veroq/) | `pip install crewai-veroq` |
| [Vercel AI](https://www.npmjs.com/package/@veroq/ai) | `npm i @veroq/ai` |
| [CLI](https://www.npmjs.com/package/@veroq/cli) | `npm i -g @veroq/cli` |
| [n8n](https://www.npmjs.com/package/n8n-nodes-veroq) | `npm i n8n-nodes-veroq` |

## Examples

| Repo | Description |
|------|-------------|
| [veroq-cookbook](https://github.com/Veroq-api/veroq-cookbook) | 10 ready-to-run examples in Python + TypeScript |
| [trading-agent](https://github.com/Veroq-api/trading-agent) | Autonomous trading bot with signals + verification |
| [financial-research-agent](https://github.com/Veroq-api/financial-research-agent) | Multi-step research with evidence chains |
| [TradingAgents-Pro](https://github.com/Veroq-api/TradingAgents-Pro) | 18 AI agents — full trading framework |

## Links

- [veroq.ai](https://veroq.ai) — Interactive demos
- [API Reference](https://veroq.ai/api-reference) — 300+ endpoints
- [Documentation](https://veroq.ai/docs) — Guides + tutorials
- [Pricing](https://veroq.ai/pricing) — Free tier: 1,000 credits/month

---

*Free to start. No credit card required.*
