# Python Flask Authentication 🌐
A Python Flask application that provides authentication services, including user registration, login, and session management. The application uses MongoDB as the database, with HTML and CSS for the front-end.
## Features
 - **User Registration**: Securely register users and store their credentials in MongoDB.
 - **User Login**: Validate user credentials and establish secure sessions.
 - **Password Security**: Store passwords securely using hashing (e.g., bcrypt).
 - **Custom Frontend**: Responsive and user-friendly interface using HTML and CSS.
## 🛠️ Technologies Used
 - **Backend**: Flask (Python)
 - **Frontend**: HTML, CSS
 - **Database**: MongoDB
 - **Password Hashing**: bcrypt or similar hashing library
## 📦 Installation
- Prerequisites
- Python 3.x installed
- MongoDB server running locally or hosted (e.g., MongoDB Atlas)
- A virtual environment (optional but recommended)
**Clone the Repository**:
```bash
git clone https://github.com/It-Specialist-Deepak/Python-Flask-Authentication.git
```
**Set Up a Virtual Environment (Optional)**:
```bash
 python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```
**Install Dependencies**:
 ```bash
pip install -r requirements.txt
```
**Set Environment Variables**: Create a .env file in the root directory and add:
```bash
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/dbname
SECRET_KEY=your-secret-key
```
**Run the Application**:
```bash
python app.py
```
Access the Application:
Open your browser and go to: **http://127.0.0.1:5000**

Let me know if you'd like any additional sections or enhancements! 😊
## 🛠️ Made By
Deepak Rathore
- **https://deepak-web-portfolio.onrender.com**


