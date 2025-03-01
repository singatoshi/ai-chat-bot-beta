# 🚀 Dynamic AI Chatbot with Custom Training Sources

## 🤖 Customizable GPT Chatbot

This project is a **dynamic AI chatbot** that can be trained from various sources, such as PDFs, documents, websites, and YouTube videos. It features a **user authentication system** with Google social login and uses the **Django REST framework** for its backend. The chatbot integrates **OpenAI's GPT-3.5** language model for intelligent and responsive conversations. Designed for **scalability and ease of use**, this chatbot is a powerful solution for AI-driven interactions.

---

## ✨ Features

- ✅ **Train chatbot from multiple sources** (PDFs, documents, websites, YouTube videos)
- ✅ **User authentication** with social login via Google
- ✅ **OpenAI GPT-3.5 integration** for intelligent conversations
- ✅ **Vector indexing** with Pinecone and FAISS
- ✅ **Text embedding** using OpenAI's `text-embedding-ada-002`
- ✅ **Python Langchain** for file processing and text conversion
- ✅ **Scalable architecture** with environment-specific settings (local, staging, production)
- ✅ **Dynamic site settings** (e.g., customizable title and prompt updates)
- ✅ **Multilingual support**
- ✅ **PostgreSQL database support** for efficient storage
- ✅ **Task scheduling** with Celery and Redis (AWS SQS option available)
- ✅ **AWS S3 bucket** support for scalable file hosting
- ✅ **Easy deployment** on **Heroku** or **AWS**

---

## 🛠 Tech Stack & Major Libraries

- **Backend:** Django REST Framework
- **LLM:** OpenAI GPT-3.5
- **Vector Indexing:** Pinecone, FAISS
- **Embeddings:** OpenAI `text-embedding-ada-002`
- **File Processing:** Langchain
- **Task Queue:** Celery + Redis/AWS SQS
- **Database:** PostgreSQL
- **Storage:** AWS S3
- **Deployment:** Heroku / AWS

---

## 🔮 Future Roadmap

- 🔗 **Integration with more third-party authentication services**
- 📂 **Support for additional file formats and media types**
- 🧠 **Enhanced context-awareness in chatbot conversations**
- 🌍 **Improved multilingual support with automatic language detection**
- 💬 **Integration with popular messaging platforms (Telegram, WhatsApp, Slack, Discord, etc.)**

---

## 🔧 Installation & Setup

### Prerequisites

Ensure you have the required dependencies installed on **Linux** or **Mac**:

```bash
sudo apt install python3-dev -y
sudo apt-get install libcurl4-openssl-dev gcc libssl-dev -y
pip install --upgrade pip setuptools
pip install pycurl
```

### Clone the Repository

```bash
git clone https://github.com/muffin819/AI-Chat-Bot.git
cd AI-Chat-Bot
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py migrate
```

### Start the Server

```bash
python manage.py runserver
```

---

## 🚀 Deployment

You can deploy the chatbot easily on **Heroku** or **AWS**.

### Deploy on Heroku

```bash
git push heroku main
```

### Deploy on AWS

Follow AWS Elastic Beanstalk or EC2 setup guides to deploy your Django app efficiently.

---

## 📩 Contact

Telegram | [dogewhiz]\([https://t.me/dogewhiz](https://t.me/dogewhiz))

