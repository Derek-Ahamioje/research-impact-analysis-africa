# Research Impact Analysis in Africa

## Project Overview

This project investigates scientific research output and impact across African countries using machine learning techniques and bibliometric analysis. The study evaluates publication productivity, citation performance, collaboration trends, and dominant research themes using data extracted from the Scopus Citation Database (2013–2022).

The project was developed as part of an MSc Data Science dissertation and demonstrates the application of unsupervised machine learning techniques to research analytics and scientometrics.

---

## Project Summary

This project presents a machine learning framework for evaluating research output and impact across Africa using bibliometric data from the Scopus Citation Database. Scientific publications produced between 2013 and 2022 were analysed to identify research productivity patterns, citation impact, collaboration trends, and dominant research themes.

Using DBSCAN clustering and Latent Dirichlet Allocation (LDA) topic modelling, the project explores alternative approaches for assessing regional research impact beyond traditional bibliometric indicators.

The framework was designed to support evidence-based decision-making by academic institutions, policymakers, and funding agencies seeking to better understand research productivity and collaboration across Africa.

---

## Research Objectives

- Assess regional research productivity across Africa.
- Evaluate citation impact and citation efficiency.
- Identify collaboration patterns among African countries.
- Discover dominant research themes.
- Generate evidence-based insights for policymakers, funding agencies, and academic institutions.

---

## Dataset

### Source
Scopus Citation Database

### Period
2013–2022

### Dataset Characteristics

- Publication records
- Citation counts
- Country affiliations
- Collaboration indicators
- Research subject areas
- Author metadata
- Research abstracts

Following data cleaning and preprocessing, the final dataset contained publications suitable for clustering and topic modelling analysis.

---

## Methodology

### Data Collection

Publication metadata and abstracts were retrieved from the Scopus Citation Database and prepared for analysis.

### Data Preprocessing

- Data cleaning
- Duplicate removal
- Missing value treatment
- Feature engineering
- Data normalisation
- Text preprocessing

### DBSCAN Clustering

Density-Based Spatial Clustering of Applications with Noise (DBSCAN) was used to identify research performance clusters and uncover patterns within the publication dataset.

### Topic Modelling

Latent Dirichlet Allocation (LDA) was applied to publication abstracts and keywords to identify dominant research themes and emerging topics.

### Statistical Analysis

Additional statistical techniques were used to explore relationships between publication volume, citation impact, and regional research performance.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Gensim
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Findings

- Significant disparities exist between publication volume and citation impact across African countries.
- South Africa produced the highest publication output in the dataset.
- Egypt demonstrated exceptionally strong citation efficiency.
- Tanzania achieved notable citation impact relative to publication volume.
- Distinct regional collaboration patterns emerged through clustering analysis.
- Topic modelling revealed health-related and societal research themes as dominant areas of influence.
- Strong relationships were observed between publication productivity and citation performance.

---

## Project Outputs

The project generated visual insights into:

- Publication trends across African countries
- Citation impact and citation efficiency
- Research collaboration patterns
- DBSCAN research clusters
- Dominant research topics identified through LDA topic modelling

Visualisations and outputs can be found in the `images` folder.

---

## Skills Demonstrated

- Machine Learning
- Unsupervised Learning
- DBSCAN Clustering
- Topic Modelling (LDA)
- Natural Language Processing
- Bibliometric Analysis
- Research Analytics
- Data Mining
- Statistical Analysis
- Data Visualisation
- Python Programming

---

## Repository Structure

```text
research-impact-analysis-africa
│
├── data
├── images
├── notebooks
├── reports
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Repository Contents

### Executive Summary
See `reports/`

### Dissertation Report
See `reports/`

### Analysis Notebooks
See `notebooks/`

### Visualisations
See `images/`

### Dataset Information
See `data/`

---

## Project Impact

This project demonstrates how machine learning can be applied to scientometric and bibliometric research to generate actionable insights for research evaluation, funding allocation, and policy development.

---

## Author

**Derek Ahamioje**

Data Scientist | Research Analytics Specialist | Published Researcher | Computer Science Lecturer
