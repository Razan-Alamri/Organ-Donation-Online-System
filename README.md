<<<<<<< HEAD
# Machine Learning Algorithms Comparison

This project evaluates and compares the performance of **Random Forest** and **Support Vector Machine (SVM)** on the **Bank Marketing Dataset**. The experiments were conducted using **Weka** and **RapidMiner**, employing both **cross-validation** and **split-validation** techniques.

---

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Purpose](#purpose)
- [Approach](#approach)
- [Dataset Description](#dataset-description)
- [Algorithms](#algorithms)
  - [Random Forest](#random-forest)
  - [Support Vector Machine (SVM)](#support-vector-machine-svm)
- [Results](#results)
  - [Random Forest Results](#random-forest-results)
  - [SVM Results](#svm-results)
- [Conclusion](#conclusion)
- [Appendix](#appendix)
- [References](#references)

---

## Introduction

Machine learning is a crucial subset of artificial intelligence that allows systems to learn from data. This project analyzes the suitability of **Random Forest** and **SVM** for predicting client subscription behavior using the **Bank Marketing Dataset**.

---

## Problem Statement

The objective is to determine which machine learning algorithm performs better in classifying client responses to a marketing campaign.

---

## Purpose

The project aims to:
1. Explore the application of machine learning algorithms on real-world data.
2. Compare the accuracy of **Random Forest** and **SVM**.
3. Evaluate results using **Weka** and **RapidMiner** under various validation techniques.

---

## Approach

1. Preprocessed the **Bank Marketing Dataset**.
2. Implemented algorithms using **Weka** and **RapidMiner**.
3. Conducted evaluations using:
   - **Cross-validation (10-fold, 20-fold)**
   - **Split-validation (66%, 76%)**
4. Analyzed and compared results.

---

## Dataset Description

The **Bank Marketing Dataset** includes data from direct marketing campaigns conducted by a Portuguese bank. The goal is to predict if a client subscribes to a term deposit based on features such as demographics, campaign information, and economic indicators.

---

## Algorithms

### Random Forest
- Ensemble learning method.
- Combines multiple decision trees.
- High accuracy and resistance to overfitting.

### Support Vector Machine (SVM)
- Identifies optimal decision boundaries.
- Effective for small datasets but computationally expensive.

---

## Results

### Random Forest Results
- **Cross-validation:**
  - Weka: 90.39% (10-fold), 90.53% (20-fold)
  - RapidMiner: 89.74% (10-fold), 89.78% (20-fold)
- **Split-validation:**
  - Weka: 90.55% (76%), 90.32% (66%)
  - RapidMiner: 89.85% (76%), 89.73% (66%)

### SVM Results
- **Cross-validation:**
  - Weka: 82.86% (10-fold), 88.04% (20-fold)
  - RapidMiner: 88.91% (10-fold), 88.97% (20-fold)
- **Split-validation:**
  - Weka: 65.55% (76%), 77.22% (66%)
  - RapidMiner: 88.72% (76%), 88.70% (66%)

---

## Conclusion

- **Random Forest** achieved higher accuracy (~90%), making it better for large datasets.
- **SVM** performed well (~88%) but is more suited for smaller datasets.
- Weka outperformed RapidMiner for Random Forest, while RapidMiner excelled for SVM.

---

## Appendix

Detailed results, confusion matrices, and screenshots are included in the [full report](Machine%20Learning%20Algorithms%20Comparison%20Report.pdf).

---

## References

- [Weka Documentation](https://www.cs.waikato.ac.nz/ml/weka/)  
- [RapidMiner Documentation](https://docs.rapidminer.com/)  