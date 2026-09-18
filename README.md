# Water Quality Analysis

A Python project analyzing daily water-quality measurements from Korea's national water quality monitoring network, focused on **Total Phosphorus (T-P)** — a key indicator of nutrient pollution and a driver of algal blooms in rivers and reservoirs.

The project looks at long-term nutrient trends on the **Geumho River** (Daegu/Gyeongsan area).

## Project structure

- `analysis/learning.ipynb` — Main analysis notebook
- `data/` — Raw Excel source files
- `figure/` — Saved plots

## Data

Data comes from Korea's national water quality monitoring system, as yearly Excel files of daily measurements across hundreds of stations nationwide.

## Notebook overview (`analysis/learning.ipynb`)

1. **Single-station pass (2025)** — station **오산천2 (Osan Stream 2)**: load, filter, clean, summarize, and plot Total Phosphorus over 2025.
2. **10-year trend (2016–2025)** — station **금호강3** on the Geumho River: combine five yearly files, clean, plot the full trend, compute yearly averages, and compare years with a bar chart.

## Requirements

- pandas
- matplotlib
- openpyxl

Install with: `pip install pandas matplotlib openpyxl`
