# Series B — Six Pillars of Modern Optical Engineering

**Author:** Jyh-Long Chern  
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

## Six Bridge Equations

The pillars are connected by six cross-pillar bridge equations:

| # | Bridge Equation | Pillars | Source |
|---|----------------|---------|--------|
| 1 | M^T J M = J (symplectic) | B3 | Hamiltonian |
| 2 | S = F (Strehl = Fidelity) | B3 ↔ B4 | Both |
| 3 | C ~ C_0 exp(-2 S_mod) | B4 ↔ B5 | Hamiltonian |
| 4 | Gutzwiller trace formula | B5 ↔ B3 | Path integral |
| 5 | Influence functional: gamma = pi J(omega) | B5 ↔ B4 | Path integral |
| 6 | Maslov: phase shift = -pi mu / 2 | B1 ↔ B3 | Path integral |

---

## Nine Design Rules

| DR# | Pillar | Scope |
|-----|--------|-------|
| DR1–DR3 | B1 / B3 | Singularity & invariant: entropy binning, N-split manufacturing, etendue feasibility |
| DR4–DR6 | B4 | Coherence & entanglement: cooperativity gate, coherence budget, component substitution |
| DR7–DR9 | B5 | Complexity: chaos-regime identification, operator card, fidelity threshold |

---

## Relationship to Other Series

```
Series A (Textbooks) ← synthesizes → Series B (Theory, this repo)
Series C (Toolkits)  ← implements  → Series B
Series D (Examples)  ← validates   → Series C using Series B
```

- **Series A** depends on B (textbooks synthesize theory)
- **Series C** implements B (toolkits translate theory into callable code)
- **Series D** validates C using B (worked examples exercise toolkits against theory)

---

## How to Read

- **Practitioners:** Start with B3 (invariants — feasibility gates, design ceilings) and B2 (algorithms — optimization strategies).
- **Researchers:** Start with B1 (singularities) and B5 (complexity), then B6 (path integral).
- **Quantum photonics engineers:** Start with B4 (coherence & entanglement), then B6.
- **Everyone:** The bridge equations (Table above) are the connective tissue.

---

## Repository Structure

```
series-B/
├── B1_OAC_v35.pdf               # Optics After Continuity
├── B2_AOE_v7.pdf                 # Algorithms for Optical Engineering
├── B3_IOE_v18.pdf                # Invariants in Optical Engineering
├── B4_CE_v8.pdf                  # Coherence and Entanglement
├── B5_CS_v58.pdf                 # Complexity Spectrum
├── B6_POE_v8.pdf                 # Path Integral in Optical Engineering
├── series-summary-v3.md          # Master architecture document
└── README.md                     # This file
```

---

## Citation

If you find this work useful, please cite:

```
J.-L. Chern, "Six Pillars of Modern Optical Engineering,"
Open-Source Engineering Optics Series, Series B, v1 (2025–2026).
Available: https://github.com/jlchern-251016
```

---

## License

This work is shared for educational and research purposes. Please contact the author for commercial use.

---

*Series B — Six Pillars of Modern Optical Engineering*  
*Author: Jyh-Long Chern*  
*Last updated: March 2026*
