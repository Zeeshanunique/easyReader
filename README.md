PDF Document Merging and chatting with FAISS Embeddings

Description:

This project aims to develop an AI application using Google Gemini Pro and Langchain to merge multiple PDF documents based on their semantic similarity. Leveraging FAISS vector embeddings, the application will identify documents with similar content and combine them into a single document.

Technologies:

- Google Gemini Pro: An open-source framework for building large-language models.
- Langchain: A Python library that simplifies the building and deployment of LLMs.
- Faiss: A library for efficient similarity search in high-dimensional spaces.
- PDF Parser: A library for extracting text from PDF documents.

**Goals:**

- Develop an LLM model that can identify documents with similar content.
- Use the LLM model to merge documents based on their similarity.
- Implement a user-friendly interface for uploading and merging documents.

Implementation:

1. Data Preparation: Convert PDF documents into text format and extract features using the PDF parser library.
2. Vector Embeddings: Create FAISS vector embeddings for each document based on its text content.
3. Similarity Search: Use FAISS to find documents with similar embeddings to the given document.
4. Document Merging: Combine documents with similar content into a single document using the LLM model.
5. Interface: Develop a user interface for uploading documents and initiating the merging process.

Possible Extensions:

- Integrate with other PDF processing tools to extract additional information, such as tables and images.
- Implement a mechanism to handle different document formats and structures.
- Develop a more sophisticated LLM model that can take into account other factors, such as document structure and style.

Additional Resources:

- [Google Gemini Pro](<url of Google Gemini Pro documentation>)
- [Langchain](<url of Langchain documentation>)
- [Faiss](<url of Faiss documentation>)
- [PDF Parser](<url of PDF Parser library>)

Contribution:

Contributions are welcome! Please feel free to fork the repository and make changes. Please submit pull requests for any changes you make.
