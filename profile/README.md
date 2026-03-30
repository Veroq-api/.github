# VEROQ

**The trust protocol for agentic AI.**

Two endpoints. Every answer verified. `/ask` anything. `/verify` everything.

```python
pip install veroq
```

```python
from veroq import VeroqClient
client = VeroqClient()

answer = client.ask("How is NVDA doing?")       # 41 intents, LLM summaries, trade signals
result = client.verify("NVIDIA beat Q4 earnings") # evidence chains, confidence breakdown
```

## SDKs

| Package | Install | |
|---------|---------|--|
| [**Python**](https://github.com/Veroq-api/veroq-python) | `pip install veroq` | `.ask()` `.verify()` `.ask_stream()` |
| [**TypeScript**](https://github.com/Veroq-api/veroq-js) | `npm i @veroq/sdk` | `.ask()` `.askStream()` `.verify()` |
| [**MCP Server**](https://github.com/Veroq-api/veroq-mcp) | `npm i -g veroq-mcp` | 52 tools for Claude / Cursor |
| [**CLI**](https://github.com/Veroq-api/veroq-cli) | `npm i -g @veroq/cli` | `veroq ask` `veroq verify` |
| [**LangChain**](https://github.com/Veroq-api/langchain-veroq) | `pip install langchain-veroq` | 40 tools |
| [**CrewAI**](https://github.com/Veroq-api/crewai-veroq) | `pip install crewai-veroq` | 40 tools |
| [**Vercel AI**](https://github.com/Veroq-api/veroq-vercel-ai) | `npm i @veroq/ai` | 53 tools |
| [**n8n**](https://github.com/Veroq-api/veroq-n8n) | `npm i n8n-nodes-veroq` | 38 operations |

## Demo Apps

| App | What it does |
|-----|-------------|
| [**trading-agent**](https://github.com/Veroq-api/trading-agent) | Autonomous trading — scans, analyzes, verifies, signals |
| [**financial-research-agent**](https://github.com/Veroq-api/financial-research-agent) | Multi-step research with evidence chains |
| [**TradingAgents-Pro**](https://github.com/Veroq-api/TradingAgents-Pro) | 18 AI agents — full trading framework |
| [**portfolio-tracker**](https://github.com/Veroq-api/portfolio-tracker) | Real-time SSE portfolio monitoring |
| [**earnings-agent**](https://github.com/Veroq-api/earnings-agent) | Earnings calendar tracking + analysis |
| [**crypto-monitor**](https://github.com/Veroq-api/crypto-monitor) | 200 tokens — prices, DeFi, sentiment |
| [**fact-checker**](https://github.com/Veroq-api/fact-checker) | CLI — verify any claim with evidence |
| [**market-brief**](https://github.com/Veroq-api/market-brief) | Daily briefings to Slack / Discord |
| [**veroq-chat**](https://github.com/Veroq-api/veroq-chat) | Interactive REPL with streaming |

## Tools

| Tool | What it does |
|------|-------------|
| [**veroq-sheets**](https://github.com/Veroq-api/veroq-sheets) | `=VEROQ_ASK("NVDA price")` in Google Sheets |
| [**veroq-cursor**](https://github.com/Veroq-api/veroq-cursor) | Financial intelligence in your editor |
| [**veroq-evals**](https://github.com/Veroq-api/veroq-evals) | Benchmark accuracy, speed, and coverage |
| [**veroq-cookbook**](https://github.com/Veroq-api/veroq-cookbook) | 10 ready-to-run examples (Python + TypeScript) |

## What You Get

- **`/ask`** — 41 intents: price, technicals, earnings, sentiment, screener, backtest, competitors, financials, candles, movers, forecast, debate, and more. LLM summaries, SSE streaming, trade signals.
- **`/verify`** — Evidence chain (source names, quotes, URLs), confidence breakdown (agreement, quality, recency, corroboration), live web fallback.
- **1,061+ tickers** — equities, crypto, ETFs, commodities + auto-discovery for any valid ticker
- **200+ sources** across 18 categories
- **Trade signals** — composite 0-100 score
- **300+ API endpoints** when you need granular control

## Links

[veroq.ai](https://veroq.ai) · [API Reference](https://veroq.ai/api-reference) · [Docs](https://veroq.ai/docs) · [Pricing](https://veroq.ai/pricing)

Free tier: 1,000 credits/month. No credit card required.
