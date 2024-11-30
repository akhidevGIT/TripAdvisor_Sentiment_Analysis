# Sentiment Analysis Using TextBlob and Transformer-Based Models

## 📜 Overview

This project demonstrates a **Sentiment Analysis** pipeline leveraging two distinct methods:
1. **TextBlob** for polarity analysis (Positive/Negative sentiment).
2. **Hugging Face's Transformer Model** (`nlptown/bert-base-multilingual-uncased-sentiment`) for fine-grained sentiment scoring on a scale of **1-5**.

The aim is to analyze textual data such as Trip Advisor hotel reviews to assess the sentiment of the reviews.

---

## 🛠️ Features

- **TextBlob Polarity Analysis**:
  - Quick and effective sentiment polarity detection (Positive or Negative).
  - Suitable for lightweight applications and initial sentiment filtering.

- **Transformer-Based Sentiment Scoring**:
  - Fine-grained sentiment scoring using a pre-trained multilingual BERT model.
  - Scores range from **1 (most negative)** to **5 (most positive)**.
  - Supports multilingual text, enabling sentiment analysis across various languages.

- **Performance Visualization**:
  - Comparison of sentiment distribution between the two methods.


---

## 🔧 Technologies Used

- **Programming Language**: Python
- **Libraries and Tools**:
  - Text Analysis: `TextBlob`
  - Transformer Models: `Hugging Face Transformers`
  - Data Manipulation: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
- **Version Control**: Git and GitHub

---

## 📂 File Structure

```plaintext
Sentiment-Analysis/
│
├── data/                      # Dataset folder
│   ├── reviews.csv            # Input text data   
│
├── sentiment-analysis.ipynb   # Sentiment Analysis Jupyter notebook  
│
├── artifacts/                 # outputs from analysis
│   ├── bert_scores.csv     # Transformer model checkpoint (if fine-tuned)
│
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
