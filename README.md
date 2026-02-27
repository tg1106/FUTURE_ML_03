# Resume Screening ML System

An ML-powered resume screening system that ranks candidates based on job description similarity using TF-IDF and cosine similarity.

## Setup

```bash
pip install pandas numpy scikit-learn nltk spacy matplotlib seaborn
python -m spacy download en_core_web_sm
```

## Project Structure

```
resume-screening-ml/
├── data/
│   └── resume_dataset.csv
├── notebooks/
│   └── Resume_Screening_System.ipynb
├── src/
│   ├── preprocessing.py
│   ├── skill_extractor.py
│   ├── scorer.py
│   └── utils.py
├── requirements.txt
├── README.md
└── main.py
```
