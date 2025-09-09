# HIPAA RAG Agent Backend

FastAPI backend for the HIPAA-compliant healthcare AI chat system.

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Set environment variables:
```bash
AZURE_CHAT_API_KEY=your_azure_chat_api_key
AZURE_EMBEDDINGS_API_KEY=your_azure_embeddings_api_key
```

3. Run the server:
```bash
uvicorn rag_service:app --reload
```

## Deployment

This backend is configured for deployment on Render.

## API Endpoints

- `POST /chat` - Main chat endpoint
- `POST /upload` - PDF upload endpoint
- `GET /health` - Health check endpoint