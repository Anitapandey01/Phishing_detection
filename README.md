# 🛡️ Phishing Detection Project  
A Machine Learning–based system to detect phishing URLs using feature extraction and classification techniques.

---

## 📌 Overview  
This project analyzes website URLs and predicts whether they are **phishing** or **legitimate**.  
The system uses **Machine Learning algorithms**, a trained model, and vectorization techniques to identify malicious patterns in URLs.

---

## 🧠 Features  
- Detects phishing vs. legitimate URLs  
- Trained using Natural Language Processing (NLP)  
- Uses **TF-IDF vectorizer**  
- Classification model using  
  - Multinomial Naive Bayes  
  - Linear Regression / Logistic Regression  
- Web interface using **Flask (app.py)**  
- Ready-to-use model files (`.pkl`)

---

## 📁 Project Structure  
├── app.py # Flask web application
├── detction code.ipynb # Model training and EDA notebook
├── phishing.pkl # Trained ML model
├── phishing_mnb.pkl # MNB-based model
├── phishing_site_urls.csv # Dataset
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # Necessary libraries
└── README.md # Project documentation


---

## 🗂 Dataset  
The project uses a dataset containing phishing and legitimate website URLs with labels.  
CSV File: `phishing_site_urls.csv`

---

## 🧪 Algorithms Used  
### ✔ Multinomial Naive Bayes  
Used for text classification and URL pattern detection.

### ✔ Logistic / Linear Regression  
Used to classify URLs based on probability.

### ✔ TF-IDF Vectorization  
Converts URL text into numerical format for model training.

---

## 🔧 Installation and Setup  
Follow these steps to run the project locally:

### **1️⃣ Clone the repository**
git clone https://github.com/Anitapandey01/Phishing_detection.git


### **2️⃣ Install required libraries**


pip install -r requirements.txt


### **3️⃣ Run the Flask application**


python app.py


The app will start on:


http://127.0.0.1:5000/


---

## 💡 How It Works  
1. User enters a URL  
2. URL is converted into numeric features using **vectorizer.pkl**  
3. Model (`phishing.pkl` or `phishing_mnb.pkl`) predicts phishing probability  
4. Output displayed on the screen

---

## 🚀 Future Enhancements  
- Improve accuracy using advanced models (Random Forest, XGBoost)  
- Deploy the model using AWS / Render / Vercel  
- Add real-time URL scanning  
- Build frontend dashboard with charts  

---

## 📚 Requirements  
All dependencies are listed in:

requirements.txt


---

## 🧑‍💻 Author  
**Anita Pandey**  
B.Tech CSE | Machine Learning & Web App Development

---

## ⭐ Support  
If you like this project, please give it a ⭐ on GitHub!
