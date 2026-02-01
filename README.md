# ntwist-predictive-maintenance
# NTWIST Predictive Maintenance – ML Engineering Assessment

## Overview
This repository contains a predictive maintenance analysis for a critical
crushing machine (MILL_CRUSHER_01), completed as part of the NTWIST
Machine Learning Engineering assessment.

## Problem Statement
Operators reported that the machine felt unstable, while the monitoring
dashboard showed normal operation. The objective was to analyze raw sensor
data and validate the claim using data-driven methods.

## Approach
- Robust ingestion of raw industrial sensor logs
- Explicit handling of data quality issues (drop vs tag vs normalize)
- Time-series feature engineering (rolling statistics, trends)
- Baseline-driven anomaly detection
- Risk analysis for production deployment

## Key Findings
- Dashboard thresholds failed to detect early-stage degradation
- Temperature and vibration trends indicate progressive instability
- Operator feedback was validated using statistical evidence

## Deliverables
- Jupyter Notebook with full pipeline and analysis
- Technical Decision Document
- Cleaned sensor dataset
- Diagnostic visualizations

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn  
Google Colab

## Status
⚠️ Not production-ready without ground truth validation  
✅ Suitable for human-in-the-loop monitoring
