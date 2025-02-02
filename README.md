# Business_Analytics_Bootcamp_3


# Google Causal Impact (Econometrics &amp; Causal Inference)


# Overview

    This repository contains a Google Colaboratory notebook that explores Google 
    Causal Impact in the context of Econometrics & Causal Inference. The analysis
    revolves around a case study assessing the impact of PayPal's announcement to 
    accept Cryptocurrency payments on Bitcoin prices.


# Topics Covered

1. Why Econometrics and Causal Inference?

        * Understanding the necessity of causal inference in econometrics.
        
        * Differentiating correlation from causation.
        
        * Applications of causal inference in real-world scenarios.
  

2. Google Causal Impact Game Plan

        * Introduction to Google's Causal Impact package.
        
        * Overview of the methodology and practical use cases.
        
        * Importance of case study-driven learning.
  

3. Case Study: Bitcoin and PayPal

        * Event Date: On October 21st, 2020, PayPal announced its acceptance of Bitcoin payments.
        
        * Investigating how this event influenced Bitcoin prices.
        
        * Defining treatment and control periods.
  

4. Time Series Data

        * Introduction to time series data in econometrics.
        
        * Preparing financial data for causal analysis.
  

5. Difference-in-Differences Framework

        * Understanding how Difference-in-Differences (DiD) helps in causal inference.
        
        * Application of DiD to financial market data.


6. Causal Impact Step-by-Step Guide

        * (1) Define pre and post periods.
        
        * (2) Retrieve necessary financial data.
        
        * (3) Check correlation of variables in the pre-period.
        
        * (4) Remove non-correlated data.
        
        * (5) Apply Google Causal Impact.
  

7. Assumptions for Causal Impact Analysis

        * Parallel Trends Assumption: Ensuring that the control group behaves similarly to the           treatment group in the absence of intervention.
        
        * Confounding Policy Change: Avoiding other external policy influences that may distort           the analysis.


8. Correlation Recap and Stationarity

        * Importance of correlation analysis in time series data.
        
        * Checking for stationarity and handling non-stationary time series.
  

9. Interpretation of Results

        * Understanding output plots from Causal Impact:
      
              --> Observed vs Counterfactual Predictions.
              
              --> Impact Effect Graph.
              
              --> Cumulative Effect Graph (for absolute metrics).
    
        * Summary of impact results and key takeaways.


# Implementation Details

    * Financial Data Source: Yahoo Finance (yfinance library).
    
    * Statistical Tests: Augmented Dickey-Fuller Test for stationarity.
    
    * Libraries Used:
    
          --> yfinance (for financial data retrieval)
          
          --> causalimpact (Google’s Causal Impact package)
          
          --> pandas, seaborn, matplotlib (for data processing and visualization)
