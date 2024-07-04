# Precision-Driven RAG (Retrieval-Augmented Generation)

## Experiencing RAG with "Alice in Wonderland"

This notebook demonstrates a Precision-Driven RAG implementation using the classic novel "Alice in Wonderland" as our knowledge base.

Getting Started
To begin your RAG experience:

- Open the RAG.ipynb notebook in your Jupyter environment.
- Execute all cells in the notebook sequentially.
- Navigate to the "User's Query" section.
- Enter your question about "Alice in Wonderland" in the designated input area.

## How to Query Your Own Document
To load your own document into the ChromaDB vector database and query it using the Precision-Driven-RAG system, follow these instructions:

 - Ensure your document is in .txt format.

 - Process the document using both Raptor_chunks.ipynb and Semantic_chunks.ipynb notebooks. This will populate the vector database with the appropriate chunks.

 - If you want to enhance the metadata set for each semantic chunk, use the Metadata_Studio.ipynb notebook.

 - Finally, run the RAG.ipynb notebook to perform queries on your processed document.

This workflow allows you to leverage the Precision-Driven-RAG methodology for hallucination-free, context-rich information synthesis on your own documents.