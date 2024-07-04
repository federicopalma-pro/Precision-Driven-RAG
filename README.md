# Precision-Driven RAG (Retrieval-Augmented Generation)

## Experiencing RAG with "Alice in Wonderland"

This notebook demonstrates a Precision-Driven RAG implementation using the classic novel "Alice in Wonderland" as our knowledge base.

Getting Started
To begin your RAG experience:

- write your OPENAI_API_KEY into the .env file
- Open the RAG.ipynb notebook in your Jupyter environment.
- Execute all cells in the notebook sequentially.
- Navigate to the "User's Query" section.
- Enter your "Alice in Wonderland" question in the designated input area.

## How to Query Your Document
To load your document into the ChromaDB vector database and query it using the Precision-Driven-RAG system, follow these instructions:

 - Ensure your document is in .txt format.
 - Process the document using both Raptor_chunks.ipynb and Semantic_chunks.ipynb notebooks. This will populate the vector database with the appropriate chunks.
 - Use the Metadata_Studio. ipynb notebook to enhance the metadata set for each semantic chunk.
 - Finally, run the RAG.ipynb notebook to perform queries on your processed document.

This workflow allows you to leverage the Precision-Driven-RAG methodology for hallucination-free, context-rich information synthesis on your documents.
