# Heart Failure Prediction Project

A single Jupyter Notebook that builds and evaluates models to predict heart failure outcomes. All work was performed on Kaggle; no local data, code, or environment is required.

## Files

- **Notebook:** [HeartFailurePredictionProject.ipynb](HeartFailurePredictionProject.ipynb) — main analysis and model pipeline.

## Dataset

- **Source:** Dataset used and referenced inside the notebook was loaded via Kaggle (added through the notebook's "Add data" UI). No local files were used or required.

## How to run (Kaggle only)

- **Step 1:** Go to Kaggle and create a new Notebook (or open a new Kernel).
- **Step 2:** Upload the `HeartFailurePredictionProject.ipynb` notebook to your Kaggle notebook (or import it via the Notebook upload feature).
- **Step 3:** In the Kaggle notebook, click **Add data** and attach the same Kaggle dataset used in the notebook. (The notebook expects the dataset to be available in the Kaggle environment.)
- **Step 4:** (Optional) In the Notebook settings, select a GPU/TPU if you plan to run heavy models — otherwise the default CPU environment is sufficient.
- **Step 5:** Run the notebook cells top-to-bottom.

## Dependencies

Uses typical Kaggle Python stack: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn` (Kaggle already provides these). If you add extra packages in the notebook, install them via `%pip install` inside the Kaggle notebook.

## Notes

This repository intentionally uses only Kaggle for data and execution — there are no local scripts, environment files, or local data downloads.
