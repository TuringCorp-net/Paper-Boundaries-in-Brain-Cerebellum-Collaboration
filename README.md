# Paper: Boundaries in Brain–Cerebellum Collaboration

**Exploring Execution-Form Boundaries in Brain–Cerebellum Collaboration: An Empirical Study from Cloud–Edge to Cost-Tiered Architectures**

Preprint (v1). Author: Li Zhang. Affiliation: TuringCorp.

## Files

- `main.tex` — LaTeX source (compile with pdfLaTeX, e.g. on Overleaf)
- `LICENSE` — CC-BY-4.0

## Abstract (short)

Agent systems commonly pair a high-capability "brain" model with a low-cost "cerebellum" execution model. This paper reports a bounded but counter-intuitive counter-example: cloud–edge collaboration (a local 14B Gemma model as a DSH sub-agent) did not reduce tokens or wall-clock time (substantive output 8/21; output +74%; wall-clock 8.1×), with variable-isolation experiments (V0–V4) attributing the failure to an interaction between execution form and model capability tier rather than to model ability alone. A cost scenario analysis under a fixed price snapshot estimates 45.0%–71.5% savings for cost-tiered collaboration with cheap cloud executors, pending real sub-agent validation.

## Data availability

All result data (task-level and per-run pass rates, token details, cost computations) are reported in the paper. Raw session logs and execution scripts are not made public.
