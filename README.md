A real-time credit intelligence system that generates transparent creditworthiness scores using structured (financial APIs, macro data) and unstructured (news, sentiment) data. Built for the CredTech Hackathon – Explainable Credit Scorecard.


---

🚀 Features

Data Pipeline: Ingests financial + news data, cleans & extracts features.

Scoring Engine: Decision Trees / XGBoost with incremental learning.

Explainability: SHAP/LIME feature breakdown, trend indicators, plain summaries.

Dashboard: Real-time score trends, feature importance, alerts, rating comparison.

Deployment: Dockerized, cloud-hosted, auto-refresh & retraining enabled.



---

🏗️ Architecture

Data Sources → Ingestion & Preprocessing → Scoring Engine → Explainability → Dashboard


---

⚙️ Tech Stack

Backend: Python (Flask/FastAPI), Scikit-learn, XGBoost

NLP: SpaCy, Transformers (event detection)

Explainability: SHAP, LIME

Frontend: React.js, Chart.js

Deployment: Docker, Cloud hosting



---

📊 Trade-offs

Decision Trees (simple, interpretable) vs. XGBoost (accurate, SHAP for explainability)

Structured data (accuracy) + unstructured events (market reactivity)

Real-time (costly) vs. batch updates (scalable)

