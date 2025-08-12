# 📰 AI News App

An AI-powered web application that fetches news articles, summarizes them using **BART Transformer** and performs **sentiment analysis** using **DistilBERT**.  
Built with **Python, Hugging Face Transformers, Flask, and BeautifulSoup**.

---

## 📌 Features
- Fetches full news content from any given article URL.
- Generates a concise summary using `facebook/bart-large-cnn`.
- Performs sentiment analysis using `distilbert-base-uncased-finetuned-sst-2-english`.
- Simple and clean Flask-based web UI.
- Runs locally with minimal setup.

---

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **AI Models:** Hugging Face Transformers (BART & DistilBERT)
- **Web Scraping:** Requests, BeautifulSoup4
- **Frontend:** HTML, CSS

---

## 📂 Folder Structure
ai-news-app/
│── app.py # Flask app
│── requirements.txt # Dependencies
│── templates/
│ └── index.html # Web UI
│── static/
│ └── style.css # Styling
│── summarizer.py # AI summarization logic
│── sentiment.py # Sentiment analysis logic


---

## 🚀 Installation & Usage

# 1️⃣ Clone the Repository
git clone https://github.com/Nj130/ai-news-summarizer.git
cd ai-news-summarizer

# 2️⃣ Install Dependencies

pip install -r requirements.txt

# 3️⃣ Run the Application

python app.py

# 4️⃣ Open in Browser

http://127.0.0.1:5000

⚙️ How It Works
1.User enters a news article URL.
2.App scrapes the article content using BeautifulSoup.
3.AI model BART summarizes the text.
4.AI model DistilBERT analyzes sentiment (Positive, Neutral, Negative).
5.Results are displayed in the browser.

📦 Requirements
Python 3.8+
Flask
Transformers
Torch
Requests
BeautifulSoup4

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

👨‍💻 Author
Your Name
GitHub: @Nj130
Email: neerajpatil8888@example.com
