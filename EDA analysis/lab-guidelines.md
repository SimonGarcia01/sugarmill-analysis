# Context

Ingenio Providencia has a historical dataset that gathers relevant information about sugarcane production. The objective of this workshop is for you, as students, to apply the knowledge acquired during the course to develop models that will enable the completion of the following tasks.

## Business Objective

Build and validate an AI model to predict either the variable "percentage of sucrose in sugarcane" or "tons of cane per hectare (TCH)."

You will find below a database from the year 2017 with data associated with the most important variables for a sugar mill (TCH and sucrose). The goal of this lab is to make progress on exploratory data analysis (EDA) in order to explore the dataset, clean it, and prepare it for ingestion by AI models for the purpose of making the above-mentioned predictions.

---

## 1. Regression (`HISTORICO_SUERTES.xlsx`)

Predict two key variables:

- **Tons of cane per hectare (TCH):** Indicator of land productivity.
- **Sucrose percentage (%Sac.Caña):** A measure of cane quality and the amount of extractable sugar.

---

## 2. Classification (`BD_IPSA_1940.xlsx`)

From the continuous variables (TCH and %Sac.Caña), create categories that allow classification of the records into performance levels:

- For %Sac.Caña: High, medium, and low sucrose levels.
- For TCH: High, medium, and low productivity levels.

Correct prediction and categorization of these variables will allow the sugar mill to make more informed and efficient decisions regarding crop planning and management.

---

## General Instructions

### Regression Model

**Exploratory Data Analysis (EDA):**

- Perform an initial exploration of the dataset: identify relevant variables, detect missing values, and possible outliers.
- Visualize the distribution of the target variables (TCH and %Sac.Caña).

---

### Classification Model

**Creation of Categories:**

- Define thresholds to transform the continuous variables TCH and %Sac.Caña into categories: high, medium, and low.
- Justify the methodology used to define these thresholds (e.g., percentiles, business criteria, etc.).

---

## Evaluation Criteria

### Clarity and Rigor in Analysis

- Ordered presentation of the EDA.
- Justification of decisions made during data transformation and preprocessing.

### Clarity

- You must submit a PDF report including the names of all team members.
- In this first part, you should **not** submit trained models.
- You must deliver the EDA and a detailed description of the data preparation process and analysis, ready to be passed on to the models.