---
title: career_conversation_app
app_file: app.py
sdk: gradio
sdk_version: 5.38.2
---
# Career Conversation App

## Overview

The Career Conversation App is an AI-powered chatbot interface that represents me, a seasoned software engineer and Python developer. The app is designed to answer questions about my career, background, skills, and experience, acting as a virtual professional profile and interactive assistant. It leverages large language models (LLMs) and integrates with Gradio for a user-friendly chat experience. The app can also record user details and unknown questions for further follow-up.


## Features
- Chat with an AI agent representing Raza Ullah
- Get answers about Raza's professional background, skills, and experience
- Records unknown questions and user contact details for follow-up
- Uses Gradio for a web-based chat interface

## Setup & Installation

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd career_conversation_app
   ```

2. **Install dependencies**
   It is recommended to use a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Environment Variables**
   - Create a `.env` file in the project root.
   - Add your Google API key for Gemini (or OpenAI-compatible) as follows:
     ```env
     GOOGLE_API_KEY=your_google_api_key_here
     ```

4. **Required Files**
   - Ensure the following files are present in the `me/` directory:
     - `Raza_LinkedIn.pdf` (Raza's LinkedIn profile in PDF)
     - `raza_summary.txt` (Raza's professional summary)

## Running the App

To start the Gradio chat interface, run:
```bash
python app.py
```
This will launch a local web server and open the chat interface in your browser.

## Usage
- Ask questions about Raza's career, skills, or experience.
- If you have a question the AI cannot answer, it will be recorded for follow-up.
- You may be prompted to provide your email for further contact.

## License
This project is for personal/professional portfolio use.
