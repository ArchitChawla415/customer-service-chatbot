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

📄 **[Archit Chawla - ETliens Project Report.pdf](Archit%20Chawla%20-%20ETliens%20Project%20Report.pdf)** — Project report (via Git LFS)  
📄 **[ETLiens Project Presentation.pptx](ETLiens%20Project%20Presentation.pptx)** — Project presentation (via Git LFS)  

📄 **[BDAE_Codebase_1_Initial_Data_Prep.ipynb](BDAE_Codebase_1_Initial_Data_Prep.ipynb)** — Initial data preparation  
📄 **[BDAE_Codebase_2_CSAT_Score_Classification.ipynb](BDAE_Codebase_2_CSAT_Score_Classification.ipynb)** — CSAT score classification  
📄 **[BDAE_Codebase_3_finetuned_data_creation.ipynb](BDAE_Codebase_3_finetuned_data_creation.ipynb)** — Fine-tuned data creation  
📄 **[BDAE_Codebase_4_Conversation_Evaluation_Model.ipynb](BDAE_Codebase_4_Conversation_Evaluation_Model.ipynb)** — Conversation evaluation model  
📄 **[BDAE_Codebase_5_Charts.ipynb](BDAE_Codebase_5_Charts.ipynb)** — Visualization and charts  

📄 **[amazon_reviews_electronics_20K_sample.csv](amazon_reviews_electronics_20K_sample.csv)** — Raw dataset  
📄 **[customer_finetuning_data_preprocessed.csv](customer_finetuning_data_preprocessed.csv)** — Preprocessed dataset  
📄 **[customer_service_chatbot_dataset.csv](customer_service_chatbot_dataset.csv)** — Raw dataset  
📄 **[daily_dialog.csv](daily_dialog.csv)** — Raw dataset  
📄 **[enhanced_finetuning_data_with_diversified_feedback.csv](enhanced_finetuning_data_with_diversified_feedback.csv)** — Augmented dataset  
📄 **[finetuning_2_columns.csv](finetuning_2_columns.csv)** — Fine-tuning dataset (2 columns)  
📄 **[finetuning_data_diversified_output_text.csv](finetuning_data_diversified_output_text.csv)** — Diversified output text dataset  
📄 **[finetuning_data_merged.csv](finetuning_data_merged.csv)** — Merged fine-tuning dataset  
📄 **[preprocessed_amazon_df_with_vader_scores_and_score_classification.csv](preprocessed_amazon_df_with_vader_scores_and_score_classification.csv)** — Preprocessed Amazon review dataset  
📄 **[preprocessed_amazon_df_with_vader_scores_and_score_classification_and_imputations.csv](preprocessed_amazon_df_with_vader_scores_and_score_classification_and_imputations.csv)** — Preprocessed dataset with imputations  

📄 **[README.md](README.md)** — Project documentation  
📄 **[.gitattributes](.gitattributes)** — Git LFS tracking

## 📄 Documentation

- [📑 **Project Report (PDF)**](Archit%20Chawla%20-%20ETliens%20Project%20Report.pdf) — Full methodology, dataset details, preprocessing, model training, and evaluation.
- [📊 **Project Presentation (PPTX)**](ETLiens%20Project%20Presentation.pptx) — Slides summarizing the project workflow, models, and results.


## 📊 Results & Insights

### CSAT Score Prediction (RoBERTa)
![CSAT Model Results](docs/images/csat_model_results.png)

### Conversation Evaluation (Flan-T5)
![Conversation Evaluation Chart](docs/images/conversation_eval_chart.png)

### Tableau Dashboard Overview
![Dashboard Screenshot](docs/images/dashboard_screenshot.png)

