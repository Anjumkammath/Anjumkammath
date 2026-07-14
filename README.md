<div align="center">

# Hi, I'm Anju M Kammath

### NLP-focused AI/ML Engineer | Multilingual AI | Model Evaluation | Applied Data Science

I build multilingual NLP and model-evaluation systems that make AI outputs easier to retrieve, inspect, and improve. My work combines retrieval-augmented generation, dataset quality analysis, error analysis, and applied machine learning, with a long-term direction toward Master's research in NLP and multilingual AI with a Japan-focused academic path.

[![GitHub](https://img.shields.io/badge/GitHub-Anjumkammath-181717?style=flat&logo=github)](https://github.com/Anjumkammath)
[![Email](https://img.shields.io/badge/Email-anjumkammath2002%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:anjumkammath2002@gmail.com)
[![Location](https://img.shields.io/badge/Location-Chennai%2C%20India-blue?style=flat)](#)

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

**Current scope:** supports [NEEDS NUMBER] languages, indexes [NEEDS NUMBER] document types or files, and retrieves from [NEEDS NUMBER] chunks/passages during evaluation.  
**Impact:** demonstrates my target specialization in multilingual NLP, RAG, retrieval quality, and applied LLM systems.

**Tech:** Python, LangChain, Hugging Face, embeddings, vector search, RAG, Streamlit/FastAPI  
**Repo:** [PolyGlotAI-Research-Assistant](https://github.com/Anjumkammath/PolyGlotAI-Research-Assistant)

---

## Selected Projects

### LabelGuard AI - NLU Model Error Analysis Dashboard

**Problem solved:** Intent-classification models can look accurate at a summary level while still hiding mislabeled samples, confusing intent pairs, and repeated failure patterns that reduce production reliability.

LabelGuard AI evaluates NLU model outputs through confidence analysis, semantic similarity checks, and intent-level error patterns. Instead of only reporting metrics, it helps identify which samples should be reviewed by an annotator or ML team before the dataset is reused for training or evaluation.

The key technical challenge was translating model behavior into reviewable signals: low-confidence predictions, near-duplicate utterances, and overlapping intents had to be surfaced in a way that supports human judgment rather than producing another opaque score.

**Current scope:** analyzes [NEEDS NUMBER] intents and [NEEDS NUMBER] utterances; flags [NEEDS NUMBER] categories of review issues.  
**Impact:** connects directly to my professional work in dataset quality, annotation consistency, and model-evaluation workflows.

**Tech:** Python, Scikit-learn, Hugging Face Transformers, Sentence-BERT, Streamlit, Plotly, SQLite  
**Repo:** [LabelGuard-AI](https://github.com/Anjumkammath/LabelGuard-AI)

---

### AI Resume Builder and ATS Analyzer

**Problem solved:** Job applicants often receive vague feedback on resumes; this tool turns a resume and job description into structured, explainable ATS-style feedback.

The application extracts text from PDF resumes, compares it against a target job description, and identifies matched skills, missing skills, section completeness, readability issues, and keyword gaps. It uses rule-based NLP and scoring logic to make the result interpretable rather than presenting a black-box ranking.

The main technical challenge was handling noisy resume text extraction from PDFs and turning unstructured content into consistent signals for scoring. I designed the workflow so the user can see not only the score, but the reason behind missing-skill and section-level feedback.

**Current scope:** evaluates [NEEDS NUMBER] resume sections, extracts [NEEDS NUMBER] contact/profile fields, and compares against [NEEDS NUMBER] job-skill categories.  
**Impact:** demonstrates applied NLP, FastAPI backend design, document parsing, and explainable scoring.

**Tech:** Python, FastAPI, NLP, PDF text extraction, keyword matching, scoring logic  
**Repo:** [AI-Resume-Builder-ATS-Analyzer](https://github.com/Anjumkammath/AI-Resume-Builder-ATS-Analyzer)

---

### SolarNova AI - Computer Vision and IoT

**Problem solved:** Dust buildup reduces solar panel efficiency, and manual inspection is not scalable for continuous monitoring.

SolarNova AI uses computer vision to classify solar panel images as clean or dusty and connects the model output to an IoT cleaning workflow. The project combines CNN-based image classification, OpenCV preprocessing, Raspberry Pi integration, and motor-control logic for automated cleaning.

The main technical challenge was bridging software inference with hardware behavior. A prediction is only useful if the system can convert it into a controlled physical action, so the workflow had to account for camera input, classification confidence, motor triggering, and safe termination.

**Current scope:** classifies clean vs dusty panel states and runs real-time inference through camera input. Add measured model accuracy, dataset size, and inference latency here when available: [NEEDS NUMBER].  
**Impact:** shows range beyond NLP by connecting ML inference with embedded AI and IoT automation.

**Tech:** Python, TensorFlow, Keras, OpenCV, CNNs, Raspberry Pi, IoT  
**Repo:** [Solarnova-AI](https://github.com/Anjumkammath/Solarnova-AI)

---

### Scholarship Recommendation System

**Problem solved:** Students often miss relevant scholarships because eligibility criteria are written as long, inconsistent text descriptions.

This NLP recommendation system compares student profiles against scholarship eligibility text using TF-IDF and cosine similarity. It ranks opportunities based on profile-to-eligibility relevance, making scholarship discovery more structured and explainable.

The technical challenge was converting mixed profile attributes and eligibility descriptions into comparable text representations. I focused on transparent similarity scoring so recommendations can be inspected and improved without relying on a black-box model.

**Current scope:** matches [NEEDS NUMBER] profile attributes against [NEEDS NUMBER] scholarship records.  
**Impact:** demonstrates applied NLP fundamentals, recommendation logic, and interpretable similarity-based matching.

**Tech:** Python, NLP, TF-IDF, Cosine Similarity  
**Repo:** [Scholarship-Recommendation-System](https://github.com/Anjumkammath/Scholarship-Recommendation-System)

---

### Customer Churn Prediction

**Problem solved:** Businesses need to identify customers likely to leave before churn affects revenue and retention.

This project builds a supervised ML workflow for churn prediction, including data cleaning, feature analysis, model training, and classification-based evaluation. The goal is not only to predict churn, but to understand which customer attributes are useful signals for retention strategy.

The technical challenge was structuring a clean ML baseline: preparing features, selecting evaluation metrics, and interpreting churn drivers in a way that supports business action rather than just model output.

**Current scope:** add dataset size, model types, and best metric here when available: [NEEDS NUMBER].  
**Impact:** demonstrates core ML fundamentals: preprocessing, classification, evaluation, and business interpretation.

**Tech:** Python, Pandas, Scikit-learn, Machine Learning  
**Repo:** [Customer-Churn-Prediction](https://github.com/Anjumkammath/Customer-Churn-Prediction)

---

### Diwali Sales Exploratory Data Analysis

**Problem solved:** Sales data is only useful when it can reveal which customer segments, regions, and product categories drive demand.

This EDA project analyzes Diwali-season purchasing behavior across demographic and product dimensions. It converts raw transaction data into insights about customer groups, regional sales contribution, and category-level demand patterns.

The technical challenge was moving from visualization to business interpretation: each analysis step needed to answer a decision-oriented question about customer targeting, inventory planning, or campaign focus.

**Current scope:** analyzes [NEEDS NUMBER] sales records across customer demographics, regions, occupations, and product categories.  
**Impact:** demonstrates data cleaning, exploratory analysis, visualization, and business insight communication.

**Tech:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
**Repo:** [Exploratory_Data_Analysis](https://github.com/Anjumkammath/Exploratory_Data_Analysis)

---

## Experience

**ML Data Associate, L3**  
**Amazon - Alexa Data Services, AGI DS**  
Chennai, India | Aug 2025 - Present

I work on conversational AI dataset quality for Alexa workflows, where the quality of annotations, ground truth, and linguistic edge-case handling directly affects model readiness. My role involves reviewing high-volume language data, identifying ambiguous utterances, validating labels against project guidelines, and escalating recurring error patterns that can affect downstream model behavior.

- Perform annotation validation and ground-truth review for production conversational AI datasets
- Identify ambiguous language patterns, edge cases, and labeling inconsistencies during error analysis
- Review high-volume language data against quality, policy, and annotation standards: [NEEDS NUMBER] tasks/items reviewed would strengthen this
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

## GitHub Stats

<div align="center">

![Anju's GitHub stats](https://github-readme-stats.vercel.app/api?username=Anjumkammath&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Anjumkammath&layout=compact&hide_border=true)

</div>

---

## Let's Connect

I am open to AI/ML Engineer, Associate Data Scientist, NLP, model-evaluation, and applied AI opportunities. I am especially interested in work involving multilingual data, retrieval systems, conversational AI evaluation, and dataset-quality improvement.

**Email:** [anjumkammath2002@gmail.com](mailto:anjumkammath2002@gmail.com)  
**GitHub:** [github.com/Anjumkammath](https://github.com/Anjumkammath)
