# Stability by Design: Machine Learning Models for Smart Grid Predictions

This repository contains the code and analysis for a comparative study of several machine learning models to predict the stability of smart grids. The project explores the performance of Random Forest, Decision Tree, Support Vector Machine (SVM), and XGBoost classifiers in classifying grid states as stable or unstable.

## Project Overview

The smart grid system represents a significant advancement in electricity supply chains, enhancing efficiency, sustainability, and reliability. However, maintaining grid stability is paramount, requiring sophisticated predictive models to foresee potential instability. This project evaluates different machine learning strategies to identify the most effective approach for predicting smart grid stability.

### Dataset Description

The dataset features variables related to the characteristics of a smart grid system, including:

- **tau1, tau2, tau3, tau4:** Time constants related to different components within the grid.
- **p1, p2, p3, p4:** Power measurements or demands at four different points in the grid.
- **g1, g2, g3, g4:** Generation capacities or efficiency parameters for generators at four locations.
- **stab:** A numerical stability indicator.
- **stabf:** A categorical stability indicator (`stable` or `unstable`).

### Models Evaluated

- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machine (SVM) Classifier
- Gradient Boosting (XGBoost) Classifier
