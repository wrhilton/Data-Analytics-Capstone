This is my capstone project I did for the B.S. in Data Analytics at WGU. Dataset provided by IBM. Work is my own.

# Employee Attrition Prediction and Analysis Capstone Project

## Overview

This project analyzes the factors influencing employee turnover using the IBM HR Analytics Employee Attrition & Performance dataset[cite: 4, 144]. High employee turnover presents significant costs to organizations, including recruitment, training, and the loss of institutional knowledge[cite: 2, 139]. This project aims to identify the key drivers of employee attrition and develop predictive models to assist HR departments in implementing targeted retention strategies, thereby improving workforce stability[cite: 3, 140].

## Research Question

The primary research question guiding this analysis is:
"Are ensuring that employees are well compensated and find satisfaction in their jobs the leading factors in preventing employee turnover?" [cite: 1, 138]

## Data Source

* **Dataset:** IBM HR Analytics Employee Attrition & Performance [cite: 4, 144]
* **Source:** Kaggle [cite: 4, 144]
* **Volume:** 1,470 employee records with 35 features [cite: 5]

## Methodology

The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology[cite: 14], encompassing the following phases:
1.  Business Understanding
2.  Data Understanding
3.  Data Preparation (including cleaning and encoding) [cite: 12]
4.  Exploratory Data Analysis (EDA) [cite: 8, 12]
5.  Predictive Modeling (Logistic Regression and Naïve Bayes models developed) [cite: 9, 12]
6.  Evaluation (using metrics like Accuracy, Precision, Recall, ROC-AUC) [cite: 10, 12]
7.  Deployment (formulating actionable insights and recommendations) [cite: 14]

## Tools Used

* **Programming Language:** Python [cite: 7]
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn [cite: 7]
* **Development Environment:** Jupyter Notebook [cite: 8]
* **Data Storage:** CSV Files [cite: 8]

## Files in this Repository

1.  **`Capstone Paper.pdf`**: A comprehensive research paper detailing the project's overview, execution, results, analysis, and actionable recommendations[cite: 1].
2.  **`Wesley_Hilton_Employee_Attrition_Capstone.ipynb`**: The Jupyter Notebook containing all Python code for data loading, cleaning, exploratory data analysis, model training, evaluation, and visualization[cite: 1].
3.  **`Capstone Research Question and Organizational Need.pdf`**: A document outlining the research question, organizational need, project context, and summaries of related published works[cite: 138, 139, 140, 145].

## Key Findings

The analysis identified several key factors influencing employee turnover, with compensation and job satisfaction emerging as significant predictors[cite: 11, 80, 146]. Predictive models (Logistic Regression, Naïve Bayes) were successfully developed and evaluated to identify employees at risk of attrition[cite: 9].

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    ```
2.  **Navigate to the directory:**
    ```bash
    cd <repository_directory>
    ```
3.  **Install Dependencies:** Ensure you have Python and the necessary libraries (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn) installed. You can typically install them using pip:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```
4.  **Run the Analysis:** Open and run the `Wesley_Hilton_Employee_Attrition_Capstone.ipynb` notebook using Jupyter Notebook or JupyterLab to view the complete analysis, code, and visualizations.
5.  **Review Documentation:** Refer to `Capstone Paper.pdf` for a detailed explanation of the project, methodology, and findings. The `Capstone Research Question and Organizational Need.pdf` provides additional context.

## Actionable Strategies

Based on the analysis, targeted retention strategies focusing on improving compensation structures and enhancing job satisfaction were formulated to help HR leadership reduce attrition[cite: 7, 11, 80].
