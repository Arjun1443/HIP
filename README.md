# Insurance Cost Regression Experiments

## Interactive Streamlit app

A companion application is available in [streamlit_app/app.py](streamlit_app/app.py).

```bash
python -m pip install -r streamlit_app/requirements.txt
python -m streamlit run streamlit_app/app.py
```

This app fits a fresh random-forest baseline from the included dataset. Its evaluation is separate from prior notebook runs.

See [DEPLOYMENT.md](DEPLOYMENT.md) for Community Cloud setup, validation coverage, and runtime requirements. A live deployment is not yet confirmed.


A collection of notebooks exploring insurance-cost data, preprocessing, regression models, and hyperparameter tuning.

## Why this project matters

Regression experiments help connect tabular data preparation with model selection and error analysis for cost-estimation problems.

## Technical focus

Python · pandas · scikit-learn · scaling · encoding · regression evaluation

## Explore the implementation

Open [the notebook](<2)_insurence.ipynb>) to inspect preprocessing, implementation, and saved outputs.

## Run locally

```bash
git clone https://github.com/Arjun1443/HIP.git
cd HIP
python -m venv .venv
# Activate .venv before continuing.
python -m pip install numpy pandas matplotlib seaborn scikit-learn jupyter
python -m jupyter notebook
```

Select `2)_insurence.ipynb` in Jupyter and review its configuration before executing cells in order.

## Reproducibility notes

Included datasets: `insurance.csv` and `insurance123.csv`. The main notebook references a Google Drive path; point it to the intended local dataset. Additional experiments are in `insurence data.ipynb` and `hyperparameter tuning on insurence data.ipynb`. Review imports before running: some cells reference estimators that may need an explicit import.

Saved notebook outputs describe a prior execution; they are not an independently reproduced benchmark. Dependency versions are not locked, so compatibility may require adjustment.


## Author

[Naga Anweesh Reddy](https://github.com/Arjun1443/Naga-Anweesh-Reddy) · AI development and technical training
