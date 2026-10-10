# ZenSation AI

**An independent research lab in Kiel, Germany. We research collective intelligence on cognitive architecture — humans and machines together, on a structure that retains knowledge.**

Every number on this page is backed by a public record, a passing test suite, or a reproducible build. Nothing here asks to be believed.

## What we have shown

- In a controlled, same-budget benchmark judged by independent LLM judges, **three of nine head-to-head comparisons hold** for ZenBrain against Letta, Mem0 and A-Mem — all three against A-Mem, the remaining six are ties, none lost (3 competitors × 3 judges, Bonferroni-corrected, version-matched) — and the paper also prints where it loses: retrieval-proper metrics to a competing system, an aggregate-F1 metric to lexical search.
- The memory library is **extracted from a production platform** (440K+ LOC, 12,000+ tests as of August 2026) — not a research toy. Releases are built in public CI, and the current version of every package is published to npm with build provenance, so it traces back to its commit.
- The research trail is fully public: **open records** with DOIs, an arXiv preprint, and defensive publications establishing prior art.

## Use it

### 🧠 [ZenBrain](https://github.com/zensation-ai/zenbrain) — dynamic agent memory

7 layers, FSRS spaced repetition, Hebbian learning, emotional tagging, sleep consolidation. Pure TypeScript, zero dependencies, tested in CI on Node 22, 24 and 26.

```bash
npm install @zensation/algorithms
```

- **[Try it in your browser](https://zensation.ai/en/playground?utm_source=github&utm_medium=profil&utm_campaign=evergreen)** — runs the published code, no install.
- Packages: [`@zensation/algorithms`](https://www.npmjs.com/package/@zensation/algorithms) · [`@zensation/core`](https://www.npmjs.com/package/@zensation/core) · [`@zensation/adapter-postgres`](https://www.npmjs.com/package/@zensation/adapter-postgres) · [`@zensation/adapter-sqlite`](https://www.npmjs.com/package/@zensation/adapter-sqlite)
- Drop it into what you already use: [`@zensation/mcp`](https://www.npmjs.com/package/@zensation/mcp) gives any Model Context Protocol client the seven layers as four tools; [`@zensation/ai-sdk`](https://www.npmjs.com/package/@zensation/ai-sdk) is Vercel AI SDK middleware that recalls before the model call and stores the turn after it.
- New here? Pick a [good first issue](https://github.com/zensation-ai/zenbrain/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) or ask in [Discussions](https://github.com/zensation-ai/zenbrain/discussions).

### 🗳️ [voteworth](https://github.com/zensation-ai/voteworth) — the effective number of independent votes in an LLM judge panel

Measure error correlation in an LLM judge panel or voter ensemble, report the effective number of independent votes, and correct the majority vote for correlated voters — including the panel shape where it cannot. Closed-form, label-free, numpy only.

```bash
pip install git+https://github.com/zensation-ai/voteworth
```

### 🤖 [ZenAI](https://github.com/zensation-ai/zenai) — the platform it came from

The self-hosted AI OS ZenBrain was extracted from: 60 AI tools, multi-agent system, knowledge graph, real-time voice. Published as a frozen, readable snapshot (8 May 2026). Its terminal agent [`@zensation/cli`](https://www.npmjs.com/package/@zensation/cli) is retired and deprecated on npm since 1 October 2026; the maintained memory tooling is [`@zensation/mcp`](https://www.npmjs.com/package/@zensation/mcp).

## Check it

- **Preprint:** [arXiv:2604.23878](https://arxiv.org/abs/2604.23878) — *ZenBrain: A Neuroscience-Inspired 7-Layer Memory Architecture for Autonomous AI Systems*
- **Corpus:** [**Open records**](https://zensation.ai/en/publikationen?utm_source=github&utm_medium=profil&utm_campaign=evergreen) on Zenodo — preprints, software / reproduction packages, datasets and notes, every preprint under CC BY 4.0, each with its own version and concept DOI
- **Author ID:** [ORCID 0009-0001-1793-012X](https://orcid.org/0009-0001-1793-012X)
- **Prior art:** defensive publications on [Technical Disclosure Commons](https://www.tdcommons.org)
- Benchmarks are reported with the protocol, the effect sizes and the cases where the system loses — including the metric on which a competing system wins.

## Work with us

- Library questions → [GitHub Discussions](https://github.com/zensation-ai/zenbrain/discussions)
- Research, replication, consortium inquiries → research@zensation.ai
- Everything else → open-source@zensation.ai · [zensation.ai](https://zensation.ai/?utm_source=github&utm_medium=profil&utm_campaign=evergreen)

---

**Company:** [ZenSation Enterprise Solutions](https://zensation.ai/?utm_source=github&utm_medium=profil&utm_campaign=evergreen) · Kiel, Germany · **Code:** Apache 2.0 · **Records:** CC BY 4.0 / Apache 2.0
