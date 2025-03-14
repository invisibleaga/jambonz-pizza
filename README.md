# Jambonz Pizza Ordering Assistant

This is a **Jambonz-based voice assistant** for **pizza ordering**. It uses:
- **Deepgram** for Speech-to-Text (S2T) and Text-to-Speech (T2S)
- **OpenAI GPT-4o** for natural language processing

## 📌 Setup Instructions

1. **Clone the Repository**
```
git clone https://github.com/yourrepo/jambonz_pizza_assistant.git
cd jambonz_pizza_assistant
```

2. **Install Dependencies**
```
npm install
```

3. **Set Up Environment Variables**
- Rename `.env.example` to `.env`
- Add your API keys for **Deepgram** and **OpenAI**.

4. **Run the Server**
```
npm start
```

5. **Configure Jambonz Webhook**
- Set **Inbound Call Webhook** to `https://your-public-url.com/orders/webhook`

## 🚀 Features
✅ **Takes pizza orders using AI**  
✅ **Understands natural language inputs**  
✅ **Confirms orders before placing them**  
✅ **Uses Deepgram for S2T & T2S**  
✅ **Handles inbound calls via Jambonz**