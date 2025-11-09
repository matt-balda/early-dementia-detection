# Multimodality and Temporality: predicting blood pressure crises in patients with dementia using IoT data and machine learning

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

This project uses multimodal IoT device data to predict adverse events in people living with dementia in the United Kingdom. Our target variable was blood pressure (systolic and diastolic): when a crisis surpassed predefined thresholds, the goal was to notify and intervene early, particularly considering that the population involved is older.

We applied binary classification (0 = no event, 1 = blood pressure crisis) using the following models: Perceptron, XGBoost, CatBoost, Logistic Regression, Naive Bayes, and SVM. SHAP values were also used to explain the impact of each variable on the model and on the prediction outcome.

**Team:** Dayane, Eric and Mateus.

**Kaggle:** ( https://www.kaggle.com/datasets/mateusbaldamota/dementia-dataset-activity-and-physiology/code )

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         early_dementia_detection and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
└── 
```

--------

