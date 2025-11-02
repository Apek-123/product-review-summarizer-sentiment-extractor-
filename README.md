# 🛍️ Product Review Summarizer + Sentiment Extractor for E-Commerce Analytics  

### 📘 Project 14 | ABL-1 Activity | SIT  

---

## 📖 Overview  

This project automatically analyzes thousands of e-commerce product reviews and summarizes what customers **like** and **dislike** about different product features.  
It also extracts the **sentiment** (positive/negative) for each feature and allows **tone control** (formal or casual).  

Built entirely in **Python** using **Google Colab**, **Transformers**, and **Gradio**, this project follows the exact structure given by our faculty.  

---

## ⚙️ Features  

- 🧹 Text cleaning and preprocessing  
- 🔍 Automatic feature extraction using NLP (Spacy)  
- 💬 Sentiment analysis using Hugging Face Transformers  
- 🪄 LLM-based summarization (BART)  
- ✨ Tone-controlled summaries (formal & casual)  
- 📊 Evaluation using ROUGE metrics  
- 🌐 Interactive dashboard using Gradio  
- 📈 Beautiful data visualizations (Matplotlib)  

---

## 🧠 Tech Stack  

| Category | Technology |
|-----------|-------------|
| Language | Python 3 |
| Libraries | Transformers, Datasets, Evaluate, Gradio, Pandas, Numpy, Matplotlib, Spacy |
| Model | `facebook/bart-large-cnn` for summarization, Hugging Face Sentiment Pipeline |
| Platform | Google Colab |
| Dataset | Amazon Product Reviews (Public Subset) |

---

## 🧩 Project Architecture  

```plaintext
📦 Product Review Summarizer
 ┣ 📜 FINAL.ipynb
 ┣ 📜 feature_sentiment_summary.csv
 ┣ 📜 product_summaries.json
 ┣ 📜 metrics.json
 ┣ 📜 requirements.txt
 ┗ 📘 README.md
