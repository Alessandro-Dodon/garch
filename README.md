# GARCH Model for SP500 Daily Returns

## Overview
This repository contains a university project that examines the suitability of the GARCH(1,1) model for SP500 daily returns. The project includes parameter estimation, volatility modeling, confidence interval simulation, and model validation.

## Project Details
The analysis explores whether the GARCH(1,1) model effectively captures the dynamics of SP500 returns, accounting for heavy tails using both normal and Student's t-distributions. Key steps include:

1. **Data Collection:** 15 years of daily SP500 data downloaded from Yahoo Finance.
2. **Model Implementation:** A custom GARCH(1,1) model built without relying on built-in Python functions.
3. **Confidence Interval Simulation:** Using estimated parameters, 95% confidence intervals are simulated for a 30-day prediction horizon.
4. **Validation:** The frequency of actual returns violating these intervals is evaluated and visualized.

## Files
### `Garch.ipynb`
- **Description:** Contains the full analysis, including data processing, GARCH model implementation, parameter estimation, and validation steps.
- **Highlights:** Includes well-documented markdown sections and visualizations.

### `Report.pdf`
- **Description:** A comprehensive summary of the project, covering objectives, theoretical background, results, and conclusions.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```
2. Open `Garch.ipynb` in Jupyter Notebook to explore the analysis.
3. Refer to `Report.pdf` for a detailed project summary.

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scipy`, `yfinance`
- Jupyter Notebook for interactive exploration.

## Acknowledgments
This project was developed as part of a university course on financial econometrics. Special thanks to the instructors for their guidance.

