# ✈️ Airline Overbooking Optimization

This project addresses airline revenue loss due to passenger no-shows. Using **Bayesian inference** and **Monte Carlo simulation**, we estimate the optimal overbooking limits that balance **profit maximization** with **minimized customer denial risk**.

---

## 🚀 Overview

- Built a **Bayesian probabilistic model** to update no-show rate predictions using prior and real-time data.
- Implemented **Monte Carlo simulations** to estimate posterior distributions and expected overbooking outcomes.
- Proposed optimal overbooking range (12–15%) to increase revenue without risking excessive denied boardings.

---

## 📌 Problem Statement

### Current Scenario:
- Airlines rely on historical no-show averages without real-time adaptation.
- Overbooking decisions lack statistical modeling, leading to either revenue loss or customer dissatisfaction.

### Objective:
To build a **data-driven, adaptive model** using:
- **Bayesian Inference**: Incorporates new observations with prior data.
- **Monte Carlo Estimation**: Simulates flight outcomes and revenue under varying overbooking levels.

---

## 📈 Bayesian Framework

Bayesian modeling enables dynamic updates to no-show predictions.

| Term        | Meaning                                                  |
|-------------|----------------------------------------------------------|
| **Prior**   | Historical data from 8+ years of no-show records         |
| **Likelihood** | Recent passenger behavior (e.g., current booking trends) |
| **Posterior** | Updated no-show probability combining both sources     |

> Based on literature (DOI:10.4338/ACI-2014-04-RA-0026), prior distribution was modeled using multi-source passenger data.

---

## 🎲 Monte Carlo Simulation

- **500 flight simulations** run per experiment.
- For each flight: 400 seats sold with variable no-show behavior.
- Posterior updated in each trial, tracking denied boarding and revenue scenarios.
- Simulations indicate **12–15% overbooking** yields optimal return under typical no-show rates (~10%).

---

## 📊 Key Insights

- The model adapts to changing no-show rates dynamically.
- Airlines can reduce **empty seat losses** while keeping denied boardings below critical levels.
- Visualization from simulation shows revenue plateaus and risk thresholds clearly.

---

## 🧰 Technologies Used

```bash
Python, NumPy, Matplotlib, SciPy, PyMC3, Jupyter Notebook
