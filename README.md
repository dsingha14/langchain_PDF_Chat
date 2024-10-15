# Chat with PDFs

## Overview

**Chat with PDFs** is a Streamlit web application that enables users to interactively chat with multiple PDF documents. Users can upload PDFs, extract their text, and ask questions to receive relevant answers based on the content of the documents.

## Features

- **Upload PDFs**: Users can upload multiple PDF files for processing.
- **Text Extraction**: The app extracts text from the uploaded PDFs.
- **Question-Answering**: Users can ask questions and get answers based on the PDF content.
- **Interactive Interface**: User-friendly interface built with Streamlit.

## Technologies Used

- **Streamlit**: For building the web interface.
- **PyPDF2 or PyPDF**: For extracting text from PDF documents.
- **LangChain**: For text splitting, embeddings, and conversational retrieval.
- **Hugging Face**: Utilizes models for natural language processing and embeddings.
## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/chat-with-pdfs.git
   cd chat-with-pdfs
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Create a `.env` file for environment variables (if needed).**

## Usage

1. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser and go to** [http://localhost:8501](http://localhost:8501) **to access the app.**

3. **Upload your PDF documents, and start asking questions!**

## Challenges

- Efficiently processing large PDF files and managing system resources.
- Handling model loading and inference errors, particularly with large Hugging Face models.

## Future Improvements

- Implement user authentication for personalized experiences.
- Enhance the text extraction algorithm to support more complex PDF formats.
- Optimize model loading to reduce initial wait time for users.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
