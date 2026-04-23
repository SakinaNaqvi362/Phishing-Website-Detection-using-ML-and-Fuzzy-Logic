# 🚀 Phishing Website Detection using Machine Learning & Fuzzy Logic

## 📌 Overview
This project detects phishing websites by analyzing URLs using Machine Learning and Fuzzy Logic.  
It classifies a given URL as **Safe (0)** or **Phishing (1)**.

---

## 🎯 Objectives
- Detect phishing websites automatically  
- Improve user security  
- Apply Machine Learning techniques  
- Combine ML with Fuzzy Logic for better decision-making  

---

## 🧠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TF-IDF (Term Frequency – Inverse Document Frequency)  
- Flask  
- Joblib  
- Matplotlib  

---

## 📂 Project Structure

```
phishing_project/
│
├── dataset/
│   └── phishing.csv
│
├── preprocessing/
│   └── preprocess.py
│
├── models/
│   ├── lr.py
│   ├── svm.py
│   ├── nn.py
│
├── fuzzy/
│   └── fuzzy_logic.py
│
├── main.py
├── predict.py
├── app.py
├── graphs.py
├── README.md
├── requirements.txt
```

---

## ⚙️ How It Works

1. Load dataset of URLs  
2. Convert URLs into numerical features using TF-IDF  
3. Train Machine Learning models:
   - Logistic Regression  
   - Support Vector Machine (SVM)  
   - Neural Network (MLP)  
4. Evaluate models using accuracy  
5. Apply Fuzzy Logic for risk scoring  
6. Predict whether URL is Safe or Phishing  

---

## 📊 Results

| Model | Accuracy |
|------|----------|
| Logistic Regression | ~97% |
| SVM | ~99% |
| Neural Network | ~99% |

---

## 📈 Visualization
- Model Accuracy Comparison Graph  
- Confusion Matrix (optional)  

---

## ▶️ How to Run

### 1️⃣ Install dependencies
```
pip install -r requirements.txt
```

### 2️⃣ Train models
```
python main.py
```

### 3️⃣ Test prediction
```
python predict.py
```

### 4️⃣ Run web app
```
python app.py
```

Then open browser:
```
http://127.0.0.1:5000
```

---



---

## 🏆 Acknowledgement
This project was developed under  
**PITP (Professional IT Program) – NED Academy**

---

## 👨‍💻 Author    
**Sakina Naqvi**  
Computer Engineering Student  

---

## 📌 Future Improvements
- Use Deep Learning models (CNN/RNN)  
- Real-time browser extension  
- Larger dataset for improved accuracy  
