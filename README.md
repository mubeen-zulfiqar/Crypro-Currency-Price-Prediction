# Crypro-Currency-Price-Prediction

Historical machine learning project from 2023, exploring Bitcoin, Ethereum, and Dogecoin price data with Python, pandas, and scikit-learn linear regression.

## Repository contents

- `project.ipynb`: data exploration, model fitting, and error calculations.
- `bitcoin.csv`, `ethereum.csv`, and `dogecoin.csv`: input datasets.
- `.joblib` and `.pkl` files: original serialized model artifacts.

## Evaluation context

The notebook uses a random train/test split and estimates same-row prices from trading volume and elapsed days. It does not define a future forecasting horizon, so the reported errors are not evidence of out-of-time forecasting performance. A forecasting study would need chronological evaluation, features available at prediction time, and comparison with a simple baseline.

## Environment

The notebook imports pandas, NumPy, Matplotlib, scikit-learn, and joblib. Dependency versions are not pinned, and the original environment and serialized models have not been revalidated as part of this documentation update. The original code and repository name are preserved.
