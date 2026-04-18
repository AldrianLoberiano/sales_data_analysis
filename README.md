# Sales Data Analysis

This project contains a Jupyter Notebook for exploring and analyzing sales data.

## Project Structure

```text
sales_data_analysis/
├── salesdataanalysis.ipynb   # Main notebook for data cleaning, analysis, and visualization
├── requirements.txt          # Ready-to-use Python dependencies
└── README.md                 # Project documentation
```

## Prerequisites

- Python 3.9 or later
- Jupyter Notebook or VS Code with Jupyter extension

## Setup

1. Open this folder in VS Code or your terminal.
2. (Optional but recommended) Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Install dependencies:

```powershell
pip install -r requirements.txt
```

## How To Run

1. Start Jupyter Notebook:

```powershell
jupyter notebook
```

2. Open `salesdataanalysis.ipynb`.
3. Run cells from top to bottom to reproduce the full analysis.

In VS Code, you can also open `salesdataanalysis.ipynb` directly and run cells using the notebook UI.

## Google Colab And Raw Data Source

- This notebook was also used in Google Colab.
- The notebook includes Colab-specific support via `from google.colab import sheets`.
- Raw dataset source used in the notebook:
  - https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv
- Dataset repository reference:
  - https://github.com/mwaskom/seaborn-data

## Recommended Next Structure (Optional)

As the project grows, you can organize files like this:

```text
sales_data_analysis/
├── data/
│   ├── raw/                  # Original source files
│   └── processed/            # Cleaned or transformed datasets
├── outputs/
│   ├── figures/              # Exported charts
│   └── reports/              # Generated summaries
├── salesdataanalysis.ipynb
└── README.md
```

## Notes

- Keep raw data unchanged and perform transformations in notebook cells.
- Dependencies are listed in `requirements.txt` for quick environment setup.
