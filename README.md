# CS 6220 — Homework 1

Environment setup and a scikit-learn pipeline tested on the UCI Iris dataset.

## What this does
- Loads the Iris dataset from the UCI Machine Learning Repository (dataset id 53)
- Splits it 80% / 20% into train/test (stratified)
- Builds a scikit-learn `Pipeline`: `StandardScaler` + `LogisticRegression`
- Trains and evaluates the model, reporting test accuracy
- Measures and reports training time and testing time

## Environment
- **Language:** Python 3
- **Editor / runner:** Google Colab (browser-based Jupyter notebook that runs on Google's cloud)
- **Libraries:** scikit-learn, pandas, NumPy, matplotlib, ucimlrepo

## How to run

### Option A — Google Colab (what I used)
1. Open https://colab.research.google.com
2. `File > Upload notebook` and choose `homework_1.ipynb`
   (or `File > Open notebook > GitHub` tab and pick it from the repo).
3. `Runtime > Run all`.
   - The first cell installs `ucimlrepo`; everything else runs automatically.

### Option B — Local Jupyter
1. Create and activate a virtual environment (e.g., `python -m venv .venv && source .venv/bin/activate`).
2. `pip install -r requirements.txt`
3. `jupyter lab`, open `homework_1.ipynb`, and run all cells.

## Files
- `homework_1.ipynb` — the notebook (commit it **with cell outputs saved**)
- `requirements.txt` — dependencies
- `README.md` — this file

## Dependencies
See `requirements.txt`. The listed floors match Google Colab's defaults. To freeze the
exact versions from your environment, run `pip freeze > requirements.txt`.
