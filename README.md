# PhD Milestones — Oriolson Rodriguez

**Queensland University of Technology**
Student ID: n12608521

**Topic:** Computational modelling of multilateral treaties and consensus dynamics — AI, game theory, and the Antarctic Treaty System

**Supervisors:**
- Principal: Prof. Michael Bode
- Associate: Prof. Jonathan Rhodes

---

## Repository structure

```
Phd_milestones/
  references.bib          # Shared bibliography for all sub-projects
  confirmation/           # Stage 2 — Confirmation of Candidature
  thesis/                 # Final thesis
  papers/
    paper1-affinity/      # Paper 1: Affinity dynamics
    paper2-aversion/      # Paper 2: Aversion dynamics
    paper3-simulation/    # Paper 3: Simulation framework
```

## Building a document

Each sub-project is a self-contained LaTeX project pointing at the root `references.bib`.
From inside any sub-project directory:

```bash
latexmk -pdf -interaction=nonstopmode main.tex
```

Or with `pdflatex` + `biber`:

```bash
pdflatex main && biber main && pdflatex main && pdflatex main
```

## Milestones

| Milestone | Folder | Status |
|-----------|--------|--------|
| Stage 2 — Confirmation | `confirmation/` | In progress |
| Thesis | `thesis/` | Not started |
| Paper 1 — Affinity | `papers/paper1-affinity/` | Not started |
| Paper 2 — Aversion | `papers/paper2-aversion/` | Not started |
| Paper 3 — Simulation | `papers/paper3-simulation/` | Not started |
