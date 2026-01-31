# 🎬 YouTube Trailer Sentiment Analysis using NLP & Transformers

This project performs **sentiment analysis on YouTube trailer comments** using Natural Language Processing (NLP) techniques and pretrained transformer models. It classifies audience reactions as **positive, negative, or neutral**, computes sentiment scores, and visualizes key opinion words using word clouds.

The system combines **rule-based sentiment scoring (VADER)** with a **deep learning transformer model (DistilBERT)** to improve sentiment detection accuracy.

---

# 📌 Features

- Analyze YouTube trailer comments
- Sentiment classification (Positive / Negative / Neutral)
- Sentence-level sentiment scoring
- Word-level sentiment extraction
- Hybrid model approach (Rule-based + Transformer)
- Positive & Negative word clouds
- Overall sentiment score calculation
- Excel dataset support

---

# 🧠 Models Used

## ✅ VADER Sentiment Analyzer
- Rule-based sentiment model
- Optimized for social media text
- Fast and lightweight
- Produces polarity scores:
  - Positive
  - Negative
  - Neutral
  - Compound score

**Used for:**
- Sentence sentiment scoring
- Word-level polarity detection
- Neutral sentiment handling

---

## ✅ DistilBERT Transformer Model
- Pretrained deep learning NLP model
- Loaded using Hugging Face transformers pipeline
- Context-aware sentiment classification
- Outputs:
  - POSITIVE
  - NEGATIVE
  - Confidence score

**Used for:**
- Final sentiment label prediction

---

# 🛠 Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- NLTK
- VADER Sentiment
- Pandas
- Matplotlib
- WordCloud
- OpenPyXL

---

# 📂 Dataset

- Input data is read from an **Excel file**
- Contains YouTube trailer comments
  

