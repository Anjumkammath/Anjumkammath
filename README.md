<div align="center">

# Hi, I'm Anju M Kammath

### NLP-focused AI/ML Engineer | Multilingual AI | Model Evaluation | Applied Data Science

I build multilingual NLP and model-evaluation systems that make AI outputs easier to retrieve, inspect, and improve. My work combines retrieval-augmented generation, dataset quality analysis, error analysis, and applied machine learning, with a long-term direction toward Master's research in NLP and multilingual AI with a Japan-focused academic path.

[![GitHub](https://img.shields.io/badge/GitHub-Anjumkammath-181717?style=flat&logo=github)](https://github.com/Anjumkammath)
[![Email](https://img.shields.io/badge/Email-anjumkammath2002%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:anjumkammath2002@gmail.com)

</div>

---

## About Me

I specialize in **NLP, multilingual AI, retrieval-augmented generation, and model evaluation**. I am building toward AI/ML Engineer and Associate Data Scientist roles where the work sits close to language data, evaluation workflows, retrieval systems, and production-quality model behavior.

At **Amazon - Alexa Data Services, AGI DS**, I work on conversational AI data quality through annotation validation, ground-truth review, ambiguity analysis, and high-volume dataset inspection. That experience shapes how I build projects: I care not only about whether a model runs, but whether its inputs, labels, evaluation logic, and failure cases are reliable.

My current flagship project is **PolyGlotAI Research Assistant**, a multilingual RAG system for document-grounded question answering across languages. It reflects the technical direction I want to deepen further: retrieval quality, multilingual representation, answer grounding, and NLP systems that can support cross-lingual access to knowledge.

---

## Core Focus

- **Multilingual NLP:** cross-lingual retrieval, language-aware preprocessing, semantic search, and multilingual user-facing AI systems
- **RAG and LLM Applications:** document ingestion, chunking, embeddings, vector search, retrieval evaluation, answer generation, and grounded response design
- **Model Evaluation:** error analysis, low-confidence review, mislabeled-sample detection, confusion-pattern analysis, and dataset-quality improvement
- **Applied ML:** classification, recommendation systems, dashboarding, computer vision, and end-to-end data workflows
- **Research Direction:** Master's preparation in NLP, multilingual AI, and language technology, with a Japan-focused academic path

---

## Technical Skills

**NLP, GenAI and Retrieval**  
LangChain, LLM applications, Hugging Face Transformers, Sentence-BERT, TF-IDF, NLTK, embeddings, semantic search, RAG workflows

**Machine Learning and Evaluation**  
Scikit-learn, TensorFlow, Keras, PyTorch, CNNs, YOLO, classification pipelines, model evaluation, error analysis, data quality review

**Data, Analytics and Visualization**  
Pandas, NumPy, Power BI, Matplotlib, Seaborn, Plotly, Excel, Jupyter Notebook

**Backend, Databases and Tools**  
Python, SQL, C, FastAPI, Streamlit, Docker, Git, GitHub, OpenCV, MySQL, SQLite

---

## Flagship Project

### PolyGlotAI Research Assistant - Multilingual RAG System

**Problem solved:** Researchers and students often need to search across documents written in different languages, but keyword search fails when the question and source material do not share the same wording or language.

PolyGlotAI Research Assistant is a multilingual retrieval-augmented generation system that ingests documents, builds a searchable knowledge base, retrieves relevant passages, and generates grounded answers for user questions. The system is designed around multilingual retrieval rather than generic chatbot behavior, making answer grounding, source relevance, and language handling central to the workflow.

The main technical challenge was building a pipeline where document parsing, chunking, embedding, retrieval, and generation work together without losing context across languages. I treated retrieval quality as the core engineering problem: the assistant should return useful evidence before it attempts to generate an answer.

**Current scope:** implements a 5-stage RAG workflow covering document ingestion, chunking, embedding generation, semantic retrieval, and grounded answer generation. The next evaluation layer will track retrieval relevance, answer grounding, and multilingual response quality.  
**Impact:** demonstrates my target specialization in multilingual NLP, RAG, retrieval quality, and applied LLM systems.

**Tech:** Python, LangChain, Hugging Face, embeddings, vector search, RAG, Streamlit/FastAPI  
**Repo:** [PolyGlotAI-Research-Assistant](https://github.com/Anjumkammath/PolyGlotAI-Research-Assistant)

---

## Selected Projects

### Customer Churn Prediction - Explainable ML and Business Framing

**Problem solved:** Businesses need to identify customers likely to leave before churn affects revenue and retention.

This project builds a full supervised ML workflow for churn prediction using the Telco Customer Churn dataset. It covers data cleaning, exploratory analysis, feature engineering, model comparison, class-imbalance handling, SHAP explainability, revenue-impact framing, and a Streamlit prediction app.

The technical challenge was moving beyond a raw notebook into a complete, reviewable data science project. I structured the workflow so the model is evaluated with precision, recall, F1-score, and ROC-AUC, then translated predictions into plain-language churn drivers and retention actions.

**Current scope:** analyzes 7,043 customer records, compares Logistic Regression and XGBoost variants, selects XGBoost with class weighting, and reports ROC-AUC of 0.8429 with recall of 0.7888.  
**Impact:** demonstrates core ML fundamentals, model evaluation, explainability, and business interpretation.

**Tech:** Python, Pandas, Scikit-learn, XGBoost, SHAP, Streamlit, Matplotlib, Seaborn  
**Repo:** [Customer-Churn-Prediction](https://github.com/Anjumkammath/Customer-Churn-Prediction)

---

### Scholarship Recommendation System - Explainable Matching

**Problem solved:** Students often struggle to identify scholarships they are genuinely eligible for among schemes with different academic, income, category, and study-level requirements.

This Streamlit application uses a transparent two-stage recommendation pipeline. It first applies rule-based eligibility filtering, then ranks the eligible scholarships with TF-IDF similarity to return the three most relevant matches with plain-language explanations.

**Current scope:** includes 20 curated Indian scholarship schemes, percentage and CGPA inputs, income brackets, category-aware filtering, explainable ranking, source links, and automated tests for the recommendation logic.  
**Impact:** demonstrates interpretable recommendation systems, NLP ranking, data validation, modular Python engineering, and user-focused application design.

**Tech:** Python, Streamlit, Pandas, Scikit-learn, TF-IDF, Pytest  
**Repo:** [scholarship-recommendation-system](https://github.com/Anjumkammath/scholarship-recommendation-system)

---

### Exploratory Data Analysis Portfolio

**Problem solved:** Raw datasets only become useful when they are cleaned, questioned, visualized, and translated into decision-relevant findings.

This repository contains a multi-domain EDA portfolio covering retail, healthcare, financial transactions, job-market data, student performance, and social media sentiment. Each project follows a structured workflow: objective definition, data quality review, cleaning, univariate and multivariate analysis, visualization, findings, recommendations, and limitations.

The technical challenge was building a repeatable analysis structure across very different datasets while keeping each project interpretable to a non-technical reader. The portfolio emphasizes measured findings, responsible interpretation, and clear business or operational recommendations.

**Current scope:** includes 6 EDA projects across transaction data, healthcare appointments, financial risk, job postings, education data, and text sentiment data.  
**Impact:** demonstrates data cleaning, exploratory thinking, visualization, analytical storytelling, and decision-focused communication.

**Tech:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
**Repo:** [Exploratory_Data_Analysis](https://github.com/Anjumkammath/Exploratory_Data_Analysis)

---

### SolarNova AI - Computer Vision and IoT

**Problem solved:** Dust buildup reduces solar panel efficiency, and manual inspection is not scalable for continuous monitoring.

SolarNova AI uses computer vision to classify solar panel images as clean or dusty and connects the model output to an IoT cleaning workflow. The project combines CNN-based image classification, OpenCV preprocessing, Raspberry Pi integration, and motor-control logic for automated cleaning.

The main technical challenge was bridging software inference with hardware behavior. A prediction is only useful if the system can convert it into a controlled physical action, so the workflow had to account for camera input, classification confidence, motor triggering, and safe termination.

**Current scope:** classifies 2 panel states, clean and dusty, using 224x224 image preprocessing, real-time camera input, 2-second inference intervals, and a 0.90 confidence threshold before triggering the cleaning workflow.  
**Impact:** shows range beyond NLP by connecting ML inference with embedded AI and IoT automation.

**Tech:** Python, TensorFlow, Keras, OpenCV, CNNs, Raspberry Pi, IoT  
**Repo:** [Solarnova-AI](https://github.com/Anjumkammath/Solarnova-AI)

---

## In Development

I am also planning additional NLP and model-evaluation projects that will be added here once their repositories are ready for public review:

- **LabelGuard AI:** NLU model error analysis and annotation-quality review dashboard
- **AI Resume Builder and ATS Analyzer:** explainable resume-to-job-description matching workflow

---

## Experience

**ML Data Associate, L3**  
**Amazon - Alexa Data Services, AGI DS**  
Aug 2025 - Present

I work on conversational AI dataset quality for Alexa workflows, where the quality of annotations, ground truth, and linguistic edge-case handling directly affects model readiness. My role involves reviewing high-volume language data, identifying ambiguous utterances, validating labels against project guidelines, and escalating recurring error patterns that can affect downstream model behavior.

- Perform annotation validation and ground-truth review for production conversational AI datasets
- Identify ambiguous language patterns, edge cases, and labeling inconsistencies during error analysis
- Review high-volume language data against quality, policy, and annotation standards, with attention to recurring ambiguity patterns and downstream model-readiness risks
- Collaborate with Machine Learning Engineers and Quality Analysts to align dataset decisions with updated guidelines
- Build transferable judgment in model evaluation, dataset reliability, language-pattern analysis, and human-in-the-loop AI quality workflows

---

## Education

**B.Tech in Computer Science, Artificial Intelligence**  
Adi Shankara Institute of Engineering and Technology, KTU  
CGPA: 8.18 | 2020 - 2024

---

## Certifications

- Microsoft Certified: Azure AI Fundamentals AI-900
- Google Data Analytics Professional Certificate - Coursera

---

## Current Direction

I am strengthening my portfolio around **multilingual NLP, retrieval systems, and model evaluation**. My next goals are to:

- Improve PolyGlotAI with measurable retrieval metrics, multilingual evaluation cases, and documented failure analysis
- Add stronger benchmarks for NLU error analysis, including confusion matrices, confidence bands, and annotation-review outcomes
- Build more LLM/NLP applications with clear evaluation logic instead of demo-only chatbot behavior
- Prepare for Master's study in NLP with a focus on multilingual AI, retrieval, and language technology in Japan

---

## Profile Snapshot

- **Core specialization:** Multilingual NLP, RAG, model evaluation, and dataset-quality analysis
- **Current role:** ML Data Associate, L3 at Amazon - Alexa Data Services, AGI DS
- **Flagship project:** PolyGlotAI Research Assistant - multilingual RAG for document-grounded question answering
- **Portfolio direction:** language data quality, retrieval systems, NLU error analysis, and applied ML systems

<!--
Optional GitHub stats widgets:
These use a third-party service and may show errors if the service is rate-limited.

<div align="center">

![Anju's GitHub stats](https://github-readme-stats.vercel.app/api?username=Anjumkammath&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Anjumkammath&layout=compact&hide_border=true)

</div>
-->

---

## Let's Connect

I am open to AI/ML Engineer, Associate Data Scientist, NLP, model-evaluation, and applied AI opportunities. I am especially interested in work involving multilingual data, retrieval systems, conversational AI evaluation, and dataset-quality improvement.

**Email:** [anjumkammath2002@gmail.com](mailto:anjumkammath2002@gmail.com)  
**GitHub:** [github.com/Anjumkammath](https://github.com/Anjumkammath)
