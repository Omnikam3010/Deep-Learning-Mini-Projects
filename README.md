# NLP Preprocessing and Text Classification

## 📌 Objective

The objective of this project is to implement Natural Language Processing (NLP) preprocessing techniques and build a text classification model using machine learning algorithms.

---

## 🎯 Learning Outcomes

* Apply NLP preprocessing techniques:

  * Tokenization
  * Stopword Removal
  * Lemmatization
* Perform text vectorization:

  * TF-IDF
  * CountVectorizer
* Build classification models
* Evaluate model performance using metrics

---

## 📂 Dataset

We used the **SMS Spam Collection Dataset** from Kaggle.

* Total messages: 5574
* Labels:

  * **Ham (0)** → Normal message
  * **Spam (1)** → Unwanted message

---

## ⚙️ Preprocessing Steps

The following preprocessing steps were applied:

1. Converted text to lowercase
2. Removed special characters and numbers
3. Tokenized the text
4. Removed stopwords
5. Applied lemmatization

---

## 🔢 Feature Extraction

Two vectorization techniques were used:

* **TF-IDF Vectorizer**
* **CountVectorizer**

TF-IDF helps reduce the importance of commonly occurring words and improves model performance.

---

## 🤖 Models Implemented

### 1. Logistic Regression

* Suitable for classification problems
* Handles complex relationships well

### 2. Naive Bayes

* Based on probability theory
* Works efficiently for text classification

---

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score

### Results Summary:

* Logistic Regression achieved higher accuracy compared to Naive Bayes
* TF-IDF performed better than CountVectorizer

---

## 📈 Analysis

* Logistic Regression performed better due to its ability to capture complex patterns
* Naive Bayes performed well but assumes feature independence
* Preprocessing significantly improved model performance
* TF-IDF reduced noise from frequent words

---

## ✅ Conclusion

* NLP preprocessing is essential for improving model accuracy
* TF-IDF + Logistic Regression gave the best performance
* The model can be used for real-world spam detection systems

---

## 🚀 Future Improvements

* Use Deep Learning models (LSTM, BERT)
* Hyperparameter tuning
* Use larger datasets

---

## 🧑‍💻 Author

Your Name
