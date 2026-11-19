# PIML Stress-Strain Prediction for LPBF

Physics-informed machine-learning stress-strain prediction project for laser
powder bed fusion (LPBF) materials.

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

Experimental source data for Ti-6Al-4V and AlSi10Mg are included in `data/`.
The analysis scripts are still placeholders and exit with an explicit "not
implemented" message until their workflows are added.

## Working with the project

1. Read `data/README.md` for dataset provenance, citations, and license.
2. Implement and run the relevant scripts from the repository root.
3. Store tabular outputs in `results/result_csv_files/` and generated plots in
   `figures/`.
4. Record each quantitative or scientific claim, its supporting evidence, and
   its source in `claim_ledger/`.

Do not overwrite source data. Record dataset provenance, preprocessing steps,
software versions, and run configuration alongside generated results.
