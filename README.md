# ✈️ Flight Delays Analysis

This project aims to explore and model flight delay patterns using a real-world dataset. The objective is to identify key factors associated with delays and cancellations and build a basic predictive model to anticipate them.

---

## 📂 Project Structure

```bash
flight-delays-analysis/
├── data/
│   ├── raw/                # Original dataset (CSV)
│   └── processed/          # Cleaned and transformed data
├── notebooks/
│   └── 01_eda_modeling.ipynb
├── scripts/
│   ├── clean_data.py       # Data cleaning functions
│   └── utils.py            # General utilities
├── outputs/
│   ├── figures/            # Plots and charts
│   ├── reports/            # Presentations or PDFs
│   └── model/              # Trained model, metrics, etc.
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE

### 📁 Dataset

This project uses the [**Airline Delay Causes** dataset](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses), which must be downloaded manually due to GitHub's file size limitations.

> Once downloaded, place the file `DelayedFlights.csv` inside the folder:  
> `data/raw/`
