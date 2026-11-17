<div align="center">

# 🌾 Crop Yield Prediction

### Machine learning experiments for understanding and estimating agricultural productivity

<p>
  <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&w=1400&q=85" alt="Green agricultural fields under an open sky" width="100%" />
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white" alt="Jupyter notebooks" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-2E8B57" alt="Machine learning regression" />
  <img src="https://img.shields.io/badge/Project-Educational-6C63FF" alt="Educational project" />
</p>

<p>
  Explore agricultural data, visualize crop and climate trends, and compare regression approaches for crop-yield prediction.
</p>

</div>

---

## 🧭 Contents

- [About](#-about)
- [What’s inside](#-whats-inside)
- [Project workflow](#-project-workflow)
- [Repository layout](#-repository-layout)
- [Technology stack](#-technology-stack)
- [Getting started](#-getting-started)
- [Notes and limitations](#-notes-and-limitations)

## 🌱 About

This educational project explores how agricultural and climate-related data can be used to analyze and predict crop yield. The notebooks investigate patterns across crops, seasons, states, and years, then experiment with data preparation and regression models.

The work includes an Indian agricultural productivity analysis using features such as crop, state, season, area, production, annual rainfall, fertilizer, and yield. Other scripts explore additional model workflows.

## ✨ What’s inside

- 📊 Exploratory analysis and visualizations of agricultural trends
- 🧹 Data inspection, preprocessing, categorical encoding, and transformation
- 🌦️ Investigation of rainfall, fertilizer, crop, season, and regional patterns
- 🤖 Regression experiments, including Linear Regression, Random Forest, and CatBoost
- 📏 Evaluation with R², Mean Absolute Error (MAE), and Mean Squared Error (MSE)
- 📓 Jupyter notebooks alongside Python scripts and datasets

## 🔄 Project workflow

```mermaid
flowchart LR
    A[📁 Agricultural data] --> B[🔎 Explore and clean]
    B --> C[🧰 Prepare features]
    C --> D[🤖 Train regression models]
    D --> E[📏 Evaluate predictions]
    E --> F[📊 Compare results]
```

## 🗂️ Repository layout

```text
.
├── code/       # Analysis notebooks and Python scripts
├── datasets/   # CSV and Excel data files
├── images/     # Project images
└── videos/     # Project videos
```

A good place to start is the agricultural productivity notebook in `code/`:

- `indian-agricultural-productivity-analysis-ffebf0.ipynb`
- `indian_agricultural_productivity_analysis_ffebf0.py`

The primary crop-yield dataset used by that analysis is `datasets/crop_yield.csv`.

## 🧰 Technology stack

| Area | Tools |
| --- | --- |
| Language and notebooks | Python, Jupyter, Google Colab |
| Data analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Machine learning | Scikit-learn, CatBoost |
| Additional experiments | TensorFlow / Keras |

## 🚀 Getting started

### 1. Clone the repository

```bash
git clone https://github.com/Hemanth-kumar-pujari/crop_yeild_prediction_using_ml_college.git
cd crop_yeild_prediction_using_ml_college
```

### 2. Install the analysis dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn plotly scikit-learn scipy statsmodels catboost openpyxl
```

Some scripts use TensorFlow and SciKeras; install those separately if you plan to run those experiments:

```bash
python -m pip install tensorflow scikeras
```

### 3. Open a notebook or run a script

Open a notebook from `code/` in Jupyter or Google Colab. For a Python script, run it from the repository root, for example:

```bash
python code/indian_agricultural_productivity_analysis_ffebf0.py
```

Make sure the dataset path in the selected notebook or script points to a file available in your environment. Some notebooks use Google Colab's upload flow, and some scripts may need their local paths updated before running.

## ⚠️ Notes and limitations

- This is an educational/research project; results are exploratory and should not be treated as agronomic advice.
- The repository contains multiple datasets and experiments. Verify that a dataset matches the script you intend to run.
- Model scores depend on the dataset, preprocessing, and train/test split. Re-run the workflow to validate any reported metrics.
- No license file is currently included. Please check with the repository owner before reuse or redistribution.

## 👤 Author

**Hemanth Kumar Pujari**

---

<div align="center">

🌾 *Turning agricultural data into insights for smarter crop-yield analysis.*

</div>
