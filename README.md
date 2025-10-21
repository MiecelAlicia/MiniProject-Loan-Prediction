# Bayesian Loan Status Prediction (Mini Project)

This project analyzes loan data to predict loan status using Bayesian logistic regression techniques implemented in R and JAGS.

## 🧠 Overview
This project is part of a "Mini Project - Group 3" assignment. The primary goal is to build and compare two Bayesian logistic regression models: one using uninformative priors and another using informative priors, to predict the likelihood of a loan default (`loan_status`).

## 🧮 Tools & Libraries
- R
- rjags
- coda (untuk analisis output MCMC)

## 📊 Features
- Data preprocessing (scaling covariates)
- **Model 1:** Bayesian Logistic Regression with Uninformative Priors
- **Model 2:** Bayesian Logistic Regression with Informative Priors
- MCMC (Markov Chain Monte Carlo) simulation for parameter estimation
- Model convergence checking (burn-in) and posterior analysis

## 📁 Files
- `MiniProject.Rmd` → Main R Markdown file containing all analysis and JAGS models.
- `loan_data.csv` → The dataset used for the analysis.
