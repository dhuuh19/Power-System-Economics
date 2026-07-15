# Power System Economics — Learning Portfolio

Self-study implementations of core power-market optimization problems,
following Kirschen & Strbac, *Fundamentals of Power System Economics* (2nd ed., 2019).
Each notebook is a self-contained experiment report: formulation → results → interpretation.

## Roadmap

| # | Notebook | Topic | Status | Key result |
|---|----------|-------|--------|-----------|
| 1 | Economic_Dispatch.ipynb | Economic dispatch (LP), merit order, SMP | Done | Reproduces Kirschen Eq. (5.28)–(5.29); λ verified by finite difference |
| 2 | (planned) | DC-OPF and locational marginal prices | — | Reproduce 3-bus constrained dispatch, nodal prices 7.5/11.25/10 $/MWh |
| 3 | (planned) | Unit commitment (MILP) | — | — |
| 4 | (planned) | Two-stage stochastic dispatch / ESS | — | — |

## Environment
Google Colab, Python, CVXPY. Data: Kirschen & Strbac (2019), Table 5.4 (cited, retyped).
