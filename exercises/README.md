# Exercises

Focused practice notebooks grouped by topic.

## Modules

- `numpy/` — array manipulation drills (`06_reshaping`, `08_transpose`, `09_resize`,
  `10_concatenate`), plus `challenge_01.ipynb` and the `numpy_demo.py` script.
  Numbers mirror the topics in `notes/numpy/`.
- `pandas/` — a numbered course, `01_introduction` → `11_exporting_data`.
  Small helper scripts live in `pandas/scripts/`.
- `feature_engineering/` — encoding, scaling, and sklearn transformers
  (`01_standardization` → `05_function_transformer`), with an end-to-end
  `06_sklearn_pipeline/` walkthrough.
- `understanding_data/` — EDA workflow, `01_asking_basic_questions` →
  `05_sales`. Summary notes are in `notes/EDA/`.
- `sql/` — SQL basics against the sample `world` database.
- `web_scraping/` — scraping notebook; the `*.csv` files next to it are its output.

## Conventions

- Sequential notebooks are named `NN_topic.ipynb` (zero-padded, snake_case).
- Datasets are **not** stored here — they live under
  `resources/datasets/<module>/` and are loaded with a relative path.

## How to use

1. Create and activate a Python environment (venv or conda).
2. `pip install -r requirements.txt` from the repo root.
3. Launch Jupyter and open the notebook you want.
