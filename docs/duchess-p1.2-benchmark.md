# Duchess P1.2B vs GPT-5.5 — Benchmark Record

## Result

The preserved head-to-head used **24 records** and **96 scoring points**.

| Measurement | Duchess P1.2 | GPT-5.5 |
|---|---:|---:|
| Total | **49 / 96** | **30 / 96** |
| Percentage | **51.04%** | **31.25%** |
| Routing contribution | **35** | **16** |
| Exact S/Y field matches | **14 / 48** | **14 / 48** |

**Duchess led by 19 scoring points (+19.79 percentage points)** in this head-to-head evaluation, with **35 routing points** versus **16 for GPT-5.5**.

## Task

The 24 source excerpts came from NIST cybersecurity publications: 12 existing validation records and 12 existing test records.

Each system was required to produce structured outputs under the same evaluation contract.

### Routing

The allowed route choices were:

- **KC-01 — Project Continuity**
- **KC-02 — Program Sequencing**
- **KC-01 / KC-08 / KC-24 — Governance and Architecture Control**

Route scoring evaluated the expected Knowledge Cell / Cell Block classification.

### S and Y extraction

- **S**: earliest sentence designated by the benchmark as describing a system state.
- **Y**: earliest sentence designated by the benchmark as describing an outcome/effect.

Predictions were compared with withheld reference labels using a deterministic scorer.

## What the result says

**Duchess demonstrated a substantial routing advantage** against GPT-5.5 on the measured task. Routing contributed **35 points for Duchess versus 16 for GPT-5.5**. Both systems recorded **14 / 48 exact S/Y matches**.

## Reproducibility record

The original experiment retained:

- blind question packet;
- Duchess predictions;
- GPT-5.5 predictions;
- withheld answers;
- Python scorer.


## Scope

These results report the observed performance of both systems on the same 24-record structural task using the same scoring contract.

The research question for ALTO is whether specialized process intelligence can become highly capable with materially smaller, purpose-built systems.
