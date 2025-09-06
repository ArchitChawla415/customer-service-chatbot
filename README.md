# Echo Insight (ETLiens)
Empathy-driven customer service insights powered by **RoBERTa** (CSAT scoring) and **Flan-T5** (conversation evaluation). End-to-end pipeline: **ETL → Modeling → API/UI → MySQL (RDS) → Tableau**. 

---

## 📌 Overview
Customer service is a $93B industry, yet many interactions lack empathy and clarity. **Echo Insight** is designed to:
- **Evaluate** conversations for empathy, clarity, tone, and missed concerns.
- **Predict** Customer Satisfaction (CSAT) scores from text.
- **Visualize** agent performance via analytics dashboards.

--- 

## 🛠️ Tech Stack
| Area | Tools / Services |
|--------------|------------------|
| **Languages** | Python |
| **Libraries (ML)** | Transformers, Datasets, PyTorch, VADER Sentiment |
| **Models** | RoBERTa, Flan-T5 | | **ETL & Data** | Pandas, NumPy, NLTK, SpaCy |
| **Backend/API** | Flask, Gunicorn |
| **Cloud** | AWS EC2, S3, RDS (MySQL) |
| **Analytics** | Tableau |
| **Version Control** | Git, GitHub LFS | 

--- 

## 📂 Repository Structure

📁 **[notebooks/](notebooks)** — Data prep, training, evaluation, EDA  
📁 **[data/](data)**  
  📁 **[raw/](data/raw)** — Unprocessed datasets  
  📁 **[processed/](data/processed)** — Preprocessed datasets  
📁 **[docs/](docs)** — Report & presentation  
  📄 **[Archit Chawla - ETliens Project Report.pdf](docs/Archit%20Chawla%20-%20ETliens%20Project%20Report.pdf)**  
  📄 **[ETLiens Project Presentation.pptx](docs/ETLiens%20Project%20Presentation.pptx)**  
📁 **[src/](src)**  
  📁 **[app/](src/app)** — Flask API  
  📁 **[training/](src/training)** — Model training scripts  
📁 **[dashboards/](dashboards)** — Tableau/Power BI dashboards  
📁 **[models/](models)** — Trained model files (LFS or external)  
📄 **[requirements.txt](requirements.txt)**  
📄 **[LICENSE](LICENSE)**  
📄 **[README.md](README.md)**  
