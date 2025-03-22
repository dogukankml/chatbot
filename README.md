# AI Chatbot

A modern and user-friendly AI chatbot application. An advanced chat interface that can provide smart responses using OpenAI's GPT API and supports multi-tab conversations.


## Features

- 🎨 Modern and user-friendly design
- 💬 Multi-tab support for parallel conversations
- 🤖 Smart responses powered by OpenAI GPT
- 📝 Chat history management
- ⚡ Real-time response streaming
- 📤 Chat export (DOCX, TXT, PDF)
- 📎 File upload support

## Installation

1. Clone the repository:
```bash
git clone https://github.com/dogukankml/chatbot.git
cd chatbot
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file: 
- Add your OpenAI API key to the `.env` file.
```
OPENAI_API_KEY=your_api_key_here
```

## Usage

To start the application:
```bash
streamlit run app.py
```

It will open automatically in your browser. If it doesn’t, copy and paste the URL shown in the console into your browser.

## Feature Details

- **Multi-Tab**: Run parallel conversations on different topics.
- **File Upload**: Upload and analyze text and PDF files.
- **Export**: Export your chats in DOCX, TXT, or PDF formats.
- **Clear Chat**: Clear conversations independently in each tab.

## Lisans

This project is licensed under the MIT License. See the `LICENSE` file for details.