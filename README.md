# 🍔 AI Smart Food Ordering System

An AI-powered Food Ordering and Restaurant Analytics platform built using Python, Streamlit, SQLite, and Machine Learning.

This project provides:

- 🍕 Online food ordering
- 📊 Customer analytics dashboard
- 📈 Food demand prediction
- 🤖 Food recommendation system
- 🍽️ AI chatbot waiter
- 🗄️ SQLite database integration
- 📉 Interactive visualizations

---

# 🚀 Features

## 🛒 Food Ordering
- Select food items
- Place orders
- Automatic bill calculation
- Save orders in database

## 📊 Customer Analytics
- Revenue analysis
- Most ordered foods
- Sales dashboard
- Interactive charts

## 📈 Demand Prediction
- Machine learning-based prediction
- Forecast future food demand
- Trend visualization

## 🤖 Food Recommendation System
- Mood-based food recommendations
- Smart suggestions

## 🍽️ AI Chatbot Waiter
- Recommends food
- Suggests budget meals
- Healthy food suggestions
- Interactive chatbot interface

---

# 🧠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend Logic |
| Streamlit | Frontend UI |
| SQLite | Database |
| Pandas | Data Processing |
| Scikit-learn | Machine Learning |
| Plotly | Interactive Charts |
| Pyngrok | Public Deployment |

---

# 📂 Project Structure

```text
AI-Food-App/
│
├── app.py
├── food_app.db
├── requirements.txt
├── README.md
└── assets/
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/AI-Food-App.git
```

---

## 2️⃣ Move into Project Folder

```bash
cd AI-Food-App
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Application

```bash
streamlit run app.py
```

---

# 🌐 Run in Google Colab

## Install Libraries

```python
!pip install streamlit pyngrok pandas scikit-learn plotly
```

---

## Start Streamlit

```python
from pyngrok import ngrok
import threading
import os

ngrok.set_auth_token("YOUR_NGROK_TOKEN")

def run():
    os.system("streamlit run app.py --server.port 8501")

thread = threading.Thread(target=run)
thread.start()

public_url = ngrok.connect(8501)

print(public_url)
```

---

# 🗄️ Database Schema

## Orders Table

| Column | Type |
|---|---|
| id | INTEGER |
| customer | TEXT |
| item | TEXT |
| quantity | INTEGER |
| price | INTEGER |
| order_time | TEXT |

---

# 📈 Machine Learning

The project uses:

- Linear Regression
- Historical order data
- Demand forecasting

Model predicts future food demand trends.

---

# 📊 Analytics Dashboard

Includes:
- Revenue by food item
- Popular food visualization
- Order trends
- Interactive charts

---

# 🤖 AI Features

## Food Recommendation System
Suggests food based on:
- Mood
- Preferences
- Weather
- User behavior

## AI Chatbot Waiter
Can answer:
- Food recommendations
- Budget options
- Healthy food suggestions
- Spicy food options

---
# 📌 Requirements

Create a `requirements.txt` file:

```text
streamlit
pandas
plotly
scikit-learn
pyngrok
```


# ⭐ Project Highlights

✅ Full Stack AI Application  
✅ Machine Learning Integration  
✅ Streamlit Dashboard  
✅ Real-Time Analytics  
✅ SQLite Database  
✅ Resume-Level Project  

