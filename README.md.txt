# 🧠 Resume Cleaning & Candidate Ranking using NLP  

### 🚀 Project Overview
This project is an **NLP-based Resume Screening System** that automatically extracts, cleans, and analyzes resumes to rank candidates according to a given job description.

It uses **spaCy embeddings** to understand the semantic meaning of text, computes **cosine similarity**, and ranks all candidates based on how closely their resumes match the job requirements.

Since many resumes do not contain readable names, the system automatically assigns clean, unique IDs such as **Candidate_001**, **Candidate_002**, etc., ensuring organized and meaningful output.

---

### 🧩 Key Features
- 📄 **Supports PDF, DOCX, and TXT resumes**
- 🧹 **Cleans and lemmatizes text using NLP preprocessing**
- 🧠 **Uses spaCy embeddings (`en_core_web_md`)**
- 📈 **Ranks candidates using cosine similarity**
- 🔢 **Auto-generates unique candidate IDs**
- 📊 **Displays visual ranking graph**
- 💾 **Exports results to CSV**

---

### 🏗️ Workflow
1. **Text Extraction:** Extracts content from multiple resume formats.  
2. **Text Cleaning:** Removes unwanted symbols and stopwords.  
3. **Embedding Generation:** Uses spaCy vectors for semantic understanding.  
4. **Similarity Computation:** Compares resumes with job description using cosine similarity.  
5. **Ranking:** Lists and visualizes top candidates.

---

### 🧮 Tech Stack
**Language:** Python  
**Libraries:** `spaCy`, `pdfplumber`, `nltk`, `tqdm`, `matplotlib`, `scikit-learn`, `numpy`, `pandas`  
**Model Used:** `en_core_web_md` (spaCy Medium English Model)

---

### 📁 Folder Structure
