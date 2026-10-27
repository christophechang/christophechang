# Christophe Chang

Technical Architect and Lead .NET Developer. I run [Soltech Consulting Ltd](https://soltechconsulting.co.uk).

## About

I'm a .NET and Azure architect who builds production systems, APIs, cloud platforms, automation, and data pipelines. Lately most of that work involves wiring LLMs into real products and keeping them on a leash: validation, guardrails, and cost control so the AI helps without going off the rails.

At Soltech I take on architecture and hands-on engineering for teams that need something shipped rather than a deck about shipping it. In practice that means owning the whole path: design, build, CI/CD, observability, and the operational corners everyone forgets until production.

Before going independent I spent my career in digital agencies, delivering enterprise systems for clients including Microsoft, Rolex, Jaguar Land Rover, Coca-Cola, Bowers & Wilkins, ARAMCO, and SABIC.

Most of my own product work sits at the intersection of audio and AI: harmonic analysis, recommendation, metadata enrichment, and staged LLM orchestration. It has grown into [Setfolio](https://setfolio.app), a family of multi-tenant SaaS tools for DJs that I design, build, and run on Azure. It comes from the other half of my life. I DJ as [Changsta](https://www.changsta.com) across House, Drum & Bass, Breakbeat, UK Garage, UK Bass, Funk, and Hip Hop, which is where most of these problems start.

What I'm digging into right now:

- AI-assisted engineering workflows
- LLM orchestration and guardrails
- Automation pipelines
- Recommendation systems
- Azure-native architectures
- Developer tooling
- Music-tech systems

> **Available for fractional architecture and AI-integration work.** If your team needs an experienced pair of hands on .NET, Azure, or shipping LLM features safely, [let's talk](https://soltechconsulting.co.uk) or reach me on [LinkedIn](https://linkedin.com/in/christophechang).

## Stack

```text
Languages        C# · Python · SQL · JavaScript · TypeScript
Frameworks       .NET 10 · ASP.NET Core · Web API · Entity Framework Core · React
Cloud            Azure App Services · Azure Functions · Azure Container Apps · Cosmos DB · Azure SQL · Azure Storage · Entra External ID · Azure DevOps
AI / Automation  OpenAI · Claude · Gemini · Groq · Mistral · OpenRouter · Ollama
Infrastructure   GitHub Actions · Bicep · Docker · Cloudflare Workers · Cloudflare Pages
Observability    OpenTelemetry · Azure Monitor · Application Insights
Data / Messaging RSS · JSON APIs · Discord Bots · SoundCloud RSS ingestion
Tooling          Git · VS Code · Claude Code · Rekordbox · Mixed In Key
```

## Products

Closed source, live on Azure.

| Product | What it does |
|---|---|
| **[Setfolio](https://setfolio.app)** | Connect SoundCloud once and get a searchable public archive of every mix: a page per set, every tracklist indexed, official embeds only. |
| **[TuneFinder](https://tunefinder.setfolio.app)** | Music discovery that watches new releases and scores them against how a DJ actually mixes. The scoring engine is fully deterministic and retunes its own weights from recorded feedback; there is no LLM in the run. |
| **[MixLab](https://mixlab.setfolio.app)** | AI-assisted set building from a Rekordbox collection: mix concepts from harmonic compatibility, energy flow, and enriched metadata. Staged LLM orchestration rather than one oversized prompt, each run an isolated Container Apps job, paid for in credits. |

## Open source

| Project | What it does |
|---|---|
| **[SoundCloud AI Mix Recommender API](https://github.com/christophechang/soundcloud-ai-mix-recommender-api)** | The .NET API behind changsta.com. Pairs deterministic validation with AI reasoning to recommend mixes from structured catalogue metadata. The AI suggests, the rules decide. |
| **[Rekordbox Metadata Enrichment](https://github.com/christophechang/rekordbox-meta-data-enrichment)** | Fills gaps in Rekordbox libraries using MusicBrainz and Discogs, with confidence scoring, caching, and LLM-assisted disambiguation for the ambiguous cases. |

## How I work

- Production-first: I design for the day it's live, not the demo.
- Deterministic rules around non-deterministic models. The validation layer in the [SoundCloud recommender](https://github.com/christophechang/soundcloud-ai-mix-recommender-api) is a good example.
- Cost-aware LLM orchestration: staged, checkable steps over one giant prompt, as in [MixLab](https://mixlab.setfolio.app). And when the signals get rich enough to explain themselves, the model comes out entirely, as in [TuneFinder](https://tunefinder.setfolio.app).
- CI/CD and observability treated as part of the build, not an afterthought.
- Simple and maintainable beats clever, most of the time.

## Elsewhere

[Soltech Consulting](https://soltechconsulting.co.uk) · [Setfolio](https://setfolio.app) · [Changsta](https://changsta.com) · [SoundCloud](https://soundcloud.com/changsta) · [LinkedIn](https://linkedin.com/in/christophechang)
