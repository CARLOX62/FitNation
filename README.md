# 🔥 FitNation - Calorie Burn Prediction Web App

FitNation is a health-focused web application built with **Flask** and **Machine Learning** to predict the number of calories burned during a workout session. It also includes a student-friendly **Tkinter-based College ChatBot** for academic queries.

![Screenshot (55)](https://github.com/user-attachments/assets/fa223d87-e989-48ad-9289-f260104cb1db)


---

## 🚀 Live Demo

🎯 **Live URL:** (http://127.0.0.1:5000/)  


---

## 🧠 Key Features

- 🔐 **User Login & Registration** system with hashed password
- 📊 **ML Model Integration** (`pipeline.pkl`) for calorie prediction
- 💬 **Smart Suggestions** based on BMI score
- 🧾 **Data Storage** in `SQLite` DB (`user_inputs.db`)
- 🧠 **CollegeBot (ChatBot)** using `Tkinter` & `nltk`
- 📄 Fully designed with HTML templates (`Flask-Jinja`)

---

## 🖥️ Technologies Used

- Python 3.8+
- Flask
- SQLite3
- Scikit-learn
- Pandas, NumPy
- Tkinter (GUI for Chatbot)
- HTML/CSS (Jinja templates)

---

## 📂 Project Structure

```
FitNation/
│
├── app.py                 # Flask app for Calorie Prediction
├── pipeline.pkl           # Trained ML model
├── user_inputs.db         # SQLite database
├── calories.csv           # Raw data
├── calories.ipynb         # Notebook for training
├── py chatbot.py          # Tkinter College Chatbot
│
├── static/
│   └── css/               # CSS styling
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── predictor.html
│   ├── result.html
│   └── index.html
│
├── Screenshot (54).png    # UI screenshot
├── requirements.txt       # Python dependencies
└── README.md              # You are here!
```

---

## ⚙️ Getting Started (Run Locally)

### 🔧 1. Clone the repository
```bash
git clone https://github.com/CARLOX62/FitNation.git
cd FitNation
```

### 📦 2. Install dependencies
```bash
pip install -r requirements.txt
```

### ▶️ 3. Run the Flask App
```bash
python app.py
```
Visit: `http://localhost:5000`

### 🤖 4. Run the College ChatBot
```bash
python "py chatbot.py"
```
![Screenshot (57)](https://github.com/user-attachments/assets/aef69aab-de74-47c9-a3f6-ba9c7c783154)

---

## 📸 Screenshot

![Screenshot (56)](https://github.com/user-attachments/assets/40a5671a-483f-46d7-b068-f962d4b64c45)


---



## 🙋‍♂️ Author

**👤 CARLOX62**  
GitHub: [@CARLOX62](https://github.com/CARLOX62)

---
