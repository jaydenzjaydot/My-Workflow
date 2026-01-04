project-name/
│
├── data/
│   ├── raw/                    # Original, immutable data
│   ├── processed/              # Cleaned data ready for analysis
│   └── external/               # Third-party data sources
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_modeling.ipynb
│   └── 05_evaluation.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_processing.py      # Data cleaning functions
│   ├── feature_engineering.py  # Feature creation
│   ├── modeling.py             # Model training
│   └── visualization.py        # Plotting functions
│
├── models/
│   ├── trained_model.pkl       # Saved models
│   └── model_config.json       # Model parameters
│
├── reports/
│   ├── figures/                # Generated graphics
│   ├── final_report.pdf        # Executive summary
│   └── technical_report.md     # Detailed findings
│
├── tests/
│   └── test_functions.py       # Unit tests
│
├── requirements.txt            # Dependencies
├── environment.yml             # Conda environment
├── README.md                   # This file
├── .gitignore
└── LICENSE