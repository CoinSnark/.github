[EN](./README.md)  |  [PT](./README.pt.md)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/EconObs)

# CoinSnark 

**Research Laboratory for Currency & Cryptocurrency Intelligence**

**CoinSnark** investigates the engineering of automated intelligence systems for currencies — fiat and crypto — enabling real-time monitoring, cross-exchange arbitrage detection, market microstructure analysis, and multi-source data fusion.

This is independent research focused on:
- 💱 **Dual-currency intelligence**: Unified observation of traditional fiat systems (forex, central banks, treasuries) and decentralized crypto networks (blockchains, DEXs, CEXs).
- 📊 **Market microstructure**: Understanding order books, liquidity patterns, spread dynamics, and price formation across venues.
- 🔄 **Cross-venue correlation**: Detecting arbitrage opportunities, latency differentials, and fragmentation inefficiencies.
- 🛡️ **Resilient data pipelines**: Systems designed for 24/7 monitoring despite API degradation, rate limits, websocket failures, or exchange outages.
- ⚙️ **Engineering-first approach**: Performance, determinism, and reproducibility as core design principles.

The output is twofold: functional open-source intelligence tools and the scientific insights derived from building them.

> *"Every tick tells a story — if you're listening systematically."*

## :microscope: Research Questions

Current investigations explore:

- How to design unified abstractions for currency data extraction across fundamentally different architectures (REST, WebSocket, gRPC, blockchain RPC, FIX protocol)?
- What is the true cost (latency, accuracy, completeness) of multi-exchange aggregation across crypto and fiat domains?
- Can intelligence systems survive exchange failures (API downtime, delistings, regulatory actions, flash crashes) through graceful degradation and circuit breakers?
- How do latency arbitrage opportunities evolve across venues, and what engineering trade-offs are required to capture them reliably?
- What signals from order book dynamics reliably predict short-term volatility or liquidity crises?

Detailed research threads are documented in each repository's `RESEARCH.md`.

## :bulb: Projects

**Status and roadmaps** are maintained in the [**CoinSnark GitHub Projects**](https://github.com/orgs/CoinSnark/projects).

Each repository is the **single source of truth** for its tool:
- 📋 Core documentation and intelligence protocols
- 🔍 Venue coverage matrix (badges for exchanges, currency pairs, data types)
- 🗂️ Issues and research discussions
- 🌐 Multi-language documentation (`README.pt.md`, `README.es.md`, etc.)

## :handshake: Collaboration

This research benefits from engagement with quantitative researchers, trading system engineers, market microstructure analysts, financial economists, and open data advocates.

| Resource | Purpose |
|----------|---------|
| [**Organization CONTRIBUTING.md**](CONTRIBUTING.md) | General guidelines for engaging with CoinSnark |
| **Repository CONTRIBUTING.md** | Tool-specific collaboration workflows |
| **Issues with `research` tag** | Discussions around currency intelligence methodologies |
| **Issues with `good first issue` tag** | Entry points for new contributors |

:globe_with_meridians: **Multi-language**: Key documentation is available in Portuguese, Spanish, and English — look for `.pt.md`, `.es.md` files alongside English versions.

## :link: Related Research Initiatives

These organizations explore complementary aspects of software engineering and intelligence gathering:

| Organization | Focus |
|--------------|-------|
| [**EconObs**](https://github.com/EconObs) | Financial Intelligence & Economic Observation — macro-financial indicators and cross-source correlation. |
| [**job-recon**](https://github.com/job-recon) | Labor Market Intelligence & Open Corporate Data — workforce dynamics and skills demand. |

Together, they form a broader investigation into resilient, cross-domain intelligence systems spanning **currencies**, **financial systems**, **labor markets**, and **infrastructure automation**.

## :pushpin: Pace & Context

Independent research, conducted alongside professional work. Updates are pragmatic, not performative. Contributions aligned with the research questions are welcome.

## :balance_scale: License

Code: Apache 2.0  
Documentation: CC BY 4.0

<br />

---

<div align="center">
  <a href="https://github.com/CoinSnark"><img alt="Static Badge" src="https://img.shields.io/badge/-GitHub?style=social&logo=github&logoSize=auto&label=CoinSnark&link=https%3A%2F%2Fgithub.com%2FCoinSnark"></a>
  <a href="https://gitlab.com/CoinSnark"><img alt="Static Badge" src="https://img.shields.io/badge/-GitLab?style=social&logo=gitlab&logoSize=auto&label=CoinSnark&link=https%3A%2F%2Fgitlab.com%2FCoinSnark"></a>
</div>
