# Telecom Churn Prediction

## Overview
This project addresses customer churn in the telecom industry by leveraging predictive analytics. Customer churn significantly impacts revenue and profitability, making it critical for businesses to proactively identify and retain at-risk customers. This project implements machine learning models to predict churn and provides actionable insights for retention strategies.

## Features
- **Exploratory Data Analysis (EDA):** Visualization and statistical summaries of customer demographics, account information, and service metrics.
- **Feature Engineering:** Handling missing values, encoding categorical data, and addressing class imbalance using techniques like SMOTE.
- **Model Development:** Training and evaluating Logistic Regression, Random Forest, and Gradient Boosting Machine models.
- **Performance Metrics:** Evaluating model performance using Precision, Recall, F1-Score, and ROC-AUC.

## Tools and Technologies
- **Python**: Core programming language.
- **Libraries**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn.
- **Jupyter Notebook**: Interactive development environment for coding and visualization.

## Project Workflow
1. **Data Preprocessing**
   - Cleaned the dataset by imputing missing values and removing duplicates.
   - Encoded categorical variables using one-hot encoding.
   - Addressed class imbalance through oversampling techniques.

2. **EDA and Visualization**
   - Analyzed features such as tenure, monthly charges, and contract types.
   - Visualized churn trends using heatmaps, bar charts, and scatter plots.

3. **Model Training and Evaluation**
   - Developed models to predict churn likelihood.
   - Evaluated models with metrics that prioritize true churners (Precision, Recall, and F1-Score).

4. **Insights and Recommendations**
   - Identified key churn predictors such as contract type and monthly charges.
   - Provided actionable insights to reduce churn through targeted campaigns.

## Results
- **Best Performing Model**: Gradient Boosting Machine (GBM)
  - **F1-Score**: 0.82
  - **ROC-AUC**: 0.91
- Key predictors of churn included short tenure, high monthly charges, and month-to-month contracts.

## Repository Structure
```
.
├── assets/                  # Images and visualizations used in the project
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter notebooks for analysis
├── src/                    # Source code for data preprocessing and model training
├── README.md               # Project overview (this file)
```

## How to Run
1. Clone the repository.
   ```bash
   git clone https://github.com/bowusus/Telecom-Churn-Prediction.git
   ```
2. Navigate to the project directory.
   ```bash
   cd Telecom-Churn-Prediction
   ```
3. Install required libraries.
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook.
   ```bash
   jupyter notebook notebooks/churn_analysis.ipynb
   ```

## Ethical Considerations
- **Bias Mitigation:** Ensured models are not biased against any demographic groups.
- **Data Privacy:** Followed anonymization practices to protect customer identities.
- **Transparency:** Clearly communicated model predictions and their implications.

## Future Work
- Incorporate additional features such as customer satisfaction scores and competitor pricing.
- Extend the analysis to other industries facing similar churn challenges.

## Author
Bernard Owusu Sefah  
[GitHub](https://github.com/bowusus) | [LinkedIn](https://www.linkedin.com/in/bernard-owusu-sefah-137188171/)

