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


### Run the Python Demo

```
python src/demo.py --config config.json
```

## License

Content is licensed under the Creative Commons Attribution 4.0 International (CC-BY-4.0).

