# Metatron Dynamics

**Domain-declaration and relational-field detection for complex operational systems.**

Metatron Dynamics has identified the primitive that mathematics derives from observation: **a directed relation declared from observable information**. Objects are read from relations, not the reverse. Alongside it, three variables are present in every observation: **energy** (how much a relation changes), **connection** (how much holds together as it changes), and **freedom** (how many independent ways it varies). Their absence is never observed; what varies, and what we measure, is their degree at a declared resolution. The ABR kernel expresses them as tunneling, entanglement, and superposition, and requires every result to trace back to a declared observable relation.

→ [Metatron Dynamics](https://relationalrelativity.dev) &nbsp;·&nbsp; arXiv:2601.22389 &nbsp;·&nbsp; *Robin Macomber, Founder*

---

## The Kernel — [abr-kernel](https://github.com/Relational-Relativity-Corporation/abr-kernel) · Kernel V9

The canonical declaration of the ABR/ABRCE kernel: operator constraints, role separation protocol, reference implementation in Rust, derived invariants, validation record, and provenance discipline.

**The foundational primitive is a directed relation declared from observable information.** A numerical value is not itself a primitive; it is the projection of an observed relational distinction through a declared measurement mapping M.

```
Observable relation → M → projection in D → declared topology → operators → result → comparison with observables

Primary kernel:   E_primary = Σ(Δ(x))
ABR kernel:       E = R(B(A(x)), ρ(A(x)))        A → B → R
Persistence:      A_p → B_p → R_p  over a declared pair of sequential observations

D := { x ∈ ℝⁿ | n < ∞  and  |x[i]| < ∞  ∀ i }
All framework claims are bounded over D. No claim beyond D.
```

The operators are domain and scale invariant: they produce the same classes of output (ε[e], τ[v], Φ[v], 𝟙[e], θ[e], J[v]) at every declared region from Primary through Planetary. What changes across regions is the declared measurement mapping M, not the operators.

**Relational Primitive Provenance Invariant (RPPI).** Every admitted value, operation, and result must have a continuous, verifiable provenance path to an Origin-declared observable relation. The kernel separates the *provenance label*, the *declaration record*, and the *calculation record*. A result is admissible only when an independent reconstruction can follow its derivation back to declared observables.

### Current status

| | |
|---|---|
| Package | `abr-kernel` **9.0.0** (crate `abr_kernel`), Rust, no external dependencies, Apache-2.0 |
| Operators | Formulas and public API unchanged from the frozen V8 implementation |
| RPPI milestones 1–3 | Specification, conformance suite, and declaration/calculation record distinction, all accepted by the Verifier |
| Bounded admission interface | `provenance.rs`, `provenanced_exec.rs`, `admission.rs`. The four RPPI failure modes (missing, fabricated, disconnected, misattributed) are enforced within the supported scope |
| Diagnostic execution | `diagnostic_exec.rs` runs A → B → R and persistence over experimental fields, keeping observed and proposed relations distinct |
| Tests | 126 passing: 61 library, 35 V9 conformance, 12 admission, 13 diagnostic execution, 3 demo, 2 doctests |
| Still open | ABR and persistence admission, other Layer 3 quantities, other M kinds, independent IRRS verification from a distinct frame |

```
git clone https://github.com/Relational-Relativity-Corporation/abr-kernel.git
cd abr-kernel && cargo test
```

Start with [`docs/kernel/kernel_reference.md`](https://github.com/Relational-Relativity-Corporation/abr-kernel/blob/main/docs/kernel/kernel_reference.md).

**Kernel V10 (in development).** The rewrite declares relation as the primitive derived from observation, and energy, connection, and freedom as the ground variables every analysis reads. Most V10 items are still proposed, awaiting Origin and Verifier review.

---

## Foundational Documents

| Document | Type |
|---|---|
| [The Clarity Dividend](https://github.com/Relational-Relativity-Corporation/metatron-dynamics-framework/blob/main/docs/the-clarity-dividend.pdf) | Investor document |
| [Mathematics of Information System Stability](https://github.com/Relational-Relativity-Corporation/metatron-dynamics-framework/blob/main/docs/mathematics-of-information-system-stability.pdf) | White paper |

---

## Earlier Applied Demonstrations

These predate Kernel V9 and are archived.

| Repository | Domain | Lead time |
|---|---|---|
| [supply-chain-early-warning-demo](https://github.com/Relational-Relativity-Corporation/supply-chain-early-warning-demo) | Multi-agent supply chain simulation | **88 steps** ahead of conventional detection |
| [robotics-instability-detection-demo](https://github.com/Relational-Relativity-Corporation/robotics-instability-detection-demo) | Discrete-time multi-robot simulation | **82 steps** ahead of conventional detection |
| [relational-rate-limiter](https://github.com/Relational-Relativity-Corporation/relational-rate-limiter) | Production token bucket with zero branches and proven correctness | — |
| [bounded-update-controller](https://github.com/Relational-Relativity-Corporation/bounded-update-controller) | Bounded update operator with magnitude constraints by construction | — |
| [bounded-plasticity-simulation](https://github.com/Relational-Relativity-Corporation/bounded-plasticity-simulation) | Invariant relational magnitude constraints with provable stability regimes | — |

---

*Metatron Dynamics, Inc. All framework documentation, repositories, and demonstrations are continuous with prior work conducted under Relational Relativity LLC.*
