<div align="center">

<img src="assets/banner.svg" width="100%" alt="Santiago López Blanco — Data Engineering · Data Quality · Databricks">

<br><br>

<a href="https://www.linkedin.com/in/santiago-lopez-blanco-ds"><img src="assets/badges/linkedin.svg" alt="LinkedIn" height="26"></a> <a href="https://credentials.databricks.com/profile/santiagolpezblanco626690/wallet"><img src="assets/badges/databricks-cred.svg" alt="Databricks Credentials" height="26"></a> <a href="https://www.credly.com/users/santiago-lopez-blanco"><img src="assets/badges/credly.svg" alt="Credly" height="26"></a> <a href="mailto:santilopbla06@gmail.com"><img src="assets/badges/email.svg" alt="Email" height="26"></a>

</div>

## About

Data Science Engineering student at Universidad Fidélitas, Costa Rica (GPA 95.9/100, expected graduation Oct 2027). I build data pipelines on Databricks with PySpark, Delta Lake and Unity Catalog, with a focus on data quality: pipelines that validate data and fail fast instead of passing bad data downstream.


**Open to:** data engineering, data analytics and data science internships or entry-level roles · Costa Rica (GAM) or remote.

<img src="assets/divider.svg" width="100%" alt="">

## Tech Stack

<table>
<tr>
<td valign="top" width="25%">

**Data Platform**

<img src="assets/badges/databricks.svg" alt="Databricks" height="26"> <img src="assets/badges/spark.svg" alt="Apache Spark" height="26"><br>
<img src="assets/badges/delta.svg" alt="Delta Lake" height="26"> <img src="assets/badges/unity.svg" alt="Unity Catalog" height="26"><br>
<img src="assets/badges/mlflow.svg" alt="MLflow" height="26"><br>
<img src="assets/badges/gcp.svg" alt="Google Cloud (Foundations)" height="26">

</td>
<td valign="top" width="25%">

**Languages & Data**

<img src="assets/badges/python.svg" alt="Python" height="26"> <img src="assets/badges/pyspark.svg" alt="PySpark" height="26"><br>
<img src="assets/badges/sparksql.svg" alt="Spark SQL" height="26"> <img src="assets/badges/sql.svg" alt="SQL (basic)" height="26"><br>
<img src="assets/badges/pandas.svg" alt="pandas" height="26"> <img src="assets/badges/numpy.svg" alt="NumPy" height="26"><br>
<img src="assets/badges/r.svg" alt="R (basic)" height="26"><br>
<img src="assets/badges/oracle.svg" alt="Oracle (basic admin)" height="26">

</td>
<td valign="top" width="25%">

**Machine Learning & Viz**

<img src="assets/badges/sklearn.svg" alt="scikit-learn" height="26"> <img src="assets/badges/xgboost.svg" alt="XGBoost" height="26"><br>
<img src="assets/badges/lightgbm.svg" alt="LightGBM" height="26"> <img src="assets/badges/matplotlib.svg" alt="Matplotlib" height="26"><br>
<img src="assets/badges/seaborn.svg" alt="Seaborn" height="26"><br>
<img src="assets/badges/powerbi.svg" alt="Power BI (basic)" height="26">

</td>
<td valign="top" width="25%">

**Engineering Practices**

<img src="assets/badges/git.svg" alt="Git" height="26"> <img src="assets/badges/github.svg" alt="GitHub" height="26"><br>
<img src="assets/badges/pytest.svg" alt="pytest" height="26"> <img src="assets/badges/jupyter.svg" alt="Jupyter" height="26"><br>
<img src="assets/badges/scrum.svg" alt="Scrum" height="26">

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Network Intrusion Data Pipeline (Kitsune)
**Databricks · Medallion Architecture · In progress**

Production-style pipeline over **2,771,276 network packets × 115 features** (UCI Kitsune, SYN DoS subset).

`landing → bronze → silver → gold (next)`

- Fail-fast data quality gates: schema contract, file size, row-count reconciliation, nulls, NaN/infinity, label domain and a post-write check
- Resolved a paper-vs-source-code conflict on the order of 115 unnamed columns by checking statistical invariants in a single PySpark pass
- Unity Catalog governance (dev catalog, per-layer schemas, comments, tags), Delta tables with liquid clustering, typed PySpark modules, PR-based Git workflow

<img src="assets/badges/tag-pyspark.svg" alt="PySpark" height="22"> <img src="assets/badges/tag-spark-sql.svg" alt="Spark SQL" height="22"> <img src="assets/badges/tag-delta-lake.svg" alt="Delta Lake" height="22"> <img src="assets/badges/tag-unity-catalog.svg" alt="Unity Catalog" height="22"> <img src="assets/badges/tag-git.svg" alt="Git" height="22">

<a href="https://github.com/SantiLopBla/kitsune-network-anomaly-detection"><img src="assets/badges/repo.svg" alt="View repository" height="26"></a>

</td>
<td width="50%" valign="top">

### Warehouse & Retail Sales Forecasting
**Databricks · Demand Forecasting**

Bronze → Silver → Gold pipeline turning **307K** U.S. government sales records into ML-ready Delta tables to forecast monthly product demand.

`ingestion → cleaning → features → modeling → forecast`

- Compared 4 models with time-series cross-validation and a 2020 (COVID) hold-out
- **LightGBM: R² 0.97 · MAE $279**, 23% below the linear baseline; registered in MLflow
- Spark SQL cut data sent to pandas by **98.4%**

<img src="assets/badges/tag-pyspark.svg" alt="PySpark" height="22"> <img src="assets/badges/tag-delta-lake.svg" alt="Delta Lake" height="22"> <img src="assets/badges/tag-mlflow.svg" alt="MLflow" height="22"> <img src="assets/badges/tag-lightgbm.svg" alt="LightGBM" height="22"> <img src="assets/badges/tag-xgboost.svg" alt="XGBoost" height="22">

<a href="https://github.com/SantiLopBla/warehouse-retail-sales-ml"><img src="assets/badges/repo.svg" alt="View repository" height="26"></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Customer Churn Prediction
**Modular ML Pipeline**

Pipeline for 7,043 telecom customers: validation, transformation, training, tuning and inference, covered by **8 pytest tests**.

- Leakage-safe preprocessing (imputer fit on training data only)
- Logistic Regression vs. Random Forest vs. tuned XGBoost with threshold optimization
- **AUC-ROC 0.85 · Recall 0.79**, prioritizing recall because missing a churner costs more than a false alarm

<img src="assets/badges/tag-scikit-learn.svg" alt="scikit-learn" height="22"> <img src="assets/badges/tag-xgboost.svg" alt="XGBoost" height="22"> <img src="assets/badges/tag-pandas.svg" alt="pandas" height="22"> <img src="assets/badges/tag-pytest.svg" alt="pytest" height="22">

<a href="https://github.com/SantiLopBla/churn-prediction"><img src="assets/badges/repo.svg" alt="View repository" height="26"></a>

</td>
<td width="50%" valign="top">

### Zara Sales EDA
**Exploratory Data Analysis**

Retail analysis of **22.2M units** and **$884.6M** in revenue.

- Jackets drive **55% of revenue** without being promoted more than other categories, a single-category concentration risk
- Business-oriented visual storytelling for non-technical readers

<img src="assets/badges/tag-pandas.svg" alt="pandas" height="22"> <img src="assets/badges/tag-matplotlib.svg" alt="Matplotlib" height="22"> <img src="assets/badges/tag-seaborn.svg" alt="Seaborn" height="22">

<a href="https://github.com/SantiLopBla/Zara-Sales-EDA"><img src="assets/badges/repo.svg" alt="View repository" height="26"></a>

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## Certifications

| Certification | Issuer | Date | Verify |
|---|---|---|---|
| **Azure Databricks Data Engineer Associate (DP-750)** | Microsoft | Oct 2026 | [Credential](https://learn.microsoft.com/api/credentials/share/es-mx/SantiagoLpezBlanco-2204/6BC60448E3684F2?sharingId=E76EF72697970AEE) |
| Google Cloud Computing Foundations | Google Cloud | Sep 2026 | [Credly](https://www.credly.com/badges/95a2dbda-fc95-4b11-be71-15df1b7b03b5/public_url) |
| Get Started with Databricks for Machine Learning | Databricks Academy | Jun 2026 | [Wallet](https://credentials.databricks.com/profile/santiagolpezblanco626690/wallet) |
| Generative AI Fundamentals | Databricks Academy | May 2026 | [Credential](https://credentials.databricks.com/77d2610b-0e6e-459f-ac92-d63373e33760#acc.Cc0L3UPG) |
| Machine Learning Specialization | Stanford Online / DeepLearning.AI | May 2026 | [Coursera](https://www.coursera.org/account/accomplishments/specialization/EGLC12RFQOIY) |
| Introduction to Python for DS & DE | Databricks Academy | Dec 2025 | [Credential](https://credentials.databricks.com/78bb0747-02bc-4b2c-b4b3-a6f236b3e3f7?username=santiagolpezblanco626690) |
| Databricks Fundamentals | Databricks Academy | Nov 2025 | [Credential](https://credentials.databricks.com/c719f1f7-b09d-4200-82bd-655af8a58746) |
| Introduction to Data Science | Cisco Networking Academy | Jun 2025 | [Credly](https://www.credly.com/badges/23d5627c-938d-4be2-afa9-453274165685/public_url) |
| Business Intelligence Foundation (BIFPC) | Certiprof | Jan 2025 | [Credly](https://www.credly.com/earner/earned/badge/d72c334d-9f7e-48f8-af2e-0cbc9012a40b) |
| Business Agility (BAPC) · Scrum Foundation (SFPC) | Certiprof | Dec 2024 | [BAPC](https://www.credly.com/earner/earned/badge/54dcaaf5-5829-4173-a37e-458890afb7af) · [SFPC](https://www.credly.com/earner/earned/badge/c8bd637e-2e65-4361-8123-c5ba4f1ca447) |

## Languages

**Spanish** — Native · **English** — B2, Cambridge Linguaskill 

<img src="assets/divider.svg" width="100%" alt="">

<div align="center">

**Open to data engineering, analytics and data science opportunities.**

<a href="https://www.linkedin.com/in/santiago-lopez-blanco-ds"><img src="assets/badges/connect.svg" alt="Connect on LinkedIn" height="26"></a> <a href="https://credentials.databricks.com/profile/santiagolpezblanco626690/wallet"><img src="assets/badges/databricks-cred.svg" alt="Databricks Credentials" height="26"></a>

</div>
