# Heart Transplant Survival Dataset

## Project Overview
This project focuses on heart transplant survival data, including patient survival time after surgery, patient age, and censoring status. The dataset can be used to explore survival analysis concepts and investigate factors related to post-transplant survival.

## Dataset Description
The dataset contains information about survival times after receiving a heart transplant.

- **`death`**: Number of days after surgery until death.
- **`age`**: Patient's age at the time of surgery.
- **`censored`**: Indicates whether the observation is censored; `1` represents an uncensored observation.

## Project Files
- `heart.csv`: Dataset file.
- `data.py`: Python module containing dataset metadata and functions for loading the data.
- `__init__.py`: Initializes the package and exposes the dataset-loading functions.
- `.gitignore`: Specifies files that Git should ignore.

## Technologies
- Python
- CSV
- Git and GitHub

## Potential Applications
- Exploratory Data Analysis (EDA)
- Survival data exploration
- Statistical analysis of patient survival data

## Getting Started

1. Clone or download this repository.
2. Ensure Python is installed.
3. Install the required dependencies if needed.

## Data Source
The dataset documentation references:

Miller, R. (1976). *Least squares regression with censored data*. Biometrika, 63(3), 449–464.

## Project Status
Dataset and data-loading code.

*Note: This repository currently contains the dataset and its loading code. It does not yet include a completed exploratory analysis or a trained machine learning model.*
