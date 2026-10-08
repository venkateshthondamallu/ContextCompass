# ContextCompass
A Streamlit-based AI chat assistant that answers questions by searching locally indexed documents (RAG) and the web, using FAISS, LangChain, and Ollama.

Chat with your documents through a Streamlit interface. The app incrementally indexes supported files in a local FAISS vector store, then uses a LangChain agent with Ollama to choose between searching those documents and the public web via DuckDuckGo. Answers include source details to help you verify the information.
