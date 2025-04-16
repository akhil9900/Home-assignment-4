# Home-assignment-4
# NLP Mini Project - CS5720

This project demonstrates core NLP tasks using Python and popular libraries like NLTK, spaCy, NumPy, and HuggingFace Transformers.

## 📌 Tasks Covered

### Q1: NLP Preprocessing Pipeline
- **Libraries:** NLTK
- **Steps:**
  - Tokenization
  - Stopword Removal
  - Stemming
- **Input:** `"NLP techniques are used in virtual assistants like Alexa and Siri."`
- **Output:** Original tokens, tokens without stopwords, and stemmed tokens.

### Q2: Named Entity Recognition (NER)
- **Libraries:** spaCy
- **Steps:**
  - Extracts entities from text
  - Displays label, start, and end positions
- **Input:** `"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."`
- **Output:** Named entities with labels and positions.

### Q3: Scaled Dot-Product Attention
- **Libraries:** NumPy
- **Steps:**
  - Dot product of Q and Kᵀ
  - Scaled by √d
  - Softmax for weights
  - Weighted sum with V
- **Output:** Attention weights and final attention output matrix.

### Q4: Sentiment Analysis using Transformers
- **Libraries:** HuggingFace Transformers
- **Steps:**
  - Load pre-trained sentiment model
  - Analyze sentence
- **Input:** `"Despite the high price, the performance of the new MacBook is outstanding."`
- **Output:** Sentiment label and confidence score.

## ✅ Setup Instructions

1. Install dependencies:

```bash
pip install nltk spacy numpy transformers
python -m nltk.downloader punkt stopwords
python -m spacy download en_core_web_sm
