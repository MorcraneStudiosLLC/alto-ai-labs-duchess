# ALTO AI Labs — Duchess Program

**Process intelligence research by Morcrane Studios LLC**

ALTO AI Labs is the research program behind **Duchess**, a purpose-built AI system focused on process structure, evidence, routing, governed execution, and developmental intelligence.

This public evidence package makes ALTO's measured research results available for technical review. Duchess source code, model weights, private training data, sealed evaluation gold, internal prompts, and proprietary orchestration are protected intellectual property; see the repository's rights notice.

## Duchess vs GPT-5.5 — preserved 24-record comparison

The preserved P1.2B calibration lane scored multiple Duchess candidates and GPT-5.5 against the same 24-record structural task and deterministic scorer.

| System | Total | Route cell | Route block | S exact | Y exact |
|---|---:|---:|---:|---:|---:|
| **Duchess v1.3** | **49 / 96 — 51.04%** | **18 / 24** | **18 / 24** | **7 / 24** | **6 / 24** |
| **Duchess P1.2** | **49 / 96 — 51.04%** | **18 / 24** | **17 / 24** | **8 / 24** | **6 / 24** |
| **GPT-5.5** | **30 / 96 — 31.25%** | **8 / 24** | **8 / 24** | **7 / 24** | **7 / 24** |

**Duchess v1.3 led by 19.79 percentage points overall**, earning **36 / 48 routing points** versus **16 / 48 for GPT-5.5**. Exact S/Y results were **13 / 48** and **14 / 48**, respectively. The observed performance lead was driven by routing accuracy.

[Read the benchmark record](docs/duchess-p1.2-benchmark.md)  
[Read the v1.3 comparison/status record](docs/duchess-v1.3-status.md)

## Current Duchess v1.3 research status

The same v1.3 line also has later internal training/evaluation records. Verified trained-candidate manifest metrics include:

- validation exact fields: **25 / 48 — 52.08%**
- test exact fields: **26 / 48 — 54.17%**
- test route cell/block exact: **0.8333**
- validation structure gate: **pending qualification** (recorded result: not passed)
- lifecycle status: **research candidate; promotion and deployment remain separate decisions**

Those later candidate metrics are a separate evaluation track from the preserved 24-record GPT-5.5 comparison.

## What Duchess is for

ALTO's research thesis is that purpose-built intelligence can achieve exceptional capability in a defined vocation by learning to understand and operate on process:

**initiate → plan → execute → monitor/control → close**

The long-term objective is frontier-level capability within Duchess's intended process-intelligence purpose.

## Research lineage

The Duchess research line includes locally trained checkpoints based on a **Qwen3.5-0.8B** architecture. Full trained checkpoint files in the private research environment are approximately **1.5 GB** each.

Checkpoint lineage and benchmark execution identity remain separately versioned evidence tracks unless a specific run manifest links them.

## Research history

The work grew out of CL1.0 / PGM research into governed, specialized AI cells and deterministic process control.

Public background:
- Morcrane Studios: https://morcranestudios.com/
- Research updates: https://morcranestudios.com/updates/
- EchoMatch article: https://morcranestudios.com/uncategorized/echomatch-how-cl1-0-turns-vector-similarity-into-governed-intelligence/
- CL1.0 PGM milestone: https://www.linkedin.com/pulse/cl10-milestone-block-1-pgm-platform-species-runtime-tested-sheckler-p9wfc/
- Duchess vs GPT-5.5 article: https://morcranestudios.com/uncategorized/duchess-vs-gpt-5-5/
- Hacker News discussion: https://news.ycombinator.com/item?id=50287296

## Repository policy

This evidence package is public-facing research documentation, not a software distribution.

See [LICENSE-NOTICE.md](LICENSE-NOTICE.md) and [PUBLICATION_BOUNDARY.md](PUBLICATION_BOUNDARY.md).
