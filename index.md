---

title: Ladder (PBSMC)
layout: default
permalink: /
------------

<!-- MathJax v3 loader so LaTeX renders inside tables and text -->

<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    },
    svg: { fontCache: 'global' }
  };
</script>

<script defer src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js"></script>

<style>
  /* Friendly table scrolling and nicer code/latex sizing */
  table { display: block; overflow-x: auto; white-space: nowrap; }
  th, td { padding: .5rem .75rem; }
  code, kbd { font-size: .95em; }
</style>



| token              |       n-ad | canonical relation                       | minimal formula                                                                          | what it “adds”                                      | quick read              |
| ------------------ | ---------: | ---------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------- | ----------------------- |
| **gradient**       |  1 (monad) | scalar potential slope → field           | \$\mathbf{E}=-\nabla \phi\$ (or \$\nabla \mu,\ \nabla T\$)                               | a single direction of drive                         | “one arrow exists.”     |
| **e–q gradient**   |   2 (dyad) | field acting on charge → work/force      | \$\mathrm{d}W = q,\mathbf{E}!\cdot!\mathrm{d}\mathbf{\ell}\$, \$\mathbf{F}=q\mathbf{E}\$ | couples drive to a carrier                          | “drive meets bearer.”   |
| **eeq**            |  3 (triad) | energy bookkeeping with charge present   | \$U = \tfrac{1}{2} C V^2\$ and \$q=CV\$ (or chemical \$\Delta G = -zF\Delta\psi\$)       | stores/transfers energy *because* \$q\$ exists      | “capacity appears.”     |
| **eh\nu q**        | 4 (tetrad) | quantization enters the game             | \$E = h\nu\$ while \$q\$ sets coupling/selection                                         | discreteness of exchange + coupling                 | “packets now carry.”    |
| **ep\lambda\nu q** | 5 (pentad) | full wave–particle kinematics + coupling | \$E=h\nu,\ p=\tfrac{h}{\lambda},\ c=\lambda\nu\$ with \$q\$                              | energy, momentum, wave, and interaction all present | “a trafficked quantum.” |

## How to use it

* **monad → dyad**: add a **carrier** (\$q\$) to a **drive** (\$\nabla\$), and you get actionable force/work.
* **dyad → triad**: add **storage/transfer law** (capacitance, redox, etc.) to govern flows: now you can buffer and meter.
* **triad → tetrad**: add **quantization** (\$h,,\nu\$) so exchanges come in quanta—gates, photons, channel openings.
* **tetrad → pentad**: add **kinematics** (\$p,,\lambda\$) so information/impulse rides those quanta and couples via \$q\$.

## PBSMC snap‑fit (your pentad)

* **P (physical)**: gradient (monad)
* **B (biological)**: e–q gradient (dyad) → ion flows, membranes
* **S (social/strategic)**: eeq (triad) → capacities, budgets, buffers
* **M (mathematical/computational)**: eh\$\nu\$q (tetrad) → discrete packets/ticks
* **C (computational/enterprise)**: ep\$\lambda\nu\$q (pentad) → full traffic: energy+momentum+wave+coupling (signals doing work in networks)

---

### Notes

* This page includes MathJax locally via CDN so LaTeX also renders **inside tables** (some themes don’t process table cells by default without a loader).
* If your site layout already loads MathJax or KaTeX, you can remove the `<script>` tags above to avoid double‑loading.
* GitHub Pages uses kramdown by default; the table is standard Markdown and will render across GitHub and GH‑Pages.
