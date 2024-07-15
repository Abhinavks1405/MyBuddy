# MyBuddy 📘🤖

MyBuddy is an advanced study companion application designed to streamline your study experience. It integrates powerful AI tools powered by LLMWare to provide various features such as document summarization, sentiment analysis for essays, and interactive Q&A with a chatbot.

## Features 🚀

- **Summarize Notes:** Quickly summarize long texts to save time and improve study efficiency.
- **Analyze Sentiment:** Evaluate the sentiment of essays or articles to understand their emotional context.
- **Chat with StudyBot:** Engage in interactive Q&A sessions with an AI-powered chatbot for study-related queries.

## Technologies Used 🛠️

- **Python:** Backend development and integration with AI models.
- **Flask:** Web framework for building the backend server.
- **LLMWare:** For AI models integration.
- **HTML/CSS/JavaScript:** Frontend development for the user interface.
- **jQuery:** JavaScript library for simplified AJAX interactions.

## LLMWare Integration 🤖

MyBuddy leverages the capabilities of LLMWare, a powerful AI platform, to provide advanced study features:

- **Document Summarization:** Utilizes LLMWare's `slim-summary-tool` model for generating concise summaries.
- **Sentiment Analysis:** Implements LLMWare's `LLMfx sentiment` tool for analyzing the sentiment of text inputs.
- **Chatbot:** Integrates LLMWare's `bling-phi-3-gguf` model for interactive chatbot responses.

## Getting Started 🚀

To get started with MyBuddy locally, follow these steps:

1. Clone the MyBuddy repository:
   ```bash
   git clone https://github.com/Abhinavks1405/my-buddy.git
   cd my-buddy

2. Set up a Virtual Environment and install dependencies:
   ```bash
    python -m venv venv
    venv/Scripts/activate  # On mac use `source venv\bin\activate`
    pip install -r requirements.txt

   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Access my-buddy in your browser at http://localhost:5000.

## Models Used 🤖

- **Summarization:** `slim-summary-tool` Efficiently distills key information from large texts.
- **Sentiment Analysis:** `LLMfx sentiment` Accurately gauges the sentiment of texts with high confidence scores.
- **QnA Bot:** `bling-phi-3-gguf` Model for interactive chatbot responses.

## Screenshots

      
![image]()
**⚡Home Screen**

![image]()      
**🎄Summarize Screen**

![image]()
**🚀Sentiment Analysis Screen**

![image]()
**🤖Chatbot Screen**

## License 📜
This project is licensed under the [MIT License](LICENSE).


