# MediCare Plus AI Customer Service Bot- GIMO Take Home

An intelligent medical clinic assistant chatbot built with LangChain and OpenAI, featuring a 5-layer architecture for precise intent detection, contextual memory, and patient data retrieval.

## Features
5-Layer Architecture: Intent detection → RAG retrieval → Contextual memory → Escalation checks → Output formatting


Patient Data Integration: Personalized responses using patient medical records

FAQ Retrieval: Smart matching of clinic policy questions

Contextual Memory: Maintains conversation context across turns

Escalation Logic: Automatically routes emergencies and complex queries to human agents

Jupyter Widget Interface: Interactive chat interface for testing


## Quick Setup

### Configure Environment Variables
Rename the template file:

text.env → .env

Edit .env file:

OPENAI_API_KEY= your openai_api_key_here or openrouter_api_key_here 

LANGSMITH_API_KEY=your_langsmith_api_key_here  

Get API Keys:

OpenRouter: Sign up at OpenRouter.ai for GPT-5 Mini access

OpenAI: Sign up at openai.com/

LangSmith: Sign up at langchain.com/langsmith/observability

#### In the Code:

Set up for OpenAI API by default, if openrouter is needed, change USE_OPENROUTER = True


### Dependencies
See requirements.txt for complete list. Main packages:

LangChain & LangChain OpenAI

OpenAI

FAISS for vector storage

NLTK for text processing

Jupyter widgets for interface

LangSmith for tracing
