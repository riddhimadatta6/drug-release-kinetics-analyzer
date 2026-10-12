# Drug Release Kinetics Analyzer

A Python-based biomedical data analysis project for modeling and visualizing controlled drug-release profiles.

## Overview

Controlled drug-delivery systems are designed to release therapeutic compounds at a desired rate over time. This project analyzes simulated drug-release data and compares mathematical kinetic models to determine which model best describes the release profile.

The project uses Python to clean and analyze time-series data, fit drug-release models, evaluate model performance, and visualize experimental and predicted release behavior.

## Objectives

- Analyze time-dependent drug-release data
- Visualize cumulative drug release over time
- Fit zero-order, first-order, and Higuchi release models
- Compare model performance using R² and RMSE
- Estimate key release characteristics such as time to 50% release
- Interpret the physical meaning of the fitted models

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Drug Release Models

### Zero-Order Model

Drug is released at an approximately constant rate:

Q(t) = Q₀ + k₀t

### First-Order Model

Release rate depends on the amount of drug remaining:

Q(t) = Q∞(1 - e^(-kt))

### Higuchi Model

Diffusion-controlled release is modeled as proportional to the square root of time:

Q(t) = kH√t

## Dataset

The initial dataset used in this project is **simulated controlled drug-release data** created for educational and portfolio purposes.

The dataset contains:

- Time
- Cumulative percentage of drug released

A public experimental dataset may be incorporated in a future version of the project.

## Planned Analysis

1. Import and inspect the drug-release dataset
2. Perform basic data validation and cleaning
3. Visualize the release profile
4. Fit kinetic release models
5. Calculate R² and RMSE for each model
6. Compare model performance
7. Estimate release metrics such as t50
8. Interpret the results

## Project Status

🚧 In progress
