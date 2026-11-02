# Worst-case transport and light cones for quasi-periodic operators

Seth Douglas and Nidhal Mghirbi

Version 2.0.1, November 2026. A preprint; it has not been peer reviewed. Version 2.0.0: [10.5281/zenodo.23875774](https://doi.org/10.5281/zenodo.23875774). Version 1.0.0: [10.5281/zenodo.23845228](https://doi.org/10.5281/zenodo.23845228). Concept DOI (all versions): [10.5281/zenodo.23845227](https://doi.org/10.5281/zenodo.23845227).

## Abstract

We study the fastest transport exponent α_u^+ of supercritical analytic quasi-periodic Schrödinger operators at the worst phase. For finite Liouville exponent β, an upper law involving the Lyapunov exponent ℓ and acceleration ω keeps transport below one uniformly in phase. When β ≥ ℓ its local rate is 1 − ℓ/(2ωβ), and the factor 2ω is attained. For the almost Mathieu operator with L = log λ > 0, we prove the sharper uniform upper bound 1 − L/(2β) also on L/2 < β < L. Thus whenever the even-denominator exponent satisfies β_e = β > L/2, with β finite, the uniform exponent, the supremum over phases and the exponent at phase 1/4 all equal 1 − L/(2β). The same value holds on a dense G_δ set, while almost every phase has max{0, 1 − L/β}. The new upper proof uses translated one-band and two-band frames, an exact inverse-Morse factorization, matrix shells and one fixed energy unit through the full depth range. For odd-harmonic analytic potentials, a half-period sign flip gives a lower bound through a closed central gap. In the Aubry–André XY chain, for even sources and the specified receivers, the fixed-site light cone follows the typical law at almost every phase; the light cone uniform over sites follows the exact worst-case law when β_e = β > L/2 is finite. For an explicit computable chain these exponents differ and both have Turing degree 0″. We also prove computability of the Lyapunov exponent for computable analytic potentials and a transport exponent of degree 0″ throughout an explicit computable even-potential neighborhood. No computation enters the new upper proof.

## Changes in version 2.0.1

- Cites Liu and Wang (arXiv:2608.29339): for even potentials with positive Lyapunov exponent, the logarithmic growth of
  phase-uniform moment bounds is sharp, with matching lower bounds along sequences of times at a completely resonant phase.
  The introduction now places it beside the other work on sitewise and uniform dynamics. No result changes.

## Changes in version 2.0.0

- The worst-case law is now exact on the whole range: for the almost Mathieu operator with lambda > 1 and
  log(lambda)/2 < beta < log(lambda), the phase-uniform transport exponent is at most 1 - log(lambda)/(2 beta). So when beta_e = beta the
  worst exponent equals 1 - log(lambda)/(2 beta) for every finite beta > log(lambda)/2 (version 1.0.0: beta >= log(lambda)), with the
  matching extensions of the measure-versus-category theorem and of the uniform light cone of the Aubry-André XY chain.
- New sections and appendices give the proof: a two-band normal form near the rational approximants, matrix-valued shells, a fixed-unit
  estimate at every depth and a boundary Schur calculation.
- Two uncertified numerical remarks were removed; credits were extended (including Wilkinson); the almost Mathieu paper is cited at
  version 2.0.1 and the band-edges paper by its DOI.

## Contents

The paper is paper/main.pdf (72 pages). Its LaTeX source is paper/main.tex with the section files and paper/references.bib; paper/main.bbl is included. Build with pdflatex and BibTeX. No computation is used in any proof.

## Rights

CC BY 4.0. See RIGHTS.md and LICENSE-CC-BY-4.0.txt.

## Related

- "Exact transport and spectral dimensions for the almost Mathieu operator" (Seth Douglas and Nidhal Mghirbi, 2026), version 2.0.1, [10.5281/zenodo.23864352](https://doi.org/10.5281/zenodo.23864352). It proves the transport law and the spectral dimensions at almost every phase.
- "Universality of the transport law for supercritical quasi-periodic operators" (Seth Douglas and Nidhal Mghirbi, 2026), version 1.0.0, [10.5281/zenodo.23830333](https://doi.org/10.5281/zenodo.23830333). It proves the law at almost every phase for supercritical type I analytic potentials.
- "Band edges of the almost Mathieu operator at Liouville scales" (Seth Douglas and Nidhal Mghirbi, 2026), version 1.0.0, [10.5281/zenodo.23873797](https://doi.org/10.5281/zenodo.23873797). It proves that the gap-decay rate vanishes for beta > log(lambda)/2.
