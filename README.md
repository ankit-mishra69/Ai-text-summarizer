> 🧠 Built using Transformer Architecture (T5) to solve real-world NLP problems
# Ai-text-summarizer
AI-powered Text Summarization Web App using T5 Transformer, FastAPI, and Hugging Face

🧠 T5 Text Summarization App

An AI-powered text summarization web application built using T5 Transformer, FastAPI, and Hugging Face. This project allows users to input large text and get concise summaries instantly.

🚀 Features
✨ Transformer-based summarization (T5)
⚡ FastAPI backend for high performance
🌐 Simple and clean web interface
🔍 Automatic text cleaning & preprocessing
💻 Works on CPU / GPU / Apple Silicon (MPS)

🛠️ Tech Stack
Python
FastAPI
Hugging Face Transformers
PyTorch
HTML, CSS, JavaScript

📂 Project Structure
├── app.py                  # FastAPI backend
├── index.html              # Frontend UI
├── saved_summary_model/    # Trained T5 model
├── requirements.txt
└── README.md

⚙️ How It Works
User enters text in the UI
Request is sent to FastAPI backend
Text is cleaned and tokenized
T5 model generates summary
Summary is displayed on UI

📌 API Endpoint
POST /summarize/

Request Body:

{
  "dialogue": "Your text here..."
}

Response:

{
  "summary": "Generated summary..."
}

🧪 Run Locally
1. Clone Repo
git clone https://github.com/your-username/t5-text-summarization-app.git
cd t5-text-summarization-app

2. Install Dependencies
pip install -r requirements.txt

3. Run Server
uvicorn app:app --reload

4. Open in Browser
http://127.0.0.1:8000

🧹 Data Preprocessing
Removes extra spaces
Removes HTML tags
Converts text to lowercase

🧠 Model Details
Model: T5 (Text-to-Text Transfer Transformer)
Max Input Length: 512 tokens
Max Output Length: 150 tokens
Beam Search: Enabled (num_beams=4)

📸 UI Preview
Simple and clean UI for entering text and viewing summaries.

🔥 Future Improvements
Add file upload (PDF / DOCX)
Deploy on cloud (Render / AWS / GCP)
Add multiple summarization styles
Improve UI/UX

🤝 Contributing
Contributions are welcome! Feel free to fork and improve the project.

📜 License
This project is open-source and available under the MIT License.

👨‍💻 Author
Ankit Mishra
