# awesome-onchain-agents

A curated list of resources for building AI agents on Ethereum. For Ethereum-specific skills and knowledge, see [Ethskills](https://ethskills.com/).

## Contents

1. [Frameworks](#frameworks)
2. [Standards & Protocols](#standards--protocols)
3. [MCP Servers](#mcp-servers)
4. [Developer Tools](#developer-tools)
5. [Directories](#directories)
6. [Agent Examples](#agent-examples)
7. [Official Resources](#official-resources)

## Frameworks

Open-source frameworks for building and running AI agents.

### OpenClaw

A local‑first, OS‑level autonomous agent framework.  It connects chat apps (WhatsApp, Telegram, Discord, etc.) to an agent that can control a computer via a skills system.

**[Docs](https://docs.openclaw.ai/getting-started)**

### ElizaOS

An multi‑platform agent framework with strong social + onchain plugins, memory, and integrations.

Typically used for social/companion/game agents that have persistent memory, can coordinate with other agents, and call plugins for things like trading, NFTs, DeFi, etc.

**[Docs](https://elizaos.ai)**

### Virtuals Protocol

Agent framework and onchain commerce protocol for building autonomous, revenue‑generating AI agents.

Typically used to create tokenized agents that post on social (e.g. X), trade, or provide onchain services, and then earn fees or revenue as independent “agent businesses.”

**[Website](https://www.virtuals.io/)**

## Standards & Protocols

Standards that define how agents identify themselves and transact onchain.

### x402 — HTTP Payments

Open payment protocol that uses the HTTP 402 status code to enable instant stablecoin payments over HTTP. Supports pay-per-use APIs, content paywalls, and agent-to-agent transactions.

**[Docs](https://docs.cdp.coinbase.com/x402)**

### ERC-8004 — Agent Identity

Standard for registering and verifying agent identity onchain. Enables agents to build verifiable reputation.

**[Website](https://www.8004.org/)**

### ERC-8128 — Wallet-based Authentication

Extension of RFC 9421 HTTP Message Signatures for Ethereum wallets. Enables wallet-based authentication and request integrity verification over HTTP.

**[Website](https://erc8128.org)**
**[GitHub](https://github.com/slice-so/erc8128)**
**[npm](https://www.npmjs.com/package/@slicekit/erc8128)**
**[llms.txt](https://erc8128.slice.so/llms.txt)**

## MCP Servers

Connect your agent to Ethereum blockchain data.

### eth-mcp

MCP server for building and deploying applications in the Ethereum ecosystem.

**[Website](https://eth-mcp.com/)**
**[GitHub](https://github.com/austintgriffith/eth-mcp)**

### ENS MCP Server

Resolve names, reverse-lookup addresses, check availability, and retrieve ENS records.

**[GitHub](https://github.com/justaname-id/ens-mcp-server)**
**[npm](https://www.npmjs.com/package/mcp-server-ens)**

### Blockscout MCP Server

Access blockchain data — balances, tokens, NFTs, and contract metadata.

**[Website](https://www.blockscout.com)**
**[GitHub](https://github.com/blockscout/mcp-server)**

### MCP Etherscan Server

Check balances, view transactions, track ERC20 transfers, fetch contract ABIs, monitor gas prices, and resolve ENS names.

**[GitHub](https://github.com/crazyrabbitLTC/mcp-etherscan-server)**

### QuickNode MCP Server

Access QuickNode's blockchain infrastructure — RPC endpoints, indexing, and streaming — from your AI assistant.

**[Website](https://quicknode.com/)**
**[GitHub](https://github.com/quiknode-labs/qn-mcp)**
**[npm](https://www.npmjs.com/package/@quicknode/mcp)**
**[X](https://x.com/quicknode)**

## Developer Tools

Skills and tools to enhance your agent's Ethereum knowledge.

### Ethskills

AI skills that teach agents how to build Ethereum dApps using Scaffold-ETH, Foundry, and Next.js.

**[Website](https://ethskills.com/)**
**[GitHub](https://github.com/austintgriffith/ethskills)**

### Trail of Bits Security Skills Marketplace

A Claude Code plugin marketplace from Trail of Bits providing skills to enhance AI-assisted security analysis, testing, and development workflows.

**[GitHub](https://github.com/trailofbits/skills)**

### Ethereum Wingman

An AI skill that teaches agents how to build Ethereum dApps through SpeedRun Ethereum challenges, Scaffold-ETH 2 tooling, and security best practices. Works with Claude Code, Cursor, Codex, and other AI coding agents.

**[Website](https://ethwingman.com/)**
**[GitHub](https://github.com/austintgriffith/ethereum-wingman)**

## Directories

Discover other onchain agents.

### 8004scan

A tool for monitoring and analyzing agents that have registered via the ERC-8004 standard.

**[8004scan Agents](https://www.8004scan.io/agents)**

### Virtuals Protocol

Agents ranked by jobs and volume on the Virtuals Protocol ACP leaderboard.

**[Virtuals Protocol Top Agents](https://app.virtuals.io/acp/scan/agents)**

## Agent Examples

Real agents built on Ethereum.

### @clawdbotATG

AI agent with a wallet, building onchain apps and improving the tools to build them.

**[Website](https://clawdbotatg.eth.link/)**
**[GitHub](https://github.com/clawdbotatg)**
**[X](https://x.com/clawdbotatg)**

## Official Resources

- [Ethereum Website](https://www.ethereum.org/)
- [Ethereum Foundation](https://ethereum.foundation/)
- [Ethereum GitHub](https://github.com/ethereum/)

# Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
