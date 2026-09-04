# Probability Distribution Simulation & Analysis

A statistical simulation study comparing the **Poisson** and **Exponential** probability distributions, with a practical application to hospital emergency call arrivals.

## Overview

This project investigates two fundamental probability distributions commonly associated with a Poisson process:

* **Poisson distribution** — models the number of events occurring within a fixed interval.
* **Exponential distribution** — models the waiting time between consecutive events.

The project combines theoretical analysis, numerical simulation, empirical moment estimation, and a real-world application scenario.

## Objectives

* Understand the theoretical properties of Poisson and Exponential distributions.
* Compare their probability functions and parameters.
* Study how changing the rate parameter affects distribution shape.
* Verify theoretical properties through simulation.
* Compare empirical and theoretical moments.
* Apply both distributions to a hospital emergency call-centre scenario.

## Methodology

### 1. Theoretical Comparison

The project examines:

* Probability Mass Function (PMF) of the Poisson distribution
* Probability Density Function (PDF) of the Exponential distribution
* Mean and variance
* Effect of the rate parameter `λ`
* Relationship between the two distributions
* Connection with the Gaussian distribution through the Central Limit Theorem

### 2. Simulation Study

Random samples were generated from both distributions for different parameter values.

The simulations compare:

* Empirical distributions
* Theoretical distributions
* Sample means
* Sample variances
* Theoretical expectations

The results demonstrate convergence between empirical and theoretical quantities as sample size increases.

### 3. Application: Hospital Emergency Call Centre

A hospital emergency call centre is modeled using a Poisson process with:

```text
λ = 8 calls/hour
```

Two random variables are considered:

| Variable | Distribution   | Interpretation                    |
| -------- | -------------- | --------------------------------- |
| X        | Poisson(8)     | Number of calls received per hour |
| T        | Exponential(8) | Waiting time between calls        |

The model is used to estimate the probability of unusually high call volume and long waiting times between consecutive calls.

## Key Findings

* The Poisson distribution is appropriate for modeling **event counts**, while the Exponential distribution models **inter-arrival times**.
* For a Poisson distribution, the theoretical mean and variance are both equal to `λ`.
* For an Exponential distribution, the mean is `1/λ` and the variance is `1/λ²`.
* Simulated sample moments closely approximate theoretical values.
* For the hospital call-centre example, the model estimates approximately a **13% probability of receiving more than 12 calls in an hour**.
* The probability of waiting more than **15 minutes** between consecutive calls is approximately **14%**.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* SciPy

## Concepts Covered

Probability distributions · Poisson process · Exponential distribution · Random simulation · Expected value · Variance · Central Limit Theorem · Statistical modeling

**Course Instructor:** **Professor Roberta Siciliano**

This repository has been expanded and organized as a professional portfolio project for educational and demonstration purposes.

# Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 👨‍💻 Author

## **Subhadip Maity**

🌐 GitHub

https://github.com/subhadip191

💼 LinkedIn

https://linkedin.com/in/subhadipmaity191

---
