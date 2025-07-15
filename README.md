# Persona Reddit App 🧩

A Python tool that retrieves and examines a Reddit user’s posts and comments, powered by **Gemini Pro (LLM)**, to craft an insightful **User Persona**—complete with clear citations linking each personality trait to the original Reddit content.

---

## ⚙️ Highlights

* **Input**: URL of a Reddit user profile
* **Process**: Fetches the user’s most recent posts and comments
* **Analysis**: Employs Gemini Pro to interpret user behavior
* **Output**: Delivers a persona breakdown in `.txt` format
* **Transparency**: Each trait is backed by a specific post or comment
* **Best Practices**: Follows PEP‑8 style guidelines

---

## 🧪 Tech Stack

* **Python 3**
* **PRAW** (Reddit API interface)
* **Google Gemini Pro** (Generative AI)
* **dotenv** (`.env`) for secure API key management

---

## 🚀 Setup Guide

### 1. Clone the repository

```bash
git clone [https://github.com/ABHIGHUDAIYA/PersonaRedditApp]
cd reddit-persona-generator
```

### 2. (Optional) Set up a virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure your `.env` file

```bash
REDDIT_CLIENT_ID=your_reddit_client_id
REDDIT_CLIENT_SECRET=your_reddit_client_secret
REDDIT_USER_AGENT=your_user_agent_string
GEMINI_API_KEY=your_gemini_api_key
```

---

## 🛠️ Usage

Launch the script and input a Reddit profile URL:

```bash
python generate_persona.py
```

Examples of valid inputs:

* `https://www.reddit.com/user/kojied/`
* `https://www.reddit.com/user/Hungry-Move-6603/comments/`

---

## 🧠 Gemini Pro Prompt

The script crafts a prompt for Gemini Pro that ensures the output is:

1. **Structured** — formatted persona breakdown
2. **Traceable** — includes references to specific Reddit content supporting each trait


