<div align="center">

# 💬 Natural Language Processing

**Teach machines to read: from raw, messy text to clean tokens, vectors, word embeddings and a working sentiment classifier, on 50,000 real IMDB movie reviews.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-Text-154F5B)
![spaCy](https://img.shields.io/badge/spaCy-NLP-09A3D5?logo=spacy&logoColor=white)
![Gensim](https://img.shields.io/badge/Gensim-Word2Vec-4B8BBE)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)

</div>

---

## 🎯 The NLP pipeline, step by step

```
Raw text ──► Preprocessing ──► Vectorization ──► Word embeddings ──► Model
 (IMDB)      clean & tokenize    BoW · TF-IDF      Word2Vec            sentiment
```

Each notebook covers one stage of the pipeline on the same dataset, so you can see exactly how every step changes the text and the model.

---

## 📚 Lessons

| # | Lesson | What you'll learn |
|---|---|---|
| 1 | [Text preprocessing](1.%20Basic%20Text%20Preprocessing.ipynb) | Lowercasing, removing HTML & URLs, punctuation, abbreviations, spelling correction (TextBlob), stop words, tokenization (split, regex, NLTK, spaCy), stemming and lemmatization |
| 2 | [Text representation / vectorization](2.%20Text%20Representation_Vectorization.ipynb) | Why text must become numbers; one-hot encoding, Bag of Words, n-grams, TF-IDF (and why the log in IDF), topic modelling with TF-IDF + NMF, custom feature extraction |
| 3 | [Word embeddings (pre-trained)](3.%20Word%20Embeddings%20%28word_to_vector%29.ipynb) | Word2Vec with Google News 300-d vectors via Gensim: similar words, analogies and similarity on IMDB reviews |
| 4 | [Training Word2Vec + sentiment model](4.%20word2vec_self_trained_embedding_imdb.ipynb) | Train your own Word2Vec on 50k IMDB reviews, explore and visualise the 3-D vector space, then build a sentiment classifier with Logistic Regression |

---

## 🚀 Getting started

```bash
git clone https://github.com/ahmadhassan-aiops/natural-language-processing.git
cd natural-language-processing
pip install pandas numpy scikit-learn nltk spacy textblob gensim matplotlib jupyter
python -m spacy download en_core_web_sm
jupyter notebook
```

### 🗂️ Dataset

All lessons use the **IMDB Dataset of 50K Movie Reviews** (`IMDB Dataset.csv`, ~66 MB, too large to store here).
Download it from [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) and place it in the repository root, next to the notebooks.

> Lesson 3 downloads the pre-trained `word2vec-google-news-300` vectors (~1.6 GB) through `gensim.downloader` on first run.

---

## 🧭 Part of a complete Data Science path

**Python → NumPy → Pandas → Matplotlib → Seaborn → Statistics → Machine Learning → Deep Learning → NLP**

- 🐍 [Python for Data Science](https://github.com/ahmadhassan-aiops/python-for-data-science)
- 🔢 [NumPy](https://github.com/ahmadhassan-aiops/Numpy)
- 🐼 [Pandas](https://github.com/ahmadhassan-aiops/Pandas)
- 📈 [Matplotlib](https://github.com/ahmadhassan-aiops/matplotlib)
- 🎨 [Seaborn](https://github.com/ahmadhassan-aiops/seaborn)
- 📊 [Statistics](https://github.com/ahmadhassan-aiops/statistics-for-data-science)
- 🤖 [Machine Learning](https://github.com/ahmadhassan-aiops/machine-learning-algorithms-and-techniques)
- 🧠 [Deep Learning](https://github.com/ahmadhassan-aiops/deep-learning-neural-network-architecture)
- 💬 **NLP** ← you are here

---

## 👨‍🏫 About the author

**Ahmad Hassan** | AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notebooks help you learn, please star the repo. It helps other students find it!
