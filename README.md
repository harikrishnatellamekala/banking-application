# 🏦 Simple Banking Application  

This is a **basic banking web application** built using **Python, Flask, HTML, and CSS**.  
It demonstrates the use of **Object-Oriented Programming (OOP) in Python** along with simple frontend and backend integration.  

---

## ✨ Features  

- 👤 **User Authentication** – Register and Login system  
- 💰 **Deposit Money** – Add funds to your account  
- 💸 **Withdraw Money** – Withdraw funds from your account  
- 📊 **Balance Check** – Check your account balance (password protected)  
- 📜 **Transaction History** – View past transactions (password protected)  
- 🎨 **Clean & Responsive UI** – Simple, user-friendly HTML & CSS design  

---

## 🛠️ Technologies Used  

- **Python** (for backend & OOP concepts)  
- **Flask** (for server-side and routing)  
- **HTML, CSS** (for frontend and styling)  

---

## 📂 Project Structure  

Banking-App/
│── app.py # Main Flask application
│── templates/ # HTML Templates
│ ├── register.html
│ ├── login.html
│ ├── home.html
│ ├── deposit.html
│ ├── withdraw.html
│ ├── balance.html
│ └── transactions.html
│── static/ # CSS and assets
│ └── css/
│ └── style.css
│── README.md # Project Documentation

yaml
Copy code

---

## ▶️ How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/Banking-App.git
   cd Banking-App
Create a virtual environment (recommended)

bash
Copy code
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
Install dependencies

bash
Copy code
pip install flask
Run the Flask app

bash
Copy code
python app.py
Open in browser

cpp
Copy code
http://127.0.0.1:5000/
