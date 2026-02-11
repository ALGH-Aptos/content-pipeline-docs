# Knowledge Base

## The Data Behind the Scripts

Every script the pipeline produces is backed by a **curated knowledge base** — a structured collection of technical articles, academic research papers, and narrative source documents. This isn't a random scrape of the internet. Each piece of content was deliberately selected, organized, and indexed to give the script generation stage the depth it needs.

This page provides an overview of what's currently indexed.

---

## At a Glance

| Category | Count | Description |
|----------|-------|-------------|
| **Technical Articles** | 47 | In-depth coverage of core technology, features, and infrastructure |
| **Research Papers** | 5 | Peer-reviewed academic papers published on ArXiv |
| **Narrative Documents** | 17 | Industry context, policy remarks, and broader market framing |
| **Improvement Proposals** | 136 | Official protocol improvement proposals (AIPs) |

---

## Technical Articles (47)

The backbone of the knowledge base. These articles cover the full technology stack, organized by topic area.

### Core Consensus & Execution
Articles covering how the underlying blockchain achieves its performance characteristics — parallel execution, consensus protocols, latency reduction, and sharded scaling.

- Block-STM — Parallel execution engine (160K+ TPS)
- Quorum Store — Horizontal consensus scaling
- Shoal — DAG-based latency reduction
- Consensus Observer — Ultra low-latency sync
- Velociraptr — 40% faster block times
- Zaptos — Sub-second latency architecture
- Shardines — Sharded execution (1M+ TPS)

### MEV & Privacy
Articles on frontrunning protection and transaction privacy.

- Encrypted Mempool — Native MEV protection
- Confidential Transactions — Private balances and amounts

### Move Language & VM
Articles covering the smart contract language, its evolution, and virtual machine performance.

- Loader V2 — 2x VM performance improvement
- Move in 2025 — Language evolution roadmap
- Move Language Overview — Core concepts and design philosophy
- Lazy Loading — Composable dependency management
- Higher-Order Move — Function values and advanced patterns
- Move Security — Security guidelines and best practices

### Account & Transaction Innovations
Articles on wallet, account, and transaction model innovations.

- Stateless Accounts — Orderless transaction processing
- Account Abstraction — Flexible authentication models
- X-Chain Accounts — Cross-chain wallet support
- Keyless Accounts — Social login integration
- Event-Driven Transactions — Native on-chain automation

### Developer Features
Articles on SDKs, token standards, and developer tooling.

- Fungible Asset Standard — Modern token standard
- Dynamic Script Composer — Multi-call transaction batching
- TypeScript SDK — Developer SDK overview
- Move Objects — Object primitives and data model
- Randomness API — On-chain verifiable random function
- Transaction Simulation — Network forking for testing

### Infrastructure
Articles on system architecture, APIs, staking, and gas economics.

- Infrastructure 2025 — Technical roadmap
- APIs Overview — REST, GraphQL, gRPC interfaces
- Standards — Token and protocol standards
- Architecture Deep Dive — Full system design
- Staking Guide — Validator staking operations
- Multidimensional Gas — Gas pricing research

---

## Research Papers (5)

Peer-reviewed academic papers that provide the theoretical foundations behind the technology.

| Paper | Focus Area |
|-------|-----------|
| **Zaptos** | Minimal latency blockchain architecture |
| **Raptr** | Next-generation BFT consensus protocol |
| **Block-STM** | Parallel execution via optimistic concurrency |
| **Shoal** | DAG-based consensus optimization |
| **Narwhal-Tusk** | High-throughput mempool protocol |

---

## Narrative Documents (17)

These documents provide the broader context that gives scripts their narrative depth — industry history, policy positions, geopolitical framing, and market context.

| Category | Documents |
|----------|-----------|
| **Founding Context** | Libra Whitepaper (v1 & v2), Aptos Whitepaper, genesis and vision narratives |
| **Policy & Regulation** | Treasury Secretary remarks on stablecoins, monetary policy perspectives |
| **Industry Analysis** | Stablecoin market analysis, institutional adoption narratives, mainstream adoption timelines |
| **Geopolitical Context** | Money as a strategic instrument, financial surveillance frameworks, global currency dynamics |
| **Institutional Narratives** | Key industry players, institutional involvement, ecosystem coordination |

These documents are what allow the pipeline to produce scripts that go beyond surface-level reporting — connecting current events to deeper trends and historical context.

---

## Improvement Proposals (136 AIPs)

The complete set of official protocol improvement proposals. These track every significant change and feature addition to the protocol, providing a granular record of how the technology has evolved.

Notable proposals indexed:

| AIP | Feature |
|-----|---------|
| AIP-10 | Move Objects |
| AIP-41 | Randomness API |
| AIP-93 | Consensus Observer |
| AIP-106 | Baby Raptr |
| AIP-121 | X-Chain Accounts (Ethereum) |
| AIP-122 | X-Chain Accounts (Solana) |
| AIP-125 | Event-Driven Transactions |
| AIP-127 | Lazy Loading |
| AIP-131 | Velociraptr |

---

## How This Data Is Used

The knowledge base isn't just a static archive — it's actively queried during every script generation run. When a topic comes in, the system intelligently selects the most relevant articles, papers, and narrative documents to inform the script.

Different topic categories pull from different parts of the knowledge base. A script about regulation will draw on policy documents and institutional narratives. A script about technical performance will pull from research papers and consensus articles. This ensures every script is grounded in the right context for its subject matter.

---

<p style="text-align: center; color: gray; font-size: 0.85em;">
ALGH — Content Pipeline Automation
</p>
