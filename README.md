<h1 align="center">Vedant Mhapsekar</h1>
 
<p align="center">
  <b>AI &amp; Data Science Student · AI/ML Developer</b><br/>

</p>
<p align="center">
  <a href="https://www.linkedin.com/in/vedant-mhapsekar"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vedant.mhapsekar06@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/vedantmhapsekar06"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>
---
 
## About
 
Final-year B.Tech student in **Artificial Intelligence & Data Science (Honours in Cyber Security)** at K.J. Somaiya College of Engineering, Mumbai. I build end-to-end ML systems: data pipelines, retrieval and modelling, and deployable APIs with clean, tested backends.
 
- **Focus:** LLM applications, RAG systems, and explainable AI
- **Approach:** deterministic logic for decisions, LLMs for language, and tests for everything in between
- **Open to:** AI/ML internships and entry-level roles
---
 
## Major Projects
 
### [ResumeGuard](https://github.com/vedantmhapsekar06/Resume_Guard) — Multi-Agent Resume Screening
 
A fully local screening system with a recruiter mode (batch ranking) and a student mode (resume feedback).
 
- **Multi-agent pipeline:** seven agents (JD and resume analyzers, skills matching, experience, evidence, judge, improvement) coordinated by separate recruiter and student flows.
- **Deterministic scoring:** the LLM only extracts structured data and writes short commentary. Skills, experience, scores and labels are plain Python, so a model error can never change a result.
- **Explainable weighted score:** skills 40%, experience 30%, semantic similarity 20%, evidence 10%, with Fit and Priority labels and a required-skill knockout rule.
- **Resistant to keyword stuffing:** skills that are only listed earn partial credit, skills demonstrated in work bullets earn full credit, and unsupported skills are flagged for review.
- **Reliable by design:** date-aware experience analysis (overlaps merged, gaps flagged), fault-tolerant batch processing, HTML-escaped output, and 24 unit tests that run without a model.
`Python` `FastAPI` `Ollama (Llama 3.2)` `Sentence-Transformers` `scikit-learn` `SQLite`
 
### [ResearchFlow](https://github.com/vedantmhapsekar06/Research_Flow) — Hybrid-Retrieval RAG for Research Papers
 
A local chatbot for asking questions across multiple research PDFs, with answers grounded in the source text and cited by page.
 
- **Structured ingestion:** page-by-page extraction and overlapping chunks (220 words, 40 overlap) that keep page and section metadata, stored in ChromaDB with a BM25 keyword index.
- **Hybrid retrieval:** semantic search and BM25 fused with weighted Reciprocal Rank Fusion (0.6 / 0.4), absolute relevance floors, and per-paper balancing so comparison questions see every relevant paper.
- **Grounded answers:** the model must cite `[Source N]` or return a `NOT_FOUND` marker; only the sources actually cited are returned, renumbered to match the answer.
- **Conversational memory:** follow-up questions are rewritten into standalone search queries, with a fallback when the small model's rewrite is malformed.
- **Robust backend:** SHA-256 de-duplication, upload validation, atomic storage writes, automatic retry of transient Ollama failures, and 44 automated tests.
`Python` `FastAPI` `Ollama` `ChromaDB` `BM25` `PyMuPDF`
 
---
 
## Other Projects
 
| Project | Summary | Stack |
|---|---|---|
| **ECG Classification** | Classifies ECG signals into 5 cardiac conditions from clinical features, handling class imbalance with SMOTE and comparing Random Forest and SVM. | scikit-learn, SMOTE |
| **Digital Burnout Risk Prediction** | Predicts burnout risk for 1,000 users with feature-importance analysis, deployed as a Flask web app. | XGBoost, Flask |

 
---
 
## Tech Stack
 
| Area | Tools |
|---|---|
| **Languages** | Python, SQL |
| **ML / DL** | scikit-learn, XGBoost, PyTorch, TensorFlow/Keras, CNNs |
| **Computer Vision** | ConvNeXt, CLIP, Roboflow |
| **GenAI & NLP** | RAG, LangChain, Sentence Transformers, BGE, BM25, Ollama, Prompt Engineering |
| **Vector Databases** | ChromaDB, Qdrant |
| **Backend & Apps** | FastAPI, Flask, Streamlit, MongoDB, SQLite |
| **Data & Visualization** | Pandas, NumPy, Matplotlib, Power BI |
| **Tools** | Git, GitHub |
 
---
 
## GitHub Stats
 
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vedantmhapsekar06&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vedantmhapsekar06&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>
<p align="center"><i>Building practical, explainable AI systems.</i></p>
 
