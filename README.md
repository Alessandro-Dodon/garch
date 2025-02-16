# GARCH Models for S&P 500 Daily Returns  

This repository contains an updated university group project, completed during my Master's in Quantitative Finance at USI Lugano, focusing on the theory and practical implementations of the GARCH(1,1) model for S&P 500 daily returns.  

## Overview

The primary analysis examines whether the GARCH(1,1) model effectively captures the dynamics of S&P 500 returns, using both normal and Student's t-distributions. Key components include:

- **Data Collection:** 15 years of daily S&P 500 data retrieved from Yahoo Finance.  
- **Model Implementation:** A custom GARCH(1,1) model built without relying on built-in Python functions.  
- **Confidence Interval Simulation:** Using estimated parameters, 95% confidence intervals are simulated for a 30-day prediction horizon.  
- **Validation:** The frequency of actual returns violating these intervals is evaluated and visualized.  

Two additional self-contained notebooks provide practical applications of GARCH models, focusing on Monte Carlo simulations and Value-at-Risk (VaR) estimation.

## Files

- **`Garch.ipynb`**: The primary notebook containing the full analysis, model implementation, parameter estimation, and validation. This notebook corresponds to the accompanying **`Report.pdf`**, which summarizes the project’s objectives, theoretical background, results, and conclusions.  

- **`VaR.ipynb`**: A self-contained notebook applying GARCH models to calculate Value-at-Risk (VaR) and Expected Shortfall (ES), with relevant theoretical background and implementation.  

- **`MonteCarloGarch.ipynb`**: Another standalone notebook that uses Monte Carlo simulations to investigate the statistical properties and behavior of GARCH models.  

## Results Example

The plot below illustrates the VaR and ES estimates, along with the observed violations for the period from November 2019 to November 2020. For more insights, refer to the report and notebooks.

![VarandES](VarandES.png)

## User Guide

A detailed user guide for the primary project is available in **`Report.pdf`**. The other two notebooks are self-contained with instructions included within. The process is straightforward, with examples provided.

1. **Setup**:
   - Ensure Python is installed along with a Jupyter-compatible environment (e.g., VS Code, Anaconda).  

2. **Execution**:
   - Open the desired notebook and select "Run All" to execute the analysis.  
   - The S&P 500 data is downloaded automatically from Yahoo Finance during execution, so no manual data preparation is needed.  
   - **Internet connection** is required to fetch data from Yahoo Finance.  

3. **Packages**:
   - All required libraries are listed in the notebooks with corresponding `pip install` commands.  
   - If any packages are missing, simply remove the `#` from the `pip install` lines and run the cell.  

## Contacts

For any clarifications, questions, or to report issues with the code, feel free to reach out via email at alessandro.dodon@usi.ch. You can also find my LinkedIn profile in my GitHub bio.
