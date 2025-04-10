# 🚀 E-commerce Chatbot

## 📁 Directory Structure

- 📂 **backend**: FastAPI backend code (Python)
- 📂 **db**: Database dump (import into MySQL using MySQL Workbench)
- 📂 **dialogflow_assets**: Dialogflow intents and training phrases
- 📂 **frontend**: Website frontend code

## 📦 Install Dependencies

Run these commands to set up quickly:
```bash
pip install mysql-connector
pip install "fastapi[all]"
```

Or simply use:
```bash
pip install -r backend/requirements.txt
```

## 🚀 Starting FastAPI Backend

1. Open your terminal and navigate to the backend directory 📂
2. Run:
```bash
uvicorn main:app --reload
```

## 🌐 Using Ngrok for HTTPS Tunneling

1. Download Ngrok from [here](https://ngrok.com/download) suitable for your OS 💻
2. Extract and place `ngrok.exe` in your preferred folder 📂
3. Open your command prompt, navigate to the folder, and run:
```bash
ngrok http 8000
```

⚠️ **NOTE:** Ngrok sessions might expire. Restart it if you see the "session expired" message!

Enjoy coding! 🎉🚀

