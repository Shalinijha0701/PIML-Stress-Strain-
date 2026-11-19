# PIML Stress-Strain Prediction for LPBF

Repository scaffold for the physics-informed machine-learning stress-strain
prediction project for laser powder bed fusion (LPBF) materials.

## Repository layout

```text
PIML-Stress-Strain-Prediction-LPBF/
├── data/
│   └── README.md
├── scripts/
│   ├── analysis.py
│   ├── replicate_floor.py
│   ├── stats2.py
│   ├── figures.py
│   └── tables.py
├── results/
│   └── result_csv_files/
├── figures/
├── claim_ledger/
└── README.md
```

## Status

This repository currently contains the project structure and documentation.
The analysis scripts and project data have not yet been populated. The script
files exit with an explicit "not implemented" message until their workflows
are added.

## Working with the project

1. Add or document the source datasets in `data/` before running analyses.
2. Implement and run the relevant scripts from the repository root.
3. Store tabular outputs in `results/result_csv_files/` and generated plots in
   `figures/`.
4. Record each quantitative or scientific claim, its supporting evidence, and
   its source in `claim_ledger/`.

Do not overwrite source data. Record dataset provenance, preprocessing steps,
software versions, and run configuration alongside generated results.
