# Advanced-Portfolio-Construction

## Repository Structure:

00_Report : Final Report

01_Notebook 1 : 

Exploratory Data analysis for a 14‑asset universe (10 crypto, 4 traditional indices)  including Correlation heatmaps, Rolling correlations, marginal density plots, descriptive statistics...

02_Notebook 2 : 

Analyzing an equally weighted portfolio of 14 assets at peak (2021-09-11) and trough (2022-11-21). Includes covariance estimation & cleaning (eigenvalue clipping), Euler risk contributions, diversification via Effective Number of Bets, and comparison of                     losses vs. risk (Kendall’s τ)

03_Notebook 3 :

Constructing risk-based portfolios at peak (2021-09-11) and trough (2022-11-21), using the preferred covariance estimator. Implements and compares: Minimum Variance, Equal Risk Contribution (ERC), Minimum Effective Number of Bets (ENB), and Hierarchical                     Risk Parity (HRP). Comparing optimal weights across dates and portfolio types, relates results to risk contributions from Notebook 2, and discusses the role of constraints in the optimization.

04_Notebook 4 : 

Generalizes the HRP framework beyond correlation by testing alternative distance metrics (per Embrechts et al., 1999) for the dependence structure. Builds an alternative HRP (HRPe) portfolio at different dates, and compares weights with risk-based         portfolios from notebook 3. Finally, integrates time-series momentum (TSM) signals (Moskowitz et al., 2010) with the HRPe allocation, testing performance and risk structure over the full sample of crypto and traditional assets.

## Collaborators: 
This project was carried out as part of the Financial applications of blockchains and distributed ledgers course taught by Dimitrios Karyampas at the Ecole Polytechnique Fédérale de Lausanne (EPFL), in collaboration with:

Rocco Pio Lorenzo Ventruto [https://github.com/roccov]

Tallula Graber [https://github.com/Tallulaa]

Noah Louis Truttmann [https://github.com/NoahTruttmann]

Nayan Antoine Adani []

Hugo Alarcon Da Costa []


