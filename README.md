# 🎯 Play-Store-Ratings-Prediction

> Predicting Google Play Store review ratings (1–5★) using NLP and Machine Learning (Python 3.10).

[![Last Commit](https://img.shields.io/github/last-commit/Tinnne/Play-Store-Ratings-Prediction?style=flat-square)](https://github.com/Tinnne/Play-Store-Ratings-Prediction/commits)
[![License](https://img.shields.io/github/license/Tinnne/Play-Store-Ratings-Prediction?style=flat-square)](https://github.com/Tinnne/Play-Store-Ratings-Prediction/blob/main/LICENSE)
[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?style=flat-square&logo=jupyter&logoColor=white)](https://github.com/Tinnne/Play-Store-Ratings-Prediction)
[![Language](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3100/)

---

## 📚 Table of Contents

- [🎯 Play-Store-Ratings-Prediction](#-play-store-ratings-prediction)
  - [📚 Table of Contents](#-table-of-contents)
  - [🧠 Overview](#-overview)
  - [🤔 Why This Project?](#-why-this-project)
  - [🚀 Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
      - [Project](#project)
      - [TensorFlow Environment](#tensorflow-environment)
      - [PyTorch Environment](#pytorch-environment)

---

## 🧠 Overview

Play-Store-Ratings-Prediction is a **personal machine learning project** focused on predicting user star ratings (1–5) from review text collected on the Google Play Store.  
It covers the full pipeline: data collection → cleaning → text representation → model training → evaluation & insights.

---

## 🤔 Why This Project?

This work demonstrates how Natural Language Processing (NLP) and machine learning techniques can capture user sentiment and forecast review ratings.  
Key workflow components:

- 🧲 **Data Collection:** Automated extraction of user reviews using `google-play-scraper` library.
- 🧹 **Data Cleaning:** Noise removal (URLs, emojis, special characters) and text preparation.
- 🧠 **Contextual Embeddings:** Experiments with TF-IDF, Word2Vec, BERT for richer text representations.
- 🧾 **Text Vectorization:** Converting processed review text into features for ML models.
- 🔍 **Exploratory Data Analysis (EDA):** Visualizing rating distributions, embedding clusters and model behaviour.

---

## 🚀 Getting Started

### Prerequisites

- **Python version:** 3.10
- **Environment management:** Conda
- **Two framework workflows supported:** TensorFlow & PyTorch
- **Core libraries:** `pandas`, `numpy`, `google-play-scraper`, `scikit-learn`, `transformers`, `nltk`, `gensim`, `matplotlib`, `seaborn`

---

### Installation

#### Project

```bash
git clone https://github.com/Tinnne/Play-Store-Ratings-Prediction.git
cd Play-Store-Ratings-Prediction
```

#### TensorFlow Environment

The TensorFlow Environment is used for all the steps except Contextual Embeding.

```bash
conda env create -f tfenv.yml
```

#### PyTorch Environment

The PyTorch Environment is used for the Contextual Embedding step.

```bash
conda env create -f torchenv.yml
```
