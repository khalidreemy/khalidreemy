# Khalid Al Reemy
**AI Engineer**
Riyadh, KSA · +966 559 547 469 · khalidreemy@gmail.com

---

## Professional Summary

AI Engineer with 10 years building production AI/ML systems across NLP, LLMs, computer vision, and applied data science. Hands-on experience designing end-to-end pipelines — from data profiling and feature engineering to model fine-tuning, retrieval-augmented generation (RAG), and deployment behind clean APIs. Fine-tuned LLaMA 3.1 8B Instruct on 90,000+ annotated samples for skill extraction, designed an enterprise data-governance platform powered by GPT-4o/GPT-5 semantic enrichment, and shipped multiple NLP and medical-imaging models. Strong in Python, prompt engineering, vector search, and bridging AI capability with real product UX.

---

## Core Skills

- **LLMs & GenAI:** Fine-tuning (LLaMA 3.1 8B Instruct, LoRA/PEFT), RAG, prompt engineering, function/tool calling, structured outputs, OpenAI API (GPT-4o, GPT-5, GPT-4-Turbo), conversation-state management, NL-to-SQL
- **NLP:** NER, text classification, sentiment analysis, spam/outlier detection, Arabic NLP & dialect modeling, word embeddings, semantic similarity
- **Computer Vision:** CNNs, medical imaging (mammography, X-ray), classification on imbalanced data
- **ML Frameworks:** TensorFlow, PyTorch, scikit-learn, Hugging Face Transformers
- **Vector / Retrieval:** Vector databases, embeddings, similarity search, semantic indexing
- **Data Engineering:** Python (pandas, asyncio), MySQL, PostgreSQL, BigQuery, MongoDB, schema profiling, PII detection, data quality scoring
- **Backend / APIs:** FastAPI, SQLAlchemy, Alembic, REST API design, JWT auth, OAuth/Google SSO, RBAC, background job orchestration
- **DevOps & Tooling:** Docker, containerization, Git, CI/CD basics, Linux
- **Frontend (working knowledge):** React, TypeScript, Vite, TanStack Query
- **Other:** Rasa chatbots, MLOps fundamentals, model evaluation & monitoring

---

## Career History

### National eLearning Centre — *AI Engineer* (2021 – Present)
Leading AI initiatives that enhance the eLearning experience for learners across the Kingdom. Building, fine-tuning, and operating LLMs and NLP systems that power adaptive learning, the Learner Passport, and labor-market alignment.

**Selected Projects**

- **Data Discovery — Enterprise Data Governance Platform (data-compass-super / X-Cube DMO)** *(Flagship, 2026)*
  Designed and built an end-to-end AI-powered platform that automates data cataloging, classification, quality scoring, PII discovery, and risk management for enterprise databases — built for the Data Management Officer (DMO) persona.
  - Architected an **8-stage data pipeline** (Connection → Sampling → Statistics → Rule-Based Classification → PII Detection → LLM Semantic Enrichment → Metadata Indexing → Business Context Generation) with progress-tracked, resumable jobs.
  - Implemented **LLM semantic enrichment** (GPT-5 / GPT-4o) producing defensible, auditable per-table assessments: business names, entity classification, quality scores, sensitivity (Public → Restricted), PII grading (Low/Medium/High/Critical), and governance risk levels — all grounded strictly in observable profile evidence.
  - Built **two-layer PII detection**: rule-based (regex + Arabic name lists + token-ratio heuristics) plus LLM-graded sensitivity scoring with business-impact narratives.
  - Developed **Talk-to-Data** (natural language → SQL) with retry logic, model fallback (GPT-4o-mini → GPT-4-Turbo), cooperative cancellation, and safe execution against MySQL.
  - Developed **Ask-to-Dataset**, a RAG-style assistant that answers plain-language questions over the enriched metadata catalog without exposing the underlying database.
  - Built an AI-driven **reference-data standardization** workflow that clusters similar code/category columns across tables to suggest canonical values (e.g., ISO-3166 country codes).
  - Implemented **multi-tenant RBAC** (Admin, DMO/CDO, CTO/Architect, Analyst, Steward, Viewer) with dataset-level permissions and encrypted credential storage.
  - **Stack:** Python, FastAPI, SQLAlchemy, Alembic, PostgreSQL, MySQL, OpenAI API, JWT, Google SSO, Docker; React, TypeScript, Vite, shadcn/ui, TanStack Query.

- **LLaMA 3.1 8B Instruct Fine-Tuning for Skill Extraction**
  Fine-tuned Meta's LLaMA 3.1 8B Instruct on 90,000+ semi-synthetic annotated samples to extract explicit and implicit skills from job postings, course descriptions, and CVs, mapped to a standardized skill taxonomy. Powers labor-market analysis, adaptive learning, and education-to-workforce alignment.

- **AI Mentor for Students (LLM)**
  Built a domain-grounded LLM assistant that answers student questions on career paths and choices, fed with curated career-guidance resources and refined with NLP techniques.

- **Course Recommender System**
  Represented courses as skill vectors and matched them against learners' achieved skills using semantic similarity to recommend personalized next steps.

- **Labor-Market ↔ Education Alignment System**
  Trained a domain-specific NER model to extract required skills from job postings and learning materials, using shared skill vocabulary to map labor-market demand to available courses and individual CVs.

- **Course Content Classification**
  Identified course domains via supervised classification, leveraging word embeddings to generate discriminative keywords for labeling.

---

### King Khalid University — Center for Artificial Intelligence — *AI Research Engineer* (2017 – 2021)
Worked across NLP and computer-vision research projects, taking models from data collection through deployment.

- **Tourism Enquiry Bot** — Rasa-based tour-guide bot handling location queries and restaurant reservations.
- **IDA / Thalassemia Classification** — Deep neural network on Saudi medical lab data to distinguish IDA, Thalassemia, and normal patients without relying on commonly-used Hemoglobin/Ferritin markers; handled severe class imbalance.
- **Arabic Language Classification** — Supervised models distinguishing Modern Standard ("Faseeh") Arabic from Saudi-dialect tweets.
- **Geo-Locating Tweet Documents** — 30-class classification of tweets across Saudi cities with heavy imbalance; benchmarked Logistic Regression, Random Forest, SVM, and deep learning.
- **Breast Cancer Detection (CBIS-DDSM)** — Deep CNN classifier on mammography imagery.
- **COVID-19 X-Ray Classification** — End-to-end pipeline (data collection, preprocessing, model training) for COVID vs non-COVID detection.
- **MASFAH — Twitter Scraping Platform** — Web platform for collecting and labeling tweets to bootstrap supervised datasets.
- **Spam Detection (Unsupervised)** — Outlier detection on tweets using KMeans, DBSCAN, and hierarchical clustering, validated with silhouette analysis.

---

### Nataf Contracting Co. — *Programming Team Leader* (2010 – 2017)
Led a team building Windows and web applications for the contracting industry.

### Prince Sultan Tourism College — *Programming / Database Development Teacher* (2009 – 2010)
Taught first-year students computer fundamentals, web programming, and database development.

### New Horizons Computer Learning Center — *Software / Database Instructor* (2001 – 2009)
Taught A+ Hardware/Software and database development courses.

---

## Education

**B.E., Computer Science** — Allahabad University, MNREC Engineering College, Allahabad, India (1996 – 2001)

---

## Certifications & Continuous Learning

- **IBM AI Engineering Specialization** — Coursera, 2022 — [verify](https://www.coursera.org/account/accomplishments/professional-cert/M65SJ4HEHR8F)
- **MongoDB — The Complete Developer Guide** — Udemy, 2022 — [verify](https://www.udemy.com/certificate/UC-66581f1c-2d17-4ac0-a8e8-4a68ab2c85ab/)
- **Rasa Certified Developer** — 2021 (Certificate ID: XQ5 5HU 0Y2)
- **AI for Medicine Specialization** — DeepLearning.AI / Coursera, 2020 (Diagnosis · Prognosis · Treatment)
- **AI for Healthcare: Equipping the Workforce for Digital Transformation** — University of Manchester, 2020
- **DeepLearning.AI** — 2020 — [verify](https://coursera.org/verify/57D32AP9GMZ7)
- **Oracle 8i** — Software Technology Group, STG Institute, Allahabad, India, 2000
- **Visual Basic 6.0** — KAIZEN Corp, Allahabad, India, 2000

---

## Languages

Arabic (Native) · English (Fluent)
