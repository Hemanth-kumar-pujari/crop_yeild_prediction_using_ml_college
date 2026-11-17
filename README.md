# Crop Yield Prediction Using Machine Learning

This repository contains a machine learning project focused on predicting crop yield using agricultural and climatic factors such as rainfall, fertilizer use, pesticide use, area under cultivation, and crop-related data.

The project explores data preprocessing, visualization, feature selection, and model comparison to identify which regression algorithms provide the best yield predictions.

## Project Overview

The goal is to analyze agricultural data and build predictive models that estimate crop yield using historical agricultural data. The repository includes:

- Data exploration and preprocessing notebooks/scripts
- Feature engineering and model evaluation
- Multiple regression models for comparison
- Visual analysis of crop, season, and state-wise trends
- Dataset files for training and experimentation

## Repository Structure

```text
crop_yeild_prediction_using_ml_college/
├── code/
│   ├── indian_agricultural_productivity_analysis_ffebf0.ipynb
│   ├── indian_agricultural_productivity_analysis_ffebf0.py
│   ├── projectcode.py
│   ├── other analysis scripts and notebooks
├── datasets/
│   ├── crop_yield.csv
│   ├── crop_yield_new.csv
│   ├── final.csv
│   ├── final_data.csv
│   ├── rainfall.csv
│   ├── temperature.csv
│   ├── yield.csv
│   └── other agricultural datasets
├── images/
├── videos/
├── README.md
└── .gitignore
```

## Key Features

- Crop yield analysis by year, state, season, and crop type
- Data cleaning and transformation for model training
- Exploratory data analysis (EDA) using charts and visualizations
- Model experimentation with regression techniques such as:
  - Linear Regression
  - Random Forest Regressor
  - CatBoost Regressor
  - Gradient Boosting / stacked approaches
- Evaluation using metrics like:
  - R² score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- TensorFlow / Keras (in some scripts)
- CatBoost

## Dataset

The project uses CSV and Excel-based agricultural datasets stored in the `datasets/` directory. These include crop yield, fertilizer, rainfall, and temperature-related data used for analysis and prediction.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Hemanth-kumar-pujari/crop_yeild_prediction_using_ml_college.git
```

2. Navigate to the project folder:

```bash
cd crop_yeild_prediction_using_ml_college
```

3. Open the notebooks in `code/` or run the Python scripts.

4. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn tensorflow catboost openpyxl
```

5. Run a script or notebook:

```bash
python code/projectcode.py
```

## Example Use Cases

- Predict crop yield based on soil and climate parameters
- Understand how rainfall, temperature, and nutrient levels influence crop production
- Compare model performance for agricultural forecasting

## Notes

This project is primarily notebook-based and is suited for educational and research purposes. Some scripts may reference local file paths or specific dataset names, so they may require minor adjustments depending on your environment.

## License

This project is currently provided without a formal license file. If you plan to reuse or distribute it publicly, it is recommended to add a license such as MIT.

## Author

Hemanth Kumar Pujari

## Acknowledgements

Thanks to the open-source data science and machine learning ecosystem for the libraries and tools used in this project.
