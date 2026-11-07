# Demo workflow

This public demo illustrates a simplified urban-accessibility modelling workflow using **synthetic data**.

It demonstrates:

1. Loading and inspecting the synthetic dataset.
2. Defining social and spatial predictors.
3. Training a `GradientBoostingRegressor`.
4. Using `GroupKFold` so observations from the same district stay together during validation.
5. Reporting out-of-fold R², MAE and RMSE.
6. Inspecting model feature importance.
7. Optionally producing SHAP-based explanations if `shap` is available.

This is a portfolio demonstration and is not a reproduction of confidential dissertation data.
