# Duchess v1.3 — Research Status and GPT-5.5 Comparison

## Preserved GPT-5.5 comparison

Duchess v1.3 was included in the preserved P1.2B baseline-calibration comparison on the same 24-record structural task used for GPT-5.5.

| Metric | Duchess v1.3 | GPT-5.5 |
|---|---:|---:|
| Total score | **49 / 96 — 51.04%** | **30 / 96 — 31.25%** |
| Route cell | **18 / 24** | **8 / 24** |
| Route block | **18 / 24** | **8 / 24** |
| S exact | **7 / 24** | **7 / 24** |
| Y exact | **6 / 24** | **7 / 24** |
| Combined S/Y | **13 / 48** | **14 / 48** |
| Routing contribution | **36 / 48** | **16 / 48** |

The numbers previously summarized as **18 / 7 / 6** refer to Duchess v1.3's **18 route-cell matches, 7 exact S matches, and 6 exact Y matches**. Route-block accuracy was also **18 / 24**.

The v1.3 score advantage over GPT-5.5 on this task came from routing fidelity, not from S/Y extraction.

## Benchmark scope

The comparison used 24 excerpts from NIST cybersecurity publications and the same deterministic structural scorer. It measured expected Knowledge Cell / Cell Block routing plus exact state/outcome sentence extraction under the benchmark contract.

It is a task-specific process-structure result, not a universal model ranking.

## Later v1.3 trained-candidate evaluation

A separate v1.3 trained-candidate manifest records:

| Metric | Result |
|---|---:|
| Validation exact fields | **25 / 48 — 52.08%** |
| Test exact fields | **26 / 48 — 54.17%** |
| Test route cell/block exact | **0.8333** |

Training configuration recorded:

- base architecture: Qwen3.5-0.8B
- train records: 98
- validation records: 12
- test records: 12
- epochs: 3
- learning rate: 2e-5
- maximum sequence length: 4096
- gradient accumulation: 4

## Gate state

The later internal v1.3 evaluation crossed the test structure threshold but did **not** pass the validation structure gate.

No production deployment or trained-artifact promotion is represented by this document.

## Evidence separation

The preserved 24-record GPT-5.5 comparison and the later v1.3 trained-candidate evaluation are separate evidence tracks. Public reporting must not merge their denominators or imply that later candidate metrics were the GPT-5.5 comparison.
