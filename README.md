# 🤖 Coding Chatbot

An intelligent, interactive chatbot that helps developers solve coding problems, debug errors, and learn programming concepts — right from their desktop.

---

## ✨ Features

- **Real-time coding assistance** — Get instant answers to programming questions
- **Multi-language support** — Works across Python, JavaScript, Java, C++, and more
- **Natural language understanding** — Powered by NLTK for smart query processing
- **Clean, interactive UI** — Built with Tkinter for a smooth desktop experience
- **Similarity-based matching** — Uses Scikit-learn to find the most relevant answers

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-FF6F00?style=for-the-badge&logo=python&logoColor=white)

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed before you begin:

- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shravan-pandirkar/coding-chatbot.git
   cd coding-chatbot
   ```

2. **Create and activate a virtual environment** *(recommended)*
   ```bash
   python -m venv venv

   # On macOS/Linux:
   source venv/bin/activate

   # On Windows:
   venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install nltk scikit-learn
   ```

4. **Download required NLTK data**
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

5. **Run the application**
   ```bash
   python AI_coding_chatbot.py
   ```

---

## 📁 Project Structure

```
coding-chatbot/
├── AI_coding_chatbot.py   # Main chatbot logic + UI
├── chatbot_data.txt       # Training data / Q&A knowledge base
└── README.md
```

---

## 💬 Usage

Once launched, type your coding question into the input field and press **Enter** or click **Send**. Example queries:

- *"How do I reverse a list in Python?"*
- *"What is a REST API?"*
- *"Explain recursion with an example"*

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---


## 📬 Contact

Have suggestions or found a bug? Open an [issue](https://github.com/Shravan-pandirkar/coding-chatbot/issues) or reach out via GitHub.
