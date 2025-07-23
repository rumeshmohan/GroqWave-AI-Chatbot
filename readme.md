# GroqWave AI Chatbot

GroqWave AI Chatbot is a conversational AI chatbot built using the Groq API. This project includes both the backend API and the frontend UI for seamless interaction.

## Features

- Backend powered by Groq API to handle AI processing
- Responsive frontend interface for chatting
- Easy to set up and extend

## Project Structure
/backend - Server-side code (Python - FastAPI)

/frontend - Client-side code (React, Vue, or HTML/CSS/JS)

## Getting Started

### Prerequisites

- FastAPI and React (Vue.js)
- Groq API credentials

### Setup Backend

1. Navigate to the backend directory:
cd backend

2. Install dependencies:
python -m venv venv
source venv/bin/activate # On Linux/macOS
For Windows, use: .\venv\Scripts\activate

3. Install python dependencies
pip install -r requirements.txt

4. Configure your Groq API key:
Create a file named .env in the backend/ directory and add your Groq API key:
GROQ_API_KEY=your_api_key_here

5. Run the backend server:
uvicorn main:app --reload

### Setup Frontend

1. Navigate to the frontend directory:
cd frontend

2. Install dependencies:
npm install

3. Start the frontend development server:
npm run dev

The frontend will connect to the backend API automatically (adjust URLs in config if needed).

## Usage

Once both servers are running, open your browser at `http://localhost:5173` (or your frontend port) to chat with GroqWave AI Chatbot.

## License

MIT License - see the LICENSE file.
