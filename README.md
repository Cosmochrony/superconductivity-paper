This repository contains the source of the **Structural Superconductivity**
paper  
*A Unified Real-Space Frustration Mechanism for Superconductivity*
(paper G).

This work presents a **theoretical study** of superconductivity based on a
real-space geometric mechanism.

Rather than introducing a material-specific pairing interaction as the primary principle, the framework identifies
superconductivity with the stabilization and phase locking of a topological composite class that can be realized through
different microscopic channels.
In conventional superconductors this stabilization is mediated by phonons, consistent with BCS theory, while in strongly
correlated systems it arises from frustration minimization in real space.

The analysis applies to both conventional and strongly correlated materials,
providing a unified structural description of pairing symmetry selection,
phase stiffness scaling, and critical temperature trends.

## Scope and Motivation

Superconductivity exhibits distinct phenomenology across material families:

- conventional superconductors with mediator-assisted pairing
- cuprates with robust $d_{x^2-y^2}$ symmetry and pseudogap behavior
- nickelates with reduced magnetic frustration and emerging $s^{\pm}$ symmetry

These regimes are typically modeled using distinct microscopic mechanisms.

This work investigates whether pairing symmetry and phase coherence can instead
be understood as consequences of a **real-space frustration minimization
principle**, independent of a specific interaction kernel.

## Structural Framework

The framework is intentionally constraint-based rather than interaction-based.

- superconductivity is associated with formation of stable $w=2$ composites
- global phase coherence emerges from projective phase locking
- symmetry selection follows from minimization of a lattice-constrained
  raccordement cost functional
- the dominant frustration wavevector determines the sign structure of the gap

No explicit microscopic Hamiltonian is derived in this work.
Instead, symmetry and scaling constraints are analyzed directly.

## Conventional Regime

In conventional superconductors:

- composite stabilization is mediator-assisted
- the framework reproduces London electrodynamics
- Ginzburg–Landau structure emerges at long wavelengths
- amplitude and phase scales remain tightly coupled

The formalism reduces consistently to standard phenomenology in this limit.

## Strongly Correlated Regime

In cuprates and related systems:

- pairing emerges from reduction of staggered $(\pi,\pi)$ frustration
- amplitude and phase scales separate naturally
- pseudogap behavior is interpreted as local composite formation
  without global phase locking
- $d_{x^2-y^2}$ symmetry follows from geometric minimization under $D_{4h}$

The symmetry selection does not depend on the detailed functional form of the
frustration response function.

## Nickelates and Symmetry Shift

In infinite-layer nickelates:

- magnetic frustration is reduced and partially isotropized
- the framework predicts extended $s^{\pm}$ symmetry
- intermediate sensitivity to non-magnetic disorder is expected
- the shift from $B_{1g}$ to $A_{1g}^{\pm}$ symmetry follows from the same
  minimization principle

The treatment uses an effective frustration ratio rather than a full
multi-band resolution.
Quantitative multi-sheet gap structure is deferred to future work.

## Critical Temperature Scaling

To leading order, the critical temperature scales as:

Tc proportional to (π/2) × delta × J × f(rF)

where:

- delta is the carrier concentration
- J is the magnetic exchange scale
- rF is a measurable frustration amplitude
- f(rF) encodes the monotonic response of phase stiffness to frustration

The scaling is calibrated on LSCO and applied to nickelates using independently
measured RIXS and neutron scattering data.
Predicted Tc ranges overlap experimental values without adjustable parameters.

## Predictions and Falsifiability

The framework yields experimentally testable predictions:

- symmetry selection determined by dominant frustration channel
- disorder sensitivity distinguishing d-wave and s± regimes
- phase stiffness scaling with delta × J
- pressure dependence constrained by J(P) × rF(P)

If these relations are violated by independent measurements,
the mechanism is falsified.

## Relation to Companion Papers

This work is part of a broader research program.

- bounded-response dynamics are developed in paper C
- projection-based structural arguments appear in papers A and B
- phenomenological cosmological implications are explored in paper D

The present paper is focused exclusively on superconductivity
and does not rely on cosmological or gravitational assumptions.

## Repository Contents

```
paper/
├── pdf/ # Compiled article PDF (PRB format)
├── tex/ # LaTeX sources (revtex4-2)
├── figures/ # Figures and diagrams
└── README.md
```

## Links

- 📄 Paper PDF: (to be added)
- 💻 GitHub organization: https://github.com/Cosmochrony

## Citation

If you reference this work, please cite:

> J. Beau, *A Unified Real-Space Frustration Mechanism for Superconductivity*, preprint, 2026.

## Acknowledgements

Portions of editorial refinement and structural consistency checking
benefited from iterative interactions with large language models,
used strictly as analytical assistants.
All scientific interpretations, derivations, and conclusions
remain the sole responsibility of the author.

## Contributions

This repository is intended as a research reference.

Independent theoretical analysis, numerical testing,
and experimental verification are strongly encouraged.
Please open an issue to discuss limitations,
alternative interpretations, or possible extensions.
