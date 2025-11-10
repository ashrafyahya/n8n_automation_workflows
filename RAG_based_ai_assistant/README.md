### RAG Based AI Assistant
An intelligent Retrieval-Augmented Generation (RAG) AI assistant featuring:

- Chat-based interface for user queries
- Data retrieval from Google Drive knowledge base
- Vector embeddings for efficient information search
- AI-powered responses based on retrieved context
- Memory management for conversation continuity

## Implementation Details

### RAG Based AI Assistant Implementation
The RAG AI assistant workflow enables intelligent conversations by retrieving relevant information from a pre-loaded knowledge base:

1. **Data Loading**:
   - Retrieves documents from a specified Google Drive folder
   - Processes and embeds document content
   - Stores embeddings in an in-memory vector database

2. **Chat Interface**:
   - Accepts user messages via chat trigger
   - Uses AI agent with retrieval tool to find relevant context
   - Generates accurate responses based on retrieved information
   - Maintains conversation memory for context

3. **AI Processing**:
   - Leverages Google Gemini for embeddings and chat responses
   - Implements RAG for factual, context-aware answers
   - Prevents hallucinations by sticking to provided data

#### RAG Based AI Assistant Workflow
![RAG Based AI Assistant Workflow](./rag_based_ai_assistant.jpg)

## Getting Started

To use this workflow:

1. Create a workflow in n8n portal
2. Import the ashraf_RAG_based_ai_assistant.json workflow file
3. Configure your credentials for:
   - Google Drive OAuth2 API (for accessing documents)
   - Google Gemini API (for embeddings and chat)
4. Customize the workflow parameters as needed, such as the Google Drive folder ID for data loading
