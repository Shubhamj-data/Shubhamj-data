<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0a0a,100:111111&height=1&section=header"/>
</div>

<br/>

<div align="center">

# Shubham Jadhao
### AI Engineer · GenAI Systems · MLOps · Fraud Detection

[![Email](https://img.shields.io/badge/-shubhamjadhao.v@gmail.com-000000?style=flat-square&logo=gmail&logoColor=white)](mailto:shubhamjadhao.v@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubhamjadhao)
[![Location](https://img.shields.io/badge/-Nagpur,_India-000000?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![Phone](https://img.shields.io/badge/-+91_7447279737-000000?style=flat-square&logo=phone&logoColor=white)](tel:+917447279737)

</div>

<br/>

---

<br/>

> **I build AI systems that go into production.**
> From a 5M-record fraud detection pipeline that retrains itself weekly, to an agentic RAG system deployed on Hugging Face — I own the full lifecycle: data → model → API → monitoring.

<br/>

---

<br/>

## What I'm building right now

| Project | What it does | Stack |
|---------|-------------|-------|
| 🔍 **[KnowledgeOS](https://github.com/shubhamjadhao)** | Agentic RAG — employees query internal docs in plain English and get cited, confident answers | LangChain · ChromaDB · BM25 · Mistral 7B · Gemini · FastAPI |
| 🧠 **[TalentIQ](https://github.com/shubhamjadhao)** | HR intelligence platform — attrition prediction, semantic resume matching, bias-blind screening | XGBoost · SHAP · FAISS · sentence-transformers · LangChain |

<br/>

---

<br/>

## KnowledgeOS — Agentic RAG System

The problem: employees waste hours ctrl+F-ing through docs. KnowledgeOS lets them ask questions in plain English and get answers with citations back to the exact document, page, and section.

**How it works under the hood:**

```
User question
     │
     ▼
Question classifier ──► selects retrieval strategy
     │
     ▼
Hybrid retrieval: ChromaDB (semantic) + BM25 (keyword)
     │
     ▼
Reciprocal Rank Fusion → Cross-encoder reranking
     │
     ▼
Confidence check ──► low confidence? → reformat + retry
     │
     ▼
Answer with citations [document · page · section]
     │
     ▼
SQLite memory → supports natural follow-up questions
```

**What makes it different:**
- Hybrid retrieval beats single-mode on exact phrases and proper nouns — RRF + cross-encoder reranking
- Supports PDF, DOCX, PPTX, XLSX, TXT — auto-chunked (512 tokens) with full metadata tagging
- Mistral 7B local (Ollama) with Gemini API as automatic cloud fallback
- Analytics dashboard surfaces knowledge gaps — queries the system couldn't answer

[![View Project](https://img.shields.io/badge/View_on_GitHub-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/shubhamjadhao)
[![Live Demo](https://img.shields.io/badge/Live_Demo-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co)

<br/>

---

<br/>

## TalentIQ — HR Intelligence Suite

Two modules built to replace the exact job I used to do as a technical recruiter.

**Module 1 — Attrition Prediction**
- 5 models compete in a live leaderboard: LR, Decision Tree, RF, XGBoost, Neural Net
- Best model auto-selects using weighted AUC + F1 + Recall score
- SHAP explainability shows HR managers *which factor* drives each employee's risk
- What-if simulator: "What if we increase salary by 15% and remove overtime?"

**Module 2 — Semantic Hiring**
- Resume ↔ JD matching via sentence-transformers + FAISS — finds candidates keyword-ATS systems miss
- Gap-aware interview questions: generated specifically for *missing* skills, not a generic list
- Bias-blind mode: strips name, pronouns, graduation year before any model inference

[![View Project](https://img.shields.io/badge/View_on_GitHub-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/shubhamjadhao)
[![Live Demo](https://img.shields.io/badge/Live_Demo-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co)

<br/>

---

<br/>

## Professional experience

### AI Engineer — HisanLabs Pvt Ltd *(July 2025 – Present)*

End-to-end fraud detection system built from scratch:

- **Model layer:** SMOTE for class imbalance → XGBoost, Random Forest, LR, Decision Tree tuned for Recall and ROC-AUC
- **Data layer:** Full pipeline — ingestion → validation → dual-write to MySQL + MongoDB on AWS with null/outlier/bad-record tests, 5M+ records
- **Automation:** Weekly retraining pipeline runs without human involvement
- **Observability:** Power BI dashboards for fraud trends, model performance, and predictions for the business team

<br/>

---

<br/>

## Technical skills

```
GenAI & LLMs        LangChain · OpenAI API · Hugging Face · Ollama · Gemini API
                    RAG · Agentic RAG · Hybrid Retrieval · Prompt Engineering

Vector Databases    ChromaDB · FAISS · Pinecone · Weaviate · BM25 · RRF

Machine Learning    XGBoost · LightGBM · Scikit-learn · SMOTE · SHAP
                    Hyperparameter Tuning · Cross-Validation · Feature Engineering

Deep Learning       TensorFlow · Keras · PyTorch (fundamentals) · ANN · CNN · RNN

MLOps               FastAPI · Flask · Streamlit · Automated Retraining Pipelines
                    HuggingFace Spaces · REST APIs

Cloud & Databases   AWS (S3, EC2, RDS) · MySQL · MongoDB · SQLite

Computer Vision     OpenCV · YOLOv5/v8 · Image Classification · Object Detection

Analytics           Power BI · DAX · Matplotlib · Seaborn · EDA · Hypothesis Testing

Languages           Python · SQL
```

<br/>

---

<br/>

## GitHub activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shubhamjadhao&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000&title_color=ffffff&icon_color=ffffff&text_color=999999&hide_title=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shubhamjadhao&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000&title_color=ffffff&text_color=999999)

</div>

<br/>

---

<br/>

## Education

**Master of Computer Applications (MCA)** — Savitribai Phule Pune University *(2021–2023)*

**B.Com + Computer Application** — Rashtrasant Tukadoji Maharaj Nagpur University *(2017–2020)*

<br/>

---

<br/>

<div align="center">

### Open to AI Engineer / ML Engineer roles

**If you're building something with LLMs, RAG, or production ML — let's talk.**

[![Email me](https://img.shields.io/badge/Email_me-shubhamjadhao.v@gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhamjadhao.v@gmail.com)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubhamjadhao)

</div>

<br/>
