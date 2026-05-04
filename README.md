# 📰 Fake News Detection using BERT

## 📌 Overview

This project implements a **Fake News Detection system** using the **BERT (Bidirectional Encoder Representations from Transformers)** model.
The goal is to classify news articles as **Fake (0)** or **Real (1)** using deep learning and NLP techniques.

---

## 🚀 Features

* 🔍 Text classification using **BERT Transformer**
* 🧠 Context-aware understanding of news content
* 📊 Performance evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
* 📈 Visualization:

  * Training Loss Curve
  * Confusion Matrix

---

## 🧠 Model Details

* Model: **BERT (bert-base-uncased)**
* Framework: **HuggingFace Transformers**
* Task: Binary Text Classification
* Training:

  * Epochs: 3
  * Batch Size: 4
  * Max Length: 128

---

## 📂 Dataset

The dataset consists of:

* 📰 Fake news articles
* 📰 Real news articles

Source: Kaggle Fake News Dataset

---

## 📊 Results

| Metric    | Value   |
| --------- | ------- |
| Accuracy  | **82%** |
| Precision | 0.83    |
| Recall    | 0.82    |
| F1 Score  | 0.82    |

---

## 📈 Visualizations

### 🔹 Training Loss Curve

Shows how the model learns over time.

### 🔹 Confusion Matrix

Displays classification performance across classes.

---

## ⚠️ Note

Due to GitHub file size limitations, the trained BERT model is not uploaded.
You can regenerate the model by running the notebook.

---

## 🛠️ How to Run

1. Open the notebook:

   ```
   aml_project.ipynb
   ```
2. Run all cells in **Google Colab**
3. Train the model
4. View results and graphs

---

## 📦 Project Structure

```
fake-news-bert/
│
├── aml_project.ipynb
├── confusion_matrix.png
├── graph.png
├── BERT_based_detection_report.pdf
└── dataset files
```

---

## 🔮 Future Improvements

* Use advanced models like **RoBERTa**
* Deploy as a web app
* Improve dataset size
* Add explainable AI

---

## 👨‍💻 Author

**Ayush Kumar Sahoo**

---

## ⭐ Acknowledgements

* HuggingFace Transformers
* Kaggle Dataset
* Google Colab

---

## 📢 Conclusion

This project demonstrates how transformer-based models like BERT can effectively detect fake news with strong accuracy and contextual understanding.
