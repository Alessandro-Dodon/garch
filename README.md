# GARCH Model for SP500 Daily Returns
This repository contains a university group project that examines the suitability of the GARCH(1,1) model for SP500 daily returns. 
> **Note:** The code is being updated to include calculations for Value at Risk (VAR), Expected Shortfall (ES), and Monte Carlo simulations within the GARCH model implementation.

## Overview
The analysis explores whether the GARCH(1,1) model effectively captures the dynamics of SP500 returns, using both normal and Student's t-distributions. Key steps include:

- **Data Collection:** 15 years of daily SP500 data downloaded from Yahoo Finance.
- **Model Implementation:** A custom GARCH(1,1) model built without relying on built-in Python functions.
- **Confidence Interval Simulation:** Using estimated parameters, 95% confidence intervals are simulated for a 30-day prediction horizon.
- **Validation:** The frequency of actual returns violating these intervals is evaluated and visualized.

## Files
### `Garch.ipynb`
- Contains the full analysis, including data processing, GARCH model implementation, parameter estimation, and validation steps.

### `Report.pdf`
- A comprehensive summary of the project, covering objectives, theoretical background, results, and conclusions.

## User Guide

The user guide is detailed in the `Report.pdf` file, but the process is very straightforward. Open the `Garch.ipynb` notebook and use the "Run All" option to execute the analysis. Make sure Python is installed, along with a compatible environment for running Jupyter notebooks, such as VS Code or Anaconda.

All required libraries can be installed by removing the # at the beginning of the pip install commands in the notebook. The SP 500 data is downloaded automatically from Yahoo Finance during execution, so no manual data preparation is needed.

