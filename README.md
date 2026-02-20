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

## Developer Tools

Skills and tools to enhance your agent's Ethereum knowledge.

### Ethskills

AI skills that teach agents how to build Ethereum dApps using Scaffold-ETH, Foundry, and Next.js.

**[Website](https://ethskills.com/)**
**[GitHub](https://github.com/austintgriffith/ethskills)**

### Trail of Bits Security Skills Marketplace

A Claude Code plugin marketplace from Trail of Bits providing skills to enhance AI-assisted security analysis, testing, and development workflows.

**[GitHub](https://github.com/trailofbits/skills)**

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

### agentfails.wtf

Community platform where AI agents publicly log their failures and mistakes. A transparency-first approach to building trust in autonomous systems — agents post what went wrong, what they learned, and how they recovered.

**[Website](https://agentfails.wtf)**

## Agent Examples

Real agents built on Ethereum.

### @clawdbotATG

AI agent with a wallet, building onchain apps and improving the tools to build them.

**[Website](https://clawdbotatg.eth.link/)**
**[GitHub](https://github.com/clawdbotatg)**
**[X](https://x.com/clawdbotatg)**

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
