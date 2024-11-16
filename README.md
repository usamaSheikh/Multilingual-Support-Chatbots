# Multilingual-Support-Chatbots

A Flask-based customer support chatbot with real-time multilingual translation capabilities using the M2M100 model.

# Features
- Real-time chat interface
- Support for 10 languages:
  - English
  - Spanish
  - French
  - German
  - Italian
  - Chinese
  - Japanese
  - Korean
  - Russian
  - Arabic
- Keyword-based response system
- Modern, responsive UI design
- Real-time translation of responses

# Prerequisites
Before running this project, make sure you have Python 3.7+ installed. You'll also need pip for installing dependencies.

# Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/multilingual-support-chatbot.git
cd multilingual-support-chatbot

2. Create a virtual environment (recommended):
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install required dependencies:
pip install flask transformers torch
