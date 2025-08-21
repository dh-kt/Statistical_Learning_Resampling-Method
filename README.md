# Statistical Learning - Resampling Methods

## Project Overview

This repository contains my solutions to practical assignments on **Resampling Methods** from the seminal textbook *"An Introduction to Statistical Learning with Applications in R"* (ISLR).

This project implements key techniques like the **Validation Set Approach**, **Cross-Validation**, and **Bootstrapping** in **Python** to evaluate predictive models, demonstrating core skills in model assessment and selection.

## Repository Structure

| Folder | Contents |
| :--- | :--- |
| [`/data`](/data) | Stores all datasets used in the analyses. |
| [`/notebooks`](/notebooks) | Jupyter/Colab notebooks containing the full analysis for each assignment. |
| [`/scripts`](/scripts) | Helper Python scripts (`.py` files) for modular code. |
| [`/results`](/results) | Generated outputs (plots, tables, model files). |
| [`requirements.txt`](requirements.txt) | List of Python dependencies. |
| [`LICENSE`](LICENSE) | MIT License for this repository. |

## Current Assignment: Validation Set Approach

**Objective:** Estimate the test error of a logistic regression model using the Validation Set Approach on the `Default` dataset.

### Methods
1.  **Data Preparation:** Load and explore the `Default` data.
2.  **Model Fitting:** Fit a logistic regression model (`default ~ income + balance`).
3.  **Validation:** 
    - Split the data into training (70%) and validation (30%) sets.
    - Fit the model on the training set.
    - Predict on the validation set and calculate the misclassification error rate.

## Getting Started

### 1. Run in Google Colab (Easiest)
Click the link below to open the notebook and run it directly in your browser:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dh-kt/Statistical-Learning-Resampling-Methods/blob/main/notebooks/validation_set_approach.ipynb)

### 2. Run Locally on Your Machine
```bash
# 1. Clone this repository
git clone https://github.com/dh-kt/Statistical-Learning-Resampling-Methods.git

# 2. Navigate to the project folder
cd Statistical-Learning-Resampling-Methods

# 3. Install required Python libraries
pip install -r requirements.txt

# 4. Open the notebook and run it
jupyter notebook notebooks/validation_set_approach.ipynb
