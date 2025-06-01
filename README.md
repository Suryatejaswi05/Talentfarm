# 📰Tackling  Fake News 

This project is an AI-powered Fake News Detection System designed to verify whether news is real or fake. It uses Natural Language Processing (NLP) and machine learning to analyze URLs, text, or images and deliver accurate results. The system is built with a focus on user interaction, feedback, and live information validation.

---

## 🔍 Project Aim

To tackle the spread of misinformation by enabling users to verify the authenticity of news articles using AI, and optionally enhance results with Perplexity’s Sonar API for internet-backed search and reasoning.

---

## 🚀 Features

- ✅ URL/Text/Image Fake News Detection
- 🧠 Machine Learning Model for Text Analysis
- 📷 Image to Text Conversion (OCR)
- 🖼️ Image Authenticity Classification
- 🔁 Deepfake Detection (planned)
- 📊 Trending Fake News Tracker
- 🧾 Source Credibility Check
- 🌍 Multi-language Support (coming soon)
- 🔐 User Authentication & Feedback System
- 🧠 Optional Perplexity Sonar API Integration

---

## 🛠️ Tech Stack

### 🧪 Built With:
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Database**: PostgreSQL
- **AI/ML**: Scikit-learn, Google Vision API
- **Cloud & APIs**:
  - Google Vision API (for OCR & image classification)
  - Perplexity Sonar API (for real-time search & deep research)
- **Hosting**: Render / Railway (optional)

---

## 🔑 How Perplexity Sonar API is Used (Optional)

If enabled:
- Enhances verification using real-time search results.
- Validates article content against live, cited information.
- Supports deep reasoning for better decision making.

> You can disable the Perplexity integration in `config.py` if not needed.

---

## 🖥️ How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/your-repo/fake-news-detector.git
   cd fake-news-detector
Install requirements

bash
Copy
Edit
pip install -r requirements.txt
Set up environment variables:

Add your PostgreSQL credentials

(Optional) Add your Perplexity API key in config.py

Run the app

bash
Copy
Edit
python app.py
Visit http://localhost:5000 in your browser.

📂 File Structure
arduino
Copy
Edit
fake-news-detector/
├── static/
├── templates/
├── app.py
├── config.py
├── model.pkl
├── vision_model.py
└── README.md
📺 Demo Video
[Insert YouTube/Vimeo/Facebook Video URL Here]


📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤖 Powered By
OpenAI GPT / Google Vision

Perplexity Sonar API

Python, Flask, PostgreSQL

