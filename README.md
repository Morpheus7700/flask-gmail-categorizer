# Flask Gmail Categorizer

> A Flask web app that connects to Gmail via OAuth 2.0 and sorts your inbox into categories.

A lightweight web application that authenticates against a user's Gmail account, reads message headers and snippets, and groups emails into meaningful categories in a simple dashboard.

## Features
- Secure Google sign-in with OAuth 2.0
- Automatic categorisation from email headers and snippets
- Clean web dashboard to review sorted mail
- Ready to deploy (includes a `vercel.json` configuration)

## Tech Stack
- **Backend:** Python, Flask, Google API Python Client
- **Auth:** Google OAuth 2.0 (`google-auth-oauthlib`)
- **Frontend:** HTML, CSS, vanilla JavaScript

## Getting Started
1. Create a Google Cloud project and download OAuth client credentials into the project root.
2. Install dependencies and run:
   ```bash
   pip install -r requirements.txt
   python main.py
   ```
