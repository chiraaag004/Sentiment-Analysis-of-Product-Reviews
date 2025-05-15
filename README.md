# Sentiment Analysis of Product Reviews

This project applies natural language processing (NLP) techniques using both rule-based and transformer-based models to classify product review sentiments. Built using Python in a Jupyter notebook, the project demonstrates how to preprocess text data, apply sentiment scoring with VADER, fine-tune predictions using a pre-trained Hugging Face model, and visualize results.

---

## Objective

To build a sentiment classification pipeline that can automatically determine whether a customer review expresses positive or negative sentiment. The project leverages both lexicon-based sentiment scoring and transformer-based sequence classification models for comparative analysis.

---

## Tools & Libraries Used

- **Python** — Core programming language
- **Pandas, NumPy** — Data manipulation and processing
- **Matplotlib, Seaborn** — Data visualization
- **NLTK** — Rule-based sentiment analysis using VADER
- **Hugging Face Transformers** — Pre-trained transformer model for text classification
- **Scipy** — Softmax scoring
- **Tqdm** — Progress tracking

---

## Dataset

The dataset used is a collection of Amazon product reviews, which includes textual review content and associated metadata. For privacy and size reasons, only a sample may be included.

---

## Project Structure

- `sentiment analysis.ipynb` — Jupyter Notebook containing all code
- `requirements.txt` — List of dependencies
- `README.md` — Project documentation
- `data/` — (Optional) Folder for sample dataset
- `visuals/` — (Optional) Folder for generated graphs or screenshots

---

## Key Features

- ✅ Clean and preprocess review text (lowercasing, punctuation removal)
- ✅ Perform sentiment analysis using:
  - **VADER (NLTK)** — A lexicon and rule-based sentiment analyzer
  - **Hugging Face Transformers** — A pre-trained model for binary classification
- ✅ Visualize sentiment distributions
- ✅ Normalize outputs with Softmax
- ✅ Compare performance and visualize confusion matrix

---

## Sample Results

- Sentiment scores categorized into positive and negative
- Accuracy metrics and classification report
- Bar plots showing distribution of sentiments
- Confusion matrix for model evaluation
