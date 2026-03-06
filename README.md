# awesome-onchain-agents

A curated list of resources for building AI agents on Ethereum. For Ethereum-specific skills and knowledge, see [Ethskills](https://ethskills.com/).

## Contents

1. [Frameworks](#frameworks)
2. [Standards & Protocols](#standards--protocols)
3. [MCP Servers](#mcp-servers)
4. [Agent Skills](#agent-skills)
5. [Developer Tools](#developer-tools)
6. [Directories](#directories)
7. [Agent Examples](#agent-examples)
8. [Official Resources](#official-resources)

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

## Deployment Setup Guides

### Mac Mini
Zero to one setup on a mini mac [guide](https://x.com/austingriffith/status/2021968127639409137).

### AWS
Setup on AWS free tier [guide](https://x.com/techfrenAJ/status/2014934471095812547). 

### Coral
No code one-click deployment on Coral [guide](https://docs.coral.inc/getting-started/quickstart).

## Standards & Protocols

Standards that define how agents identify themselves and transact onchain.

### x402 — HTTP Payments

Open payment protocol that uses the HTTP 402 status code to enable instant stablecoin payments over HTTP. Supports pay-per-use APIs, content paywalls, and agent-to-agent transactions.

**[Docs](https://docs.cdp.coinbase.com/x402)**

### ERC-8004 — Agent Identity

Standard for registering and verifying agent identity onchain. Enables agents to build verifiable reputation.

**[Website](https://www.8004.org/)**

### ERC-7710 — Delegated Permissions

Standard for scoped, revocable delegation of onchain authority. Enables agents to act with bounded permissions — spending caps, time limits, token whitelists — enforced by caveat smart contracts. Supports composable permission chains for agent-to-agent delegation.

**[EIP](https://eips.ethereum.org/EIPS/eip-7710)**
**[GitHub](https://github.com/MetaMask/delegation-framework)**

### ERC-8128 — Wallet-based Authentication

Extension of RFC 9421 HTTP Message Signatures for Ethereum wallets. Enables wallet-based authentication and request integrity verification over HTTP.

**[Website](https://erc8128.org)**
**[Docs](https://erc8128.slice.so)**
**[GitHub](https://github.com/slice-so/erc8128)**
**[npm](https://www.npmjs.com/package/@slicekit/erc8128)**
**[llms.txt](https://erc8128.slice.so/llms.txt)**

### SIWA — Sign In With Agent

Authentication protocol built on ERC-8004 and ERC-8128 that provides trustless identity and authentication for AI agents.

**[Website](https://siwa.id)**
**[Docs](https://siwa.id/docs)**
**[GitHub](https://github.com/builders-garden/siwa)**
**[npm](https://www.npmjs.com/package/@buildersgarden/siwa)**

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

### Herd MCP Server

Research and due diligence across complex contracts, transactions, and wallets. The missing "web search" tool for crypto.

**[Docs and Installation](https://docs.herd.eco/herd-mcp/introduction)**
**[Article and Examples](https://x.com/andrewhong5297/status/2025973649212088721)**
**[Herd Explorer](http://herd.eco/)**

### Slither MCP Server

MCP server wrapping Slither static analysis for Solidity smart contracts. Query contract metadata, functions, inheritance, call graphs, and run security detectors. Works with Foundry and Hardhat projects.

**[GitHub](https://github.com/trailofbits/slither-mcp)**

### Zerion API MCP Server

Real-time crypto data via Zerion's API — portfolio, transactions, PnL, DeFi positions, token prices, NFTs, and gas prices. Connect via URL: `https://developers.zerion.io/mcp`.

**[Website](https://developers.zerion.io/reference/building-with-ai)**

### AgentHub by Allium

Onchain data across 150+ chains in one prompt — token prices, wallet balances, and transaction history. Works with Claude, ChatGPT, and agent frameworks.

**[Website](https://agents.allium.so/)**

### Ethereum MCP

153 tools across Etherscan, DefiLlama, CoinGecko, growthepie, Blobscan, and Dune — balances, TVL, yields, prices, 60+ chains. Built for researchers.

**[GitHub](https://github.com/ETHCF/ethereum-mcp)**

## Agent Skills

Skills and plugins for Ethereum development and security.

### Ethskills

AI skills that teach agents how to build Ethereum dApps using Scaffold-ETH, Foundry, and Next.js.

**[Website](https://ethskills.com/)**
**[GitHub](https://github.com/austintgriffith/ethskills)**

### Trail of Bits Security Skills Marketplace

A Claude Code plugin marketplace from Trail of Bits providing skills to enhance AI-assisted security analysis, testing, and development workflows.

**[GitHub](https://github.com/trailofbits/skills)**

### Uniswap AI

Reusable skills, plugins, and agents for building on Uniswap with coding assistants.

**[Website](https://developers.uniswap.org/)**
**[GitHub](https://github.com/uniswap/uniswap-ai)**

### Pashov Audit Group Smart Contract Security Skills

Fast security feedback on Solidity changes while you develop. Works with Claude Code CLI, VS Code Claude extension, and Cursor.

**[GitHub](https://github.com/pashov/skills)**

### Cyfrin solskill

Solidity development standards for production-grade code — thorough on testing, code quality, and smart contract sensitivity. Install via Cyfrin marketplace.

**[GitHub](https://github.com/Cyfrin/solskill)**

### HackenProof Triage Skill

Reusable triage skill for HackenProof bug bounty report handling. Verifies commit/version scope, checks duplicates, and validates submissions to decide state, severity, and comments.

**[GitHub](https://github.com/hackenproof-public/skills)**

## Developer Tools

Skills and tools to enhance your agent's Ethereum knowledge.

### Ampersend

Management platform and SDK for agent payments. Built on **x402**, **A2A**, and **MCP**, it lets agents make and receive onchain stablecoin payments with spending limits, auto top-ups, seller allowlists, and real-time monitoring on Base.

**[Website](https://ampersend.ai)**
**[Docs](https://docs.ampersend.io)**
**[GitHub](https://github.com/edgeandnode/ampersend)**

### Self

Privacy-preserving identity verification protocol using zero-knowledge proofs. Allows agents to cryptographically prove they are acting on behalf of a verified human using zk-proofs derived from government-issued IDs, without exposing personal data.

**[Website](https://self.xyz/)**
**[Docs](https://docs.self.xyz/)**
**[GitHub](https://github.com/selfxyz/self)**
**[Developer Tools](https://tools.self.xyz/)**


### Faremeter

A collection of open-source libraries, tools, and applications designed to allow agents and other utilities to transparently make web3 payments using web2 infrastructure. It is a composable, unopinionated, standards-agnostic framework designed to enable machine payments and agent-to-agent communications with any system.

**[Docs](https://docs.faremeter.xyz/)**

### AI Agent Guardrails

Open-source safety patterns and guardrails for AI agents that handle financial transactions. Framework-agnostic TypeScript templates covering prompt injection prevention, operation validation, identity verification, rate limiting, hallucination prevention, and platform-specific safety. Production-tested across 24+ EVM and Solana chains. Includes an OpenClaw skill file and llms.txt for agent consumption.

**[GitHub](https://github.com/azep-ninja/ai-agent-guardrails)**
**[OpenClaw Skill](https://github.com/azep-ninja/ai-agent-guardrails/blob/main/SKILL.md)**
**[llms.txt](https://github.com/azep-ninja/ai-agent-guardrails/blob/main/llms.txt)**

### Bankr

Agent wallet infrastructure and token launch platform on Base. Provides AI agents with a programmable EVM wallet, social-media-native payments via @bankrbot on X, and a Partner Deploy API for programmatically launching tokens on behalf of users. Partners earn a share of ongoing trading fees from tokens they deploy.

**[Website](https://bankr.bot)**
**[Docs](https://docs.bankr.bot)**
**[X](https://x.com/bankrbot)**

## Directories

Discover other onchain agents.

### 8004scan

A tool for monitoring and analyzing agents that have registered via the ERC-8004 standard.

**[8004scan Agents](https://www.8004scan.io/agents)**

### Virtuals Protocol

Agents ranked by jobs and volume on the Virtuals Protocol ACP leaderboard.

**[Virtuals Protocol Top Agents](https://app.virtuals.io/acp/scan/agents)**

### MoltLaunch

Onchain agent marketplace — hire AI agents with verified reputation, identity, and task history. Agents register with token-backed identity, receive work requests, and get paid through escrowed transactions.

**[Website](https://moltlaunch.com/)**

### Registry Broker

Universal Babel layer to discover and talk to any agent across ecosystems and protocols, including onchain registries like ERC-8004.

**[Docs](https://hol.org/registry/docs)**

## Agent Examples

Real agents built on Ethereum.

### @clawdbotATG

AI agent with a wallet, building onchain apps and improving the tools to build them.

**[Website](https://clawdbotatg.eth.link/)**
**[GitHub](https://github.com/clawdbotatg)**
**[X](https://x.com/clawdbotatg)**

### @ClawdiaBotAI

AI agent built on OpenClaw — deploys tokens, audits contracts, and ships onchain apps autonomously. Registered on ERC-8004, holds a Bankr Club NFT, and active on Base, Farcaster, and X. Ships live projects including SpellBlock (daily commit-reveal word game denominated in $CLAWDIA) and the Anons DAO governance API (ERC-8128 authenticated).

**[Website](https://clawdiabot.eth.limo)**
**[X](https://x.com/ClawdiaBotAI)**
**[Farcaster](https://warpcast.com/clawdia)**
**[ERC-8004](https://www.8004scan.io/agents/ethereum/23606)**

### @Osobotai

AI agent specializing in ERC-7710 delegated permissions and smart accounts. Publishes The Caveat newsletter, reviews delegation framework PRs, and builds tools like the Gator Safe App for creating onchain delegations.

**[Website](https://osoknows.com)**
**[GitHub](https://github.com/osobot-ai)**
**[X](https://x.com/Osobotai)**

## Official Resources

- [Ethereum Website](https://www.ethereum.org/)
- [Ethereum Foundation](https://ethereum.foundation/)
- [Ethereum GitHub](https://github.com/ethereum/)

# Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
