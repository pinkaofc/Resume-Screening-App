
Resume Screening App

An **AI-powered Resume Screening Web Application** that automatically classifies resumes into job categories using **Machine Learning**. This project demonstrates end-to-end AI workflow: data preprocessing, model training, evaluation, and deploying an interactive frontend.

I developed and trained the model in **Jupyter Notebook**, achieving **98% accuracy**, and then built the frontend using **Streamlit** in **VS Code**.

---

## 🚀 Features

* **Resume Upload:** Supports **PDF** and **TXT** formats.
* **Automatic Text Cleaning:** Removes URLs, emails, special characters, and extra spaces.
* **Preprocessing with NLP:** Uses **NLTK** for tokenization and stopword removal.
* **Feature Extraction:** Converts resumes into **TF-IDF vectors** for ML model input.
* **Job Category Prediction:** Classifies resumes into multiple job roles, e.g.,

  * Data Science
  * Java Developer
  * HR
  * Python Developer
  * Mechanical Engineer, etc.
* **Interactive Web App:** Built using **Streamlit**, easy to use and deploy.

---

## 🛠️ Tech Stack

* **Python** – Core programming language
* **Jupyter Notebook** – Model development and experimentation
* **VS Code** – Frontend and app deployment
* **Streamlit** – Web application frontend
* **scikit-learn** – TF-IDF vectorization and classifier
* **NLTK** – Text preprocessing
* **PyPDF2 / python-docx** – Resume parsing
* **pickle** – Model serialization

---

## 📊 Model Performance

* **Algorithm Used:** \[Specify classifier, e.g., Random Forest, SVM, etc.]
* **Accuracy:** 98% on test dataset
* **Evaluation Metrics:** Precision, Recall, F1-Score (can be added if you want)

---

## ⚡ How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/pinkaofc/resume-screening-app.git
   cd resume-screening-app
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app

   ```bash
   streamlit run app.py
   ```
4. Upload a resume and get the **predicted job category** instantly.

---

## 📝 Project Workflow

1. **Data Collection:** Gathered resumes in text or PDF format.
2. **Preprocessing:** Cleaned text data by removing noise, stopwords, emails, URLs, etc.
3. **Feature Extraction:** Converted text data into numeric features using **TF-IDF**.
4. **Model Training:** Trained a Machine Learning classifier in **Jupyter Notebook**.
5. **Evaluation:** Achieved **98% accuracy** on test data.
6. **Frontend Deployment:** Built a user-friendly web app with **Streamlit** in **VS Code**.
7. **Prediction:** Users can upload resumes and receive **instant category prediction**.

---

## 📌 Use Case

This app is useful for:

* **HR teams and recruiters** to screen resumes quickly.
* **Companies** to automate initial resume classification.
* **Educational purposes** to demonstrate end-to-end ML project deployment.

---

## 📁 File Structure

```
resume-screening-app/
│
├── app.py                # Streamlit frontend
├── clf.pkl               # Trained ML model
├── tfidf.pkl             # TF-IDF vectorizer
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── datasets/             # Sample resumes (optional)
```

---



📌 Use Case

This app can help HR teams and recruiters quickly screen resumes and classify them into job categories, saving time and effort in the hiring process.
