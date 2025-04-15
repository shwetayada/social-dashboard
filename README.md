🐦 Django Twitter Integration Project

A Django web application that allows users to sign up, log in, post tweets, and view their Twitter timeline using the Twitter API (via Tweepy).

---

## 🔧 Features

- 🔐 User Registration & Authentication
- 📝 Post a Tweet to your Twitter account
- 📰 View your recent tweets/timeline
- 🌐 Twitter API integration using Tweepy (OAuth 1.0a)

---

## 🚀 Getting Started

### 1. Clone the Repository

bash
git clone https://github.com/shwetayada/social-dashboard.git
cd twitter-project

On Windows:

python -m venv venv
venv\Scripts\activate


On macOS/Linux:

python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Add Environment Variables to .env

TWITTER_API_KEY=your_api_key
TWITTER_API_SECRET=your_api_secret
ACCESS_TOKEN=your_access_token
ACCESS_TOKEN_SECRET=your_access_token_secret

5. Apply Migrations

python manage.py makemigrations
python manage.py migrate

6. Run the Server
python manage.py runserver

Open http://127.0.0.1:8000 in your browser.

📂 Project Structure

twitter_project/
│
├── twitter_app/             # Your Django app
│   ├── views.py             # View logic with Tweepy
│   ├── templates/           # HTML templates
│
├── manage.py
├── requirements.txt
└── README.md

🛠 Technologies Used
Django

Tweepy

HTML 

Twitter Developer API

Python


📬 Contact
Made with 💙 by Shweta
