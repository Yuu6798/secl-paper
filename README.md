# SECL Paper

SECL (Self-Evolution Cyclic Loop) provides an evaluation cycle for AI systems. It records how question–answer pairs evolve over time using three metrics: PoR (Probability of Retention), ΔE (change in entropy), and `grv` (growth-rate vector). This repository holds the LaTeX source, experiment code, and configuration required for the preprint submission to OSF.

## Key Features

- **PoR, ΔE, and grv metrics** for tracking evaluation changes
- **Reproducible Python experiments** driven by `config.json`
- **LaTeX manuscript** ready for OSF preprint submission
- Modular workflow for benchmarking model updates

## Directory Overview

```
paper/         LaTeX source of the preprint
src/           Python experiments and utilities
config.json    Parameter file for experiments
```

## Quick Start

### Build the LaTeX Paper

```
cd paper
latexmk -pdf main.tex
```

### Run the Python Demo

```
python src/demo.py --config config.json
```

## Cite as

When referencing this project, please cite the OSF preprint:

```
@misc{secl_preprint,
  title  = {Self-Evolution Cyclic Loop (SECL)},
  author = {Your Name},
  year   = {2024},
  url    = {https://osf.io/preprint-url}
}
```

## License

Content is licensed under the Creative Commons Attribution 4.0 International (CC-BY-4.0).

