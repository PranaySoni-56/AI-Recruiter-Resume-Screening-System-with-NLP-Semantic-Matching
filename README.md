# AI Recruiter: Resume Screening System with NLP & Semantic Matching

🚀 A smart Resume Screening System built with **Python, NLP, and Machine Learning** that helps HR teams and recruiters automatically rank candidates against a given **Job Description (JD)**.  
The project is optimized to run in **Google Colab** — no local setup required.

## 📂 Features
- 📄 **Multi-format Resume Parsing**: Supports `.pdf`, `.docx`, and `.txt` resumes.  
- 🎯 **Skill Extraction**: Detects technical + soft skills (Python, SQL, ML, AWS, Communication, etc.).  
- 📊 **Multi-signal Scoring**: Combines
  - JD keyword coverage (noun phrases & tokens)
  - TF-IDF keyword similarity
  - Semantic similarity (BERT embeddings)
  - Experience heuristic (years of experience detection)  
- 📈 **Ranking & Match %**: Ranks resumes and gives a clear **match percentage (0–100%)**.  
- 📥 **Downloadable Results**: Outputs results in a clean table and downloadable `.csv`.  
- ☁️ **Colab Ready**: Upload JD & resumes, run, and get ranked candidates instantly.  

## 📦 Tech Stack
- **Python 3**  
- **NLP & ML**: `spaCy`, `sentence-transformers (BERT)`, `scikit-learn`  
- **Text Extraction**: `PyMuPDF`, `python-docx`, `tika`  
- **Fuzzy Matching**: `rapidfuzz`  
- **Data Handling**: `pandas`, `numpy`  
