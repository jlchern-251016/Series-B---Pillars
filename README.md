# Series B — Six Pillars of Modern Optical Engineering

**Explorer and Builder:** Jyh-Long Chern  
**Part of:** [Open-Source Engineering Optics Series](https://github.com/jlchern-251016)  
**Status:** All six technical reports complete (v1)

---

## What Is Series B?

Series B establishes the **theoretical framework** for modern optical engineering, organized around six pillars. Each pillar generates independent content with its own conservation laws, design rules, bridge equations, and worked examples. Together they provide the analytical machinery to identify, understand, and extend beyond the boundaries of classical simulation tools — Code V, RSoft, LightTools — from ray optics through wave optics to quantum photonics.

> Every photon in an engineered system follows three stages: it propagates, it is detected, and its energy is managed. Yet we still treat these as separate disciplines. This series tries to unify them.

---

## The Six Pillars

| # | Document | Title (Short) | Key Theme | Central Object | Version |
|---|----------|--------------|-----------|---------------|---------|
| B1 | `B1_OAC` | Optics After Continuity | Singularities | Configuration entropy S | v35 |
| B2 | `B2_AOE` | Algorithms for Optical Engineering | Algorithms | Co-design merit function | v7 |
| B3 | `B3_IOE` | Invariants in Optical Engineering | Invariants | Symplectic condition M^T J M = J | v18 |
| B4 | `B4_CE` | Coherence and Entanglement | Coherence & Entanglement | Concurrence C, Schmidt number K | v8 |
| B5 | `B5_CS` | Complexity Spectrum | Complexity | Brody beta, fidelity F | v58 |
| B6 | `B6_POE` | Path Integral in Optical Engineering | Path Integral | Propagator K, influence functional | v8 |

---



## Relationship to Other Series

```
Series A (Textbooks-level) ← synthesizes → Series B (Theory, this repo)
Series C (Toolkits)  ← implements  → Series B
Series D (Examples)  ← validates   → Series C using Series B
```

- **Series A** depends on B (textbooks synthesize theory)
- **Series C** implements B (toolkits translate theory into callable code)
- **Series D** validates C using B (worked examples exercise toolkits against theory)

---


*Series B — Six Pillars of Modern Optical Engineering*  
*Explorer and Builder: Jyh-Long Chern*  
*Last updated: March 2026*
