# 🎿 LLM Snow

> AI-powered ski trip planning assistant built with Claude API

LLM Snow is a portfolio project demonstrating real-world LLM concepts through
a practical use case : planning the perfect ski weekend.

## Concepts demonstrated

- **Tool use** — Real-time weather data via Open-Meteo API
- **Multi-turn conversation** — User onboarding and iterative recommendations
- **RAG** _(v2)_ — Ski resort knowledge base with semantic search
- **Agentic workflows** _(v2)_ — Orchestrated tools to produce a complete trip plan

## Stack

- Python 3.11+
- [Anthropic Claude API](https://docs.anthropic.com)
- [Open-Meteo API](https://open-meteo.com) (free, no key required)
- Jupyter Notebooks

## Getting started

```bash
git clone https://github.com/<username>/llm-snow
cd llm-snow
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # Add your Anthropic API key
```

## Project structure

```
notebooks/    # Exploratory development
src/          # Production-ready modules
data/         # Resort knowledge base (v2)
```

## Roadmap

- [x] Weather API integration
- [x] Tool use with Claude
- [x] Multi-turn conversation
- [ ] RAG for resort comparison
- [ ] Personalized packing list generation
