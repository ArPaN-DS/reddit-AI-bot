
# 🤖 Reddit AI Bot Project

## 📘 Overview
This project is a Reddit AI Bot that interacts with comments on a specific subreddit using **OpenAI's GPT model**. It reads new comments, generates intelligent responses using GPT-3, and replies automatically in real-time.

---

## 🚀 Technologies Used
- **Python 3**
- **PRAW (Python Reddit API Wrapper)** – Access Reddit’s API
- **OpenAI GPT-3** – Generate contextual AI responses

---

## ✨ Features
- Real-time Reddit comment monitoring
- AI-generated responses using GPT-3
- Automated comment replies
- Basic error handling for stability

---

## 🔧 Prerequisites
- Python 3.7+
- Reddit API credentials:
  - `client_id`, `client_secret`, `username`, `password`, `user_agent`
- OpenAI API key

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/reddit-ai-bot.git
cd reddit-ai-bot
```

### 2. Install Dependencies
```bash
pip install praw openai
```

### 3. Create Reddit API Credentials
- Visit [Reddit Apps](https://www.reddit.com/prefs/apps)
- Click **Create App** → Select **Script**
- Copy the following:
  - `client_id`
  - `client_secret`
  - `username`
  - `password`
  - `user_agent`

### 4. Get OpenAI API Key
- Visit [OpenAI API Keys](https://platform.openai.com/account/api-keys)
- Generate and copy your key

### 5. Configure `reddit_ai_bot.py`
Replace placeholders in your script:
```python
openai.api_key = 'YOUR_OPENAI_API_KEY'

reddit = praw.Reddit(
    client_id='YOUR_CLIENT_ID',
    client_secret='YOUR_CLIENT_SECRET',
    username='YOUR_USERNAME',
    password='YOUR_PASSWORD',
    user_agent='YOUR_USER_AGENT'
)
```

### 6. Run the Bot
```bash
python reddit_ai_bot.py
```

---

## ⚠️ Known Issues
- GPT may generate responses that are off-topic or too verbose.
- API usage from OpenAI might incur costs.
- Avoid violating Reddit’s rate limits to prevent bans.

---

## 🤝 Contributing
PRs are welcome! Fork the repo and submit a pull request.

---

## 📜 License
This project is for **educational purposes only** and adheres to Reddit and OpenAI's API usage guidelines.

---

## 📬 Contact
Developer: Arpan Majumdar  
📧 Email: `arpanmajumdar952@gmail.com`
