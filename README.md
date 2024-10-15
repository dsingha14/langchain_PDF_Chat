

Overview
Chat with PDFs is a Streamlit web application that allows users to interactively chat with multiple PDF documents. Users can upload PDFs, extract their text, and ask questions to receive relevant answers based on the content of the documents.

Features
Upload PDFs: Upload multiple PDF files for processing.
Text Extraction: Extracts text from the uploaded PDFs.
Question-Answering: Allows users to ask questions and get answers based on the PDF content.
Interactive Interface: User-friendly interface built with Streamlit.
Technologies Used
Streamlit: For building the web interface.
PyPDF2 or PyPDF: For extracting text from PDF documents.
LangChain: For text splitting, embeddings, and conversational retrieval.
Hugging Face: Utilizes models for natural language processing and embeddings.
Installation
Clone the repository:

bash
Copy code
git clone [https://github.com/yourusername/chat-with-pdfs.git](https://github.com/dsingha14/langchain.git)
Set up a virtual environment:

bash
Copy code
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Create a .env file for environment variables (if needed).

Usage
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open your browser and go to http://localhost:8501 to access the app.

Upload your PDF documents, and start asking questions!

Challenges
Efficiently processing large PDF files and managing system resources.
Handling model loading and inference errors, particularly with large Hugging Face models.
License
This project is licensed under the MIT License. See the LICENSE file for more details.
