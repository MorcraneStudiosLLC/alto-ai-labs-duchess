# Duchess P1.2B vs GPT-5.5 — Benchmark Record

## Result

The preserved head-to-head used **24 records** and **96 scoring points**.

| Measurement | Duchess P1.2 | GPT-5.5 |
|---|---:|---:|
| Total | **49 / 96** | **30 / 96** |
| Percentage | **51.04%** | **31.25%** |
| Routing contribution | **35** | **16** |
| Exact S/Y field matches | **14 / 48** | **14 / 48** |

Difference: **+19 points / +19.79 percentage points** for Duchess on this benchmark.

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

Duchess matched the benchmark's expected routing labels substantially more often than GPT-5.5. The two systems tied on combined exact S/Y matches, so the score advantage came from routing.

## Reproducibility record

The original experiment retained:

- blind question packet;
- Duchess predictions;
- GPT-5.5 predictions;
- withheld answers;
- Python scorer.


## Scope

This is a direct result on the defined structural task. It is not presented as a universal ranking of all AI capabilities.

The research question for ALTO is whether specialized process intelligence can become highly capable with materially smaller, purpose-built systems.
