# 🎭 Emotion Sentiment Analysis Chatbot 🤖

## 📌 Overview
This is a simple **Sentiment Analysis Chatbot** that detects the sentiment (positive, negative, or neutral) of user input using **TextBlob** and **NLTK**. It provides instant feedback on how the text is perceived.

---

## 🚀 Features
✅ Preprocesses input text using tokenization  
✅ Analyzes sentiment using **TextBlob**  
✅ Displays sentiment as **Positive, Negative, or Neutral**  
✅ Continuous chat loop until the user types **exit**  
✅ Handles empty input gracefully  

---

## 🛠️ Installation & Usage

1️⃣ **Install Dependencies**
Make sure you have **Python 3.x** installed, then install the required libraries:
```sh
pip install textblob nltk

2️⃣ **Run the Chatbot**
Run the Python script:

sh
Copy
Edit
python chatbot.py

3️⃣ **Chat with the Bot**
The chatbot will analyze sentiment and respond accordingly:

You: I love programming!
Chatbot: 📝 Sentiment: positive (Polarity: 0.85)

You: I hate bugs in my code.
Chatbot: 📝 Sentiment: negative (Polarity: -0.70)

You: It's a normal day.
Chatbot: 📝 Sentiment: neutral (Polarity: 0.00)
📜 How It Works
Text Preprocessing: Converts input to lowercase and tokenizes it.
Sentiment Analysis: Uses TextBlob to determine polarity.
Response Generation: Displays sentiment and numerical polarity.
🤝 Contributing
Want to improve this chatbot? Feel free to fork the repository and create a pull request! 🚀

📧 Contact
📩 Divyansh Rathore
🔗 GitHub: github.com/Rathore-Divyansh
