# EvaluatingICUTransferDCA

This repository contains code to reproduce experiments for a manuscript evaluating ICU transfer (or discharge) prediction models using decision curve analysis (DCA) and related operating-point metrics.

> **Status:** Code will be added prior to/after review in accordance with the venue’s supplementary material policy. This repository is currently a scaffold to support anonymized submission.

## Overview
The pipeline (to be uploaded) includes:
- Cohort construction and feature extraction (ICU patient-day level)
- Model training (e.g., logistic regression, random forest, gradient boosting)
- Predictive performance evaluation (ROC/PR, calibration)
- Decision-focused evaluation:
  - Decision curve analysis (net benefit across thresholds)
  - Operating consequences (e.g., reviews/day, true positives flagged, time burden)
  - Threshold selection utilities

## Repository Structure
