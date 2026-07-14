# Hybrid Time Series Forecasting

## Overview

This repository contains the implementation of a hybrid time series forecasting project developed as part of an academic internship. The objective is to investigate how classical statistical models, advanced statistical methods, machine learning algorithms, and modern deep learning architectures can be combined to improve forecasting performance on complex real-world time series.

The project follows a research-oriented workflow beginning with statistical foundations and progressing toward hybrid forecasting frameworks that integrate linear and nonlinear learning methods.

---

## Objectives

* Study the statistical properties of time series data.
* Develop and compare multiple forecasting models.
* Analyze linear, nonlinear, seasonal, and long-memory dynamics.
* Evaluate hybrid forecasting strategies.
* Compare forecasting performance using standard evaluation metrics.
* Build a reproducible and well-documented forecasting pipeline.

---

## Models Covered

### Classical Statistical Models

* Naïve Forecast
* AR
* ARIMA
* ARIMAx
* Bayesian Structural Time Series (BSTS)

### Advanced Statistical Models

* ARFIMAx
* SETAR
* TBATS
* GARCH

### Machine Learning

* Support Vector Regression (SVR)

### Deep Learning (Project Scope)

* Artificial Neural Networks
* ARNN
* LSTM
* DeepAR
* N-BEATS
* N-HiTS
* DLinear / NLinear
* TSMixer

### Hybrid Forecasting

Statistical and machine learning models will be integrated to investigate whether hybrid approaches provide superior forecasting accuracy over individual models.

---

## Repository Structure

```text
data/
│── raw/
│── processed/

docs/
models/
notebooks/
reports/
│── figures/

results/

src/

README.md
requirements.txt
```

---

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Statsmodels
* Scikit-learn
* VS Code
* Git & GitHub

Additional libraries will be included as the project progresses.

---

## Workflow

1. Literature Review
2. Data Understanding
3. Exploratory Time Series Analysis
4. Data Preprocessing
5. Statistical Modeling
6. Machine Learning Modeling
7. Hybrid Model Development
8. Forecast Evaluation
9. Comparative Analysis
10. Documentation

---

## Current Status

🚧 Project Initialization

* Repository created
* Version control configured
* Folder structure established
* Literature review in progress

Implementation of forecasting models will begin after completion of the literature review and dataset preparation.

---

## License

This project is released under the MIT License.
