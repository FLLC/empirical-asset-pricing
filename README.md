# Asset Pricing: Comparing RP-PCA, PCA, and Fama-French Factors

**Course:** FEM21003 – Asset Pricing  
**Program:** MSc Econometrics & Management Science  
**University:** Erasmus University Rotterdam  
**Instructors:** Dr. Gustavo Freire & Dr. Erik Kole  
**Date:** October 2025  

---

## 📘 Project Overview

This repository contains the code, data preparation, and analysis for the *Asset Pricing* course assignment.  
The project investigates how **Risk-Premium Principal Component Analysis (RP-PCA)** compares to both **standard PCA** and **Fama–French-style factor construction** in explaining the cross-section of expected returns.

Empirical asset pricing has identified a “**factor zoo**” — an overwhelming number of firm and portfolio characteristics correlated with returns. Using PCA-based approaches, this project explores how to **reduce dimensionality** while preserving **pricing information**.

---

## 🎯 Objectives

1. Apply standard **Principal Component Analysis (PCA)** to portfolio and factor return data.  
2. Implement **Risk-Premium PCA (RP-PCA)** following Lettau & Pelger (2020).  
3. Compare both approaches to the **Fama–French (1993, 2015)** factor framework.  
4. Evaluate the models’ ability to capture:
   - Cross-sectional variation in returns
   - Time-series pricing errors
   - Mean-variance efficiency

---

## 🧠 Theoretical Background

The assignment builds on key concepts from the *Asset Pricing* course:

- **CAPM and GRS testing** – testing whether the market portfolio is mean-variance efficient:contentReference[oaicite:5]{index=5}.  
- **Factor models and multi-factor testing** – extending CAPM to additional return-based factors:contentReference[oaicite:6]{index=6}:contentReference[oaicite:7]{index=7}.  
- **Characteristic-based factors** – constructing SMB, HML, and momentum from firm characteristics:contentReference[oaicite:8]{index=8}:contentReference[oaicite:9]{index=9}.  
- **Stochastic Discount Factor (SDF) framework** – linking asset returns to marginal utility and pricing kernels:contentReference[oaicite:10]{index=10}:contentReference[oaicite:11]{index=11}.  
- **Machine Learning in Asset Pricing** – identifying statistical factors using PCA and RP-PCA:contentReference[oaicite:12]{index=12}.

---

## 🧩 Data

- **5×5 double-sorted portfolios** from Kenneth R. French’s Data Library:  
  - First sort: Size  
  - Second sort: One of Book-to-Market, Investment, Profitability, or Momentum  
- **Fama–French 3 or 5 factors** (MKT, SMB, HML, RMW, CMA)  
- **Additional factors** from Jensen et al. (2023) “factor zoo” dataset  
- Sample period determined by group student numbers (as provided in Canvas)

---
