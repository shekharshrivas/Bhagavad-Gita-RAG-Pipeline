Retrieval-Augmented Generation (RAG) Pipeline for Bhagavad Gita Queries
This project implements a Retrieval-Augmented Generation (RAG) pipeline to provide context-aware responses to user queries based on the Bhagavad Gita text. The pipeline is designed to retrieve relevant verses and generate precise answers using advanced retrieval and language generation techniques.

Dataset
The Bhagavad Gita dataset contains columns like chapter, verse, translation, and optional question for enhanced retrieval.

RAG Pipeline Workflow
Indexing text data using retrieval algorithms (BM25, FAISS, DPR).
Retrieving relevant context from indexed data based on user queries.
Generating detailed and accurate responses using a language model.
Algorithms Implemented

BM25
FAISS (Facebook AI Similarity Search)
Dense Passage Retrieval (DPR)

Response Generation
Utilizes LLM (Large Language Model) for generating high-quality, context-aware responses.
