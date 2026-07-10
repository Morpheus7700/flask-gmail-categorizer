# EmailAI Smart Categorizer 📧

A lightweight, intelligent Flask web application that seamlessly integrates with your Gmail account to automatically categorize and organize your inbox.

## 🚀 Features
- **Secure Google Authentication:** Uses OAuth 2.0 to securely connect to your Gmail account.
- **Automated Categorization:** Analyzes email headers and snippets to sort emails into meaningful categories.
- **Clean Dashboard:** A simple, intuitive web interface to view and manage categorized emails.

## 🛠️ Tech Stack
- **Backend:** Python, Flask, Google API Client
- **Frontend:** HTML5, CSS3, JavaScript
- **Auth:** Google OAuth 2.0 (`google-auth-oauthlib`)

## ⚙️ Setup
1. Configure your Google Cloud Project and download OAuth credentials to the project root.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   python main.py
   ```
