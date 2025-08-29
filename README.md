📄 Q-A-AI-Bot – PDF Query Application

This Streamlit application allows users to upload a PDF and ask questions about its content using Groq API with LLaMA models.

🚀 Features

📂 Upload PDFs – Load any PDF document.

🔎 Extract Text – Automatically extract and display text with pdfplumber.

🤖 AI Q&A – Ask questions about the PDF and get accurate answers from the Groq API.

🖥️ Clean UI – Built with Streamlit, including sidebar, buttons, and styled inputs.

💬 Conversation Mode – Supports multiple queries in sequence (chat-like).

🛠️ Installation
Prerequisites

Python 3.9 or higher

Groq API Key (from Groq Console
)

Setup

Clone this Repository

git clone https://github.com/chetkurisai/Q_A-AI-BOT.git
cd Q_A-AI-BOT


Create Virtual Environment

python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # Mac/Linux


Install Dependencies

pip install -r requirements.txt


Set up Environment Variables
Create a .env file in the project root with:

GROQ_API_KEY=your_api_key_here

🚀 Run the App

Start the Streamlit app:

streamlit run app.py


Then open the provided URL (usually http://localhost:8501) in your browser.

🧑‍💻 Usage

Upload a PDF file.

The extracted text will appear in a text box.

Enter a query in the input box.

Click Get Answer to receive an AI-generated response.

Continue asking more queries (conversation mode is supported).

📂 Project Structure
Q-A-AI-Bot/
│── app.py             # Main Streamlit application
│── requirements.txt   # Dependencies
│── .gitignore         # Ignore sensitive files (.env, cache, etc.)
│── .env.example       # Example environment file (without real keys)

📚 Requirements
streamlit
groq
pdfplumber
python-dotenv

📊 Models Used

LLaMA 3 (via Groq API) – for natural language understanding & answering.

🤝 Contributing

Contributions are welcome! Fork this repo, make improvements, and submit a PR.

📃 License

This project is licensed under the MIT License.

👨‍💻 Author

Developed with ❤️ by @saichtkuri
