# Machine Learning & Unsupervised Learning Models | Regression & Anomaly Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-orange)
![Machine Learning](https://img.shields.io/badge/ML-Regression-red)
![Data Science](https://img.shields.io/badge/Data%20Science-Analytics-purple)

A comprehensive Machine Learning project implementing regression models and unsupervised learning techniques for real-world data analysis. Built with Scikit-learn, this repository demonstrates end-to-end ML workflows from data preprocessing to model evaluation and interpretation.

## Project Overview

This repository showcases proficiency in building machine learning models for both supervised (regression) and unsupervised (anomaly detection) learning tasks. The project focuses on predicting theoretical wind turbine power based on wind speed using multiple regression algorithms, alongside anomaly detection capabilities for identifying irregular patterns in the data.

## Key Features

- **Multiple Regression Models**: Linear Regression and Random Forest Regressor for robust predictive modeling
- **Comprehensive Evaluation**: MAE (Mean Absolute Error), RMSE (Root Mean Square Error), and R-squared metrics
- **Anomaly Detection**: Unsupervised learning techniques for identifying outliers in wind turbine data
- **Data Preprocessing**: Feature engineering, handling missing values, and data normalization
- **Model Comparison**: Side-by-side performance analysis of different regression algorithms
- **Visualization**: Plots for residuals, predictions vs actual values, and feature importance

## Technologies Used

- **Python** - Core programming language
- **Scikit-learn** - Machine learning library for model implementation
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing and array operations
- **Matplotlib & Seaborn** - Data visualization and result plotting
- **Jupyter Notebooks** - Interactive development and experimentation

## Project Structure

```
Unsupervised-Learning/
├── Task3.ipynb                 # Jupyter notebook with full implementation
├── power_anomalies.csv         # Wind turbine performance data
└── README.md                   # Project documentation
```

## Models Implemented

### Supervised Learning (Regression)

| Model | Description |
|-------|-------------|
| **Linear Regression** | Baseline model for establishing relationship between wind speed and power output |
| **Random Forest Regressor** | Ensemble model for capturing non-linear patterns and improving prediction accuracy |

### Unsupervised Learning (Anomaly Detection)

| Technique | Purpose |
|-----------|--------|
| **Statistical Methods** | Identify outliers using standard deviation and z-score analysis |
| **Clustering-based Detection** | Use unsupervised clustering to find anomalous data points |

## Methodology

1. **Data Loading & Exploration**: Load and analyze wind turbine performance data for patterns and anomalies
2. **Data Preprocessing**: Handle missing values, feature scaling, and train-test split
3. **Model Training**: Train multiple regression models with optimized hyperparameters
4. **Model Evaluation**: Assess performance using MAE, RMSE, and R-squared metrics
5. **Anomaly Detection**: Apply unsupervised techniques to identify irregular data points
6. **Visualization & Interpretation**: Create visualizations for model predictions and residual analysis

## Key Outcomes

- Successfully predicted wind turbine power output with high accuracy using ensemble methods
- Demonstrated proficiency in both supervised and unsupervised learning techniques
- Identified anomalous data points using statistical and clustering-based approaches
- Built a reproducible ML pipeline with comprehensive evaluation metrics

## Evaluation Metrics

| Metric | Description |
|--------|-------------|
| **MAE (Mean Absolute Error)** | Average absolute difference between predicted and actual values |
| **RMSE (Root Mean Square Error)** | Square root of average squared differences, penalizing larger errors |
| **R-squared** | Proportion of variance in the dependent variable explained by the model |

## Skills Demonstrated

| Skill Area | Details |
|------------|--------|
| Machine Learning | Regression modeling, ensemble methods, hyperparameter tuning |
| Unsupervised Learning | Anomaly detection, clustering techniques |
| Data Preprocessing | Feature engineering, scaling, handling missing data |
| Model Evaluation | MAE, RMSE, R-squared analysis |
| Visualization | Matplotlib, Seaborn for data and result visualization |
| Production Code | Jupyter notebooks and modular Python scripts |

## Usage

```bash
# Clone the repository
git clone https://github.com/Rishikesh7788/Unsupervised-Learning.git

# Navigate to project directory
cd Unsupervised-Learning

# Install dependencies
pip install scikit-learn pandas numpy matplotlib seaborn jupyter

# Run the notebook
jupyter notebook Task3.ipynb
```

## Future Improvements

- Implement additional unsupervised learning algorithms (DBSCAN, Isolation Forest)
- Add model deployment using Flask/FastAPI for real-time predictions
- Integrate with cloud platforms (AWS SageMaker, Google Cloud AI)
- Expand to time-series forecasting for wind power prediction
- Add interactive dashboards using Streamlit or Plotly

## Connect With Me

- GitHub: [Rishikesh7788](https://github.com/Rishikesh7788)
- LinkedIn: [Rishikesh](https://linkedin.com/in/rishikesh)
- Email: [Connect on GitHub](https://github.com/Rishikesh7788)

---
*Built with Scikit-learn & Python | Open Source | Machine Learning & Data Science*
