Student Mental Health & Stress Analysis
This project analyzes mental health, treatment, and stress factors among survey respondents. The data is loaded from an Excel dataset and visualized using Python libraries.

📌 Dataset
Source: Survey data collected in Excel format

File: Dataset.xlsx (sheet: Form Responses 1)

The dataset contains:

Demographic info (Gender, Age)

Mental health diagnosis and treatment history

Multiple stress-related questions with numeric ratings

🧹 Data Cleaning & Preparation
Column names cleaned for uniformity (lowercase, underscores, special chars removed)

Key columns renamed for clarity:

mental_health_diagnosis

treatment

Timestamp column dropped (if present)

Stress question columns renamed systematically (stress_1, stress_2, …)

String columns trimmed and normalized (e.g., gender title case)

📈 Visualizations
Gender distribution — count plot showing respondent gender breakdown

Mental health diagnosis vs. treatment — count plot grouped by treatment status

Average stress levels — bar chart showing mean stress score per stress factor

All plots use seaborn with a clean whitegrid style and are sized for clarity.

🚀 How to Run
Upload the Excel file (Dataset.xlsx) to your working directory or Google Colab

Run the provided Python script or notebook cells sequentially

Visualizations will render inline (in Jupyter/Colab) or in pop-up windows (locally)

🛠️ Tools Used
Python 3

pandas (data manipulation)

matplotlib, seaborn (visualizations)

Jupyter Notebook / Google Colab (interactive environment)

Author: Yashaswini M
Date: June 2025
Environment: Google Colab recommended for ease of file upload and visualization
