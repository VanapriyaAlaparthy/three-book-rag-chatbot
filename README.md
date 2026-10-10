# Three-Book RAG Chatbot

A Retrieval-Augmented Generation (RAG) application that answers questions from three PDF documents using Google Gemini and Gemini File Search.

## Features
- Processes three PDF books.
- Retrieves relevant document passages for user questions.
- Uses Gemini to generate answers grounded in retrieved content.
- Supports source-aware question answering.

## Tech Stack
- Python
- Google GenAI SDK
- Google Gemini 2.5 Flash
- Gemini File Search
- Google Colab

## Architecture
PDF Upload → Document Indexing → Relevant Passage Retrieval → Gemini LLM → Answer

## How to Run
1. Open the notebook in Google Colab.
2. Create a Gemini API key in Google AI Studio.
3. Configure the API key securely in Colab.
4. Upload the three PDF documents.
5. Index the documents and ask questions.

## Security
Never commit API keys, passwords, or private credentials. The original PDF books are not included in this repository.

## Future Improvements
- Add a Streamlit chat interface.
- Improve source citations with page numbers.
- Add evaluation for retrieval quality and answer accuracy.
