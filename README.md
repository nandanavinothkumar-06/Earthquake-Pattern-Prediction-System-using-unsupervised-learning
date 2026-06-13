# Earthquake Pattern Prediction System using Unsupervised Machine Learning and Explainable AI

![Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-green)
![XAI](https://img.shields.io/badge/Explainable%20AI-SHAP-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)

## Overview

Earthquake Pattern Prediction System is an Unsupervised Machine Learning and Explainable AI (XAI) project developed to discover hidden patterns, clusters, and anomalies within earthquake datasets.

Unlike traditional predictive models that require labeled target variables, this project focuses on uncovering naturally occurring structures in seismic data using clustering techniques and dimensionality reduction.

The project combines:

* K-Means Clustering
* Elbow Method
* Silhouette Score Analysis
* Principal Component Analysis (PCA)
* Isolation Forest Anomaly Detection
* SHAP Explainability
* Decision Tree Rule Extraction

The objective is to identify meaningful earthquake patterns, understand cluster characteristics, and explain the factors influencing cluster formation.

---

# Problem Statement

Earthquake datasets contain large amounts of seismic and geographical information. However, many hidden relationships within this data remain difficult to identify through traditional statistical analysis.

The goal of this project is to leverage unsupervised learning techniques to:

* Discover natural groupings of earthquakes
* Identify unusual seismic events
* Reveal hidden patterns in earthquake behavior
* Improve understanding of earthquake characteristics

without relying on predefined labels.

---

# Objectives

* Explore earthquake datasets
* Discover natural earthquake clusters
* Determine the optimal number of clusters
* Visualize high-dimensional seismic data
* Detect anomalous earthquake events
* Explain cluster formation using XAI techniques
* Extract interpretable decision rules

---

# Dataset Description

The dataset contains earthquake-related information including:

* Magnitude
* Depth
* Latitude
* Longitude
* Tsunami Indicators
* Significance Scores
* Intensity Measurements
* Geological Features

These variables were used to identify hidden patterns and cluster structures.

---

# Project Workflow

## 1. Data Collection

* Load earthquake dataset
* Inspect structure and distributions
* Understand feature characteristics

## 2. Data Cleaning

* Handle missing values
* Remove inconsistencies
* Prepare data for clustering

## 3. Exploratory Data Analysis

* Distribution Analysis
* Correlation Analysis
* Feature Visualization
* Pattern Exploration

## 4. Feature Preparation

* Feature Selection
* Data Scaling
* Transformation

## 5. Cluster Optimization

### Elbow Method

Used to determine the optimal number of clusters by analyzing Within-Cluster Sum of Squares (WCSS).

### Silhouette Score

Used to validate cluster quality and measure separation between clusters.

---

## 6. K-Means Clustering

K-Means clustering was applied to group earthquakes based on similar characteristics.

The model successfully identified meaningful cluster structures within the dataset.

---

## 7. Dimensionality Reduction

### Principal Component Analysis (PCA)

PCA was used to:

* Reduce dimensionality
* Improve visualization
* Reveal cluster separation
* Understand data structure

---

## 8. Anomaly Detection

### Isolation Forest

Isolation Forest was implemented to identify rare and unusual earthquake events.

These anomalies represent observations that differ significantly from the majority of seismic events.

---

## 9. Explainable AI (XAI)

### SHAP Analysis

SHAP (SHapley Additive Explanations) was used to:

* Interpret cluster formation
* Identify influential features
* Improve transparency
* Explain model behavior

### Decision Tree Rule Extraction

Decision Trees were trained on cluster labels to generate interpretable rules.

This enabled understanding of:

* Why earthquakes belong to specific clusters
* Key thresholds influencing cluster assignment
* Human-readable decision paths

---

# Key Findings

## Cluster Discovery

The analysis revealed:

### 1. Four Natural Clusters

Earthquakes naturally formed four distinct clusters.

### 2. High Magnitude Cluster

Cluster 0 primarily contained higher magnitude earthquake events.

### 3. Tsunami-Related Cluster

Cluster 2 contained the majority of tsunami-associated earthquakes.

### 4. PCA Visualization

Principal Component Analysis showed clear separation among discovered clusters.

### 5. Anomaly Detection

Isolation Forest successfully detected rare earthquake events that differed significantly from typical seismic activity.

### 6. Hidden Pattern Discovery

Unsupervised learning successfully uncovered meaningful earthquake structures without requiring alert labels.

---

# Explainable AI Insights

Feature importance and SHAP analysis helped identify the attributes contributing most to cluster formation.

The project demonstrates how Explainable AI can improve trust and understanding in unsupervised machine learning systems.

---

# Technologies Used

## Programming

* Python

## Data Processing

* Pandas
* NumPy

## Machine Learning

* Scikit-Learn
* K-Means Clustering
* Isolation Forest
* Decision Trees

## Explainable AI

* SHAP

## Dimensionality Reduction

* PCA

## Visualization

* Matplotlib
* Seaborn

## Development Environment

* Jupyter Notebook

---

# Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Unsupervised Machine Learning
* K-Means Clustering
* Cluster Validation
* Elbow Method
* Silhouette Score Analysis
* PCA
* Dimensionality Reduction
* Anomaly Detection
* Isolation Forest
* Explainable AI (XAI)
* SHAP Analysis
* Rule Extraction
* Data Visualization

---

# Challenges Faced

* Selecting the optimal number of clusters
* Evaluating cluster quality
* Interpreting cluster behavior
* Explaining unsupervised learning results
* Visualizing high-dimensional data
* Detecting meaningful anomalies

---

# Future Improvements

* DBSCAN Clustering
* Hierarchical Clustering
* Advanced Anomaly Detection Models
* Interactive Visualization Dashboard
* Real-Time Earthquake Monitoring
* Deep Learning-Based Representation Learning

---

# Repository Structure

```bash
Earthquake-Pattern-Prediction-System/
│
├── Earthquake_pattern_prediction.ipynb
├── README.md
└── dataset/
```

---

# Learning Outcomes

This project strengthened my practical understanding of:

* Unsupervised Machine Learning
* Cluster Analysis
* PCA
* Anomaly Detection
* Explainable AI
* SHAP Analysis
* Pattern Discovery
* Data Visualization
* Real-World Seismic Data Analysis

---

# Author

## Nandana Vinothkumar

Integrated M.Tech CSE (Data Science)
VIT Vellore

### Areas of Interest

* Data Science
* Machine Learning
* Artificial Intelligence
* Explainable AI
* Data Analytics
* Predictive Analytics

---

# License

This project is developed for educational, research, learning, and portfolio purposes.
