# Conversational Q&A Chatbot 💬❓

An intelligent **Conversational Question & Answer Chatbot** built using **LangChain**, **Groq LLMs**, and **Hugging Face models**. The chatbot maintains conversation history to provide context-aware responses and leverages prompt engineering techniques to deliver accurate and coherent answers during multi-turn interactions.

## ✨ Features

* 🤖 AI-powered conversational Q&A chatbot
* 🧠 Maintains **conversation history** for context-aware interactions
* 💬 Supports **multi-turn conversations**
* ⚡ Fast response generation using **Groq LLMs**
* 🤗 Integrates **Hugging Face APIs** for enhanced NLP capabilities
* 📝 Utilizes **ChatPromptTemplate** for structured prompt engineering
* 🔗 Built using **LangChain** for modular and scalable AI workflows
* 📓 Implemented and demonstrated in `conversationqa.ipynb`

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **Groq API**
* **Hugging Face API**
* **ChatPromptTemplate**
* **Conversation History Management**
* **Jupyter Notebook (`conversationqa.ipynb`)**
* **Python-dotenv**

## 📂 Project Structure

```text
Conversational_QA_Chatbot/
│
├── conversationqa.ipynb    # Main notebook containing chatbot implementation
├── .env                    # Environment variables (not tracked by Git)
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Areen3112/Q-A_chatbot.git
cd conversational-qa-chatbot
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**macOS/Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root directory:

```env
GROQ_API_KEY=your_groq_api_key
HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token
```

> **Note:** Never commit your API keys or `.env` files to GitHub.

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
conversationqa.ipynb
```

Run all cells to start interacting with the chatbot.

## 🧩 Key Concepts Implemented

* **Conversation History Management** – Preserves previous interactions to maintain context across multiple turns.
* **Prompt Engineering** – Uses `ChatPromptTemplate` to structure prompts effectively.
* **LLM Integration** – Leverages Groq-hosted models for efficient response generation.
* **Hugging Face API Integration** – Utilizes Hugging Face services within the conversational pipeline.
* **LangChain Chains** – Builds modular conversational workflows using LangChain abstractions.

## 🎯 Learning Outcomes

This project demonstrates:

* Building conversational AI applications with memory
* Managing multi-turn interactions using LangChain
* Integrating Groq and Hugging Face APIs
* Applying prompt engineering techniques with ChatPromptTemplate
* Developing interactive chatbot systems in Jupyter Notebooks

## 🚀 Future Improvements

* Add Retrieval-Augmented Generation (RAG) capabilities
* Develop a web interface using Streamlit or FastAPI
* Implement persistent chat memory
* Add support for document-based Q&A
* Deploy the chatbot as a cloud-hosted service

## 🤝 Contributing

Contributions and suggestions are welcome. Feel free to fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

---

**Built with ❤️ using LangChain, Groq, Hugging Face, and Conversational AI techniques.**
