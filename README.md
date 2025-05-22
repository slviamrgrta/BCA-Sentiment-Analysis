# BCA-Sentiment-Analysis

# 🤖 Sentiment Analysis on BCA Mobile App Reviews using IndoBERT

A natural language processing (NLP) project that applies sentiment analysis to user reviews of the BCA Mobile Banking app from the Google Play Store. The project uses the IndoBERT model to classify sentiments as **positive**, **neutral**, or **negative**, and provides insights on **factors influencing user satisfaction** and **the bank’s response behavior**.

---

## 📌 Background

- 📱 BCA Mobile is one of the most popular mobile banking apps in Indonesia.
- 🔍 With the rise of user-generated reviews, analyzing sentiment can uncover valuable feedback to improve user experience.
- 🇮🇩 This project focuses on sentiment classification in the Indonesian language using IndoBERT, a pre-trained BERT model for Bahasa Indonesia.

---

## 🎯 Objectives

- Classify user reviews into **positive**, **neutral**, or **negative** sentiment.
- Identify **key factors** affecting user satisfaction: performance, security, usability.
- Evaluate **BCA’s response** to reviews and its impact on user perception.
- Highlight the most **relevant reviews** using thumbs-up count as a metric.

---

## 🧠 Methods & Tools

### 📚 Libraries & Tools
- `Python`, `Pandas`, `NLTK`, `Scikit-learn`, `Matplotlib`, `Seaborn`
- `Transformers`, `IndoBERT`, `Huggingface`, `Tokenizers`

### 🧪 Methodology
1. Data collection from Google Play Store reviews
2. Text preprocessing (normalization, stopword removal, tokenization)
3. Sentiment modeling using **IndoBERT**
4. Evaluation with Accuracy, F1-Score, Precision
5. Visualization (word clouds, label distribution)
6. Optional deployment interface

---

## 📊 Results

| Sentiment | Proportion |
|-----------|------------|
| Positive  | 39.4%      |
| Neutral   | 30.9%      |
| Negative  | 29.7%      |

- **Accuracy**: 92.35%  
- **F1 Score**: 92.33%  
- **Precision**:  
  - Positive: 94%  
  - Neutral: 96%  
  - Negative: 86%

> ✅ The model performs well in predicting sentiments, with particularly strong results for neutral and positive classes.

---

## 📈 Visualization Samples

- Word cloud of most frequent terms
- Distribution of sentiment labels
- Top reviews by thumbs-up (most helpful feedback)

---

## 💡 Recommendations

1. **Improve App Performance** – address frequent issues like lag/crash.
2. **Enhance Security Features** – respond to user concerns about data protection.
3. **Faster Response to Reviews** – improve reputation by acknowledging feedback.

---

## 🧾 Conclusion

- Most users are satisfied with BCA Mobile’s ease of use.
- Key concerns lie in **performance** and **security**.
- A quick, proactive response by the bank to user reviews significantly improves public perception and trust.

---

## 📁 Project Structure

