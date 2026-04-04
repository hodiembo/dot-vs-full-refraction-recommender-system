# dot-vs-full-refraction-recommender-system
Machine learning based recommendation system for classifying participants into DOT Glasses or Full Refraction using screening, prescription, demographic, and process-related data from low-resource eye-care settings in Kenya.

# DOT vs Full Refraction Recommender System

This repository contains the implementation notebook for a machine learning based recommendation system that classifies participants into either the DOT Glasses pathway or the Full Refraction pathway.

## Project Title
Development of a Data-Driven Recommendation System for Eyewear Selection in Low-Resource Settings

## Project Overview
The project was developed to support decision making in low-resource eye-care settings where community health workers often need to decide whether a participant should receive simplified DOT Glasses or be referred for full refraction. The system uses participant screening, prescription, demographic, and process-related variables to generate a recommendation.

## Objective
To develop a data-driven recommendation system that predicts the most suitable eye-care pathway between simplified DOT Glasses and full refraction.

## Methods
The implementation involved:
- data loading and merging
- preprocessing and logMAR standardization
- feature preparation
- model training and comparison
- validation and evaluation
- deployment packaging

The candidate models tested were:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Final Model
Logistic Regression was selected as the final model because it gave the strongest and most stable performance across the experimental stages.

## Final Performance
- Accuracy: 64.6%
- Precision: 64.2%
- Recall: 55.8%
- F1-score: 59.7%
- ROC-AUC: 62.5%

## Repository Contents
- `usiu_project_implementation.ipynb` — main implementation notebook
- additional outputs and figures where applicable

## Dataset
The dataset used in this project is stored separately and can be accessed through the project dataset link provided in the report appendix.



## Institution
United States International University Africa
