# abalone-PCA-analysis
Exploratory PCA analysis of the Abalone dataset to identify low-dimensional structure in biological measurements.
# Exploratory PCA of the Abalone Dataset

## Overview
This project performs an exploratory multivariate analysis of the Abalone dataset from the UCI Machine Learning Repository.

The goal is to:
1. Examine marginal distributions of numeric variables
2. Investigate correlation structure
3. Identify low-dimensional structure using Principal Component Analysis (PCA)
4. Interpret principal components in a biological context

## Dataset
Source: UCI Machine Learning Repository  
The dataset contains physical measurements of abalone (length, diameter, height, weight variables) and a target variable representing ring count (proxy for age).

## Methods

### 1. Exploratory Data Analysis
- Histograms of numeric variables
- Assessment of skewness
- Correlation heatmap

### 2. Principal Component Analysis (Correlation-based PCA)
- Standardized variables
- Scree plot (eigenvalues)
- Cumulative variance explained
- Score plot (PC1 vs PC2)
- Loading plot for interpretation

## Key Findings
- Strong positive correlations among size and weight variables
- Clear low-dimensional structure
- PC1 interpreted as overall size/mass factor
- PC2 captures shape or relative mass composition
- First two PCs explain most standardized variance

## Repository Structure
