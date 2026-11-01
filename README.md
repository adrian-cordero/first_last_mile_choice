# Discrete Choice Model Estimation

## Pipeline

Run the scripts in order from the project root:

1. `scripts/01_prepare_data.py` – clean and reshape raw data
2. `scripts/02_descriptives.py` – descriptive statistics
3. `scripts/03_estimate_models.py` – estimate models defined in `config/models/`
4. `scripts/04_postestimation.py` – WTP, elasticities, simulations
5. `scripts/05_make_tables_figures.py` – export tables/figures to `outputs/`

## Layout

- `config/` – paths and model specifications
- `data/` – raw (read-only), interim, processed data
- `src/dcm/` – project package
- `outputs/` – estimates, tables and figures (for Overleaf)
