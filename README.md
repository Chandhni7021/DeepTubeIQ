🎥 DeepTubeIQ  
Ask Smart Questions About Any YouTube Video Using LLMs + Groq

📖 Overview

DeepTubeIQ is a powerful yet simple AI tool that allows you to ask intelligent questions about YouTube videos by analyzing their transcripts. With just a video URL, the app extracts the content, builds a semantic understanding using embeddings, and uses a Large Language Model (LLaMA-3 via Groq API) to answer user queries — all through a clean Gradio interface.

Whether you're reviewing lectures, interviews, or tech talks, DeepTubeIQ helps you get **quick, accurate insights** without watching the entire video.

🚀 Features

- 🔗 Paste any YouTube video URL  
- 🧠 Extracts and processes the transcript  
- 💬 Ask natural language questions about the video  
- ⚡ Answers powered by **Groq's blazing-fast LLaMA-3 inference**  
- 💻 Clean and interactive **Gradio UI**

🛠️ Tech Stack

- Python 3.x  
- LangChain  
- FAISS for vector search  
- HuggingFace Embeddings (`MiniLM-L6-v2`)  
- Groq LLaMA-3 API (`llama3-70b-8192`)  
- Gradio (UI)

![Screenshot 2025-06-22 104233](https://github.com/user-attachments/assets/525b63e4-9cdd-4dc6-9c5d-c31a91092e99)
![Screenshot 2025-06-22 104252](https://github.com/user-attachments/assets/435ca262-6f6c-4b29-adae-d4f98cc8feac)


📦 Installation

1️⃣ Clone the repository

pip install -r requirements.txt

api_key="your-groq-api-key-here"

python app.py

deeptubeiq/
├── app.py                       # Main Gradio app
├── utils/
│   └── yt_processor.py          # YouTube transcript processing & QA logic
├── requirements.txt
└── README.md

🧠 Why This Project?
Save time by getting answers without watching the whole video

Useful for students, researchers, and content reviewers

Shows how RAG pipelines + LLMs can enable smart video understanding

Combines real-world AI utility with an accessible, interactive interface

📜 License
MIT License — free to use, modify, and distribute with attribution.

Built with ❤️ using Groq + LangChain + Gradio

📌 AI that helps you learn faster, not longer.

