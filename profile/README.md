# Metatron Dynamics

**Domain-declaration and relational-field detection for complex operational systems.**

Metatron Dynamics has identified the primitive that mathematics derives from observation: **a directed relation declared from observable information**. Objects are read from relations, not the reverse. Alongside it, three variables are present in every observation: **energy** (how much a relation changes), **connection** (how much holds together as it changes), and **freedom** (how many independent ways it varies). Their absence is never observed; what varies, and what we measure, is their degree at a declared resolution. The ABR kernel expresses them as tunneling, entanglement, and superposition, and requires every result to trace back to a declared observable relation.

→ [Metatron Dynamics](https://relationalrelativity.dev) &nbsp;·&nbsp; arXiv:2601.22389 &nbsp;·&nbsp; *Robin Macomber, Founder*

---

## The Kernel — [abr-kernel](https://github.com/Relational-Relativity-Corporation/abr-kernel) · Kernel V10

The canonical declaration of the ABR kernel: operator constraints, role separation protocol, reference implementation in Rust, derived invariants, validation record, and provenance discipline.

**Relation is the primitive, derived from observation:** a directed relation declared from observable information. A numerical value is not itself a primitive; it is the projection of an observed relational distinction through a declared measurement mapping M.

**Three ground variables, one relational object.** Energy (how much a relation changes), freedom (how many independent ways relations vary) and connection (shared relational structure persisting through evolution) are distinct, and all three are read from the same object: the pattern of 2×2 minors between relations. Per minor, freedom and connection are complementary; energy moves minors toward or across zero.

**Simultaneity.** All operators and all variables occur together. The order of the operators and the sequence of observations are orders of analysis. A relational field needs at least two consecutive registrations; a single snapshot is insufficient information.

```
Observable relation → M → projection in D → declared topology → operators → result → comparison with observables

Operators:   A(x)[e] = x[s] − x[t]     B(g)[e] = g[e] + Σ_succ g     Ξ(g)[e] = Σ_succ g − Σ_pred g
Minors:      m_ij(e,f) = A[i][e]·A[j][f] − A[j][e]·A[i][f]
             held unresolved → connection   held resolved → freedom   crossing → reorganization
Energy:      ε[e] = |A(c)[e]|  for the declared carrier c

D := { x ∈ ℝⁿ | n < ∞  and  |x[i]| < ∞  ∀ i }
All framework claims are bounded over D. No claim beyond D.
```

The kernel expresses energy, freedom and connection as tunneling, superposition and entanglement. When a declared topology does not let a variable be calculated, the result is a finding about the declaration (the Primary Region, or a domain not fully declared), never a statement that the variable is absent.

**Relational Primitive Provenance Invariant (RPPI).** Every admitted value, operation, and result must have a continuous, verifiable provenance path to an Origin-declared observable relation.

### Current status

| | |
|---|---|
| Package | `abr-kernel` **10.1.0** (crate `abr_kernel`), Rust, no external dependencies, Apache-2.0 |
| V10 | Ground variables (`ground_variables.rs`), relational field (`relational_field.rs`), parameter-free circulation Ξ. The weighting parameters ρ and χ are retired from V10 |
| V9 record | V9 operators and readers unchanged and kept in place behind the `v9` Cargo feature (off by default), so V10 work uses only V10 forms (W13); every transition kept in the commit history |
| Tests | 68 passing in the default (V10) build, 153 with `--features v9`, including a clean-room build; synthetic fixtures only |
| Next | Invariant tests against registered data (structural consistency, I-SC) |

```
git clone https://github.com/Relational-Relativity-Corporation/abr-kernel.git
cd abr-kernel && cargo test
```

Start with [`docs/kernel/V10_README.md`](https://github.com/Relational-Relativity-Corporation/abr-kernel/blob/main/docs/kernel/V10_README.md) and [`docs/kernel/kernel_reference.md`](https://github.com/Relational-Relativity-Corporation/abr-kernel/blob/main/docs/kernel/kernel_reference.md).

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
