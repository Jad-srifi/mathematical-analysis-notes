# Foundations of Real Analysis & Spectral Linear Algebra

**Author:** Mohamed Jad Srifi  
**Scope:** 25-Page Self-Directed Theoretical Mathematics Monograph  
**Deliverable:** [`real-analysis-linear-algebra.pdf`](./real-analysis-linear-algebra.pdf)

## Overview
This monograph provides an axiomatic, proof-based development of foundational Real Analysis and Linear Algebra. Designed as an independent theoretical sequence, the paper establishes the analytical machinery of metric topologies and uniform convergence before bridging into the geometry of linear operators and finite-dimensional spectral decompositions.

Every theorem and lemma is proven from first principles with full analytical rigor (no abbreviated proofs or computational heuristics).

---

## Contents Summary

### [Chapter 1: Foundations of Real Analysis (pp. 1–9)](#)
* **Axiomatic Construction of $\mathbb{R}$:** The Least Upper Bound property, Dedekind cuts vs. Cauchy completion equivalence.
* **Point-Set Topology of $\mathbb{R}^n$:** Open/closed balls, limit points, compact subspaces, and the Heine-Borel Theorem.
* **Metric Continuity & Convergence:** Strict $(\epsilon, \delta)$-limits, uniform continuity, sequential compactness, and the Bolzano-Weierstrass Theorem.

### [Chapter 2: Integration & Function Sequences (pp. 10–17)](#)
* **Generalizations of Differentiability:** Rolle's Theorem, the Cauchy Mean Value Theorem, and Taylor expansions with Lagrange remainders.
* **Riemann-Stieltjes Integration:** Darboux upper/lower sums, refinement partition lemmas, and the Lebesgue criterion for integrability (measure-zero discontinuities).
* **Function Sequences:** Pointwise vs. uniform convergence, uniform Cauchy criteria, and interchange of limits with derivatives and integrals.

### [Chapter 3: Finite-Dimensional Spectral Theory (pp. 18–25)](#)
* **Operator Spaces:** Vector spaces over $\mathbb{R}$ and $\mathbb{C}$, invariant subspaces, and the Rank-Nullity Theorem.
* **Spectral Decomposition:** Self-adjoint operators, inner product geometry, and the complete proof of the Spectral Theorem for symmetric/Hermitian matrices.
* **Singular Value Decomposition (SVD):** Orthogonal diagonalization, geometric projections, and matrix 2-norm bounds.

---

## Compilation Instructions
To build the 25-page document from the raw LaTeX sources:

```bash
git clone [https://github.com/Jad-srifi/mathematical-analysis-notes.git](https://github.com/Jad-srifi/mathematical-analysis-notes.git)
cd mathematical-analysis-notes/src
pdflatex main.tex
pdflatex main.tex  # Second pass for hyperref and TOC generation
