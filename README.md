# Tokopedia Sentiment Classification under Extreme Class Imbalance

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afbrntly/joscex-tokopedia-sentiment/blob/main/notebooks/joscex_pipeline_final.ipynb)

Code and supplementary results for the manuscript submitted to JOSCEX:
"Tokopedia Sentiment Classification Using XGBoost, Synthetic Minority Oversampling, and Hybrid Feature Engineering for Extreme Class Imbalance"
by Ayumi Febrianty, Nuur Wachid Abdul Majid, and Salma Nurkamila.

## Dataset
Tokopedia Product Reviews 2025 (Kaggle):
https://www.kaggle.com/datasets/salmanabdu/tokopedia-product-reviews-2025

The dataset is not redistributed in this repository. The notebook downloads it automatically with `kagglehub`.

## How to run
1. Click the "Open in Colab" badge above (or open `notebooks/joscex_pipeline_final.ipynb` in Google Colab).
2. Runtime > Restart session and run all.
3. Outputs are written to `/content/final_results/`.

All random processes use `RANDOM_STATE = 42`. Library versions are listed in `requirements.txt`.

## Repository contents
- `notebooks/` – full analysis pipeline
- `results/` – tables, figures, raw per-fold scores, and validation files produced by the notebook
- `requirements.txt` – library versions

## Mapping to the manuscript
| Manuscript item | File |
|---|---|
| Table 1 | results/table1_dataset_description.csv |
| Table 2 | results/table2_feature_space_configuration.csv |
| Table 3 | results/table3_configuration_results.csv |
| Table 4 | results/table_baseline_model_comparison.csv |
| Table 5 | results/table_repeated_cv_results.csv |
| Table 6 | results/table_statistical_test_results_FINAL.csv |
| Table 7 | results/table_smote_variant_comparison.csv |
| Table 8 | results/table_ngram_comparison.csv |
| Table 9 | results/table_dimensionality_distance_analysis.csv, results/table_block_distance_isolation.csv |
| Table 10 | results/table5_feature_importance.csv |
| Per-fold CV scores | results/raw_scores/ |
| Effect size (Cohen's dz) | results/validation/ |
| Figures | results/figures/ |

## License
MIT License (see `LICENSE`).
