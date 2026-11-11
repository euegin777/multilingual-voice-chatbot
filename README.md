# 🌍 Multilingual Voice Chatbot

## 📌 Project Overview

The **Multilingual Voice Chatbot** is an AI-powered conversational application developed using Python and Streamlit. It allows users to interact with an AI assistant through voice recordings or text messages.

The application automatically detects the spoken language, converts voice into text, generates intelligent responses using the Llama 3.2 model, translates responses into the user's language, and provides audio replies.

It supports multiple languages, making communication with AI easier and more accessible.

## ✨ Features

- 🎙️ **Voice Input:** Record questions using your microphone.
- ⌨️ **Text Input:** Send messages through the chat interface in English.
- 🌐 **Multilingual Support:** Supports languages including English, Tamil, Telugu, Hindi, Kannada, Malayalam, French, Spanish, German, and many more.
- 🔍 **Automatic Language Detection:** Uses Faster Whisper to identify the spoken language.
- 🤖 **AI-Powered Responses:** Uses Ollama with the Llama 3.2 model to generate intelligent answers.
- 🔄 **Language Translation:** Automatically translates questions and answers.
- 🔊 **Text-to-Speech:** Converts AI responses into audio using Google Text-to-Speech (gTTS).
- 💬 **Conversation History:** Maintains chat context during the conversation.
- 🎨 **Multiple Themes:** Includes Aurora, Ocean, Light, and Dark themes.
- 🆕 **New Conversation:** Allows users to start a fresh chat.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| Faster Whisper | Speech recognition and language detection |
| Ollama | Local AI model integration |
| Llama 3.2 | AI response generation and translation |
| gTTS | Text-to-speech conversion |
| Truststore | SSL certificate integration |

## 📂 Project Structure

```text
Multilingual-Voice-Chatbot/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Multilingual-Voice-Chatbot.git
```

### 2. Navigate to the Project Folder

```bash
cd Multilingual-Voice-Chatbot
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Install Ollama

Download and install Ollama from:

https://ollama.com/download

### 5. Download the Llama 3.2 Model

Open your terminal and execute:

```bash
ollama pull llama3.2
```

Make sure the Ollama service is running before launching the application.

### 6. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser, usually at:

```text
http://localhost:8501
```

## 📦 Requirements

Create a `requirements.txt` file with the following dependencies:

```text
streamlit
faster-whisper
ollama
gTTS
truststore
```

## 🚀 How to Use

1. Launch the Streamlit application.
2. Select your preferred interface theme.
3. Record a voice message or type a question in English.
4. The application detects the spoken language automatically.
5. The AI processes the question using Llama 3.2.
6. The chatbot generates an appropriate response.
7. The response is translated into the detected language.
8. Listen to the generated audio response.
9. Continue the conversation or start a new one.

## 🧠 Working Process

```text
User Voice / Text Input
          |
          v
Speech Recognition
(Faster Whisper)
          |
          v
Language Detection
          |
          v
Translation to English
          |
          v
AI Response Generation
(Ollama - Llama 3.2)
          |
          v
Translation to User Language
          |
          v
Text-to-Speech Conversion
          |
          v
Audio Response
```

## 🔮 Future Enhancements

- Add support for more regional and international languages.
- Improve speech recognition accuracy.
- Add conversation export functionality.
- Integrate additional AI language models.
- Deploy the application to a cloud platform.
- Improve voice response customization.

## 👨‍💻 Author

**Euegin Sanjay**

## ⭐ Support

If you find this project useful, please give this repository a ⭐ on GitHub.
https://github.com/euegin777/multilingual-voice-chatbot/edit/main/README.md
---

**Keywords:** Python, Artificial Intelligence, AI Chatbot, Multilingual Chatbot, Voice Assistant, Speech Recognition, Streamlit, Ollama, Llama 3.2, Faster Whisper, Text-to-Speech, Natural Language Processing.
