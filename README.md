# Boosting Tutorial: AdaBoost vs Gradient Boosting

## Overview
This project compares AdaBoost and Gradient Boosting for handwritten digit classification using the scikit-learn digits dataset. The aim is to evaluate model performance and understand the differences in their learning mechanisms.

## Objectives
- Implement a weak learner baseline  
- Train and evaluate AdaBoost  
- Train and evaluate Gradient Boosting  
- Compare models using accuracy, precision, recall, and F1-score  
- Analyse performance using confusion matrices and misclassified samples  
- Study the effect of the number of estimators on model performance  

## Dataset
The dataset used in this project is the handwritten digits dataset provided by scikit-learn, consisting of 8×8 pixel images of digits (0–9).

## Methods
- Decision Stump (baseline model)  
- AdaBoost  
- Gradient Boosting  

## Key Results
- Gradient Boosting achieved the highest performance across all evaluation metrics  
- AdaBoost improved significantly over the baseline model  
- Misclassification analysis highlights challenges with visually similar digits  
- Increasing the number of estimators improves performance, with Gradient Boosting showing more stable behaviour  

## Project Structure
- `Boosting.ipynb` – main notebook with implementation and analysis  
- `figures/` – saved output images  
- `README.md` – project description  

## Requirements
Python 3.8+
Install the following libraries:
- numpy  
- pandas  
- matplotlib    
- scikit-learn  

## How to Run
1. Clone the repository:
   git clone https://github.com/Lojana96/boosting-tutorial-digits-classification  
2. Install dependencies:
   pip install numpy pandas matplotlib scikit-learn
3. Open Jupyter Notebook:
4. Then open:
     Boosting.ipynb
5. Run All Cells
   Click “Run All” in Jupyter
   The notebook will:
   Load the dataset
   Train models (AdaBoost & Gradient Boosting)
   Generate evaluation metrics
   Display plots
## Outputs
The notebook will produce:
  Model performance comparison
  Accuracy scores
  Confusion matrices
  Training vs testing performance plots

## Reproducibility
The dataset is loaded directly from scikit-learn, and all results can be reproduced by running the notebook from top to bottom.

## Author
Lojana Jegatheeswaran  
MSc Data Science  
University of Hertfordshire  
