# AI-Powered Credit System

## Overview
This repository contains an AI-powered credit scoring system designed to predict the probability that a borrower will experience financial distress in the next two years. The models are built using historical credit data to help financial institutions make informed lending decisions.

## Project Structure
- `GiveMeSomeCredit/`: Contains the raw datasets used for training and testing (`cs-training.csv`, `cs-test.csv`, `sampleEntry.csv`) along with the data dictionary.
- `barclays_prototype.ipynb`, `prototype.ipynb`, `prototype1.ipynb`: Jupyter Notebooks containing the core exploratory data analysis (EDA), data preprocessing, feature engineering, and machine learning model training.
- `Untitled.html`: Exported web version of the notebook analysis or prototype UI.
- `data.csv`: Supplementary or processed data utilized during the analysis.

## Dataset
The project is built on the popular "Give Me Some Credit" dataset. It includes historical data on borrowers, such as their age, income, debt ratio, and number of dependents, alongside their credit history (e.g., times past due). The target variable is whether the borrower experienced 90 days past due delinquency or worse.

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/jayxmukati/AI-Powered-Credit-System.git
   cd AI-Powered-Credit-System
   ```

2. **Set up the environment:**
   Ensure you have Python installed along with Jupyter, Pandas, Scikit-Learn, and visualization libraries like Matplotlib or Seaborn.
   ```bash
   pip install jupyter pandas scikit-learn matplotlib seaborn
   ```

3. **Run the Notebooks:**
   Open the Jupyter Notebooks to explore the data and models:
   ```bash
   jupyter notebook barclays_prototype.ipynb
   ```

## Future Enhancements
- Deploy the machine learning model as a REST API (using FastAPI or Flask).
- Develop a frontend web application for loan officers to enter applicant details and receive real-time credit score predictions.
- Experiment with more advanced ensemble models (e.g., XGBoost, LightGBM) for improved predictive accuracy.
