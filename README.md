# 🤖 AI-Powered Chatbot Assistant

An **AI Chatbot Assistant** with persistent memory, external tool integration, and an interactive UI for enhanced user experience. Leveraging the latest AI technologies, this assistant provides dynamic conversational intelligence and seamless integration with external services.

---

## 🚀 Features

- **Conversational AI**: Built using OpenAI API with LangChain, LangGraph, and LangSmith for advanced conversational intelligence.  
- **Persistent Memory**: Chat histories stored in **SQLite**, allowing continuity across sessions.  
- **Retrieval-Augmented Generation (RAG)**: Enhanced response generation using knowledge retrieval for context-aware conversations.  
- **External Tool Integration**:
  - 🧮 Calculator  
  - 🌐 DuckDuckGo Web Search  
  - 📈 Stock API  
- **Interactive UI**: Streamlit-based interface with:
  - Left sidebar for thread-based conversation history  
  - Easy revisit of prior chats  
  - Clean and intuitive user experience  

---

## 🛠️ Tech Stack

- **LangChain, LangGraph, LangSmith** - Conversational intelligence & AI orchestration  
- **OpenAI API** - Natural language processing and generation  
- **SQLite** - Persistent memory storage  
- **Streamlit** - Interactive web interface  
- **RAG (Retrieval-Augmented Generation)** - Context-aware responses  

---

## 💻 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ai-chatbot-assistant.git
    cd ai-chatbot-assistant
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    streamlit run app.py
    ```

---

## ⚙️ Usage

- Interact with the chatbot through the **Streamlit UI**.  
- Use **external tools** by typing commands like:
  - `/calc 2+2` → Calculator  
  - `/search AI Chatbots` → DuckDuckGo Search  
  - `/stock TSLA` → Stock API  

- Chat history is automatically saved for **persistent sessions**.

---

## 📂 Project Structure

