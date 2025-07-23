# ATS Resume Checker 🔍📄

An AI-powered system that automatically analyzes resumes, extracts skills and entities (name, email, phone), and matches them with relevant job descriptions using NLP and ML models.

---

## 🚀 Features

- 📄 Extract text from PDF and TXT resumes
- 🤖 Named Entity Recognition (NER) for name, email, phone
- 🧠 Semantic similarity with Job Descriptions using Sentence Transformers
- 📊 Resume-JD matching score with cosine similarity
- 🌐 Skill extraction with NLP and Word2Vec (GloVe)
- 📉 Visualization of skill frequency, clustering, and ROC analysis

---

## 🛠️ Tech Stack

- Python 3.10+
- [spaCy](https://spacy.io/)
- [NLTK](https://www.nltk.org/)
- [sentence-transformers](https://www.sbert.net/)
- [gensim (GloVe)](https://radimrehurek.com/gensim/)
- [scikit-learn](https://scikit-learn.org/)
- [matplotlib & seaborn](https://matplotlib.org/)
- [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/en/latest/)

---

## 🧪 Installation

1. Clone the repository:

```bash
git clone https://github.com/codersayan0/ATS-resume-checker.git
cd ATS-resume-checker
