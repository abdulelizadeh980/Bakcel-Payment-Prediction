# 📊 SPSS Capstone Project – 30, 60, 90 Day Non-Payment Prediction

This project aims to identify subscribers who are likely to **miss their payments within 30, 60, and 90 days** using both **statistical** and **artificial intelligence (AI)** modeling techniques.  
The entire analysis was conducted in **IBM SPSS Modeler (Clementine)** following the **CRISP-DM** data mining methodology.

---

## 🧠 Project Overview

![SPSS Bakcell](SPSS_Bakcell_Prediction.png)


**Dataset:** `Ecmp_Crdt_Scr_BA.xls`  
**Created On:** 01.03.2018  
**Number of Records:** 25,000 subscribers  

**Business Requirement:**  
Predict the **probability of non-payment** at 30, 60, and 90 days for each subscriber.

**Objective:**  
- Build **two types of models** (Statistical & AI-based) for predicting non-payment risk.  
- Evaluate and compare their performance.  
- Discuss potential integration of both models for optimal decision-making.

**Project Deadline:** 26 September, 23:59  

---

## ⚙️ Tools and Methods Used

| Tool / Method | Purpose |
|----------------|----------|
| **IBM SPSS Modeler (Clementine)** | Data mining, modeling, and deployment |
| **Statistical Model (e.g., Logistic Regression)** | Baseline risk prediction |
| **AI Model (e.g., Neural Network / Decision Tree)** | Advanced prediction with nonlinear relationships |
| **CRISP-DM Framework** | End-to-end analytical workflow structure |

---

## 🧩 Project Workflow (CRISP-DM Methodology)

The project follows a **hierarchical CRISP-DM process**, where each phase is represented as a **SuperNode** within the SPSS Modeler stream.

### 1. Business Understanding
- Defined the key question: *Which subscribers are likely to default within 30, 60, or 90 days?*  
- Established project goals and performance metrics.  
- Determined that models will be compared by accuracy, sensitivity, and ROC/AUC values.

### 2. Data Understanding
- Imported data from `Ecmp_Crdt_Scr_BA.xls`.  
- Reviewed variable definitions, types, and missing values.  
- Identified potential predictors affecting payment behavior.  
- Explored initial patterns and anomalies using visualization nodes.

### 3. Data Preparation
- Cleaned invalid, missing, or duplicate records.  
- Transformed variables (normalization, reclassification).  
- Derived new features relevant to payment behavior.  
- Prepared structured data for modeling.  
- Created summarized analytics and visual dashboards.

### 4. Modeling
Two distinct modeling approaches were used:

#### a. **Statistical Model**
- Technique: Logistic Regression (or similar)
- Objective: Establish a baseline model for default prediction.
- Advantages: Easy interpretability, statistical validity.

#### b. **AI Model**
- Technique: Neural Network or Decision Tree
- Objective: Capture nonlinear relationships and improve accuracy.
- Advantages: Strong predictive performance, adaptability to complex data.

#### c. **Time Horizons**
Each model was trained separately for:
- **30-Day Non-Payment Prediction**
- **60-Day Non-Payment Prediction**
- **90-Day Non-Payment Prediction**

### 5. Model Evaluation
- Compared both models using SPSS evaluation charts and metrics:
  - Accuracy
  - Precision / Recall
  - ROC Curve / AUC
  - Lift & Gain charts
- Discussed performance differences between Statistical vs. AI models.
- Evaluated combined or hybrid model potential.

### 6. Deployment
- Integrated the best-performing model(s) into a **Decision Support System** concept.
- Created **Deployment Nodes** for scoring and result export.
- Discussed how predictive results could be used in subscription risk management.

---

## 📊 Project Stream Design

Each CRISP-DM phase was implemented as a **SuperNode** in SPSS Modeler:

| SuperNode Name | Purpose |
|----------------|----------|
| **Business Understanding** | Define objective and project plan |
| **Data Understanding** | Explore and analyze raw data |
| **Data Preparation** | Clean, transform, and prepare dataset |
| **Modeling** | Build Statistical and AI models |
| **Model Evaluation** | Compare model results and select the best |
| **Deployment** | Generate outputs and prepare for integration |

The main SPSS stream includes branches for **30-day**, **60-day**, and **90-day** modeling, each followed by evaluation and deployment nodes.

---

## 🧮 Results Summary (Example Template)

| Model Type | Time Horizon | Accuracy | AUC | Notes |
|-------------|--------------|-----------|------|-------|
| Statistical | 30 Days | 0.86 | 0.91 | Good interpretability |
| Statistical | 60 Days | 0.83 | 0.88 | Slight drop over time |
| Statistical | 90 Days | 0.81 | 0.85 | Predictive power declines |
| AI Model | 30 Days | 0.90 | 0.94 | Best short-term prediction |
| AI Model | 60 Days | 0.87 | 0.92 | Balanced results |
| AI Model | 90 Days | 0.85 | 0.90 | Strong long-term stability |

> *(The above table is a placeholder for your actual model evaluation results.)*

---

## 🧰 Technical Requirements

- IBM SPSS Modeler (version 18 or later)
- Microsoft Excel (for `.xls` dataset)
- Windows OS environment

---

## 🚀 How to Run

1. Open **IBM SPSS Modeler**.  
2. Load the dataset: `Ecmp_Crdt_Scr_BA.xls`.  
3. Follow the CRISP-DM workflow:
   - Business Understanding → Data Understanding → Data Preparation → Modeling → Evaluation → Deployment  
4. Execute the **SuperNodes** step-by-step or run the complete stream.  
5. Compare model outputs for 30-, 60-, and 90-day predictions.

---

## 👤 Author

**Name:** Abdulsalam Elizade  
**Role:** Data Analyst  
**Project Type:** Predictive Modeling & Risk Analysis  
**Focus Areas:** Credit Scoring, Customer Behavior Prediction, AI vs. Statistical Comparison  

---

## 📌 Notes

This project demonstrates a real-world predictive analytics scenario using **IBM SPSS Modeler**, comparing **statistical** and **AI-based** modeling approaches for **subscription payment risk** prediction at multiple time horizons (30, 60, 90 days).

The project is structured according to **CRISP-DM methodology** and serves as a complete example of applied data science for business decision support.

---

🧡 _Created by Abdulsalam Elizade — Applying data science and CRISP-DM methodology for intelligent decision-making._
