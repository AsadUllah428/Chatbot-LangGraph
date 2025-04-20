# 🧠 LLaMA3 Chatbot with LangGraph

A conversational AI assistant built using [LangGraph](https://docs.langchain.com/langgraph/), [LangChain](https://www.langchain.com/), and the blazing-fast [Groq API](https://console.groq.com/).
This project uses LLaMA3 (70B) to create a responsive, memory-enabled chatbot that runs in a loop and gracefully exits on command.

---

## 🚀 Features

- ✅ Stateful, node-based conversation flow using LangGraph  
- 💬 Supports memory with `ConversationBufferWindowMemory`  
- ⚙️ Runs with LLaMA 3 via Groq API  
- 👋 Graceful exit on `Ctrl+C` or by typing `exit` or `quit`  
- 📜 Clean, modular Python code with type annotations

## 🔧 Configuration :
- os.environ["GROQ_API_KEY"] = "your-groq-api-key-here"
- model_name="your-desired-model-name"

## 🙋‍♂️ Contributing:
Contributions are welcome! Feel free to fork, create issues, or submit pull requests with improvements.

## 📦 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/yourusername/llama3-chatbot-graph.git
   cd llama3-chatbot-graph

