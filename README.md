This repository contains the source of the **Emergent Geometry Presentation Note** Cosmochrony paper  
*The Emergent Geometry Sub-Programme — Presentation Note 2*.

This work is a **structured entry point** to the emergent geometry sub-programme of the
Cosmochrony corpus, not a summary of results. It maps the constituent papers, identifies
the internal phases, records the status of every result as proved, structural, numerical,
or open, and states the remaining open deliverables.

## Central Question

The admissibility filter $\Pi_q$ acts on a supplied Heisenberg carrier, the
Heisenberg--Schrödinger representation $\pi_c$ of $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$ on
$\mathcal{H}_c = L^2(\mathbb{Z}/q\mathbb{Z})$, selecting admissible modes under the Born--Infeld
bounded-flux constraint. The carrier is not selected by the admissibility axioms (an explicit
$\mathfrak{S}_3$ countermodel, HeisenbergStructure); identifying the admissible fibre with it is a
modelling dictionary, and its associated Weil action is a further representation of the symplectic
automorphism group.

> What effective geometry is selected in the large-$q$ limit of this structure, and what
> determines the numerical values of its metric coefficients?

**Status revision (version 1.1).** Q5a version 3.0 withdraws the first link of the chain
(the Mosco derivation of $L_\Pi = -A\partial_x^2$): the canonical filtration is exactly a
growing toric Fourier window, the published form converges to the zero form, and no common
scalar normalisation produces a non-trivial toric differential operator. The spatial limit
operator is now the explicit, unestablished hypothesis **[H-L]** (Q5b 2.0), every metric
result is conditional on it, and Q5 is open. The geometric convergence results (Carnot,
$D_{\mathrm{hom}}=4$) are independent of [H-L]. No metric coefficient value is established:
invariance fixes the shape of an invariant spatial form and leaves its scale free (Q8), leaves the
temporal coefficient independent of the spatial one (Q11), and the isotropy route of Q10 rests on
inputs that are not supplied.

The sub-programme aims to remove the postulate of a background spacetime by reconstructing the
effective metric from admissibility rather than postulating it; the reconstruction is at present
conditional and incomplete (a rank-three co-metric, with the rank-four extension open as Q5b-O2). This note concerns the **reconstruction**
of the metric only; its dynamics (the Einstein equations) belong to the spectral gravity
sub-programme.

## Logical Chain

$\Pi_q
\;\Longrightarrow\;
\mathcal{H}_c = L^2(\mathbb{Z}/q\mathbb{Z})
\;\Longrightarrow\;
\mathrm{Heis}_3(\mathbb{R})
\;\Longrightarrow\;
L_{\mathrm{eff}}
\;\Longrightarrow\;
g^{\mu\nu}
\;\Longrightarrow\;
g^{\mu\nu} \propto \eta^{\mu\nu}$.

The last link presupposes a rank-four extension of the rank-three co-metric of Q5b, which is not
constructed (open problem Q5b-O2); it holds only for an extension satisfying the hypotheses of Q11
Corollary 6.1 ([T] and [INV$^+$] of Q8, [ACT$_\tau$] invariance and a negative ordering term), after rescaling $\tau$, with an
overall scale that no source fixes. A rank-four Lorentzian extension alone does not suffice: the
extension $\mathrm{diag}(-1,1,1,3)$ of the Q5b block has central entry different from the horizontal one,
and no rescaling of $\tau$ makes it proportional to $\eta^{\mu\nu}$.

Five conceptually distinct stages, each resolved by a distinct group of papers:

1. **Discrete-to-continuum** — now the open hypothesis [H-L]: Q5a 3.0 withdraws the Mosco
   derivation of $L_\Pi = -A\partial_x^2$ (H2 closed hypothesis [H2] of the withdrawn framework;
   Q5a-O2 establishes the pipeline's pure-Fourier structure and truncation status, leaving
   [H-E1] and [C] open).
2. **Dimensional promotion** — the Carnot convergence of BFS shells and the Bass--Guivarc'h
   homogeneous dimension $D_{\mathrm{hom}} = 4$ promote $L_\Pi$ to a 4D operator $L_{\mathrm{eff}}$
   on $\mathbb{R}_\tau \times \mathrm{Heis}_3(\mathbb{R})$ (Q5b).
3. **Metric extraction** — a rank-three effective co-metric $g^{\mu\nu} \propto A_{\mu\nu}$, with empty
   central slot, from the principal symbol of $L_{\mathrm{eff}}$, and signature $(-,+,+)$ on its non-degenerate
   block; the signs are stipulated, and [H-hyp$_{\mathrm{red}}$] makes them the only ones compatible with a
   $\tau$-ordered finite characteristic cone. A diagonal extension with $A_z > 0$ would have signature
   $(-,+,+,+)$; constructing it is the open problem Q5b-O2 (Q5b; co-metric conditional on [H-L] and the open lifting
   hypothesis [H-lift], signature additionally on [H-hyp$_{\mathrm{red}}$]; Q9 version 2.0 gives sufficient conditions for a kinetic Mosco limit and does not
   discharge [H-lift]).
4. **Coefficient determination** — no coefficient value is derived. Under the supplied
   identification [ID] and action [ACT], an equivariant bridge is zero or an isomorphism, unique up
   to one complex scalar (Q7); for a supplied positive rank-three target with full
   $\mathfrak{su}(2)$-invariance, $A_H = A_Z = 2\lambda$ with $\lambda > 0$ free (Q8); Q10 bounds the
   ratio $A_H/A_Z$ under [U] and three further inputs that are not supplied; [U] is open (U1 2.0).
5. **Metric closure** — invariance leaves $A_\tau$ independent of the spatial scale (Q11). For a
   supplied rank-four extension satisfying [T] and [INV$^+$] of Q8, invariant under [ACT$_\tau$] and
   with a negative ordering term (Q11 Corollary 6.1; Q5b-O2 open), the co-metric is
   $\mathrm{diag}(-A_\tau, 2\lambda, 2\lambda, 2\lambda)$, and $g^{\mu\nu} \propto \eta^{\mu\nu}$ after
   rescaling $\tau$; the overall scale is free. [H-w] is open (W1 2.0.1).

The value 2 is the eigenvalue of the $\mathfrak{su}(2)$ Casimir on the spin-one module
$\mathrm{Sym}^2(V_\rho)$ in one normalisation of the generators; it fixes no coefficient, and setting a
coefficient to 2 is a choice of units (Q8, Q11).

## Position in the Programme

The sub-programme sits at the interface between Branch I (axiomatic primitive) and Branch III
(physical observables). It takes from Branch I the Born--Infeld admissibility constraint and, as
a supplied input, the Heisenberg carrier $\mathcal{H}_c$ of $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$,
and from
Presentation Note 1 (spectral admissibility) the supplied inputs that the admissible sector is
carried by the spin-$\tfrac12$ carrier $V_\rho \cong \mathbb{C}^2$ and that $\Sigma_c(n_3) = 3$
(a supplied selection rule, with $\mathrm{Im}\,\mathbb{H} \cong \mathfrak{su}(2)$ the adjoint
dimension of that carrier). It aims to produce the effective Lorentzian metric used
throughout Branch III; it currently yields, conditionally, a rank-three co-metric.

*Notation.* Here $\mathcal{H}_c = L^2(\mathbb{Z}/q\mathbb{Z})$ is the $q$-dimensional supplied
Heisenberg carrier and $V_\rho \cong \mathbb{C}^2$ the supplied spin-$\tfrac12$ carrier, so that
$\mathrm{Sym}^2(V_\rho) \cong \mathbb{C}^3$. The convention is local to this note and establishes no
derived relation between the two carriers; companion papers use $V_\rho$ differently.

## Constituent Papers

The note maps **twelve** constituent papers, organised by internal phase:

| Phase | Papers | Central output | Status |
|---|---|---|---|
| Discrete-to-continuum | Q5a, Q5a-O2, H2 | Fourier window; no-go; $L_\Pi \to$ [H-L] | C |
| Dimensional promotion | Q5b | $D_{\mathrm{hom}} = 4$; Carnot convergence | S |
| Metric extraction | Q5b | rank-3 $g^{\mu\nu} \propto A_{\mu\nu}$; block $(-,+,+)$ | C$^\dagger$/C$^\ddagger$ |
| Coefficient determination | Q7, Q8, Q10, U1 | $A_H = A_Z = 2\lambda$, $\lambda$ free | P$_{\mathrm{s}}$ |
| Metric closure | Q11 | $A_\tau$ free; $g^{\mu\nu} \propto \eta^{\mu\nu}$$^\ast$ | P$_{\mathrm{s}}$ |
| Integrative output | Q6b | $\Pi_q \to L_{\mathrm{eff}} \to g^{\mu\nu} \to G_{\mu\nu}$ | C$^{\ddagger\ast}$ |

Status codes: **P** = proved, **S** = structural, **C** = conditional on the unestablished
spatial limit hypothesis [H-L] (Q5a 3.0, Q5b 2.0); **C$^\dagger$** = conditional on [H-L] and on the
open lifting hypothesis [H-lift] (Q5b 2.2.1, Hypothesis 4.1); **C$^\ddagger$** adds the hyperbolicity
hypothesis [H-hyp$_{\mathrm{red}}$] to [H-L] and [H-lift] (Q5b 2.2.1, Theorem 6.1); **C$^\dagger$/C$^\ddagger$** = C$^\dagger$ for the
co-metric, C$^\ddagger$ for the signature; **$^\ast$** = additionally presupposes a supplied rank-four extension
of the co-metric (Q5b-O2, open); $g^{\mu\nu} \propto \eta^{\mu\nu}$ further requires the invariance hypotheses
of Q11 Corollary 6.1, and its overall scale is free;
**P$_{\mathrm{s}}$** = proved only under supplied inputs, with no coefficient value derived.

## Open Deliverables

1. **An extended spatial target and the coefficient data.** Construct the extended target of Q7
   Conjecture 4.7 and Q8-O1, which would also supply the rank-four extension of Q5b-O2, and the
   dimensionful data fixing the spatial scale (Q8-O3) and the temporal-to-spatial ratio (Q11). No
   coefficient value is established in the meantime; an equivariant bridge at finite $q$ is part of
   this construction.
2. **Hypothesis [H1] on the full $L^2$ space.** Open; the full-space version is not needed by
   any result and is listed for completeness.

## Build

```bash
bash compile.sh
```

This runs `pdflatex → bibtex → pdflatex → pdflatex` on `tex/EmergentGeometryNote.tex` and
produces `out/EmergentGeometryNote.pdf`.
