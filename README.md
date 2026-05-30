/ml_nlp_project
├── /data                          # Raw and processed data
│   ├── /raw                       # Original, immutable data dumps
│   └── /processed                 # Cleaned and feature-engineered datasets
├── /notebooks                     # Jupyter Notebooks for EDA and experimentation
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_model_experiments.ipynb
├── /src                           # Modular Python scripts for the final pipeline
│   ├── __init__.py
│   ├── preprocess.py              # Text cleaning or feature engineering
│   ├── train.py                   # Model training and saving
│   └── evaluate.py                # Metrics and visualization
├── /models                        # Saved model files (e.g., .pkl or .h5)
├── /documentation                 # Flowcharts or model architecture diagrams
├── .gitignore                     # Excludes large files, model binaries, and data
├── requirements.txt               # List of libraries (pandas, scikit-learn, transformers, etc.)
└── README.md                      # Project description, results, and instructions
