# Measuring Political Bias in AI-Generated News Articles

**USC DSCI 531 — Fairness in AI (Spring 2026)**

Brandon Han, Madhusudan Rajesh, Jesse Mena

## Accessing Project Files

**Primary Method — Google Drive:**

[USC_DSCI531_Project Drive folder](https://drive.google.com/drive/folders/1leaPmfaaFMF7Sn-VZZr9K88-lNCOgHgB?usp=sharing)

This shared Drive folder contains all necessary data - trained classifier, Qbias data, generated articles, scored results, and figures.

**Backup Method — this GitHub repository:**

The trained DeBERTa classifier weights and other data are also contained within this repo.

## Running the Notebook

The notebook is designed for Google Colab with a recommended A100 GPU. Execution takes approximately 4 hours.

1. Open `notebook.ipynb` in Google Colab.
2. Either copy the shared Drive folder to your own Drive (right-click → "Add shortcut to Drive"), or set `PROJECT_ROOT` in Cell 1 to point at a local directory containing the data and classifier.
