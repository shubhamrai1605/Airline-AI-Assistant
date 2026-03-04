# ✈️ FlightAI – Airline AI Assistant

FlightAI is an AI-powered Airline Assistant built using OpenAI APIs and Gradio.

It can:
- 💬 Answer customer travel questions
- 💰 Fetch real-time ticket prices from a database (via tool calling)
- 🔊 Respond with AI-generated voice
- 🎨 Generate destination images
- 🖥 Provide an interactive Gradio chat interface

---

## 🚀 Features

- OpenAI Chat Completion (GPT)
- Function Calling (Tool Use)
- SQLite Database Integration
- Text-to-Speech (TTS)
- Image Generation (DALL·E)
- Gradio Web Interface

---

## 🛠 Tech Stack

- Python
- OpenAI API
- Gradio
- SQLite
- Pillow (Image Processing)
- dotenv

---


---

## ⚙️ Setup Instructions

### Clone the Repository

git clone https://github.com/shubhamrai1605/Airline-AI-Assistant.git
cd Airline-AI-Assistant

### Add OpenAI API Key

Create a .env file:

OPENAI_API_KEY=your_api_key_here

### Run the App
python main.py

It will launch a local Gradio interface.

### 🧠 How It Works

User enters a message.

GPT processes the query.

If pricing info is needed:

The model calls a function.

The function queries SQLite.

The result is returned to GPT.

GPT generates a final response.

Response is converted to speech.

Destination image is generated.

### 💰 Example Cities & Prices
City	Price ($)
London	799, 
Paris	899, 
Tokyo	1420, 
Sydney	2999 

### 📌 Future Improvements

Flight booking integration

User authentication

Real-time flight tracking

Deployment on Hugging Face Spaces

Streaming responses

### 👨‍💻 Author

Shubham Rai: 
AI Developer, LLM Engineer

### ⭐ If You Like This Project

Give it a star on GitHub!