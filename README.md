<h1 align="center">Hi, I'm Shigil S</h1>
<h3 align="center">Data Scientist | ML Engineer</h3>

<p align="center">
  <a href="https://linkedin.com/in/ShigilSasi">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin">
  </a>
  <a href="mailto:shigilshalu@gmail.com">
    <img src="https://img.shields.io/badge/Email-red?style=flat&logo=gmail">
  </a>
  <a href="https://github.com/ShigilSasi">
    <img src="https://img.shields.io/badge/GitHub-black?style=flat&logo=github">
  </a>
</p>

---

## About Me

Passionate about turning raw data into intelligent systems that solve real problems.
Strong in Data Science, Machine Learning, and end-to-end ML deployment.
MCA Graduate from SRM University, Chennai.

I don't just build models — I build complete products. From raw data to ML pipelines to interactive dashboards that real users can interact with.

---

## Flagship Project

### Axis Bank — Smart Banking Intelligence Platform
**Python | AWS Lambda | FastAPI | Streamlit | PostgreSQL | Scikit-learn**

An end-to-end AI platform that takes a raw PDF bank statement and delivers a fully personalised financial intelligence dashboard in under 60 seconds — no manual steps, no human intervention.

**The Problem**
Banks have all your transaction data but still send you generic promotions. Relationship managers cannot manually review thousands of accounts every month. This platform does it automatically.

**How It Works**
- Upload your Axis Bank PDF statement via Streamlit
- AWS Lambda triggers automatically via S3 event and extracts every transaction using pdfplumber
- Transactions are categorised (Food, Rent, EMI, Shopping, Transport) and payment channels identified (UPI, POS, NEFT)
- All data is stored in PostgreSQL across 5 normalised tables
- FastAPI runs 6 ML models and returns a complete financial profile in one API call
- A 5-tab dashboard loads with spending analytics, behavioural ratios, ML insights and personalised recommendations

**6 ML Models**

| Model | Algorithm | Result |
|---|---|---|
| Customer Segmentation | KMeans (k=4) | Silhouette Score: 0.61 |
| Churn / Relationship Score | Random Forest | Accuracy: 96%, F1: 0.95 |
| Credit Card Eligibility | Random Forest | Accuracy: 90% |
| Loan Eligibility | Random Forest | Accuracy: 98% |
| Offer Eligibility | Random Forest | Accuracy: 98% |

**13 Engineered Features** including savings_ratio, emi_ratio, digital_ratio, food_ratio — behavioural signals that mirror how a bank relationship manager evaluates a customer.

**Key Technical Decisions**

XGBoost was evaluated and rejected. It achieved 1.0 accuracy on the loan model — a red flag for overfitting, not a success. Random Forest at 0.98 reflects genuine learning. Occam's Razor: the simpler model that works well is the better model.

Churn risk is reframed as a Banking Relationship Score — how connected a customer is with the bank based on transaction patterns and digital adoption. Same model, completely different story for the user.

**Stack:** Streamlit · FastAPI · Scikit-learn · AWS Lambda · AWS S3 · AWS RDS · PostgreSQL · pdfplumber · boto3 · pandas

---

## Tech Stack

**Programming & Libraries**

![Python](https://img.shields.io/badge/Python-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-black?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-blue?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?logo=scikitlearn)
![PySpark](https://img.shields.io/badge/PySpark-red?logo=apachespark)

**Cloud & Deployment**

![AWS](https://img.shields.io/badge/AWS-orange?logo=amazonaws)
![FastAPI](https://img.shields.io/badge/FastAPI-green?logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-red?logo=streamlit)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-blue?logo=postgresql)

**Data & BI**

![Power BI](https://img.shields.io/badge/Power%20BI-yellow?logo=powerbi)
![Tableau](https://img.shields.io/badge/Tableau-blue?logo=tableau)
![Excel](https://img.shields.io/badge/Excel-green?logo=microsoft-excel)

**Machine Learning**
- Supervised & Unsupervised Learning
- Classification, Regression, Clustering
- KMeans, Random Forest, XGBoost
- Feature Engineering & Selection
- Model Evaluation — ROC-AUC, Confusion Matrix, Silhouette Score

**Databases & Tools**

![MySQL](https://img.shields.io/badge/MySQL-blue?logo=mysql)
![SQLite](https://img.shields.io/badge/SQLite-lightgrey?logo=sqlite)
![Git](https://img.shields.io/badge/Git-orange?logo=git)
![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)

**Environment**

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-black?logo=linux)
![VS Code](https://img.shields.io/badge/VS%20Code-blue?logo=visualstudiocode)
![Jupyter](https://img.shields.io/badge/Jupyter-orange?logo=jupyter)

---

## Other Projects

### Client Query Management System
**Python | Streamlit | SQLite | Pandas**

Role-based web application for managing client support queries with full lifecycle tracking — Open to Pending to Closed. Built-in analytics dashboards for query trends, status distribution and user roles. Secure authentication with SHA-256 password hashing.

---

### NutriClass — Food Classification Using Nutrition Data
**Machine Learning | Scikit-Learn | Statistics**

Trained on 31,000+ records across 10 food classes. Used ANOVA and Chi-Square tests for feature relevance validation. Achieved ~99% accuracy with hyperparameter tuning via GridSearchCV. Built for diet tracking, health analytics and food recommendation use cases.

---

### Stock Market Analysis Dashboard — NIFTY 50
**Python | Pandas | Plotly | Streamlit**

Processed 14 months of NIFTY 50 stock data. Calculated daily, monthly and cumulative returns. Identified top gainers, losers and volatile stocks. Sector-wise and correlation analysis with interactive filters.

---

### Swiggy Restaurant Recommendation System
**Machine Learning | Cosine Similarity | Streamlit**

Content-based recommendation system with city and cuisine filtering. Ranked results using cosine similarity combined with ratings and popularity scores.

---

### Predictive Modeling of Indian Elections
**Machine Learning | Data Analysis | Visualization**

Built predictive models using historical Indian election data. Feature engineering and trend analysis to forecast election outcomes with ML models.

---

## Internship Experience

**Data Scientist Intern — iNoesis Technologies**
Mar 2024 – Mar 2025

Analysed real-world business data using Python, SQL and Machine Learning. Built Power BI dashboards that reduced manual reporting effort by 40%. Delivered actionable insights for retail and business clients.

---

**Python Developer Intern — Kriha IT Solutions**
Apr 2025

Developed Face Recognition API using FastAPI and face_recognition library. Built Drowsiness and Yawning Detection System using OpenCV and MediaPipe. Implemented secure APIs with validation, CORS and error handling.

---

## Certifications

- Data Science & Machine Learning — Illinois Tech (US), Entri Elevate
- Microsoft Excel Certification — Entri Elevate

---

## Let's Connect

Email: shigilshalu@gmail.com
LinkedIn: https://linkedin.com/in/ShigilSasi

If you find my work useful, consider starring the repositories.
