# DayleSeaChat - Customized RAG Chatbot

## Overview
DayleSeaChat is a custom-built, self-hosted conversational AI solution designed specifically for Daylor Engineering's maritime services website. The chatbot leverages a fine-tuned DeepSeek model with Retrieval-Augmented Generation (RAG) to provide accurate, contextual responses about Daylor's services, technical specifications, and maritime engineering expertise.

## Project Architecture

```
DayleSeaChat/
├── data/
│   ├── raw/                  # Raw scraped website content
│   ├── processed/            # Cleaned and structured data
│   └── embeddings/           # Vector embeddings for RAG
├── models/
│   ├── base/                 # Base DeepSeek model
│   └── fine_tuned/           # Our custom fine-tuned model
├── src/
│   ├── scraper/              # Website data extraction tools
│   ├── preprocessing/        # Data cleaning and preparation
│   ├── embedding/            # Embedding generation code
│   ├── training/             # Model fine-tuning scripts
│   ├── evaluation/           # Performance testing utilities
│   ├── rag/                  # Retrieval-Augmented Generation pipeline
│   └── api/                  # FastAPI server for web integration
├── ui/                       # Web interface components
├── tests/                    # Testing scripts
├── config/                   # Configuration files
└── deploy/                   # Deployment scripts and instructions
```

## Key Features
- **Domain-Specific Knowledge**: Trained on Daylor Engineering's maritime expertise and services
- **Self-Hosted Solution**: Complete ownership and control of the model and user data
- **Context-Aware Responses**: RAG system provides accurate answers based on website content
- **Technical Accuracy**: Fine-tuned for maritime engineering terminology and specifications
- **Seamless Website Integration**: Designed to match the existing dev.daylesea.com aesthetic

## Technical Implementation
- **Base Model**: DeepSeek reasoning model (optimized for Apple Silicon)
- **RAG Pipeline**: Custom retrieval system for technical documentation and service information
- **Training Infrastructure**: Apple M3 Max MacBook Pro with 64GB unified memory
- **Deployment**: Lightweight API server with WebSocket support for responsive interactions
- **Frontend**: JavaScript widget easily integrated with existing website

## Development Roadmap
1. ✅ Initial planning and architecture design
2. 🔄 Data collection and preprocessing
3. 🔄 RAG pipeline implementation
4. ⬜ Model training and fine-tuning
5. ⬜ Evaluation and reinforcement learning
6. ⬜ API development and deployment
7. ⬜ UI integration and testing
8. ⬜ Production deployment

## Setup and Installation
*Detailed setup instructions will be added as development progresses*

