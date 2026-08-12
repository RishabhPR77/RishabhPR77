# Rishabh Patidar

### AI/ML Engineer building production ML systems 

I design and ship end-to-end machine learning systems: hybrid RAG pipelines, gradient-boosted models in production, and multi-modal biometric systems deployed as real APIs and dashboards. My focus is systems that hold up under real data, real latency, and real constraints.

📍 B.Tech IT, MITS Gwalior (Class of 2027) · 🥈 1st Runner-Up, SSH '26 National Hackathon
🌐 [Portfolio](https://rishabhpatidar.vercel.app) · [LinkedIn](https://linkedin.com/in/rishabh-ptdr) · [Email](mailto:rishabhpatidar400@gmail.com)

---

## Impact Snapshot

| Metric | Project |
|---|---|
| **$233,917** revenue-at-risk quantified | Customer Churn Prediction |
| **0.8793 ROC-AUC** on 2.5M+ transactions | Customer Churn Prediction |
| **R² = 0.96**, zero invalid predictions | Event Footfall & Sponsorship Engine |
| **60/40 hybrid retrieval** (dense + BM25) | Code Archaeologist (RAG) |
| **0.7/0.3 face-pose fusion** for re-ID | Video Target Identification |

---

## Featured Projects

### 🔍 [Code Archaeologist](https://github.com/RishabhPR77/code-archaeologist-demo) — Natural-Language Git History Search
A RAG system that lets you query any Git repository conversationally.
- Hybrid retrieval combining BGE dense embeddings with BM25 keyword reranking (60/40 weighting)
- Pinecone vector store with per-user namespace isolation and Redis TTL-based cleanup
- LLaMA-3.3-70B (via Groq) for commit summarization and intent classification
- Deployed on Streamlit Cloud with IP rate-limiting and admin access control

### 📉 [Customer Churn Prediction](https://github.com/RishabhPR77/customer-churn) — Churn Intelligence at Scale
End-to-end churn pipeline processing 2.5M+ transactions to flag revenue at risk.
- Modular SQL-to-Pandas ETL engineering 22 RFM and behavioral features
- Random Forest classifier (ROC-AUC = 0.8793) with SMOTE oversampling for class imbalance
- SHAP analysis pinpointing recency as the dominant churn driver
- Quantified $233,917 in revenue-at-risk across 392 high-risk households

### 🎬 [CinemaIQ](https://github.com/RishabhPR77/movie-success-predictor) — Box Office Intelligence Platform
Predicts box office revenue and generates AI-driven scenario commentary.
- 30+ domain-specific features, including custom talent power indices
- XGBoost selected over 5 benchmarked models on lowest RMSE
- LLaMA-3.3-70B powering scenario simulation and an ROI analytics dashboard

### 🎥 [Video Target Identification System](https://github.com/RishabhPR77/video-target-id) — Multi-Camera Biometric Re-ID
Re-identifies individuals across CCTV feeds using fused biometric signals.
- Fuses InsightFace 512-d face embeddings with MediaPipe 12-d pose descriptors
- Weighted cosine similarity (face: 0.7, pose: 0.3) for robust re-identification
- Forensic Streamlit dashboard with automated evidence export

### 📊 [Event Footfall Prediction & Sponsorship Engine](https://github.com/RishabhPR77/eventsight) — LLM-Integrated ML Pipeline
Predicts event footfall and scores brand-sponsorship fit in one pipeline.
- EDA across 50+ features to identify footfall drivers, cutting model noise by 30%
- Two-stage XGBoost pipeline (R² = 0.96) with a Dynamic Physical Clamping algorithm enforcing venue-capacity constraints — zero physically invalid predictions
- LLaMA-3.3-70B for semantic brand-event synergy scoring, output as structured JSON via a stateless FastAPI microservice

---

## Tech Stack

**Languages** `Python` `SQL` `TypeScript` `Java`
**ML / AI** `Scikit-learn` `XGBoost` `LangChain` `Pinecone` `Whisper` `MediaPipe`
**Deployment** `FastAPI` `Streamlit` `React` `Docker`
**Data** `MongoDB` `Redis`

---

## Achievements

- 🥈 1st Runner-Up — SSH '26 National Hackathon (Feb 2026)
- 🏅 Top Performer, Web Dev Track — Hacksagon @ ABV-IIITM Gwalior (Apr 2026)
- 🎯 Finalist — ABV-IIITM Hackatron powered by GitHub (Oct 2025)
- 📜 Mathematical Foundations of ML — NPTEL, IIT Madras (73/100)

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rishabh-ptdr)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://rishabhpatidar.vercel.app)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rishabhpatidar400@gmail.com)
