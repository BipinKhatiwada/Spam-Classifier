# 📩 Spam Classifier using Machine Learning

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

---

## 🚀 Features

* Classifies text messages into Spam or Ham
* Uses **TF-IDF Vectorization**
* Implements multiple ML models:

  * Multinomial Naive Bayes
  * Random Forest
  * Support Vector Machine (SVM)
* Uses **Voting Classifier (Soft Voting)** for better performance
* Interactive **Streamlit Web App**

---

## 🧠 Tech Stack

* Python
* Scikit-learn
* NLTK
* Pandas & NumPy
* Streamlit

---

## ⚙️ How It Works

1. Text preprocessing (lowercase, remove stopwords, stemming)
2. Convert text into numerical form using **TF-IDF**
3. Train ML models on transformed data
4. Use **Voting Classifier** to improve prediction accuracy
5. Predict whether a message is Spam or Ham

---

## 📂 Project Structure

```
spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/BipinKhatiwada/Spam-Classifier.git
cd Spam-Classifier
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the app

```
python -m streamlit run app.py
```

---

## 📌 Example

Input:

```
Congratulations! You have won a free lottery ticket.
```

Output:

```
Spam
```

---

## 📊 Model Performance

* High accuracy using TF-IDF + ML models
* Improved results using ensemble (Voting Classifier)

---

## 🎯 Future Improvements

* Add deep learning models (LSTM, BERT)
* Improve UI design
* Deploy online (Streamlit Cloud / Render)

---

## 👨‍💻 Author

**Bipin Khatiwada**

---

## ⭐ Acknowledgement

This project is part of my **100 Days of Machine Learning** journey 🚀
