# Fake News Detector — Multi-Agent Inspired Project

A simple fake-news detection project using TF-IDF + Logistic Regression and a Streamlit demo.  
This repo is designed as a clean starter you can extend into a multi-agent system later.

## Repo Structure
fake-news-detector/
├─ data/ # place your train.csv here (not in repo)
├─ outputs/ # saved model will be stored here
├─ src/
│ ├─ init.py
│ ├─ preprocessing.py
│ ├─ models.py
│ └─ inference.py
├─ app/
│ └─ streamlit_app.py
├─ train.py
├─ requirements.txt
├─ Dockerfile
├─ tests/
│ └─ test_preprocessing.py
└─ README.md
