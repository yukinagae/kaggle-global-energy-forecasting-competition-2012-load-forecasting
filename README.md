# Kaggle: [Global Energy Forecasting Competition 2012 - Load Forecasting](https://www.kaggle.com/c/global-energy-forecasting-competition-2012-load-forecasting)

> A hierarchical load forecasting problem: backcasting and forecasting hourly loads (in kW) for a US utility with 20 zones.

The competition has been closed and one of the winner's solution is described here, [A gradient boosting approach to the Kaggle load forecasting competition](https://robjhyndman.com/papers/kaggle-competition.pdf).

In this repo, following how the winner proceeded the task, I will try to gain more insights and better understanding of machine learning, especially timeseries forecasting.

## Table of Contents

- [Kaggle: Global Energy Forecasting Competition 2012 - Load Forecasting](#kaggle-global-energy-forecasting-competition-2012---load-forecasting)
  - [Table of Contents](#table-of-contents)
  - [Motivation](#motivation)
  - [Installation](#installation)
  - [Dependencies](#dependencies)
  - [Results](#results)
  - [Project Organization](#project-organization)
  - [References](#references)

## Motivation

TODO

## Installation

TODO

## Dependencies

TODO

## Results

TODO

## Project Organization

```text
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.testrun.org
```

## References

- Competiton Details: [Global Energy Forecasting Competition 2012 - Load Forecasting](https://www.kaggle.com/c/global-energy-forecasting-competition-2012-load-forecasting)
- Solution: [A gradient boosting approach to the Kaggle load forecasting competition](https://robjhyndman.com/papers/kaggle-competition.pdf)
