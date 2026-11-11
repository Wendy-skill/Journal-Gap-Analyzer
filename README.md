# Journal Gap Analyzer

A research-paper Skill designed to answer one practical question:

> **How far is this manuscript from the current pattern of the target journal?**

It does this by building a benchmark from comparable recent papers, then comparing the manuscript on the same dimensions.

## Core idea

```text
target-journal papers
→ Journal Benchmark
→ manuscript profile
→ gap analysis
→ relative fit
→ Top Gaps
→ Closest Fixes
```

## What it compares

- scope fit
- novelty framing
- methodological evidence
- results depth
- discussion depth
- literature positioning
- claim calibration
- reproducibility
- visual / quantitative communication
- journal writing architecture

## Key output

Example:

```text
Relative Journal Fit: 72/100
Fit band: Moderate–High
Benchmark confidence: Medium

Largest gaps:
1. Discussion depth
2. Literature positioning
3. Novelty framing
```

The score is **not an acceptance probability**.

A `72/100` score does not mean a 72% chance of acceptance. It only describes relative alignment with the benchmark built from the sampled papers.

## Closest Fixes

The Skill ranks revisions by both effort and likely alignment gain.

Example:

| Fix | Effort | Expected alignment gain |
|---|---|---|
| Add quantitative validation errors | Low | High |
| Expand mechanism + literature comparison | Medium | High |
| Add a new sensitivity case | High | Medium |

It prioritises fixes that can be made from existing data before recommending new experiments or simulations.

## No-Change Zone

The Skill also identifies areas already aligned with the journal benchmark so the author does not rewrite strong sections unnecessarily.

## Benchmark design

Preferred benchmark:
- 5–10 recent papers;
- same journal;
- same article type;
- similar research area;
- similar methodology where possible.

A smaller sample can still be used, but confidence is reduced.

## Recommended use

```text
Use $journal-gap-analyzer to compare this manuscript with these recent papers from the target journal.

Build the Journal Benchmark first.
Then identify the largest gaps and highest-leverage fixes.
Do not interpret the fit score as acceptance probability.
```

Created by **Wendy.z**.

## Copyright & Licence

Author / Copyright holder: **wendy.z** ([GitHub: Wendy-skill](https://github.com/Wendy-skill)).

Except for material carrying a separate notice, original material by wendy.z in this repository is licensed under the Apache License, Version 2.0. Commercial use, modification, and redistribution are permitted subject to its terms, including retaining applicable copyright, license, and NOTICE notices and marking modified files. Apache-2.0 does not grant trademark or endorsement rights. See [LICENSE](LICENSE) and [NOTICE](NOTICE). The citation metadata is in [CITATION.cff](CITATION.cff).

