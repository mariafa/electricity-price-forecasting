# A Unified Heterogeneous Ensemble Framework for Day-Ahead Electricity Price Forecasting

This repository contains the full workflow (data processing, feature construction, forecasting, ensemble ablation, statistical testing, and uncertainty evaluation) associated with the article:
***A Unified Heterogeneous Ensemble Framework for Day-Ahead Electricity Price Forecasting*** by F. Rodrigues and G. Pereira.

## Data Source
The original electricity and weather datasets are obtained from the [Kaggle Energy Consumption, Generation, Prices, and Weather Dataset](https://kaggle.com).

## Repository Structure

* **`01_data_preparation.ipynb`**: Initial cleaning and preparation of raw datasets.
* **`02_feature_construction.ipynb`**: Engineering and construction of predictive features.
* **`03_statistical_models.ipynb`**: Implementation of baseline statistical forecasting models.
* **`04_base_models_and_tuning.ipynb`**: Machine learning and deep learning base model training and hyperparameter tuning.
* **`05_ensemble_ablation.ipynb`**: Evaluation and ablation studies of the integrated ensemble frameworks.
* **`data/`**: Directories for `raw`, `processed`, and engineering `features` data.
* **`outputs/`**: Model checkpoints, performance audits, and statistical evaluation summaries.

## License
This project is licensed under the Apache-2.0 License.
