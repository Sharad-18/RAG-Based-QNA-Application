# Generative AI-Powered Insights Platform

## Overview
Welcome to the Generative AI-Powered Insights Platform! This project is designed to provide in-depth insights from various types of documents using advanced generative AI and vector stores. The platform features a conversational interface that allows users to ask questions about their documents and receive detailed, contextual responses.

## Features
- **Conversational Interface**: Engage in a natural language conversation to extract information and insights from your documents.
- **Document Support**: Compatible with PDF, CSV, and TXT files for versatile document processing.
- **Embeddings Models**: Utilizes state-of-the-art embeddings from OpenAI and Cohere for precise information retrieval.
- **Efficient Processing**: Built with multiprocessing and Chroma to handle large datasets and ensure fast, efficient retrieval.
- **Interactive Web Interface**: Powered by Streamlit for a user-friendly experience.

## Technologies Used
- **Streamlit**: For creating an interactive web interface.
- **LangChain**: To facilitate conversational AI capabilities.
- **FAISS & Chroma**: For efficient vector store management and retrieval.
- **OpenAI & Cohere**: Embedding models for accurate and meaningful document processing.
- **Python**: Core programming language used for development.

## Installation
### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Setup
1. Clone the repository:
   ```python
   git clone https://github.com/yourusername/generative-ai-insights-platform.git
   cd generative-ai-insights-platform
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    streamlit run LLM_tool.py

##Contribution<br>
- **Contributions are welcome! Please fork the repository and submit a pull request for any enhancements, bug fixes, or new features.

##License
- **This project is licensed under the MIT License. See the LICENSE file for details.

##Acknowledgements <br>
Thanks to the open-source community and the developers of the tools and libraries used in this project.
Special mention to Streamlit, LangChain, FAISS, Chroma, OpenAI, and Cohere for their powerful technologies.
