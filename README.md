# Project Management Analytics: EDA & Predictive Modeling

This repository contains a complete project demonstrating how data analysts, business analysts and program managers can leverage data science techniques to extract insights from project data and build predictive models. The project is designed as a **portfolio piece** for roles in business analysis, program management or data analytics.

## Overview

Organizations monitor metrics like budget adherence, schedule performance, risk levels and stakeholder engagement to evaluate project success【729401205523784†L170-L207】. By analysing these metrics, analysts can uncover patterns, identify risks early and make data‑driven decisions to improve outcomes. This repository provides:

- A **synthetic dataset** simulating 500 project records with attributes such as budget, team size, complexity, risk level, stakeholder engagement and a binary success indicator.
- A **Jupyter notebook** that performs exploratory data analysis (EDA), visualizes relationships among variables and trains predictive models (logistic regression and random forest) to estimate project success.
- A **requirements.txt** file listing Python dependencies.

The project gradually increases in difficulty: starting with simple summary statistics and plots, moving to correlation analysis, and culminating with machine learning models. You can extend the notebook with more advanced algorithms, cross‑validation and feature engineering to demonstrate deeper expertise.

## Dataset

The dataset (`synthetic_project_data.csv`) is synthetic but loosely based on common project management KPIs. Each row represents a project and includes:

| Column | Description |
|-------|------------|
| `project_id` | Unique identifier for each project. |
| `start_date`, `end_date` | Project start and end dates (YYYY‑MM‑DD). |
| `budget_usd` | Estimated project budget in US dollars. Budget control is a core metric in project management【729401205523784†L170-L207】. |
| `team_size` | Number of people assigned to the project. |
| `complexity` | Integer from 1–10 representing technical or organizational complexity. |
| `risk_level` | Integer from 1–5 indicating perceived project risk. Monitoring risk helps mitigate problems early【729401205523784†L220-L235】. |
| `stakeholder_engagement_score` | Score from 1–10 summarizing stakeholder involvement and communication【154641038672183†L638-L653】. |
| `business_value` | Numeric estimate of the value delivered by the project. |
| `duration_days` | Duration of the project in days. |
| `success` | Binary indicator (1 = success, 0 = failure) derived from other features.

> **Note:** Because the data is synthetic, it does not represent any real organization or confidential information. It is safe to use publicly as a demonstration project.

## Getting Started

### Prerequisites

Install the required Python libraries (ideally within a virtual environment):

```bash
pip install -r requirements.txt
```

### Running the Notebook

1. Launch JupyterLab or Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open `analysis_notebook.ipynb` and run the cells sequentially. The notebook will:

   - Load and explore the dataset.
   - Produce summary statistics and visualizations.
   - Build logistic regression and random forest models to predict project success.
   - Summarize results and suggest next steps.

You can modify the notebook to experiment with additional models, feature engineering or cross‑validation techniques.

## Extending This Project

To increase the difficulty and showcase more advanced skills:

- Add calculations for classic project management metrics such as Schedule Variance (SV), Cost Performance Index (CPI) and Earned Value (EV)【729401205523784†L248-L287】.
- Perform hyperparameter tuning and cross‑validation for the machine learning models.
- Build dashboards using libraries like Plotly or PowerBI to communicate insights.
- Deploy the model as a web service or integrate it into a project management tool.

## License

This project is provided for educational purposes and may be used freely. There is no warranty implied.

