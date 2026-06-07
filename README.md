# ✈️ Flight Price Prediction & Surge Pricing Analytics Dashboard

## 🚀 Project Overview

This project analyzes aviation transactional data to uncover critical insights related to ticket pricing dynamics, booking windows, and travel class distributions.
Additionally, it integrates a Machine Learning predictive engine to forecast flight fares and optimize dynamic surge pricing matrices.
The entire lifecycle spans data engineering in Python, relational feature analysis, and deployment via an interactive executive dashboard in Power BI.

---

## 🎯 Objectives

* Track airline fare variations across multiple operational attributes.
* Evaluate the price elasticity of tickets based on the booking window (`days_left`).
* Measure and isolate the asymmetric impact of surge triggers across distinct travel classes.
* Deploy an interactive, high-fidelity Business Intelligence repository for predictive performance monitoring.

---

## 🛠️ Tools & Technologies

* **Python (Pandas, NumPy, Seaborn)**
* **Jupyter Notebook**
* **Machine Learning (Random Forest / XGBoost Regressors)**
* **Power BI Desktop**
* **Power Query & Advanced DAX**
* **Custom JSON Telemetry Injections**

---

## 📂 Project Workflow

### 1. Data Engineering & Pre-processing (Python)
* Executed systematic data cleaning and feature profiling within Jupyter Notebook.
* Programmatically handled structural attributes (`airline`, `flight`, `source_city`, etc.) for over 300,150 raw records.
* Exported the fully scrubbed and optimized dataset as a production-ready baseline.

### 2. Predictive Pipeline Modeling (ML)
* Engineered supervised regression frameworks to predict prices.
* Validated model telemetry, achieving an **$R^2$ Score (Accuracy) of 0.91** and a highly controlled **Root Mean Squared Error (RMSE) of ₹2,145**.

### 3. ETL Transformation & DAX Analytics
* Ingested datasets into Power BI via Power Query for schema parsing and conditional group mapping.
* Authored custom DAX measures to calculate runtime executive metrics like total training matrices, model validation errors, and overall prediction accuracy limits.

### 4. Enterprise UI/UX Design & Dashboarding
Injected a custom `Cyber Slate Dark` theme layout to construct a unified multi-page analytics ecosystem:
* **Flight Pricing Insights (Page 1):** Focuses on volumetric distribution patterns and market share metrics.
* **ML Models Insights (Page 2):** Implements dynamic visual cockpits to evaluate pricing densities and dynamic surge triggers.

---

## 📈 Key Insights

* **Volume Dominance vs Equity:** Economy class commands **88.88%** of absolute booking volume, while Business class captures **11.12%**. However, revenue pools are heavily concentrated in the premium spectrum.
* **Asymmetric Surge Constraints:** Business Class tickets entirely bypass baseline flat-rate categories, operating solely inside active yield matrices that scale past **₹50,000** under heavy demand triggers.
* **Booking Elasticity Window:** Data density curves prove sharp price elasticity in lower tiers, indicating that discount restrictions should strictly trigger exactly **20 days prior to departure** to maximize revenue margins.

---

## 📸 Dashboard Preview

![image alt](https://github.com/ShubhamCodesDS/Flight-Price-Prediction-Surge-Pricing-Analytics/blob/1d199d5f00a79f75785ee0d61dd2cb86be553baa/Dashboard.png)

---

## 📁 Repository Structure

```text
Flight-Price-Prediction-Project/
│
├── Data/
│   └── Clean_Flight_Dataset.csv                                                    # Cleaned baseline dataset (300K+ records)
├── Notebooks/
│   └── Flight Fare Analytics and Dynamic Pricing Insights Using Python & Machine Learning.ipynb  # Python ML Training Pipeline
├── Theme/
│   └── ML_Theme.json                                                               # Injected Custom Theme Layout Configuration
├── Flight_Pricing_Pro.pbix                                                         # Master Power BI Application File
├── Dashboard_Screenshot.png                                                        # System application preview image
└── README.md                                                                       # Comprehensive Project Documentation

💡 Skills Demonstrated
End-to-End Data Science Pipeline Execution

Programmatic Feature Engineering & Data Cleansing

Predictive Regression Modeling (Supervised ML)

Custom DAX Architecture & Modeling

Advanced Corporate Data Visualization

Yield Management & Strategic Business Intelligence Reporting

👨‍💻 Author
Shubham Prajapati

Aspiring Data Analyst and Machine Learning Developer passionate about transforming raw enterprise datasets into actionable predictive frameworks and high-impact business intelligence solutions.
