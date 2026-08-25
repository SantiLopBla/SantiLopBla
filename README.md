<div align="center">

# Santiago López Blanco

### Data Science Engineering Student · ML & Analytics

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&pause=1000&color=FF3621&center=true&vCenter=true&width=600&lines=Building+ML+Pipelines+on+Databricks;Supervised+%26+Unsupervised+Learning;Feature+Engineering+%26+Model+Tuning;From+Raw+Data+to+Actionable+Predictions)](https://git.io/typing-svg)

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiago-lopez-blanco-ds)
[![Databricks](https://img.shields.io/badge/Databricks_Profile-FF3621?style=flat-square&logo=databricks&logoColor=white)](https://credentials.databricks.com/profile/santiagolpezblanco626690/wallet)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/SantiLopBla)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/users/santiago-lopez-blanco)

<br>

</div>

## 👤 About me

Data Science Engineering student at Universidad Fidélitas (Costa Rica), focused on machine learning and end-to-end data pipelines. I'm drawn to problems where data changes how an organization makes decisions, and I enjoy the full process — from raw data to production-ready predictions.

Currently seeking my first professional role in **data science / data analytics**.

## 🛠️ Tech stack

<table>
  <tr>
    <td valign="top" width="25%">

**Data & AI Platform**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

  </td>
  <td valign="top" width="25%">

**Languages & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

  </td>
  <td valign="top" width="25%">

**Machine Learning & Viz**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2C8EBB?style=flat-square&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat-square&logoColor=white)

  </td>
  <td valign="top" width="25%">

**Dev & Version Control**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

  </td>
  </tr>
</table>

## 🚀 Featured projects — Machine Learning

<table>
  <tr>
    <td width="50%" valign="top">

### 🟠 Warehouse & Retail Sales ML

**Demand Forecasting · Databricks**

Machine learning pipeline to predict monthly product demand for a wholesale liquor distributor, using 307,645 real sales transactions from a U.S. government dataset.

`data ingestion → cleaning → analysis → modeling → forecast`

Compared 4 models. Best result: **LightGBM · 96.81% accuracy · mean error of $279 per prediction**, tested on 2020 data — a COVID year the model never saw during training.

`Python` `Apache Spark` `Delta Lake` `MLflow` `LightGBM` `XGBoost`

[![Repo](https://img.shields.io/badge/View_Repository-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/SantiLopBla/warehouse-retail-sales-ml)

  </td>
  <td width="50%" valign="top">

### 🔵 Churn Prediction

**End-to-End ML Pipeline**

Production-style ML pipeline to predict customer churn from telecom data.

`ingestion → validation → feature engineering → training → tuning → evaluation`

Models: Logistic Regression · Random Forest · XGBoost · GridSearchCV

`Python` `Scikit-learn` `XGBoost` `Pandas`

[![Repo](https://img.shields.io/badge/View_Repository-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/SantiLopBla/churn-prediction)

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### 🟣 Kitsune Network Anomaly Detection

**Network Intrusion Detection · Databricks — In progress**

Medallion Architecture pipeline built on the Kitsune Network Attack dataset (UCI, SYN DoS subset) to detect anomalous network traffic at scale.

`bronze (raw ingestion) → silver (transformation) → gold (feature store / modeling)`

Bronze layer complete: Unity Catalog structure, Delta table with **2,771,276 rows**, 115 renamed features, labels joined via `monotonically_increasing_id()`. Silver transformation notebook next.

`Python` `PySpark` `Databricks` `Delta Lake` `Unity Catalog`

[![Repo](https://img.shields.io/badge/View_Repository-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/SantiLopBla/kitsune-network-anomaly-detection)

  </td>
  <td width="50%" valign="top">

  </td>
  </tr>
</table>

## 📂 Other projects

### 🟡 Zara Sales EDA — Exploratory Data Analysis

Deep-dive retail analytics uncovering revenue patterns, product performance, and seasonality trends. Business-oriented visual storytelling.

`cleaning → univariate analysis → bivariate analysis → insights`

`Python` `Pandas` `Matplotlib` `Seaborn`

[![Repo](https://img.shields.io/badge/View_Repository-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/SantiLopBla/Zara-Sales-EDA)

## 📜 Certifications

| Certificate | Issuer | Date | Verify |
|---|---|---|---|
| Get Started with Databricks for Machine Learning | Databricks Academy | Jun 2026 | [View on Wallet](https://credentials.databricks.com/profile/santiagolpezblanco626690/wallet) |
| Generative AI Fundamentals | Databricks Academy | May 2026 | [Link](https://credentials.databricks.com/77d2610b-0e6e-459f-ac92-d63373e33760#acc.Cc0L3UPG) |
| Machine Learning Specialization | Stanford Online / DeepLearning.AI | May 2026 | [Link](https://www.coursera.org/account/accomplishments/specialization/EGLC12RFQOIY) |
| Introduction to Python for DS & DE | Databricks Academy | Dec 2025 | [Link](https://credentials.databricks.com/78bb0747-02bc-4b2c-b4b3-a6f236b3e3f7?username=santiagolpezblanco626690) |
| Databricks Fundamentals | Databricks Academy | Nov 2025 | [Link](https://credentials.databricks.com/c719f1f7-b09d-4200-82bd-655af8a58746) |
| Excel Básico (Virtual) | Universidad Fidélitas | Aug 2025 | — |
| Introduction to Data Science | Cisco Networking Academy | Jun 2025 | [Link](https://www.credly.com/badges/23d5627c-938d-4be2-afa9-453274165685/public_url) |
| Business Intelligence Foundation (BIFPC) | Certiprof | Jan 2025 | [Link](https://www.credly.com/earner/earned/badge/d72c334d-9f7e-48f8-af2e-0cbc9012a40b) |
| Business Agility (BAPC) | Certiprof | Dec 2024 | [Link](https://www.credly.com/earner/earned/badge/54dcaaf5-5829-4173-a37e-458890afb7af) |
| Scrum Foundation (SFPC) | Certiprof | Dec 2024 | [Link](https://www.credly.com/earner/earned/badge/c8bd637e-2e65-4361-8123-c5ba4f1ca447) |

**In progress**
- Microsoft Azure Databricks Data Engineer Associate (DP-750) — exam scheduled October 2026
- Google Cloud Computing Foundations — Google Skills Boost (Universidad Latina & Google scholarship)

## 🌐 Languages

| Language | Level |
|---|---|
| Spanish | Native |
| English | B2 — Linguaskill (Cambridge) |

## 📊 GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SantiLopBla&show_icons=true&theme=github_dark&hide_border=true&count_private=true" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SantiLopBla&layout=compact&theme=github_dark&hide_border=true" width="48%"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=SantiLopBla&theme=github-dark&hide_border=true" width="60%"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SantiLopBla&theme=github-compact&hide_border=true&color=FF3621&line=FF3621&point=ffffff" width="100%"/>

</div>

## 🤝 Let's connect

<div align="center">

I'm open to opportunities in data science and analytics. Feel free to reach out.

<br>

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiago-lopez-blanco-ds)
[![Credly](https://img.shields.io/badge/View_my_badges-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/users/santiago-lopez-blanco)
[![Databricks](https://img.shields.io/badge/Databricks_Profile-FF3621?style=flat-square&logo=databricks&logoColor=white)](https://credentials.databricks.com/profile/santiagolpezblanco626690/wallet)

</div>
