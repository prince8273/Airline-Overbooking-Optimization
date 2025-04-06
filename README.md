# ✈️ Airline Overbooking Optimization

This project implements a probabilistic model using **Bayesian inference** and **Monte Carlo simulation** to optimize airline overbooking strategies. The goal is to help airlines maximize revenue by estimating the optimal number of tickets to overbook based on historical no-show data while minimizing the risk of denied boardings and passenger dissatisfaction.

---

## 🚀 Overview

- Developed a Bayesian model to calculate the **posterior distribution** of no-show probabilities using historical data.
- Applied **Monte Carlo simulation** to estimate the expected outcomes for various overbooking limits.
- Enabled **data-driven decision-making** for dynamic airline overbooking strategies.
- Balanced the trade-off between revenue maximization and customer experience.

---

## 🧠 Problem Statement

Airlines face the challenge of passenger no-shows, which leads to revenue loss. Overbooking can mitigate this but comes with the risk of denied boardings. The objective is to estimate an **optimal overbooking limit** that minimizes losses from empty seats while avoiding customer dissatisfaction from overbooking.

---

## 🛠️ Technologies Used

- **Python**  
- **NumPy**, **Pandas**  
- **Matplotlib** (for visualization)  
- **PyMC3 / SciPy** (for Bayesian modeling)  
- **Monte Carlo simulation** techniques  

---

## 📊 Methodology

1. **Data Collection**: Historical passenger and no-show data used as input.
2. **Bayesian Modeling**:
   - Defined prior distribution for no-show probability.
   - Likelihood computed from observed data.
   - Posterior distribution inferred using Bayes’ Theorem.
3. **Monte Carlo Simulation**:
   - Simulated thousands of flight scenarios.
   - Evaluated outcomes based on varying overbooking limits.
   - Identified the optimal threshold maximizing revenue.

---

## 📈 Results

- The model successfully estimated realistic overbooking limits.
- Provided a probabilistic understanding of denied boarding risk.
- Demonstrated improved expected revenue with controlled overbooking.

---

## 📌 Future Work

- Integrate real-time data for dynamic optimization.
- Extend model for multi-leg flights and airline networks.
- Deploy as a dashboard or microservice for airline management tools.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

