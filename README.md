# Manufacturing Defect Prediction

This project simulates a manufacturing test environment and shows how to:
- clean and explore production test data,
- build a defect prediction model,
- and use the model to predict failures for new test runs.

The data and structure are inspired by production test systems, but all datasets here are **synthetic**.

---

## Project Structure

```text
MANUFACTURING-DEFECT-PREDICTION/
│
├── data/
│   ├── demo_test_1.csv          # example test item-level data
│   ├── demo_test_2.csv           # example test run-level data
│   └── production_test_data.csv     # synthetic "full" production dataset
│
├── notebooks/
│   ├── 01_data_cleaning_and_EDA.ipynb      # data loading, cleaning, EDA
│   ├── 02_defect_prediction_model.ipynb    # model training & evaluation
│   └── 03_test_run_prediction.ipynb        # predicting on new test runs
│
├── results/                        # saved figures / model outputs
├── requirements.txt                # Python dependencies
└── README.md
