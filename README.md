# 🧠 Learning Style Classifier

A machine learning-based web application that predicts a user's learning style — **Visual, Auditory, or Kinesthetic** — using questionnaire responses.

---

## 🚀 Features

* Predicts learning style using trained ML models
* Interactive web interface built with Flask
* Real-time prediction from user inputs
* End-to-end pipeline: data → training → deployment

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Flask (Python)
* **Machine Learning:** Scikit-learn
* **Libraries:** NumPy, Pandas, Pickle

---

## 📂 Project Structure

```
Learning-Style-Classifier/
│
├── app.py
├── learningstyledataset.csv
├── svm_best_model.pkl
├── LEARNING_STYLE_CLASSIFIER.ipynb
├── requirements.txt
├── README.md
│
├── static/
│   ├── style.css
│   ├── script.js
│   └── image.png
│
└── templates/
    ├── index.html
    └── result.html
```

---

## 📊 Dataset

* Dataset sourced from **Kaggle (public dataset)**
* Contains user responses along with corresponding learning styles
* Preprocessed and encoded before training
* Used for training and evaluating multiple models

---

## 🧠 Model Selection

Multiple machine learning models were trained and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

After evaluation, **Support Vector Machine (SVM)** provided the best performance in terms of accuracy and generalization.

The final deployed model is:

```
svm_best_model.pkl
```

---

## ⚙️ How to Run Locally

### 1. Clone the repository

```
git clone https://github.com/your-username/Learning-Style-Classifier.git
cd Learning-Style-Classifier
```

### 2. Create virtual environment (optional)

```
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run the application

```
python app.py
```

### 5. Open in browser

```
http://127.0.0.1:5000/
```

---

## 📌 Future Improvements

* Improve UI/UX design
* Add model performance visualization
* Deploy the application online (Render / Heroku)
* Enhance dataset and model accuracy

---

## 👩‍💻 Developed By

**Shreejaa S M**
