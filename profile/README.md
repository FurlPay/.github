<div align="center">

![Furlpay — The On-Chain Financial Operating System](https://raw.githubusercontent.com/FurlPay/.github/main/profile/banner.png)

**Stablecoin payments · global banking · virtual cards · fractional investing — with a developer ecosystem to build on all of it.**

[Website](https://furlpay.com) · [Docs](https://furlpay.com/docs) · [API Spec](https://github.com/FurlPay/furlpay-openapi) · [hello@furlpay.com](mailto:hello@furlpay.com)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=fff)
![Next.js](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=fff)
![React](https://img.shields.io/badge/React-087EA4?logo=react&logoColor=fff)
![Solana](https://img.shields.io/badge/Solana-9945FF?logo=solana&logoColor=fff)
![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=fff)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![OpenAPI](https://img.shields.io/badge/OpenAPI%203.1-6BA539?logo=openapiinitiative&logoColor=fff)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-111)
![MIT](https://img.shields.io/badge/License-MIT-00E599)

</div>

---

## Start here

**[furlpay-examples](https://github.com/FurlPay/furlpay-examples)** — clone-and-run examples for Next.js, Express, FastAPI, Go, Rust, AI agents (MCP), and selling API access to agents over x402.

## SDKs — one API, four languages

Same client surface and the same webhook signature scheme (`t=<unix>,v1=<hmac-sha256-hex>`, 5-minute replay tolerance) everywhere.

| Language | Install | Repo |
|---|---|---|
| Node.js / TypeScript | `npm i @furlpay/furlpay-node` | [furlpay-node](https://github.com/FurlPay/furlpay-node) |
| Python | `pip install furlpay` | [furlpay-python](https://github.com/FurlPay/furlpay-python) |
| Go | `go get github.com/furlpay/furlpay-go` | [furlpay-go](https://github.com/FurlPay/furlpay-go) |
| Rust | `cargo add furlpay` | [furlpay-rust](https://github.com/FurlPay/furlpay-rust) |

## Build with Furlpay

| Repo | What it is |
|---|---|
| [furlpay-examples](https://github.com/FurlPay/furlpay-examples) | ⭐ Runnable examples for every stack — the fastest path to a first payment |
| [furlpay-cli](https://github.com/FurlPay/furlpay-cli) | `stripe-cli` for stablecoins — webhook forwarding & test events (`@furlpay/cli`) |
| [furlpay-elements](https://github.com/FurlPay/furlpay-elements) | Embeddable React checkout components (`@furlpay/elements`) |
| [furlpay-account-kit](https://github.com/FurlPay/furlpay-account-kit) | Safe/ERC-4337 smart accounts, paymaster, time-locked escrow (`@furlpay/account-kit`) |
| [furlpay-x402](https://github.com/FurlPay/furlpay-x402) | x402 facilitator + payment middleware — the first Solana-native x402 facilitator |
| [x402-guard](https://github.com/FurlPay/x402-guard) | x402 hardening middleware — nonce, replay & duplicate-settlement protection, zero deps (`@furlpay/x402-guard`) |
| [furlpay-extension](https://github.com/FurlPay/furlpay-extension) | MV3 browser extension (open for security audit) |
| [furlpay-openapi](https://github.com/FurlPay/furlpay-openapi) | OpenAPI 3.1 spec — generate SDKs in any language |
| [furlpay-solana-actions-template](https://github.com/FurlPay/furlpay-solana-actions-template) | Starter: Solana Actions & Blinks checkout links |

## AI agents — payment rails for the agentic internet

Give an AI agent a wallet: check balances, create checkouts, move stablecoins, invest, and **pay for x402-metered APIs within a spending budget**.

| Repo | What it is |
|---|---|
| [furlpay-mcp-server](https://github.com/FurlPay/furlpay-mcp-server) | MCP server — drive Furlpay from Claude, Cursor & AI agents (`@furlpay/mcp-server`) |
| [furlpay-langchain](https://github.com/FurlPay/furlpay-langchain) | Furlpay tools for **LangChain** — 12 agent tools incl. autonomous x402 payments (`pip install furlpay-langchain`) |
| [furlpay-llamaindex](https://github.com/FurlPay/furlpay-llamaindex) | Furlpay tool spec for **LlamaIndex** — same agent toolset (`pip install furlpay-llamaindex`) |
| [furlpay-openbb-plugin](https://github.com/FurlPay/furlpay-openbb-plugin) | The **execution layer** for OpenBB Workspace — trade, DCA & settle in stablecoins |

## Data & investing

| Repo | What it is |
|---|---|
| [furlpay-market-data](https://github.com/FurlPay/furlpay-market-data) | Real-time stock/ETF quotes & bars — Alpha Vantage + Nasdaq aggregator with demo fallback (`npm i @furlpay/market-data`) |
| [furlpay-auto-invest](https://github.com/FurlPay/furlpay-auto-invest) | Automated dollar-cost averaging — schedule recurring USDC-funded buys (`npm i @furlpay/auto-invest`) |

## Contribute

We're building payment rails for the agentic internet, and the hard problems are open:
agent spend mandates, Know-Your-Agent trust signals, idempotency & retry semantics,
and SDK parity across languages.

- **[Open issues across the org](https://github.com/search?q=org%3AFurlPay+state%3Aopen&type=issues)** — look for `good first issue` and `help wanted`
- **`agentic-payments` label** — the frontier problems (x402, spend mandates, KYA)
- **[Contributing guide](https://github.com/FurlPay/.github/blob/main/CONTRIBUTING.md)**

## Community

- **Questions & integration help** — GitHub Discussions, enabled on every repo
- **Security reports** — [hello@furlpay.com](mailto:hello@furlpay.com) (see each repo's SECURITY.md — please don't open public issues)
- **Show what you built** — Discussions "Show and tell"

## What stays private

Core custody engines, fraud models, HSM signing policies, and the production
application are developed in a private monorepo. The packages here are mirrored
from it and are the supported public surface.
