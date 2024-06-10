# learning_RAG

Run these on Google Collab

Contains scraping.py which can be used to scrape first 10 google search results and store in drive to be use as context for the llm search

BasicRAG_Gemini_langchain
- Uses GeminiPro conversational model with context coming from ChromaDB vector db, using GoogleGenerativeAIEmbeddings.

BasicRAG_HuggingFace_langchain
- Uses google/flan-t5-small model with context coming form ChromaDB vector db, using HuggingFaceEmbeddings.
