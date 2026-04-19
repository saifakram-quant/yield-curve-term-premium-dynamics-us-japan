# yield-curve-term-premium-dynamics-us-japan
Quantitative macro-finance research on yield curve and term premium dynamics under U.S. vs Japan monetary regimes (2000–2023).
# Yield Curve and Term Premium Dynamics: A Comparative Study of the United States and Japan (2000–2023)

## Overview

This project presents a quantitative macro-finance analysis of sovereign yield curve behavior and term premium dynamics under structurally divergent monetary regimes. The study compares the United States and Japan over the period 2000–2023, focusing on the contrast between market-driven and policy-constrained yield formation.

## Research Objective

The objective is to analyze how monetary regimes influence:

* Yield curve structure and dynamics
* Term premium behavior
* Macroeconomic linkages
* Volatility and structural breaks

The study contrasts:

* United States: market-responsive yield curve
* Japan: policy-anchored yield curve under ZIRP and Yield Curve Control (YCC)

## Methodology

The research implements a multi-model quantitative framework:

**Short-Rate Models**

* Vasicek
* CIR++

**Term Structure Modeling**

* Nelson–Siegel (level, slope, curvature)
* Expectations Hypothesis and term premium decomposition

**Macroeconomic Analysis**

* Cointegration (Engle–Granger, Johansen)
* Vector Error Correction Model (VECM)

**Time-Series Diagnostics**

* GARCH volatility modeling
* Structural break tests (Zivot–Andrews, Bai–Perron)
* Stationarity testing (ADF, Phillips–Perron)

**Cross-Country Analysis**

* Rolling correlations and regressions
* Spillover and transmission analysis

## Data

* Frequency: Monthly
* Period: January 2000 – December 2023

**United States**

* 3M and 10Y Treasury yields
* CPI inflation, GDP growth
* M2 money supply
* Federal Reserve balance sheet
* VIX

**Japan**

* 3M and 10Y JGB yields
* CPI inflation, GDP growth
* M2 money supply
* Bank of Japan balance sheet

Sources include FRED, Bank of Japan, BIS, and IMF.

## Key Findings

* The U.S. yield curve is market-driven, information-rich, and strongly linked to macroeconomic fundamentals.
* The Japanese yield curve is policy-constrained, with suppressed volatility and reduced informational content.
* CIR++ outperforms Vasicek in dynamic U.S. regimes; Vasicek performs better in Japan’s low-volatility environment.
* Term premia in the U.S. reflect market risk, while in Japan they are compressed by policy intervention.
* Cross-country spillovers from the U.S. to Japan are weak under Yield Curve Control.

## Full Thesis

Access the complete thesis (methodology, empirical analysis, and results):

[https://drive.google.com/drive/folders/1WRwOGZc0CajskkCeq6H9l7cruwAP7Bzl?usp=drive_link]

## Repository Status

This repository currently documents the research framework and findings. A full reproducible code implementation will be added in a subsequent update.
