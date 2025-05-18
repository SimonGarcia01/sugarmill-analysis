# Context

Ingenio Providencia has a historical dataset that gathers relevant information about sugarcane production. The objective of this workshop is for you, as students, to apply the knowledge acquired during the course to develop models that will enable the completion of the following tasks.

## Business Objective

Build and validate an AI model to predict either:

- The **percentage of sucrose in sugarcane**, or
- The **tons of cane per hectare (TCH)**.

A 2017 dataset is provided, containing the most relevant variables for a sugar mill (TCH and sucrose). The goal of this lab is to conduct exploratory data analysis (EDA) to explore, clean, and prepare the dataset for AI model ingestion in order to make the aforementioned predictions.

---

## 1. Regression (`HISTORICO_SUERTES.xlsx`)

Predict two key variables:

- **Tons of cane per hectare (TCH):** Indicator of land productivity.
- **Sucrose percentage (%Sac.Caña):** Measure of the quality of the cane and amount of extractable sugar.

### Model Development

- Fit linear regression models to predict TCH and %Sac.Caña.
- Analyze variable significance, interpret model coefficients, and evaluate assumptions (linearity, homoscedasticity, error normality).
- Diagnose and address issues such as multicollinearity or outliers (e.g., using regularization).

### Validation and Evaluation

- Use validation strategies (holdout and/or cross-validation).
- Calculate and report at least two appropriate evaluation metrics (e.g., R², RMSE, MAE).
- Discuss the results obtained.

---

## 2. Classification (`BD_IPSA_1940.xlsx`)

Use the continuous variables (TCH and %Sac.Caña) to create performance categories:

- **%Sac.Caña:** High, medium, and low sucrose levels.
- **TCH:** High, medium, and low productivity levels.

### Creation of Categories

- Define thresholds to transform TCH and %Sac.Caña into categorical levels.
- Justify the methodology used (e.g., percentiles, business rules).

### Model Development

- Fit a logistic regression model and/or apply the K-Nearest Neighbors (KNN) algorithm.
- Use regularization to analyze the impact of predictor variables on classification performance.

### Validation and Evaluation

- Employ a validation strategy (e.g., cross-validation) and justify the choice.
- Report and analyze classification metrics: accuracy, precision, recall, F1-score, and kappa.

---

## Evaluation Criteria

### Clarity and Rigor in Analysis

- Correct implementation of regression and classification models.
- Proper interpretation of results, variable significance, and model assumptions.

### Validation and Metrics

- Appropriate selection and application of validation strategies.
- Accurate use of evaluation metrics and critical analysis of results.

### Communication of Results

- Clear and concise written report detailing the process, results, and conclusions.
- Use of graphs and visualizations to support the analysis.

---

## Deliverable

- Work must be done in groups of **three or four students**.
- Submit a **PDF report** (max 5 pages) including the **names of the members**.
- The report must **detail the full analysis process**, results, interpretations, and conclusions.
- **Do not include code** in the document.