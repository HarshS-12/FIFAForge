## 🏆 FIFAForge: AI-Powered FIFA Player Rating Prediction System

An intelligent machine learning application that predicts **FIFA player overall ratings** using player stats and in-game attributes. Built with regression models, dimensionality reduction (PCA), clustering techniques, and deployed using Flask with MongoDB integration.

![Dashboard Preview](assets/fifaforge-dashboard.png)  

---

### 🧰 Tech Stack

| Layer      | Technology                                   |
|------------|----------------------------------------------|
| Backend    | Python, Flask, MongoDB                       |
| ML/Models  | scikit-learn (Linear, Ridge, Lasso), KMeans |
| Data       | Pandas, NumPy, PCA                           |
| Frontend   | HTML, CSS, Jinja2 Templates                  |
| Deployment | Render (with Gunicorn)                      |

---

### ✨ Features

#### ✏️ Player Rating Prediction
Input player stats and get an instant predicted **Overall Rating** using ML models.

#### 🔄 Dimensionality Reduction
Implemented **PCA** to simplify data while preserving essential variance.

#### 🌐 Player Clustering
Grouped players into meaningful clusters using **K-Means** for advanced insights.

#### 🔗 Flask Interface
Clean web app interface for user interaction and prediction submission.

#### 🛠️ MongoDB Integration
Store predicted player data and ratings dynamically in a local MongoDB database.

---

### 🧠 Architecture Overview

1. User inputs FIFA player stats via web form
2. Data is standardized and passed to ML models
3. PCA reduces dimensionality, predictions are generated
4. Clustering categorizes players
5. Flask displays prediction & saves it to MongoDB

---

### 📁 Project Structure
```
FIFAForge/
├── static/               # CSS, JS, and images
├── templates/            # Jinja2 HTML templates
├── model/                # Trained ML models, scaler, PCA
├── app.py                # Flask application
├── requirements.txt      # Project dependencies
└── README.md             # Project overview (this file)
```

---

### ⚙️ Environment Setup

```bash
# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
# or
source venv/bin/activate  # Mac/Linux

# Install required packages
pip install -r requirements.txt
```

---

### 🚀 Run the Application
```bash
# For development
python app.py

# For production (with Gunicorn)
gunicorn app:app
```
Visit: `http://127.0.0.1:5000/` (locally)

---

### 🌍 Use Cases
- Player scouting and team-building analysis
- Fantasy football prediction tools
- Interactive FIFA dashboards
- Sports data visualization and model deployment practice

---

### 🔮 Future Enhancements
- Deploy on cloud (Render, Railway, or AWS)
- Add player image upload and face clustering
- Enhance UI with Bootstrap or Tailwind
- Add user login and role-based prediction saving
- Dashboard with visual analytics using Plotly or Dash

---

### 🙋‍♂️ Author
**Created by:** Harsh Sharma  
📧 Email: harshsharma91318@gmail.com  
🔗 GitHub: [HarshS-12](https://github.com/HarshS-12)  
🔗 LinkedIn: [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)

 

 

 

> 💡 GitHub Repo: [https://github.com/HarshS-12/FIFAForge](https://github.com/HarshS-12/FIFAForge)
