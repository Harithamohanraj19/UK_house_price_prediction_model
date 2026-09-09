## UK House Price Prediction Model & Production ML Pipeline

###  Project Overview
This repository contains a comprehensive, end-to-end Machine Learning pipeline built to predict real estate pricing structures. Rather than a singular notebook, the architecture is broken down into 5 production-style phases—covering data extraction, exploratory analysis, dimensionality reduction, cross-validation tuning, and model serialization for deployment readiness.

###  Tech Stack & Engineering Core
- **Language:** Python (Jupyter Notebook Framework)
- **Machine Learning & Pipeline Tooling:** Scikit-Learn, NumPy, Pandas
- **Dimensionality Reduction:** Principal Component Analysis (PCA)
- **Data Engineering Operations:** ETL (Extract, Transform, Load), Hyperparameter Tuning, Cross-Validation, Serialization (Joblib/Pickle)

### Production Pipeline Architecture
1. **`data_understanding_etl.ipynb`** – Handles raw data ingestion, primary type-casting, and structural ETL data cleaning pipelines.
2. **`Data_analysis_eda.ipynb`** – Executes deep Exploratory Data Analysis, outlier evaluation, and target variable distribution mapping.
3. **`feature_engineering_pca.ipynb`** – Drives statistical feature engineering, scaling, and implements Principal Component Analysis (PCA) to reduce high-dimensional correlation matrices.
4. **`Model_training.ipynb`** – Configures diverse regressor algorithms, structures K-Fold cross-validation loops, and executes fine-grained hyperparameter optimization.
5. **`final_pipeline.ipynb`** – Compiles all modules into a singular, automated production-ready pipeline, exporting the final trained model weights for live system inference.




