# ✈️ Airline Overbooking Optimization

This project implements a probabilistic model using **Bayesian inference** and **Monte Carlo simulation** to optimize airline overbooking strategies. It helps airlines determine optimal overbooking limits by estimating the likelihood of no-shows based on historical and simulated data.

---

## 🚀 Overview

- Built a Bayesian model to compute **posterior distributions** for no-show rates.
- Used **Monte Carlo simulations** to evaluate overbooking decisions.
- Recommended optimal overbooking range (12–15%) to maximize revenue and reduce passenger denial risk.

---

## 🧠 Problem Statement

Airlines struggle with empty seats due to passenger no-shows. Overbooking can address this but may cause denied boardings if overdone. This project provides a data-driven framework to determine overbooking limits that balance profit and passenger satisfaction.

---

## 📊 Key Concepts & Methodology

### 📌 Bayesian Inference

- **Prior**: Historical no-show rate (e.g., 8-year data)
- **Likelihood**: Simulated flight data using binomial distribution  
- **Posterior**: Updated no-show rate after combining prior and likelihood

> ![Bayesian Prior Distribution](images/prior_distribution.png)  
> *Fig: Prior distribution of no-show rates from historical data*

---

### 🎲 Monte Carlo Simulation

- Repeatedly sampled from prior distribution
- Simulated 500 flights with 400 tickets sold per flight
- Computed posterior distribution after each simulation

> ![Posterior Distributions](images/posterior_distributions.png)  
> *Fig: Posterior distributions for no-show rates after simulation*

---

## ✅ Results

- Posterior distributions peaked around 10% no-show rate.
- Optimal overbooking range identified: **12–15%**
- Beyond 15% increases passenger denial risks and operational costs.

---

## 🛠️ Technologies Used

`Python`, `NumPy`, `Matplotlib`, `SciPy`, `PyMC3`, `Jupyter Notebook`

---

## 📌 Contributors

- **Prince Kumar** (22MC3039)  
- **Shaunak** (22MC3029)  
- **Mentor**: Dr. Dhrubasish Bhattacharyya

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

