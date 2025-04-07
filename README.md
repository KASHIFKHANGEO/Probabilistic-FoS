
# Slope Stability Analysis using Monte Carlo Simulation and Bayesian Inference

This repository contains the Python code and data used for slope stability analysis in a specified study area. It includes Monte Carlo simulations, regression analysis, OAT (One-At-a-Time) and multivariate sensitivity analyses, and Bayesian inference. The project is built entirely in a Python environment using real-world data.

## 📌 Study Area
The case study is located in a rocky mountainous region with slope data and rock discontinuity parameters recorded from field surveys.

## 📂 Repository Structure
```
slope_stability_analysis/
│
├── data/                   # Input data files (e.g., joint orientations, slope angles)
├── src/                    # Source code for simulations and analysis
│   ├── monte_carlo.py      # Monte Carlo simulation code
│   ├── regression.py       # Regression analysis
│   ├── sensitivity.py      # OAT & multivariate sensitivity analysis
│   └── bayesian_inference.py # Bayesian inference module
├── results/                # Output figures and results
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation (this file)
```

## 📈 Features
- Monte Carlo simulation for probabilistic slope stability assessment.
- Regression analysis using real geotechnical parameters.
- Sensitivity analysis using both OAT and multivariate techniques.
- Bayesian inference to update slope stability predictions.

## 🧪 How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/slope_stability_analysis.git
cd slope_stability_analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run simulations:
```bash
python src/monte_carlo.py
python src/regression.py
python src/sensitivity.py
python src/bayesian_inference.py
```
