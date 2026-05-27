This repository contains the source of the **Emergent Geometry Presentation Note** Cosmochrony paper  
[*The Emergent Geometry Sub-Programme — Presentation Note 2*](out/EmergentGeometryNote.pdf).

This work is a **structured entry point** to the emergent geometry sub-programme of the
Cosmochrony corpus, not a summary of results. It maps the constituent papers, identifies
the internal phases, records the status of every result as proved, structural, numerical,
or open, and states the remaining open deliverables.

## Central Question

The admissibility filter $\Pi_q$ acts on the Weil representation
$V_\rho \simeq L^2(\mathbb{Z}/q\mathbb{Z})$ of the Heisenberg group
$\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$, selecting admissible modes under the Born--Infeld
bounded-flux constraint.

> What effective geometry is selected in the large-$q$ limit of this structure, and what
> determines the numerical values of its metric coefficients?

The sub-programme removes the postulate of a background spacetime: the effective metric is a
forced consequence of admissibility, not an input. This note concerns the **reconstruction**
of the metric only; its dynamics (the Einstein equations) belong to the spectral gravity
sub-programme.

## Logical Chain

$\Pi_q
\;\Longrightarrow\;
V_\rho \simeq L^2(\mathbb{Z}/q\mathbb{Z})
\;\Longrightarrow\;
\mathrm{Heis}_3(\mathbb{R})
\;\Longrightarrow\;
L_{\mathrm{eff}}
\;\Longrightarrow\;
g^{\mu\nu}
\;\Longrightarrow\;
g^{\mu\nu} = 2\eta^{\mu\nu}$.

Five conceptually distinct stages, each resolved by a distinct group of papers:

1. **Discrete-to-continuum** — Mosco convergence of the admissibility Dirichlet forms to the
   one-dimensional shadow $L_\Pi = -A\partial_x^2$ (Q5a; Q5a-O2 and H2 close the open hypotheses).
2. **Dimensional promotion** — the Carnot convergence of BFS shells and the Bass--Guivarc'h
   homogeneous dimension $D_{\mathrm{hom}} = 4$ promote $L_\Pi$ to a 4D operator $L_{\mathrm{eff}}$
   on $\mathbb{R}_\tau \times \mathrm{Heis}_3(\mathbb{R})$ (Q5b).
3. **Metric extraction** — the effective co-metric $g^{\mu\nu} \propto A_{\mu\nu}$ and Lorentzian
   signature $(-,+,+,+)$ from the principal symbol of $L_{\mathrm{eff}}$ (Q5b, unconditional via Q9).
4. **Coefficient determination** — $A_Z = A_H = 2$ via Casimir rigidity and spectral universality
   (Q7, Q8, Q10, U1).
5. **Metric closure** — $A_\tau = 2$ via temporal Casimir rigidity, giving $g^{\mu\nu} = 2\eta^{\mu\nu}$
   (Q11; W1 closes [H-w]).

All four metric coefficients equal **2** — a single representation-theoretic datum: the
eigenvalue of the $\mathfrak{su}(2)$-Casimir on the spin-1 module $\mathrm{Sym}^2(V_\rho)$.

## Position in the Programme

The sub-programme sits at the interface between Branch I (axiomatic primitive) and Branch III
(physical observables). It takes from Branch I the Weil representation of
$\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$ and the Born--Infeld admissibility constraint, and from
Presentation Note 1 (spectral admissibility) the facts that the admissible sector is the
spin-$\tfrac12$ sector $V_\rho \cong \mathbb{C}^2$ and that $\Sigma_c(n_3) = 3$ with
$\mathrm{Im}\,\mathbb{H} \cong \mathfrak{su}(2)$. It produces the effective Lorentzian metric used
throughout Branch III.

## Constituent Papers

The note maps **twelve** constituent papers, organised by internal phase:

| Phase | Papers | Central output | Status |
|---|---|---|---|
| Discrete-to-continuum | Q5a, Q5a-O2, H2 | $L_\Pi = -A\partial_x^2$; [H-E1],[C],[H2] closed | P/S |
| Dimensional promotion | Q5b | $D_{\mathrm{hom}} = 4$; Carnot convergence | S |
| Metric extraction | Q5b + Q9 | $g^{\mu\nu} \propto A_{\mu\nu}$; signature $(-,+,+,+)$ | P |
| Coefficient determination | Q7, Q8, Q10, U1 | $A_Z = A_H = 2$ | P/S |
| Metric closure | Q11, W1 | $A_\tau = 2$; $g^{\mu\nu} = 2\eta^{\mu\nu}$ | S/P |
| Integrative output | Q6b | $\Pi_q \to L_{\mathrm{eff}} \to g^{\mu\nu} \to G_{\mu\nu}$ | C |

Status codes: **P** = proved, **S** = structural, **C** = conditional on the Q5a Mosco hypotheses.

## Open Deliverables

1. **Bridge existence at finite $q$.** The asymptotic results ($A_Z = A_H = A_\tau = 2$) and the
   metric closure $g^{\mu\nu} = 2\eta^{\mu\nu}$ hold in the $q \to \infty$ limit. An explicit
   $\mathfrak{su}(2)$-equivariant bridge $\phi_q: \mathrm{Sym}^2(V_\rho) \xrightarrow{\sim} W_{\mathrm{sp}}$
   at each prime remains an open structural problem (no published result depends on it).
2. **Hypothesis [H1] on the full $L^2$ space.** Closed on the admissible sector by Q5a-O2; the
   full-space version is not needed by any result and is listed for completeness.

## Build

```bash
bash compile.sh
```

This runs `pdflatex → bibtex → pdflatex → pdflatex` on `tex/EmergentGeometryNote.tex` and
produces `out/EmergentGeometryNote.pdf`.
