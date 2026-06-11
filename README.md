# Maksym Chunikhin

**Data Science & Machine Learning** — predictive modeling, NLP, time series forecasting, and market intelligence. I build end-to-end projects: from raw data to validated models, explainability, and Streamlit apps.

🌐 English / Italian / Ucraine / Russian · 💼 Open to **Junior Data Scientist / ML Engineer** roles

Background in telecommunications (field network infrastructure) and commercial operations — I know what messy real-world data and business processes look like from the inside.

---

## Featured Projects

### 📝 [Amazon Review Intelligence](https://github.com/MaksymChunikhin/Amazon-Review-Intelligence)
End-to-end NLP system on **500k Amazon reviews**: sentiment classification, topic modeling, customer analytics, Streamlit dashboard.
**Tuned TF-IDF + LinearSVC (macro-F1 0.717) vs fine-tuned DistilBERT (0.744)** — honest classic-vs-transformer comparison with a leakage-free shared split. LDA topics chosen over BERTopic with a documented trade-off analysis.

### 🛡️ [Fraud Detection System](https://github.com/MaksymChunikhin/Advanced-Fraud-Detection-System)
IEEE-CIS Kaggle pipeline on **590k transactions / 471 features**: UID aggregation features, **time-aware validation**, Optuna-tuned LightGBM, SHAP, analyst-facing Streamlit dashboard with review queue.
**ROC-AUC: 0.949 public / 0.919 private LB.** <!-- TODO: verify exact numbers match the repo README -->

### 🏠 [Airbnb Smart Pricing & Market Intelligence](https://github.com/MaksymChunikhin/PROJECT-AIRBNB-pricing-market-intelligence)
End-to-end system on Inside Airbnb Amsterdam data: price model (**ensemble MAE €53, R² 0.68**, ~€10 better than linear baseline), residual-based undervalued/overpriced detector, host segmentation (KMeans + HDBSCAN), MiniLM content-based recommender, Streamlit app.

### 📈 [Store Sales Forecasting](https://github.com/MaksymChunikhin/PET-Store-Sales-Time-Series-Forecasting)
Corporación Favorita (Kaggle): LightGBM with lag/rolling/Fourier features and **iterative day-by-day forecasting** — validation simulates real inference by recomputing lags from the model's own predictions.
**Top 7% — rank 66 / 931.**

<details>
<summary>More projects</summary>

### [Customer Segmentation & Market Intelligence](https://github.com/MaksymChunikhin/customer-segmentation) <!-- TODO: fix link -->
GPU-accelerated clustering (RAPIDS / cuML): RFM analytics, KMeans / DBSCAN / HDBSCAN, UMAP, inference-ready pipeline.

### [Hotel Rating Prediction](https://github.com/MaksymChunikhin/project-3-hotel-rating-prediction)
SkillFactory course competition (Kaggle Community): **2nd place of ~700 participants**, MAPE 10.45. LightGBM + NLP features, leakage-free out-of-fold target encoding.

### [Titanic Survival Prediction](https://github.com/MaksymChunikhin/titanic-honest-craft)
Clean reproducible sklearn pipeline: preprocessing inside CV, leakage screening, 7-model comparison, Optuna, SHAP. CV accuracy 0.814 ± 0.023.

</details>

---

## Tech Stack

**Data:** Python, SQL, pandas, NumPy, PyArrow
**ML:** scikit-learn, LightGBM, CatBoost, XGBoost, Optuna, SHAP
**NLP:** Hugging Face Transformers (DistilBERT), sentence-transformers (MiniLM), NLTK, spaCy
**Clustering / GPU:** KMeans, HDBSCAN, UMAP, RAPIDS cuML
**Apps & Viz:** Streamlit, Plotly, Folium, matplotlib, seaborn

## Currently Learning

Production ML pipelines · model deployment · recommender systems

## Contact

[LinkedIn](https://www.linkedin.com/in/maksym-chunikhin-6423476b/) · m.chunihin@gmail.com <!-- TODO: real email -->

