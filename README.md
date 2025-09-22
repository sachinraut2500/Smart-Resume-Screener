# Smart Resume Screener

Match resumes to job descriptions and rank candidates by relevance and skills.

## Features
- Extract skills and keywords from resumes
- Compute semantic similarity between resumes and job descriptions
- Produce scores and overlapping skills

## Tech stack
Python, spaCy, SentenceTransformers, scikit-learn, pandas

## Install
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python -m spacy download en_core_web_sm
====
