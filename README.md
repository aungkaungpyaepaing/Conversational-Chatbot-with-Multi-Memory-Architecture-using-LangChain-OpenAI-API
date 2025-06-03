<h1>📄 Description</h1>


This project demonstrates a conversational AI chatbot built using LangChain and OpenAI's API, enhanced with two types of memory:

🧠 ConversationBufferMemory: preserves the raw message history.

🧠 ConversationSummaryMemory: maintains a dynamic summary of the conversation.

These memories are combined using CombinedMemory to give the LLM a richer context: raw user interactions and a concise abstract. The chatbot responds with improved coherence, continuity, and awareness of long-term context.




<h1>🛠️ Features</h1>


💬 OpenAI GPT-based chatbot (ChatOpenAI)

📚 Multi-memory support (CombinedMemory)

📖 Prompt engineering with dynamic input injection

🧪 Interactive examples in Jupyter Notebook (.ipynb)

✅ Modular, beginner-friendly, and production-ready



<h1>🧠 How Memory Works</h1>


ConversationBufferMemory helps the LLM remember the latest turns verbatim.

ConversationSummaryMemory uses a language model to summarize the conversation progressively.

CombinedMemory feeds both to the prompt template to enable deep reasoning.
