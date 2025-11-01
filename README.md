# PLS-SEM (Partial Least Squares Structural Equation Modeling) Simulator

This repository provides an **interactive and customizable framework** for generating and analyzing **Partial Least Squares Structural Equation Modeling (PLS-SEM)** with **synthetic (dummy) data**.  
Designed to support **researchers, educators, and data scientists**, this simulator enables **rapid prototyping** of both *inner* (structural) and *outer* (measurement) models with full control over parameters, data distributions, and correlation structures.

---

## 📖 Background

In quantitative research, especially in **social sciences, marketing, and behavioral studies**, **PLS-SEM** plays a crucial role in analyzing complex relationships between **latent variables** and **observed indicators**.  
However, building and validating such models often require **large and well-structured datasets**, which are not always accessible.

This project addresses that limitation by introducing a **PLS-SEM Simulator** that can:
- Generate **controlled synthetic datasets** based on defined measurement and structural paths.  
- Visualize **model relationships**, **data distributions**, and **evaluation metrics** intuitively.  
- Provide a **teaching and experimentation tool** to better understand how parameter changes affect model validity and reliability.

---

## 🧠 Key Features

- **Model Definition Layer**  
  Build **inner (structural)** and **outer (measurement)** models interactively, defining latent constructs, indicators, and causal paths.

- **Dummy Data Generation**  
  Automatically generate **synthetic data** with controlled **distribution types**, **correlations**, and **error terms** to simulate realistic research conditions.

- **Visual Descriptive Analytics**  
  Explore data behavior and construct relationships using **Python visualization** tools for better interpretability and model refinement.

- **Statistical Evaluation**  
  Evaluate **Composite Reliability**, **Average Variance Extracted (AVE)**, **Path Coefficients**, and **R²** values to assess both **measurement** and **structural** model validity.

- **Scenario Testing**  
  Simulate various hypothetical conditions to understand how **parameter shifts** or **sample variations** impact model results — supporting both **teaching** and **decision-support system (DSS)** use cases.

---

## 📊 Example Visualizations

| Model Structure | Data Distribution | Statistical Evaluation |
|:--:|:--:|:--:|
| <img src="assets/model_visualization.png" width="260"/> | <img src="assets/data_distribution.png" width="260"/> | <img src="assets/statistical_evaluation.png" width="260"/> |

---

## 🧩 Tech Stack
**Languages & Libraries:**  
`Python`, `NumPy`, `Pandas`, `Scikit-learn`, `Matplotlib`, `Plotly`, `PLSPM`

---

## 🚀 Future Improvements
- Expansion to **nonlinear** and **moderation/mediation** path modeling.
