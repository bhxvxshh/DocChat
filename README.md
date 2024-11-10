# DocChat
DocChat is a Streamlit app that allows users to upload PDFs, extract text, and interact with the content using AI. It uses Google Generative AI for embeddings and FAISS for fast similarity search, enabling natural language queries to retrieve detailed information from documents.

The core functionality of the app involves:

PDF Upload: Users can upload one or more PDF files for processing.
Text Extraction & Chunking: Extracts text from PDFs and splits it into manageable chunks using the RecursiveCharacterTextSplitter.
Vectorization: Transforms the text chunks into vector embeddings using Google Generative AI Embeddings.
Similarity Search: Uses FAISS to perform fast search queries on the stored embeddings, ensuring accurate and relevant responses.
Conversational AI: The AI model, powered by Google Gemini, answers questions based on the provided document content, offering detailed and context-aware responses.
This tool is ideal for those looking to interact with large volumes of text, such as research papers, reports, or manuals, and seek specific information from them through natural language queries.

Tech Stack:

Streamlit: Web app interface
PyPDF2: PDF text extraction
Langchain: Text splitting and processing
FAISS: Similarity search indexing
Google Generative AI: For embeddings and question answering
Dotenv: Manage environment variables (API keys)
This app helps users query PDFs intuitively, with the power of AI, to retrieve detailed information without manually sifting through documents.
