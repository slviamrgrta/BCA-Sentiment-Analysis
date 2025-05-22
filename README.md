# 📱 Sentiment Analysis on BCA Mobile App

This project focuses on analyzing user sentiment toward the **BCA Mobile Banking Application** using reviews from the Google Play Store. By leveraging the **IndoBERT** model, we classify user feedback into **positive**, **neutral**, or **negative** sentiments to gain insights into user perception and identify areas for improvement.

---

## 🧠 Background

As internet and mobile banking usage continues to grow in Indonesia, understanding user experiences through app reviews becomes increasingly valuable. Sentiment analysis helps businesses identify customer satisfaction levels and potential pain points in their digital platforms.

---

## 🎯 Objectives

- Classify app reviews into **positive**, **neutral**, and **negative** sentiments
- Identify key factors affecting user satisfaction (e.g., **usability**, **security**, **performance**)
- Analyze how BCA responds to user reviews and its impact on user perception
- Highlight the most relevant reviews based on thumbs-up count

---

## 📊 Dataset

- Source: Google Play Store reviews of **BCA Mobile**
- Format: CSV containing `review`, `rating`, and `thumbs_up` columns
- Total reviews analyzed: over 5,000

---

## 🛠️ Tools and Technologies

- **Python**
- **IndoBERT** (Transformer model for Bahasa Indonesia)
- HuggingFace Transformers
- Pandas, NumPy
- NLTK (Text preprocessing)
- Scikit-learn (Classification metrics)
- Matplotlib, WordCloud (Visualization)

---

## 🔁 Methodology
The process consists of multiple steps from data preprocessing to model deployment. Below is the flowchart of the methodology used:

![Methodology Flowchart](https://github.com/slviamrgrta/BCA-Sentiment-Analysis/blob/main/Metodologi.png)

---

## 📈 Results and Evaluation
The model was evaluated using accuracy, precision, recall, and F1-score. The performance is summarized below:

![Model Evaluation Report](https://github.com/slviamrgrta/BCA-Sentiment-Analysis/blob/main/Hasil.png)

---

## 🧾 Conclusion and Recommendations

- The majority of user sentiment is **positive**, indicating general satisfaction.
- **Performance issues** and **security concerns** were the most common sources of negative feedback.
- Users value **ease of use**, which significantly influences positive sentiment.
- BCA’s **fast response** to feedback helps improve perception and customer loyalty.
- It is recommended to:
  - Improve app **performance** and reduce crashes
  - Add more **security features**
  - Enhance the **responsiveness** to user reviews

---

