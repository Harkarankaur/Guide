💬 Text-Based Chatbot
A lightweight AI chatbot built with Python and Streamlit that answers your text queries. Powered by local LLMs like Ollama, it is designed to serve domain-specific or general-purpose Q&A.

📌 Features
🧠 Ask any text-based query

⚡ Fast and interactive responses

🗂️ Customizable prompt for specific domains

🔒 Optional scope limitation to restrict unrelated questions

🖥️ Simple and responsive UI using Streamlit

🛠️ Tech Stack
Component	Technology
Language Model Ollama
UI	Streamlit
Env Mgmt	python-dotenv
Language	Python 3.10+

📂 Project Structure
text-chatbot/
├── app.py                # Streamlit UI
├── .env                  # Environment variables (API keys)
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
📥 Setup & Installation

1. Install dependencies

pip install -r requirements.txt
2. Add your API key
Create a .env file in the root folder:

env
Copy
Edit
OPENAI_API_KEY=your_openai_key
If you're using Ollama, adjust the bot_engine.py to use local models instead.

▶️ Running the Bot

streamlit run app.py
Visit http://localhost:8501 in your browser.

✏️ Customizing the Prompt
To restrict the chatbot to a specific topic or domain, edit prompt_template.txt:

You are an assistant that only answers questions about Python programming.
If asked anything else, respond: "Sorry, I only answer Python-related questions."

 Add chat history support

 Add option to switch topics dynamically

 Deploy to Streamlit Cloud

👤 Author
Harkaranjit kaur

📄 License
MIT License – free to use and modify.
