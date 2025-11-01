# 🧠 Rock vs Mine Predictor

A Machine Learning project that classifies sonar signals as either **Rock** or **Mine** using **Logistic Regression**.

---

## 📖 Project Overview

This project uses the **Sonar Dataset** (UCI) to build a binary classification model that identifies whether an object detected by sonar is a **Rock (R)** or a **Mine (M)**.

The dataset consists of **60 features**, each representing the energy of a sonar signal at different frequencies.  
By training a **Logistic Regression model**, the system learns to detect patterns and classify new inputs accurately.

---

## 🧩 Features

- Implements **Logistic Regression** for binary classification  
- Processes and splits data into training and testing sets  
- Evaluates accuracy on both training and test data  
- Provides a **Flask-based web interface** for real-time predictions  
- Clean, beginner-friendly code structure  

---

## ⚙️ Tech Stack

- **Python**
- **NumPy**, **Pandas**, **scikit-learn**
- **Flask** (for web app deployment)
- **HTML5**, **CSS3** (for frontend interface)

---

## 📊 Model Details

- **Algorithm:** Logistic Regression  
- **Training/Test Split:** 90% training, 10% testing  
- **Evaluation Metric:** Accuracy Score  
- **Dataset:** Sonar Data (UCI Machine Learning Repository)

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/rock-vs-mine-predictor.git
cd rock-vs-mine-predictor

2. Install dependencies
pip install -r requirements.txt

3. Run the training script
python train_and_save.py

4. Launch the Flask app
python app.py

5. Open in browser

Go to: http://127.0.0.1:5000/

💡 Example Input & Output
Each prediction requires 60 sonar readings as input.
The model will output one of the following results:
🪨 Rock
💣 Mine
📈 Results

Training Accuracy: 0.8342245989304813
Test Accuracy: 0.7619047619047619

📂 File Structure
rock-vs-mine-predictor/
│
├── app.py                 # Flask web app  
├── train_and_save.py      # Model training script  
├── model.pkl              # Saved logistic regression model  
├── templates/
│   └── index.html         # Frontend HTML page  
├── static/
│   └── style.css          # CSS styling  
├── Copy of sonar data.csv # Dataset file  
└── requirements.txt       # Python dependencies  

🧠 What I Learned
Fundamentals of Logistic Regression and binary classification, Data preprocessing, feature selection, and model evaluation, Deploying ML models with Flask, Integrating a simple frontend with a Python backend

🏷️ Credits
Dataset: UCI Machine Learning Repository - Sonar Dataset
Developed by: Sohan Varkhedi

🪩 Future Improvements
Add more algorithms (SVM, Random Forest) for comparison
Deploy on a cloud platform (Render / Heroku / AWS)
Improve frontend UI with React or Tailwind CSS

⭐ If you found this project helpful, consider giving it a star!
