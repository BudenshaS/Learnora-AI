<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
</p>

# 📚 Learnora AI

An AI-powered PDF Study Assistant that helps students learn from their own study materials using *RAG (Retrieval-Augmented Generation)* and *Google Gemma*.

## 🚀 What is Learnora AI?

Learnora AI allows students to upload a subject PDF and interact with it through an AI-powered study assistant. 

It can:
- 📄 **Read and process** PDF study material
- 💬 **Answer questions** based on the uploaded PDF
- 🧠 **Explain topics** in simpler language
- 📝 **Generate** a quick study summary
- 🎯 **Create** interactive quizzes
- 🔎 **Retrieve** relevant information from the study material using semantic search

---

## 🧠 How It Works

```text
       [ PDF ]
          ↓
[ Text Extraction ]
          ↓
 [ Text Chunking ]
          ↓
[ MiniLM Embeddings ]
          ↓
[ FAISS Vector Search ]
          ↓
[ Relevant Study Material ]
          ↓
      [ Gemma ]
          ↓
   [ Student Answer ]

## ⚙️ Getting Started

Follow these steps to set up the project locally.

### 1. Clone the repository 👯
```bash
git clone https://github.com/BudenshaS/Learnora-AI.git
cd Learnora-AI
```

### 2. Install the required dependencies 📦
```bash
pip install -r requirements.txt
```

### 3. Run the application 🚀
```bash
streamlit run app.py
```

You can copy this directly into your `README.md` editor. What do you think of this layout? We could also add a section for "Upcoming Features" or "Troubleshooting" if you have plans to expand it!
