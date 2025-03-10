# MedBot

MedBot is an AI-powered chatbot designed to provide medical insights using Retrieval-Augmented Generation (RAG) with Gemini 1.5 Pro. It is built on the knowledge extracted from *Harrison's Principles of Internal Medicine*. The system employs Pinecone as the vector database, Flask for backend development, LangChain for processing queries, and a simple HTML & CSS frontend for user interaction.

## Features
- Uses Gemini 1.5 Pro API for generating medical insights.
- Implements Retrieval-Augmented Generation (RAG) for accurate responses.
- Stores and retrieves vector embeddings using Pinecone.
- Backend built with Flask.
- Frontend built with HTML & CSS.
- Utilizes LangChain for query processing and response generation.

## Installation and Setup
Follow these steps to set up and run MedBot locally.

### 1. Clone the Repository
```bash
git clone <repository-url>
cd medbot
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```
Activate the virtual environment:
- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **Mac/Linux:**
  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables
Create a `.env` file in the root directory and add the following:
```env
GEMINI_API_KEY=your_gemini_api_key
PINECONE_API_KEY=your_pinecone_api_key
```

### 5. Run the Application
```bash
python app.py
```

## Usage
- Enter medical queries in the chat interface.
- The bot retrieves relevant information from *Harrison's Principles of Internal Medicine* using RAG.
- It processes the query and generates a response using the Gemini 1.5 Pro API.

## Contributing
Feel free to fork this repository, create a new branch, and submit a pull request with improvements.

## License
This project is open-source under the MIT License.

---
Developed by Kavya Soni

